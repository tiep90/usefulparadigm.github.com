---
layout: default
title: 유스풀패러다임
tagline: 웹2.0 소프트웨어 서비스 & 솔루션
description: 웹2.0 서비스/솔루션 개발, 오픈소스 솔루션 컨설팅/호스팅, 루비/레일스/얼랭 개발, 페이스북 앱 개발/제작, 워드프레스 웹사이트 제작,  페이스북Facebook/트위터Twitter/소셜웹SocialWeb 개발 및 컨설팅
---
{% include JB/setup %}

<p class="about justify">
  <strong><a href="/">유스풀패러다임</a></strong>은
	진화하는 웹 및 인터넷 기술에 기반하여 보다 많은 사람들에게 보다 유용한 인터넷 서비스와 솔루션을 제공하는 징검다리가 되고자 합니다.
</p>


## Services & Solutions

<ul>
	<li>웹서비스 개발/ 컨설팅</li>
	<li>페이스북 앱 제작</li>
	<li>워드프레스 테마 제작</li>
	<li>HTML5 모바일 웹사이트 구축</li>
	<li>오픈소스 솔루션 기술지원</li>
</ul>	


## Recent Articles

<ul class="posts">
  {% for post in site.posts limit:5 %}
    <!-- <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li> -->
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a> | <span>{{ post.date | date_to_string }}</span></li>
  {% endfor %}
</ul>

## Contact

<p>
110-702 서울 종로구 공평동 100 스탠다드차타드은행본점빌딩 2044호<br/>
(02) 720.5059 | <a href='mailto:contact@usefulparadigm.com'>contact@usefulparadigm.com</a><br/>

	<!-- <div class="media-grid"><a class="various fancybox.iframe" href="http://map.naver.com/index.nhn?dlevel=11&lat=37.5711873&lng=126.9823252&query=&menu=location&searchCoord=&tab=1&pinId=30858388&pinType=site&pinTitle=7Jyg7Iqk7ZKA7Yyo65%2Bs64uk7J6E&mapMode=0&enc=b64"><img src="http://prt.map.naver.com/mashupmap/print?key=p1345437335473_983733216" width="270" height="160" alt="지도 크게 보기" title="지도 크게 보기" border="0" style="vertical-align:top;"/></a></div> -->
</p>
