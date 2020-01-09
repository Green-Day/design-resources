---
layout: page
title: компоненты
permalink: /components/

---

<div class="d-none d-xl-block sticky-top">
		<nav id="sidenav_scroll" class="navbar navbar-light bg-light" style="border: 0px solid #fff;">
		  <nav class="nav container">
		    <a class="nav-link" href="#defaults">дефолтные значения</a>
		    <a class="nav-link" href="#cards">карточки</a>
		    <a class="nav-link" href="#buttons">кнопки</a>
		    <a class="nav-link" href="#inputs">инпуты</a>
		    <a class="nav-link" href="#interracts">интерракты</a>
		    <a class="nav-link" href="#headers">шапки</a>
		    <a class="nav-link" href="#web">веб</a>
		  </nav>
		</nav>
</div>
<style type="text/css">
	.jumbotron{
		background: url({{site.url}}/assets/design.png);
		background-position: center;
		background-attachment: scroll;
		color: #fff;
	}
</style>
<div class="container">
	<h3 class="defaults">дефолтные значения</h3>
	<div class="alert alert-dark">⚠️ значения заданы относительно, то есть можно выбрать коэффициент уменьшения или увеличения и изменять в зависимости от размера экрана</div>
	<pre>тень - rgba(0,0,0,0.2); x-0; y-10; h-20;<br>текст - Segoe UI Bold/Regular 24/26/30/36/50px<br>отступы - 10/15/20/30/60px</pre>
	<h3 class="cards">карточки</h3>
	<ul class="list-unstyled">
	  <li class="media">
	    <img src="{{site.url}}/components/cards/1.png" class="mr-3" alt="card style 1 - recyclica_design" style="width: 460px;">
	    <div class="media-body">
	      <h5 class="mt-0 mb-1">мероприятие</h5>
	    </div>
	  </li>
	  <li class="media">
	    <img src="{{site.url}}/components/cards/2.png" class="mr-3" alt="card style 2 - recyclica_design" style="width: 460px;">
	    <div class="media-body">
	      <h5 class="mt-0 mb-1">переработка</h5>
	    </div>
	  </li>
	  <li class="media">
	  	<div class="mr-3" >
	  		<img src="{{site.url}}/components/cards/3.png" alt="card style 3.off - recyclica_design" style="width: 460px;"><br>
	    	<img src="{{site.url}}/components/cards/4.png" alt="card style 3.on - recyclica_design" style="width: 460px;">
	  	</div>
	    <div class="media-body">
	      <h5 class="mt-0 mb-1">настройки - переключатель</h5>
	    </div>
	  </li>
	  <li class="media">
	    <img src="{{site.url}}/components/cards/5.png" class="mr-3" alt="card style 4 - recyclica_design" style="width: 460px;">
	    <div class="media-body">
	      <h5 class="mt-0 mb-1">настройки - выпадающий список</h5>
	    </div>
	  </li>
	  <li class="media">
	  	<div class="mr-3" style="width: 460px;">
	    	<img src="{{site.url}}/components/cards/6.png" class="mr-3" alt="card style 5 - recyclica_design" style="width: 230px;">
	    </div>
	    <div class="media-body">
	      <h5 class="mt-0 mb-1">статистика</h5>
	    </div>
	  </li>
	  <li class="media">
	  	<div class="mr-3" style="width: 460px;">
	  		<img src="{{site.url}}/components/cards/7.png" alt="card style 6 - recyclica_design" style="width: 200px;">
	    	<img src="{{site.url}}/components/cards/10.png" alt="card style 6.icon - recyclica_design" style="width: 200px;">
	  	</div>
	    <div class="media-body">
	      <h5 class="mt-0 mb-1">карусель</h5>
	    </div>
	  </li>
	  <li class="media">
	    <img src="{{site.url}}/components/cards/8.png" class="mr-3" alt="card style 7 - recyclica_design" style="width: 460px;">
	    <div class="media-body">
	      <h5 class="mt-0 mb-1">карта</h5>
	    </div>
	  </li>
	  <li class="media">
	    <img src="{{site.url}}/components/cards/9.png" class="mr-3" alt="card style 8 - recyclica_design" style="width: 460px;">
	    <div class="media-body">
	      <h5 class="mt-0 mb-1">пункт приема</h5>
	    </div>
	  </li>
	</ul>
	<h3 class="cards">кнопки</h3>
	<ul class="list-unstyled">
	  <li class="media mb-2">
	    <img src="{{site.url}}/components/buttons/1.png" class="mr-3" alt="button style 1 - recyclica_design" style="width: 460px;">
	    <div class="media-body">
	      <h5 class="mt-0 mb-1">кнопка для формы</h5>
	    </div>
	  </li>
	  <li class="media mb-2">
	    <div class="mr-3" style="width: 460px;">
	  		<img src="{{site.url}}/components/buttons/2.png" class="mr-3" alt="button style 2 - recyclica_design" style="width: 230px;">
	  	</div>
	    <div class="media-body">
	      <h5 class="mt-0 mb-1">кнопка добавления места</h5>
	    </div>
	  </li>
	  <li class="media mb-2">
	  	<div class="mr-3" style="width: 460px;">
	  		<img src="{{site.url}}/components/buttons/3.png" class="mr-3" alt="button style 3 - recyclica_design" style="width: 60px;">
	  	</div>
	    <div class="media-body">
	      <h5 class="mt-0 mb-1">кнопка навигации</h5>
	    </div>
	  </li>
	</ul>
</div>