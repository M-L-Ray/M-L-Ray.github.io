---
permalink: /
title: "MLR's Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
欢迎您的到来，如果网页卡顿可以借助VPN，另外推荐使用电脑浏览器以90%尺寸浏览！

我是谁？
------
[华东师范大学](https://math.ecnu.edu.cn/)23级数学与应用数学在读本科生，爱好是数学，合唱，吉他，睡觉。

如何联系我？
---
**Wechat: sftdvf_nztfmg**

**QQ: 1346484237**

**知乎/小红书/微信公众号：小马同学不在**

这里有什么？
---
我的部分[课程笔记](https://m-l-ray.github.io//notes/)

我收集的部分[试卷](https://m-l-ray.github.io//exams/)

以及[Latex模板](https://github.com/M-L-Ray/template/tree/main)

（施工中，不定时更新）

创建这个主页的原因？
------
首先是给自己建一个资料库，告诉自己学过什么；而后大约可以算是为学弟学妹们提供一些帮助与指引，关于各种课程，帮助各位快速了解应该如何准备（考试）与学习，不希望大家都像我一样每到考试无比慌乱，不知如何复习亦或是去何处寻得往年题目，往后会更新一些学习心得（虽然大概只是混到不挂科？），帮助来到这个主页寻求资料的数学爱好者（也可能是临时抱佛脚者？）少走一些弯路。我的水平在同届中并不算高，但对于刚入学或是还未对大学数学学习有眉目的同学们，也许可以提供一些指引，仅此而已。

可以来玩钢琴
------
<div id="currentNote" class="current-note">点击琴键或按键盘演奏</div>
<div class="piano-container">
    <div class="piano" id="piano">
        <!-- 琴键将通过JavaScript动态生成 -->
    </div>
</div>

<style>
    .current-note {
        font-size: 2rem;
        font-weight: bold;
        margin: 20px 0;
        height: 40px;
        text-align: center;
        transition: transform 0.2s ease;
    }
    
    .current-note.active {
        transform: scale(1.1);
        color: #007acc;
    }
    
    .piano-container {
        position: relative;
        display: inline-block;
        margin: 0 auto;
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
        border-radius: 10px;
        overflow: hidden;
        max-width: 800px;
        width: 100%;
    }
    
    .piano {
        display: flex;
        height: 180px;
        position: relative;
    }
    
    .white-key {
        flex: 1;
        min-width: 60px;
        background: linear-gradient(to bottom, #fff 0%, #f5f5f5 100%);
        border: 1px solid #ddd;
        border-radius: 0 0 5px 5px;
        cursor: pointer;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        align-items: center;
        padding-bottom: 10px;
        font-weight: bold;
        color: #333;
        transition: all 0.1s ease;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        user-select: none;
        position: relative;
        z-index: 1;
    }
    
    .black-key {
        width: 7%;
        height: 110px;
        background: linear-gradient(to bottom, #333 0%, #000 100%);
        border: 1px solid #222;
        border-radius: 0 0 3px 3px;
        cursor: pointer;
        position: absolute;
        z-index: 2;
        display: flex;
        justify-content: center;
        align-items: flex-end;
        padding-bottom: 5px;
        font-weight: bold;
        color: white;
        transition: all 0.1s ease;
        box-shadow: 0 2px 6px rgba(0, 0, 0, 0.5);
        user-select: none;
    }
    
    .white-key:hover {
        background: linear-gradient(to bottom, #f0f0f0 0%, #e5e5e5 100%);
    }
    
    .black-key:hover {
        background: linear-gradient(to bottom, #444 0%, #111 100%);
    }
    
    .key.active {
        transform: translateY(2px);
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
    }
    
    .white-key.active {
        background: linear-gradient(to bottom, #e0e0e0 0%, #d5d5d5 100%);
    }
    
    .black-key.active {
        background: linear-gradient(to bottom, #222 0%, #000 100%);
    }
    
    .key-label {
        font-size: 1rem;
    }
    
    @media (max-width: 768px) {
        .piano {
            height: 140px;
        }
        
        .black-key {
            height: 85px;
            width: 6.5%;
        }
        
        .current-note {
            font-size: 1.8rem;
        }
        
        .key-label {
            font-size: 0.9rem;
        }
        
        .white-key {
            min-width: 50px;
        }
    }
    
    @media (max-width: 480px) {
        .piano {
            height: 120px;
        }
        
        .black-key {
            height: 75px;
            width: 6%;
        }
        
        .current-note {
            font-size: 1.6rem;
        }
        
        .key-label {
            font-size: 0.8rem;
        }
        
        .white-key {
            min-width: 45px;
        }
    }
</style>

<script>
    // 音符数据：频率和名称
    const notes = [
        // 白键
        { frequency: 261.63, name: 'C', key: 'A', type: 'white', position: 0 },
        { frequency: 293.66, name: 'D', key: 'S', type: 'white', position: 1 },
        { frequency: 329.63, name: 'E', key: 'D', type: 'white', position: 2 },
        { frequency: 349.23, name: 'F', key: 'F', type: 'white', position: 3 },
        { frequency: 392.00, name: 'G', key: 'G', type: 'white', position: 4 },
        { frequency: 440.00, name: 'A', key: 'H', type: 'white', position: 5 },
        { frequency: 493.88, name: 'B', key: 'J', type: 'white', position: 6 },
        { frequency: 523.25, name: 'C1', key: 'K', type: 'white', position: 7 },
        
        // 黑键
        { frequency: 277.18, name: 'C#', key: 'W', type: 'black', position: 0.5 },
        { frequency: 311.13, name: 'D#', key: 'E', type: 'black', position: 1.5 },
        { frequency: 369.99, name: 'F#', key: 'T', type: 'black', position: 3.5 },
        { frequency: 415.30, name: 'G#', key: 'Y', type: 'black', position: 4.5 },
        { frequency: 466.16, name: 'A#', key: 'U', type: 'black', position: 5.5 }
    ];

    // Web Audio API 相关变量
    let audioContext;
    let gainNode;
    const activeOscillators = new Map();

    // 初始化音频上下文（在用户交互后）
    function initAudioContext() {
        if (!audioContext) {
            audioContext = new (window.AudioContext || window.webkitAudioContext)();
            gainNode = audioContext.createGain();
            gainNode.gain.value = 0.3; // 设置音量增益
            gainNode.connect(audioContext.destination);
        }
    }

    // 播放音符
    function playNote(frequency, noteName) {
        initAudioContext();
        
        // 如果已经有该音符的振荡器，先停止它
        if (activeOscillators.has(noteName)) {
            stopNote(noteName);
        }
        
        // 创建新的振荡器
        const oscillator = audioContext.createOscillator();
        oscillator.type = 'triangle'; // 使用三角波
        oscillator.frequency.value = frequency;
        
        // 创建增益节点用于控制音量衰减
        const noteGain = audioContext.createGain();
        noteGain.gain.value = 0.3;
        
        // 连接节点
        oscillator.connect(noteGain);
        noteGain.connect(gainNode);
        
        // 开始播放
        oscillator.start();
        
        // 保存振荡器引用
        activeOscillators.set(noteName, { oscillator, noteGain });
        
        // 更新当前音符显示
        updateCurrentNote(noteName);
    }

    // 停止音符
    function stopNote(noteName) {
        if (activeOscillators.has(noteName)) {
            const { oscillator, noteGain } = activeOscillators.get(noteName);
            
            // 使用指数衰减模拟钢琴音色
            const currentTime = audioContext.currentTime;
            noteGain.gain.exponentialRampToValueAtTime(0.001, currentTime + 0.8);
            
            // 在衰减后停止振荡器
            setTimeout(() => {
                oscillator.stop();
                oscillator.disconnect();
                noteGain.disconnect();
            }, 800);
            
            // 从Map中移除
            activeOscillators.delete(noteName);
        }
    }

    // 更新当前音符显示
    function updateCurrentNote(noteName) {
        const currentNoteElement = document.getElementById('currentNote');
        currentNoteElement.textContent = noteName;
        currentNoteElement.classList.add('active');
        
        // 移除激活状态
        setTimeout(() => {
            currentNoteElement.classList.remove('active');
        }, 200);
    }

    // 创建钢琴键盘
    function createPiano() {
        const pianoElement = document.getElementById('piano');
        
        // 先创建白键
        const whiteKeys = notes.filter(note => note.type === 'white');
        whiteKeys.forEach((note, index) => {
            const keyElement = document.createElement('div');
            keyElement.className = 'white-key key';
            keyElement.dataset.note = note.name;
            keyElement.dataset.frequency = note.frequency;
            
            const labelElement = document.createElement('div');
            labelElement.className = 'key-label';
            labelElement.textContent = note.name;
            
            keyElement.appendChild(labelElement);
            pianoElement.appendChild(keyElement);
            
            // 添加鼠标事件
            addKeyEvents(keyElement, note);
        });
        
        // 然后创建黑键
        const blackKeys = notes.filter(note => note.type === 'black');
        blackKeys.forEach((note) => {
            const keyElement = document.createElement('div');
            keyElement.className = 'black-key key';
            keyElement.dataset.note = note.name;
            keyElement.dataset.frequency = note.frequency;
            
            // 计算黑键的位置（相对于白键）
            const whiteKeys = notes.filter(note => note.type === 'white');
            const keyWidth = 100 / whiteKeys.length; // 白键的百分比宽度
            
            // 黑键向右移动半个黑键的位置
            const blackKeyWidth = 7; // 黑键宽度百分比
            const offset = blackKeyWidth / 2; // 半个黑键的宽度
            const leftPosition = (note.position * keyWidth) + (offset / whiteKeys.length);
            
            keyElement.style.width = `${blackKeyWidth}%`; // 固定黑键宽度比例
            keyElement.style.left = `${leftPosition}%`;
            
            const labelElement = document.createElement('div');
            labelElement.className = 'key-label';
            labelElement.textContent = note.name;
            
            keyElement.appendChild(labelElement);
            pianoElement.appendChild(keyElement);
            
            // 添加鼠标事件
            addKeyEvents(keyElement, note);
        });
    }

    // 为琴键添加事件监听
    function addKeyEvents(keyElement, note) {
        keyElement.addEventListener('mousedown', () => {
            playNote(note.frequency, note.name);
            keyElement.classList.add('active');
        });
        
        keyElement.addEventListener('mouseup', () => {
            stopNote(note.name);
            keyElement.classList.remove('active');
        });
        
        keyElement.addEventListener('mouseleave', () => {
            stopNote(note.name);
            keyElement.classList.remove('active');
        });
        
        // 添加触摸事件支持
        keyElement.addEventListener('touchstart', (e) => {
            e.preventDefault();
            playNote(note.frequency, note.name);
            keyElement.classList.add('active');
        });
        
        keyElement.addEventListener('touchend', (e) => {
            e.preventDefault();
            stopNote(note.name);
            keyElement.classList.remove('active');
        });
    }

    // 添加键盘事件监听
    function setupKeyboardEvents() {
        document.addEventListener('keydown', (event) => {
            const key = event.key.toUpperCase();
            const note = notes.find(note => note.key === key);
            
            if (note && !event.repeat) {
                playNote(note.frequency, note.name);
                
                // 找到对应的琴键元素并添加激活状态
                const keyElement = document.querySelector(`.key[data-note="${note.name}"]`);
                if (keyElement) {
                    keyElement.classList.add('active');
                }
            }
        });
        
        document.addEventListener('keyup', (event) => {
            const key = event.key.toUpperCase();
            const note = notes.find(note => note.key === key);
            
            if (note) {
                stopNote(note.name);
                
                // 移除激活状态
                const keyElement = document.querySelector(`.key[data-note="${note.name}"]`);
                if (keyElement) {
                    keyElement.classList.remove('active');
                }
            }
        });
    }

    // 初始化
    document.addEventListener('DOMContentLoaded', () => {
        createPiano();
        setupKeyboardEvents();
    });
</script>
