<html lang="en" >

<head>

  <meta charset="UTF-8">
  
<link rel="apple-touch-icon" type="image/png" href="https://cpwebassets.codepen.io/assets/favicon/apple-touch-icon-5ae1a0698dcc2402e9712f7d01ed509a57814f994c660df9f7a952f3060705ee.png" />
<meta name="apple-mobile-web-app-title" content="CodePen">

<link rel="shortcut icon" type="image/x-icon" href="https://cpwebassets.codepen.io/assets/favicon/favicon-aec34940fbc1a6e787974dcd360f2c6b63348d4b1f4e06c77743096d55480f33.ico" />

<link rel="mask-icon" type="image/x-icon" href="https://cpwebassets.codepen.io/assets/favicon/logo-pin-8f3771b1072e3c38bd662872f6b673a722f4b3ca2421637d5596661b4e2132cc.svg" color="#111" />


  <title>CodePen - eto tkyg</title>
  
  
  
  
<style>
.angel{
  background: #eeeeee;
  border: solid 1px #fbfbfb;
  width: 700px;
  height: 760px;
  margin: auto;
  border-radius: 25px;
  overflow: hidden;
  position: relative;
  font-family: Hind;
}
.angel-header{
  display: grid;
  grid-template-columns: 200px auto;
}
.angel-icon{
  background: #111;
  height: 200px;
  color: #eee;
  overlow: hidden;
}
.angel-icon span{
  font-size: 140px;
  opacity: .2;
  margin: 20px;
  display: block;
  -webkit-text-stroke: 4px var(--color);
  color: transparent;
}
.angel-ima2{
  border-left: var(--color) 3px solid;
  border-right: transparent 3px solid;
  border-top: var(--color) solid 3px;
  border-bottom: transparent solid 3px;
  width: 150px;
  height: 150px;
  border-radius: 100%;
  position: absolute;
  top: 20px;
  left: 125px;
}
.angel-ima2 img{
  border-radius: 100%;
  position: absolute;
  border: 25px #111 solid;
  width: 100px;
}
.angel-ima1{
  background: var(--color);
  height: 200px;
}
.angel-ima0{
  filter: grayscale(1) brightness(1.5);
  mix-blend-mode: multiply;
}
.angel-name b{
  font: 900 50px Poppins;
  text-transform: uppercase;
  letter-spacing: -3px;
  color: #eee;
  text-align: right;
  line-height: 40px;
  display: block;
}
.angel-name{
  position: absolute;
  top: 30px;
  right: 20px;
  width: 300px;
  text-shadow: 0px 0px 4px rgba(15,15,15,.5);
}
.angel-name i{
  color: #fff;
  text-transform: uppercase;
  text-align: right;
  font: 200 10px Hind;
  line-height: 10px;
  display: block;
  padding: 10px 0px;
  width: 200px;
  position: absolute;
  right: 0px;
}
.angel-body{
  background: #fbfbfb;
  width: 600px;
  height: 560px;
  margin: -30px 50px 0px;
  position: relative;
  border-radius: 25px;
  box-shadow: 3px -3px 10px -2px rgba(15,15,15,.05);
  overflow: hidden;
}
.angel input{
  display: none;
}
.angel label{
  background: #fbfbfb;
  display: inline-block;
  width: 110px;
  padding: 6px;
  font: 900 10px Poppins;
  text-transform: lowercase;
  color: var(--color);
  border-radius: 10px;
  position: relative;
  top: 20px;
  text-align: center;
  left: 20px;
  box-shadow: 3px -3px 10px -2px rgba(15,15,15,.05);
  transition: .5s;
  margin-right: 10px;
  z-index: 10;
}
.angel input:checked+label{
  background: var(--color);
  color: #fbfbfb;
  transition: .5s;
}
.angel label:hover{
  transform: scale(1.1);
  transition: .5s;
}
.angel-wrap{
  width: 540px;
  height: 470px;
  position: relative;
  top: 30px;
  left: 30px;
}
.angel-index1, .angel-index2, .angel-index3, .angel-index4{
  height: 500px;
  margin-bottom: 30px;
  transition: .5;
}
#wd-ttab1:checked ~ .angel-wrap{
  margin-top: 0px;
  transition: .5s;
}
#wd-ttab2:checked ~ .angel-wrap{
  margin-top: -540px;
  transition: .5s;
}
#wd-ttab3:checked ~ .angel-wrap{
  margin-top: -1060px;
  transition: .5s;
}
#wd-ttab4:checked ~ .angel-wrap{
  margin-top: -1590px;
  transition: .5s;
}
img.angel-ima3{border-radius: 25px;}
.angel-datos{
  position: absolute;
  left: 50px;
  bottom: 50px;
  background: #eee;
  padding: 20px;
  border-radius: 25px;
}
.angel-datos span{
  display: block;
  width: 100px;
  margin-bottom: 5px;
  padding: 10px;
  color: #222;
  font: 200 10px Hind;
  text-align: center;
  text-transform: uppercase;
  line-height: 1;
  border-bottom: 1px solid var(--color);
  transition: .5s;
}
.angel-datos span:hover{
  background: var(--color);
  border-radius: 10px;
  color: #fff;
  transition: .5s;
}
.angel-datos span:nth-of-type(1){
  background: #222;
  color: #fff;
  border-radius: 10px;
}
.angel br{
  display: none;
}
.angel-pb{
  display: grid;
  grid-template-columns: 240px auto;
}
.angel-fisico{
  background: #222;
  border-radius: 25px;
  position: relative;
  top: 20px;
  margin-bottom: 20px;
  height: 140px;
  color: #eee;
  font-size: 10px;
}
.angel-fisico b{
  padding: 4px;
  font-size: 8px;
  color: #eee;
  text-transform: uppercase;
  width: 45px;
  text-align: center;
  display: inline-block;
  background: var(--color);
  margin: 5px 5px 0px 15px;
  border-radius: 10px;
  position: relative;
  top: 10px;
}
.angel-fisico i{
  color: #eee;
  font-weight: 200;
  padding: 5p;
  position: relative;
  top: 10px;
  font-style: normal;
}
.angel-fisico b:nth-of-type(3){
  width: 200px;
  text-align: center;
  top: 15px;
  position: relative;
}
.angel-fisico i:nth-of-type(3){
  width: 200px;
  display: block;
  border: transparent 10px solid;
  padding: 0px 10px;
  height: 40px;
  overflow: auto;
  text-align: justify;
}
.angel-fisico2{
  font: 200 10px Hind;
  border: 10px solid transparent;
  padding: 0px 10px;
  text-align: justify;
  width: 260px;
  position: relative;
  top: 20px;
  height: 120px;
  overflow: auto;
}
.angel-fisico2 br{display:block}
.angel-tit{
  font: 900 45px Poppins;
  color: var(--color);
  letter-spacing: -2px;
  position: relative;
  margin-top: 10px;
  margin-bottom: -10px;
}
.angel-texto1{
  font: 200 12px Hind;
  text-align: justify;
  border: 10px solid transparent;
  padding: 0px 10px;
  height: 230px;
  overflow: auto;
  background: #eee;
  border-radius: 25px;
}
.angel-texto1 br{display: block;}
.angel-texto1 b{
  color: var(--color);
  font: 900 12px Poppins;
  background: var(--color1);
  padding: 0px 5px;
}
.angel-fisico2 br{display: block}
.angel-story br{display: block;}
.angel-story{
  font: 200 12px Hind;
  border: 15px transparent solid;
  padding: 0px 10px;
  text-align: justify;
  height: 235px;
  overflow: auto;
}
.angel-dream{
  background: #222;
  height: 120px;
  color: #eee;
  border-radius: 25px;
  font: 200 12px Hind;
  border: 10px solid transparent;
  border-right: 70px solid #222;
  padding: 0px 10px;
  overflow: auto;
  position: relative;
  text-align: justify;
}
.angel-tit2{
  position: absolute;
  display: block;
  right: 0px;
  font: 900 35px Poppins;
  color: var(--color);
  transform: rotate(90deg);
  margin-top: -100px;
  margin-right:-70px;
}
.angel-content{
  position: relative;
  height: 500px;
}
.angel-extra{
  float: left;
  width: 280px;
  border: transparent 10px solid;
  margin-top: 10px;
  padding: 0px 10px;
  text-align: justify;
  font: 200 12px Hind;
  height: 390px;
  background: #eee;
  border-radius: 25px;
}
.angel-extra br{display: block}
.angel-tit3{
  position: absolute;
  bottom: 20px;
}
.angel-likes{
  margin-top: 10px;
  position: relative;
  top: 10px;
  left: 20px;
  max-height: 200px;
  font: 200 12px Hind;
  text-align: justify;
  display: flex;
  flex-flow: row wrap;
  width: 200px;
}
.angel-likes span{
  background: #222;
  color: #fff;
  padding: 5px;
  margin: 0 0 0 2px;
  flex: 1 0 auto;
  border-radius: 10px;
  margin-bottom: 3px;
  font: 10px Rajdhani;
  text-transform: uppercase;
  text-align: center;
}
.angel-gustos{
  height: 200px;
}
.angel-gustos b{
  font: 900 20px Poppins;
  text-transform: lowerase;
  color: var(--color);
  padding: 0px 20px 0px;
  position: relative;
  top: 20px;
  transition: .5s;
}
</style>

  
  
  
  

</head>

<body translate="no" >
  <div class="angel" style="--color: rgb(156, 23, 15); --color1: rgba(156, 23, 15, 0.2)">
<div class="angel-header">
<div class="angel-icon"><span class="game-icon game-icon-flamed-leaf"></span></div>
<div class="angel-ima1">
<img src="https://i.imgur.com/Z4cBqPw.png" class="angel-ima0">
</div></div>
<div class="angel-ima2"><img src="https://i.imgur.com/iw4GVyc.png"></div>
<div class="angel-name"><b>Eto</b><i>every page of tragedy is thrown away, it burned out in the flames</i></div>
<div class="angel-body">

<input type="radio" id="wd-ttab1" name="wd-ttab" checked>
<label for="wd-ttab1" id="wd-ttab1" title="Datos">Datos</label>

<input type="radio" id="wd-ttab2" name="wd-ttab">
<label for="wd-ttab2" id="wd-ttab2" title="Datos">about be</label>

<input type="radio" id="wd-ttab3" name="wd-ttab">
<label for="wd-ttab3" id="wd-ttab3" title="Datos">story on my own</label>

<input type="radio" id="wd-ttab4" name="wd-ttab">
<label for="wd-ttab4" id="wd-ttab4" title="Datos">something more</label>

<div class="angel-wrap">
<div class="angel-index1 wd1">
<img src="https://i.imgur.com/88X58Aw.png" class="angel-ima3">
<div class="angel-datos">
<span>Eto</span>
<span>R: 666 | A: 21</span>
<span>She / Her</span>
<span>Bisexual</span>
<span>Shinigami</span>
<span>Clase</span>
<span>Organizacion</span>
<span>Tipo de</span>
</div>
</div>
<div class="angel-index2 wd2">
<div class="angel-pb">
<div class="angel-fisico">
<b>Altura</b><i>1.62cm</i>
<b>Peso</b><i>45kg</i>
<b>Apariencia</b><i>Pelo rojo, piel nívea, ojos púrpura. Posee 2 cuernos en su cabeza de color negro.</i>
</div>
<div class="angel-fisico2">You’re the sort of idiot who’ll put too much faith in your power, charge ahead without thinking, and destroy yourself! I’m talking about when youYou’re the sort of idiot who’ll put too much faith in your power, charge ahead without thinking, and destroy yourself! I’m talking about when youYou’re the sort of idiot who’ll put too much faith in your power, charge ahead without thinking, and destroy yourself! I’m talking about when youYou’re the sort of idiot who’ll put too much faith in your power, charge ahead without thinking, and destroy yourself! I’m talking about when you</div>
</div>
<div class="angel-psique">
<div class="angel-tit">what to say...</div>
<div class="angel-texto1">head without thinking, and destroy yourself! I’m talking about when youYou’re the sort of idiot <b>who’ll put too much faith in your power</b>, charge ahead without thinking, and destroy yourself!<br> I’m talking about when you</div>
</div>
</div>
<div class="angel-index3 wd3">
<div class="angel-tit">want to play?</div><div class="angel-story">You’re the sort of idiot who’ll put too much faith in your power, charge ahead without thinking, <b>and destroy yourself!</b><br><br> I’m talking about when youYou’re the sort of idiot who’ll put too much faith in your power, charge ahead without thinking, and destroy yourself! I’m talking about when youYou’re the sort of idiot who’ll put too much faith in your power, charge ahead without thinking, and destroy yourself! I’m talking about when youYou’re the sort of idiot who’ll put too much faith in your power, charge ahead without thinking, and destroy yourself! I’m talking about when you</div>
<div class="angel-dream">You’re the sort of idiot who’ll put too much faith in your power, charge ahead without thinking, and destroy yourself! I’m talking about when you</div>
<div class="angel-tit2">dreams</div>
</div>
<div class="angel-index4 wd4">
<div class="angel-content">
<div class="angel-extra">You’re the sort of idiot who’ll put too much faith in your power, charge ahead without thinking, and destroy yourself! I’m talking about when you</div><div class="angel-tit angel-tit3">like a storm..</div>
<div class="angel-gustos"><b>likes...</b>
<div class="angel-likes"><span>el color rojo</span><span>sangre</span><span> calaveras</span><span>lluvia</span><span>tormentas</span><span>el fuego</span><span>gente bonita</span><span>tranquilidad</span><span>cosas bonitas</span><span>la belleza</span><span>su esposo de alguna manera</span><span>¿sus hijas?</span><span>literatura</span></div>
</div>
<div class="angel-gustos"><b>dislikes...</b>
<div class="angel-likes"><span>traición</span><span>¿sus hijas?</span><span>lo feo</span><span>ruido</span><span>calor</span><span>los espacios pequeños</span><span>multitudes</span><span>comida amarga</span><span>sus padres</span><span>sus hermanos</span><span>la bondad sin razón</span><span>la estupidez</span><span>dios</span></div>
</div></div></div></div>
</div></div>


<link href="https://fonts.googleapis.com/css?family=Montserrat:200,300,400,500,700,800" rel="stylesheet" type="text/css">
<link href="https://fonts.googleapis.com/css?family=Poppins:200,300,400,500,700,800" rel="stylesheet" type="text/css">
<link href="https://fonts.googleapis.com/css?family=Roboto:200,300,400,700,800" rel="stylesheet" type="text/css">
<link href="https://fonts.googleapis.com/css?family=Hind:200,300,400,700,800" rel="stylesheet" type="text/css">
<link href="https://fonts.googleapis.com/css?family=Rajdhani:200,300,400,700,800" rel="stylesheet" type="text/css">
<link rel="stylesheet" type="text/css" href="//icons.cappuccicons.com/cpf.css"/><link href="https://fonts.googleapis.com/css2?family=Abril+Fatface&display=swap" rel="stylesheet"><link href="https://dl.dropbox.com/s/thpzqkqhf1pzqnx/game-icons.css" rel="stylesheet"/>
  
  
  
  

</body>

</html>
