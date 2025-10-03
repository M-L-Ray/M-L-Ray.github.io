---
layout: archive
title: "Exams"
permalink: /exams/
author_profile: true
---

此处均为回忆版试卷，仅供交流使用，请勿用于商业用途。

<!-- 搜索框 -->
<div class="exams-search">
  <input type="text" id="courseSearch" placeholder="搜索课程名称..." class="search-input">
  <button id="clearSearch" style="display:none; margin-left: 10px; padding: 0.5rem 1rem; border: 1px solid #ccc; border-radius: 4px; background: #f5f5f5; cursor: pointer;">清除</button>
  <div id="searchResults" class="search-results"></div>
</div>

{% include base_path %}

<div class="exams-list" id="examsList">
  {% assign sorted_exams = site.exams | sort: "grade" %}
  {% for post in sorted_exams %}
    {% include archive-single.html %}
  {% endfor %}
</div>

<style>
/* 保持之前的样式不变 */
.exam-course-item {
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  padding: 1.5rem;
  margin-bottom: 1.5rem;
  background: transparent;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  transition: all 0.3s ease;
}

.exam-course-item:hover {
  box-shadow: 0 4px 8px rgba(0,0,0,0.15);
  transform: translateY(-2px);
}

.exam-course-header {
  margin-bottom: 1rem;
}

.archive__item-title {
  margin-bottom: 0.5rem;
}

.archive__item-title a {
  color: inherit;
  text-decoration: none;
  font-size: 1.4rem;
  font-weight: 600;
}

.archive__item-title a:hover {
  color: #3498db;
}

.course-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  font-size: 0.9rem;
  color: #666;
}

.course-meta span {
  background: #f8f9fa;
  padding: 0.25rem 0.75rem;
  border-radius: 15px;
  border: 1px solid #e9ecef;
}

.course-type {
  background: #e3f2fd !important;
  border-color: #bbdefb !important;
  color: #1976d2;
}

.course-venue {
  background: #e8f5e8 !important;
  border-color: #c8e6c9 !important;
  color: #388e3c;
}

.course-date {
  background: #fff3e0 !important;
  border-color: #ffe0b2 !important;
  color: #f57c00;
}

.course-grade {
  background: #fce4ec !important;
  border-color: #f8bbd9 !important;
  color: #c2185b;
}

.course-instructor {
  background: #f3e5f5 !important;
  border-color: #e1bee7 !important;
  color: #7b1fa2;
}

.course-notice {
  margin-top: 1rem;
  padding-top: 1rem;
  border-top: 1px solid #f0f0f0;
  color: #6c757d;
  font-size: 0.9rem;
  text-align: center;
}

/* 搜索相关样式 */
.exams-search {
  margin: 2rem 0;
  text-align: center;
}

.search-input {
  width: 100%;
  max-width: 400px;
  padding: 0.75rem 1rem;
  border: 2px solid rgba(0, 0, 0, 0.1);
  border-radius: 25px;
  font-size: 1rem;
  outline: none;
  transition: border-color 0.3s ease;
  background: transparent;
  color: inherit;
}

.search-input:focus {
  border-color: #3498db;
}

.search-input::placeholder {
  color: inherit;
  opacity: 0.6;
}

.exams-list {
  margin-top: 2rem;
}

.no-results {
  text-align: center;
  padding: 2rem;
  color: inherit;
  font-style: italic;
  opacity: 0.7;
}

/* 高亮匹配的文本 */
.highlight {
  background-color: yellow;
  color: black;
  padding: 0.1em 0.2em;
  border-radius: 0.2em;
}

/* 响应式设计 */
@media (max-width: 768px) {
  .exam-course-item {
    padding: 1rem;
  }
  
  .archive__item-title a {
    font-size: 1.2rem;
  }
  
  .course-meta {
    gap: 0.5rem;
  }
  
  .course-meta span {
    font-size: 0.8rem;
    padding: 0.2rem 0.5rem;
  }
}

/* 搜索结果样式 */
.search-results {
  margin-top: 0.5rem;
  font-size: 0.9rem;
  color: #666;
}

.hidden {
  display: none !important;
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const searchInput = document.getElementById('courseSearch');
  const clearButton = document.getElementById('clearSearch');
  const searchResults = document.getElementById('searchResults');
  const examsList = document.getElementById('examsList');
  const examItems = examsList.querySelectorAll('.exam-course-item');
  
  // 存储所有课程的原始数据
  const originalExamItems = Array.from(examItems).map(item => {
    const titleElement = item.querySelector('.archive__item-title');
    return {
      element: item,
      title: titleElement ? titleElement.textContent.trim() : '',
      originalHTML: item.innerHTML
    };
  });
  
  // 搜索功能
  function performSearch(searchTerm) {
    const normalizedSearchTerm = searchTerm.toLowerCase().trim();
    let matchCount = 0;
    
    originalExamItems.forEach(exam => {
      const normalizedTitle = exam.title.toLowerCase();
      
      if (normalizedTitle.includes(normalizedSearchTerm)) {
        exam.element.classList.remove('hidden');
        
        // 高亮匹配的文本
        if (normalizedSearchTerm && exam.title) {
          const regex = new RegExp(`(${normalizedSearchTerm})`, 'gi');
          const highlightedTitle = exam.title.replace(regex, '<span class="highlight">$1</span>');
          
          const titleElement = exam.element.querySelector('.archive__item-title');
          if (titleElement) {
            // 保持链接结构
            const link = titleElement.querySelector('a');
            if (link) {
              link.innerHTML = link.innerHTML.replace(regex, '<span class="highlight">$1</span>');
            } else {
              titleElement.innerHTML = highlightedTitle;
            }
          }
        }
        
        matchCount++;
      } else {
        exam.element.classList.add('hidden');
        // 恢复原始HTML以移除高亮
        exam.element.innerHTML = exam.originalHTML;
      }
    });
    
    // 更新搜索结果信息
    if (normalizedSearchTerm) {
      searchResults.textContent = `找到 ${matchCount} 个匹配的课程`;
      clearButton.style.display = 'inline-block';
    } else {
      searchResults.textContent = '';
      clearButton.style.display = 'none';
      
      // 恢复所有项目的原始HTML
      originalExamItems.forEach(exam => {
        exam.element.innerHTML = exam.originalHTML;
      });
    }
    
    // 如果没有匹配结果，显示提示信息
    if (normalizedSearchTerm && matchCount === 0) {
      searchResults.textContent = `没有找到包含"${searchTerm}"的课程`;
    }
  }
  
  // 输入事件监听
  searchInput.addEventListener('input', function() {
    performSearch(this.value);
  });
  
  // 清除按钮事件
  clearButton.addEventListener('click', function() {
    searchInput.value = '';
    performSearch('');
    searchInput.focus();
  });
  
  // 键盘事件
  searchInput.addEventListener('keydown', function(e) {
    if (e.key === 'Escape') {
      searchInput.value = '';
      performSearch('');
    }
  });
  
  // 初始化placeholder文本
  searchInput.placeholder = "搜索课程名称...";
});
</script>
