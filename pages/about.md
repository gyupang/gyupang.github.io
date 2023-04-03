---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
개발자로 성장해나가고자 노력하는 개발자 지망생입니다.  
이 블로그를 통해 제가 배운 것을 기록하고, 다른 사람들과 공유해 나가고자 합니다.  
개발 관련 정보와 경험을 공유하고, 같은 꿈을 가진 분들과 함께 성장할 수 있기를 희망합니다.  

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Hobbies" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>