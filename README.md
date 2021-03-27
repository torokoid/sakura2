# sakura2

<html lang="ja">
 <head>
  <meta charset="utf-8" />
	 

<style type="text/css">

  p {
color: #fffafa;
font-size: 1.5em;
 }
<!--
 .red {color:#ff0000;}
 .grey {color:#999999;}
 .snow {color:#fffafa;}
 .yellow {color:#ff0000; background:#ffff00;}
 .blue {color:#0000ff;}
 .white {color:#ffffff; blinking;}
 .waku {border:2px dotted #99cc66;
　　　　　　line-height: 200%;
　　　　　　padding: 10px;}
 -->
	
.date:before{content:"20181115";}
	
	
 #preview{
	position: relative;
	border: 3px solid #333;
	background: #444;
	padding: 5px;
	display: none;
	color: #FFF;
	text-align: center;
}

main {
background-color: rgba(255, 255, 255, 0.3);
}

section {
background-color: rgba(0, 225, 0, 0.5);
}

#wrap {background:none} /*PC用の背景はオフ*/
body::before {
  content:"";
  display:block;
  position:fixed;
  top:0;
  left:0;
  z-index:-1;
  width:100%;
  height:100vh;
  background:url(https://torokoid.github.io/sakura2/20210327_001.JPG) center/cover no-repeat; /*fixedをトル！*/
  -webkit-background-size:cover;/*Android4*/
  }
 
@media	screen and (min-width: 540px),
	screen and (orientation: landscape) {
   p.note { display: none; }
}

/* 点滅 */
.blinking{
    -webkit-animation:blink 1.5s ease-in-out infinite alternate;
    -moz-animation:blink 1.5s ease-in-out infinite alternate;
    animation:blink 1.5s ease-in-out infinite alternate;
 } 
 @-webkit-keyframes blink{
     0% {opacity:0;}
     100% {opacity:1;}
 }
 @-moz-keyframes blink{
     0% {opacity:0;}
     100% {opacity:1;}
 }
 @keyframes blink{
     0% {opacity:0;}
     100% {opacity:1;}
}


/* 回転 */
.rotateX {
  background:rgba(255,0,0,0.8);
  width: 180px;
  height:35px;
  padding-top:0px;
  text-align: center;
	-webkit-animation: animeX 3s linear infinite;
	animation: animeX 3s linear infinite;
}

@-webkit-keyframes animeX {
	0%	{ -webkit-transform: rotateX(-0deg); }
	100%	{ -webkit-transform :rotateX(360deg); }
}
@keyframes animeX {
	0%	{ transform: rotateX(-0deg); }
	100%	{ transform :rotateX(360deg); }
}

.rotateY {
  background:rgba(255,0,0,0.8);
  width: 180px;
  height:35px;
  padding-top:0px;
  text-align: center;
	-webkit-animation: animeY 3s linear infinite;
	animation: animeY 3s linear infinite;
}

@-webkit-keyframes animeY {
	0%	{ -webkit-transform: rotateY(-0deg); }
	99.9%,to	{ -webkit-transform :rotateY(360deg); }
}
@keyframes animeY {
	0%	{ transform-origin: right bottom; }
	99.9%,to	{ transform:rotateY(360deg); }
}
  
  
  
  
a.p:hover {
    position: relative;
    text-decoration: none;
}
a.p span {
    display: none;
    position: relative;
    top: -0.5em;
    left: 1em;
}
a.p:hover span {
    border: none;
    display: block;
    width: 800px;
}   
    
 <!--
    p {
margin-left: 20px;
 }
    -->

.example {/*親div*/
  position: relative;/*相対配置*/
  }

.example p {
  position: absolute;/*絶対配置*/
  color: blue;/*文字は青に*/
  bottom: 0;
  right: 0;
  font-size: 1.0em;
  }
  
  
</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">
 
</head>
<body>
<p class="note">
  モバイル端末をお使いの場合は、画面を横向きにすると
  より見やすくご覧頂けます。
</p>


<h1><span class="yellow"><marquee behavior="alternate">!!! Sakura in Japan 2021_Spring !!!</marquee></span></h1>	

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<!--
<p align="left"> <img src="QR_furuhashi.png" alt="アクセス用QRコード" width="100">アクセス用QRコード</p>
-->
<h1><span class="yellow"><marquee behavior="alternate">!!! 2021_03_27、park !!!</marquee></span></h1>
<a href="20210327_001.JPG" data-lightbox="abc"><img src="20210327_001.JPG" alt="サンプル画像" width="200" /></a>
<a href="20210327_002.JPG" data-lightbox="abc"><img src="20210327_002.JPG" alt="サンプル画像" width="200" /></a>
<a href="20210327_003.JPG" data-lightbox="abc"><img src="20210327_003.JPG" alt="サンプル画像" width="200" /></a>
<a href="20210327_004.JPG" data-lightbox="abc"><img src="20210327_004.JPG" alt="サンプル画像" width="200" /></a>
<a href="20210327_005.JPG" data-lightbox="abc"><img src="20210327_005.JPG" alt="サンプル画像" width="200" /></a>
<a href="20210327_006.JPG" data-lightbox="abc"><img src="20210327_006.JPG" alt="サンプル画像" width="200" /></a>
<a href="20210327_007.JPG" data-lightbox="abc"><img src="20210327_007.JPG" alt="サンプル画像" width="200" /></a>
<a href="20210327_008.JPG" data-lightbox="abc"><img src="20210327_008.JPG" alt="サンプル画像" width="200" /></a>
<a href="20210327_009.JPG" data-lightbox="abc"><img src="20210327_009.JPG" alt="サンプル画像" width="200" /></a>
<a href="20210327_010.JPG" data-lightbox="abc"><img src="20210327_010.JPG" alt="サンプル画像" width="200" /></a>
<a href="20210327_011.JPG" data-lightbox="abc"><img src="20210327_011.JPG" alt="サンプル画像" width="900" /></a>
<a href="20210327_012.JPG" data-lightbox="abc"><img src="20210327_012.JPG" alt="サンプル画像" width="900" /></a>
<a href="20210327_013.JPG" data-lightbox="abc"><img src="20210327_013.JPG" alt="サンプル画像" width="900" /></a>

<h1><span class="yellow"><marquee behavior="alternate">!!! 梅もまだまだ綺麗 !!!</marquee></span></h1>
<a href="20210327_014.JPG" data-lightbox="abc"><img src="20210327_014.JPG" alt="サンプル画像" width="900" /></a>
<a href="20210327_015.JPG" data-lightbox="abc"><img src="20210327_015.JPG" alt="サンプル画像" width="900" /></a>

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>







<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>	
	
	

<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>


<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script> 

</body>

<!-- フッタ -->
 <footer><span class="snow">
 Copyright 2020/04/05 S.Hada
	</span></footer>
