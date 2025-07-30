---
permalink: /
title: "MLR's Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
我是谁？
------
[华东师范大学](https://math.ecnu.edu.cn/)23级数学与应用数学在读本科生，爱好是数学，吉他，睡觉。


如何联系我？（请备注来意）
---
**Wechat: sftdvf_nztfmg**

**QQ: 1346484237**


这里有什么？
---
我的部分[课程笔记](https://m-l-ray.github.io//notes/)

我收集的部分[试卷](https://m-l-ray.github.io//exams/)

以及[Latex模板](https://github.com/M-L-Ray/template/tree/main)

（施工中，不定时更新）

创建这个主页的原因？

<!-- Gitalk 评论 start  -->
{% if site.gitalk.enable %}
<!-- Gitalk link  -->
<link rel="stylesheet" href="https://unpkg.com/gitalk/dist/gitalk.css">
<script src="https://unpkg.com/gitalk@latest/dist/gitalk.min.js"></script>

<div id="gitalk-container"></div>
    <script type="text/javascript">
    var gitalk = new Gitalk({
    clientID: '{{site.gitalk.clientID}}',
    clientSecret: '{{site.gitalk.clientSecret}}',
    repo: '{{site.gitalk.repo}}',
    owner: '{{site.gitalk.owner}}',
    admin: ['{{site.gitalk.admin}}'],
    distractionFreeMode: {{site.gitalk.distractionFreeMode}},
    id: 'about',
    });
    gitalk.render('gitalk-container');
</script>
{% endif %}
<!-- Gitalk end -->

 <!-- disqus 评论框 start  -->
{% if site.disqus.enable %}

<div class="comment">
    <div id="disqus_thread" class="disqus-thread">
    </div>
</div>
<!-- disqus 评论框 end -->

<!-- disqus 公共JS代码 start (一个网页只需插入一次) -->
<script type="text/javascript">
    /* * * CONFIGURATION VARIABLES * * */
    var disqus_shortname = "{{site.disqus.username}}";
    var disqus_identifier = "{{site.disqus.username}}/{{page.url}}";
    var disqus_url = "{{site.url}}{{page.url}}";

    (function() {
        var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
        dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
        (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
    })();
</script>
<!-- disqus 公共JS代码 end -->
{% endif %}
------
还没想好 总之有空就建了
