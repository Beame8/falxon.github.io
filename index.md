
<!DOCTYPE html>



<html>



<head>



<meta name="viewport" content="width=device-width, initial-scale=1">



<style>

@import url(https://fonts.googleapis.com/css?family=Nunito:400,700,300);



body{

font-family: 'Nunito', sans-serif;

background-color: #060e33;

}



.container{

position: absolute;

left: 50%;

top: 50%;

transform: translate(-50%, -50%);

.check{

display:none;

}

.btn{

text-transform: uppercase;

color: #fff;

border: 2px solid #cb134e;

display: inline-block;

padding: 15px;

padding-right: 50px;

padding-left: 50px;

border-radius: 3px;

cursor: pointer;

overflow: hidden;

box-sizing: border-box;

font-size:14px;

transition: all .3s ease;

.mo{

position:relative;

overflow:hidden;

bottom: -150px;

width:0px;

height:0px;

text-align:center;

display: inline-block;

opacity:0;

color: #272727;

}

&:before{

width:0%;

position: absolute;

left:0;

bottom:3px;

height: 5px;

background-color: #cb134e;

content: "";

}

&:after{

width:100%;

height:0%;

position:absolute;

bottom:3px;

left:0;

background-color: #cb134e;

content: "Download complete";

overflow:hidden;

text-align:center;

line-height: 180px;

}



&:hover{

background-color: #cb134e;

color: #060e33;

}

}

input[type=checkbox]:checked ~ .btn{

background: #ddced9;

border-radius: 0px;

border: none;

padding-top: 70px;

padding-bottom: 70px;

padding-left: 200px;

padding-right: 200px;

transition: all .5s cubic-bezier(0.68, -0.55, 0.27, 1.55);



&:before{

width:100%;

content: "";

color: #fff;

text-align: center;

line-height: 70px;

transition: all 3.5s linear;

}

&:after{

height:calc(100% - 3px);

color: #060e33;

transition: all .3s ease-in-out;

transition-delay: 3.5s;

}

.me{

display:none;

}

.mo{

transition:bottom .4s ease, opacity 1s ease;

transition-delay:.3s;

height: auto;

width:auto;

bottom: 0px;

opacity: 1;

}

}

}


.button {

background-color: #FFFFFF;

border: none;

color: black;

padding: 15px;

text-align: center;

text: #0000;

text-decoration: none;

display: inline-block;

font-size: 16px;

margin: 4px 2px;

cursor: pointer;

}



.button1 {border-radius: 9px;}

.button2 {border-radius: 4px;}

.button3 {border-radius: 8px;}

.button4 {border-radius: 12px;}

.button5 {border-radius: 50%;}



body, html {



height: 100%;



margin: 0;



font-family: Arial, Helvetica, sans-serif;



}







* {



box-sizing: border-box;



}







.bg-image {



/* The image used */



background-image: url("https://i.imgur.com/LdpKeAk.jpg");







/* Add the blur effect */



filter: blur(2px);



-webkit-filter: blur(99px);







/* Full height */



height: 100%;







/* Center and scale the image nicely */



background-position: center;



background-repeat: no-repeat;



background-size: cover;



}







/* Position text in the middle of the page/image */



.bg-text {



background-color: rgb(0,0,0); /* Fallback color */



background-color: rgba(0,0,0, 0.4); /* Black w/opacity/see-through */



color: white;



font-weight: bold;



border: 3px solid #f1f1f1;



position: absolute;



top: 50%;



left: 50%;



transform: translate(-50%, -50%);



z-index: 2;



width: 50%;



padding: 30px;



text-align: center;



}



</style>



</head>



<body>







<div class="bg-image"></div>







<div class="bg-text">



<h1 style="font-size:50px">Oranx</h1>



<p>Oranx is an app made to improve your computer performance if you're using a low end pc that you feel can't run any apps. Oranx will boost your computer perfomance by 25% and you wiil be guranteed your money back if you believe that Oranx has not fullfilled its purpose</p>







<button class="button button1">Download</button>

</div>







</body>



</html>
