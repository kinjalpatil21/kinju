<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width,initial-scale=1.0">

<title>Happy Boyfriend's Day ❤️</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Trebuchet MS',sans-serif;
}

body{

height:100vh;
overflow:hidden;
display:flex;
justify-content:center;
align-items:center;

background:#5b0b16;

background-image:
url("https://i.imgur.com/OGN3QSE.png");

background-size:300px;

background-repeat:repeat;

}

#intro{

width:100%;
height:100%;
display:flex;
justify-content:center;
align-items:center;

backdrop-filter:blur(2px);

}

.card{

width:90%;
max-width:390px;

background:#fff9f1;

border-radius:25px;

padding:30px;

box-shadow:0 20px 40px rgba(0,0,0,.35);

text-align:center;

animation:show .8s;

}

@keyframes show{

from{

opacity:0;
transform:translateY(40px);

}

to{

opacity:1;
transform:translateY(0);

}

}

h1{

color:#8b0000;
margin-bottom:15px;

}

.subtitle{

color:#5b3a29;
line-height:1.8;
margin-bottom:25px;

}

.chat{

display:flex;
flex-direction:column;
gap:12px;

}

.myMsg{

align-self:flex-start;

background:#ffe4e8;

padding:12px 16px;

border-radius:18px 18px 18px 4px;

max-width:85%;

}

.hisMsg{

align-self:flex-end;

background:#8b0000;

color:white;

padding:12px 16px;

border-radius:18px 18px 4px 18px;

max-width:85%;

}

input{

width:100%;

padding:13px;

border-radius:30px;

border:2px solid #d8b8b8;

margin-top:10px;

font-size:16px;

outline:none;

}

button{

margin-top:15px;

padding:14px 30px;

border:none;

border-radius:40px;

background:#8b0000;

color:white;

font-size:16px;

cursor:pointer;

}

button:hover{

transform:scale(1.04);

}

</style>

</head>

<body>

<div id="intro">

<div class="card">

<h1>Hieeeee Babyyyy ❤️</h1>

<p class="subtitle">

Before I let you enter...

Say hello to me first. 🥹❤️

</p>

<div class="chat">

<div class="myMsg">

Hieeeee Babyyyy ❤️

</div>

<div id="replyBox">

<input
id="reply"
placeholder="Type Hii Baby ❤️"
>

<button id="sendBtn">

Send ❤️

</button>

</div>

<div id="messages"></div>

</div>

</div>

</div>

<script>

document.getElementById("sendBtn").onclick=function(){

let msg=document.getElementById("reply").value.trim();

if(msg==""){

alert("At least say Hiiiii ❤️");

return;

}

document.getElementById("replyBox").style.display="none";

document.getElementById("messages").innerHTML=`

<div class="hisMsg">${msg}</div>

<div class="myMsg">Happy Boyfriend's Dayyyyy ❤️🥹</div>

<div class="myMsg">I made something only for you...</div>

<div class="myMsg">

<button onclick="alert('Page 1 coming next ❤️')">

Continue ❤️

</button>

</div>

`;

}

</script>

</body>

</html>