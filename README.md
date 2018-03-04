# ART MAGIC

#nav,#nav ul { 
  list-style: none outside none; 
  margin: 0; 
  padding: 0; 
} 
#nav { 
  background: url('https://raw.githubusercontent.com/Artmd/artmd.github.io/master/menu_bg.png') no-repeat scroll 0 0 transparent; 
  clear: both; 
  font-size: 12px; 
  height: 58px; 
  padding: 0 0 0 9px; 
  position: relative; 
  width: 957px; 
} 
#nav ul { 
  background-color: #222; 
  border:1px solid #222; 
  border-radius: 0 5px 5px 5px; 
  border-width: 0 1px 1px; 
  box-shadow: 0 5px 5px rgba(0, 0, 0, 0.5); 
  left: -9999px; 
  overflow: hidden; 
  position: absolute; 
  top: -9999px; 
  z-index: 2; 

  -moz-transform: scaleY(0); 
  -ms-transform: scaleY(0); 
  -o-transform: scaleY(0); 
  -webkit-transform: scaleY(0); 
  transform: scaleY(0); 

  -moz-transform-origin: 0 0; 
  -ms-transform-origin: 0 0; 
  -o-transform-origin: 0 0; 
  -webkit-transform-origin: 0 0; 
  transform-origin: 0 0; 

  -moz-transition: -moz-transform 0.1s linear; 
  -ms-transition: -ms-transform 0.1s linear; 
  -o-transition: -o-transform 0.1s linear; 
  -webkit-transition: -webkit-transform 0.1s linear; 
  transition: transform 0.1s linear; 
} 
#nav li { 
  background: url('https://raw.githubusercontent.com/Artmd/artmd.github.io/master/menu_line.png') no-repeat scroll right 5px transparent; 
  float: left; 
  position: relative; 
} 
#nav li a { 
  color: #FFFFFF; 
  display: block; 
  float: left; 
  font-weight: normal; 
  height: 30px; 
  padding: 23px 20px 0; 
  position: relative; 
  text-decoration: none; 
  text-shadow: 1px 1px 1px #000000; 
} 
#nav li:hover > a { 
  color: #00B4FF; 
} 
#nav li:hover, #nav a:focus, #nav a:hover, #nav a:active { 
  background: none repeat scroll 0 0 #121212; 
  outline: 0 none; 
} 
#nav li:hover ul.subs { 
  left: 0; 
  top: 53px; 
  width: 180px; 

  -moz-transform: scaleY(1); 
  -ms-transform: scaleY(1); 
  -o-transform: scaleY(1); 
  -webkit-transform: scaleY(1); 
  transform: scaleY(1); 
} 
#nav ul li { 
  background: none; 
  width: 100%; 
} 
#nav ul li a { 
  float: none; 
} 
#nav ul li:hover > a { 
  background-color: #121212; 
  color: #00B4FF; 
} 
#lavalamp { 
  background: url('https://raw.githubusercontent.com/Artmd/artmd.github.io/master/lavalamp.png') no-repeat scroll 0 0 transparent; 
  height: 16px; 
  left: 13px; 
  position: absolute; 
  top: 0px; 
  width: 64px; 

  -moz-transition: all 300ms ease; 
  -ms-transition: all 300ms ease; 
  -o-transition: all 300ms ease; 
  -webkit-transition: all 300ms ease; 
  transition: all 300ms ease; 
} 
#lavalamp:hover { 
  -moz-transition-duration: 3000s; 
  -ms-transition-duration: 3000s; 
  -o-transition-duration: 3000s; 
  -webkit-transition-duration: 3000s; 
  transition-duration: 3000s; 
} 
#nav li:nth-child(1):hover ~ #lavalamp { 
  left: 19px; 
} 
#nav li:nth-child(2):hover ~ #lavalamp { 
  left: 100px; 
} 
#nav li:nth-child(3):hover ~ #lavalamp { 
  left: 182px; 
} 
#nav li:nth-child(4):hover ~ #lavalamp { 
  left: 263px; 
} 
#nav li:nth-child(5):hover ~ #lavalamp { 
  left: 345px; 
} 
#nav li:nth-child(6):hover ~ #lavalamp { 
  left: 427px; 
} 
#nav li:nth-child(7):hover ~ #lavalamp { 
  left: 509px; 
} 
#nav li:nth-child(8):hover ~ #lavalamp { 
  left: 591px; 
}


<ul id="nav"> 
<li><a href="#">Главная</a></li> 
<li><a class="hsubs" href="#">Меню 1</a> 
<ul class="subs"> 
<li><a href="#">Подменю 1</a></li> 
<li><a href="#">Подменю 2</a></li> 
<li><a href="#">Подменю 3</a></li> 
<li><a href="#">Подменю 4</a></li> 
<li><a href="#">Подменю 5</a></li> 
</ul> 
</li> 
<li><a class="hsubs" href="#">Меню 2</a> 
<ul class="subs"> 
<li><a href="#">Подменю 2-1</a></li> 
<li><a href="#">Подменю 2-2</a></li> 
<li><a href="#">Подменю 2-3</a></li> 
<li><a href="#">Подменю 2-4</a></li> 
<li><a href="#">Подменю 2-5</a></li> 
<li><a href="#">Подменю 2-6</a></li> 
<li><a href="#">Подменю 2-7</a></li> 
<li><a href="#">Подменю 2-8</a></li> 
</ul> 
</li> 
<li><a class="hsubs" href="#">Меню 3</a> 
<ul class="subs"> 
<li><a href="#">Подменю 3-1</a></li> 
<li><a href="#">Подменю 3-2</a></li> 
<li><a href="#">Подменю 3-3</a></li> 
<li><a href="#">Подменю 3-4</a></li> 
<li><a href="#">Подменю 3-5</a></li> 
</ul> 
</li> 
<li><a href="#">Меню 4</a></li> 
<li><a href="#">Меню 5</a></li> 
<li><a href="#">Меню 6</a></li> 
<li><a href="#">Меню 7</a></li> 
<div id="lavalamp"></div> 
</ul>

<iframe width="390" height="270" src="https://www.youtube.com/embed/vKeOEAadlP8" frameborder="0" allowfullscreen="allowfullscreen" data-link="https://www.youtube.com/watch?v=vKeOEAadlP8"></iframe>
<iframe width="390" height="270" src="https://www.youtube.com/embed/nzg3mqBNmBs" frameborder="0" allowfullscreen="allowfullscreen" data-link="https://www.youtube.com/watch?v=nzg3mqBNmBs"></iframe>
<iframe width="390" height="270" src="https://www.youtube.com/embed/ma9TzuDIjrk" frameborder="0" allowfullscreen="allowfullscreen" data-link="https://www.youtube.com/watch?v=ma9TzuDIjrk"></iframe>
<iframe width="390" height="270" src="https://www.youtube.com/embed/08NpUFfMHl4" frameborder="0" allowfullscreen="allowfullscreen" data-link="https://www.youtube.com/watch?v=08NpUFfMHl4"></iframe>
