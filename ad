<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Sumera ❤️</title>

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Arial,sans-serif;}
body{
display:flex;
justify-content:center;
align-items:center;
height:100vh;
overflow:hidden;
background:linear-gradient(-45deg,#ff5f9e,#ff8ec7,#ffc2d9,#ff5f9e);
background-size:400% 400%;
animation:bg 8s infinite;
color:white;
text-align:center;
}
@keyframes bg{
0%{background-position:0% 50%;}
50%{background-position:100% 50%;}
100%{background-position:0% 50%;}
}
.card{
width:90%;
max-width:500px;
padding:30px;
border-radius:20px;
background:rgba(255,255,255,.15);
backdrop-filter:blur(12px);
box-shadow:0 0 20px rgba(255,255,255,.4);
}
button{
margin-top:20px;
padding:14px 30px;
border:none;
border-radius:30px;
background:white;
color:#ff2d75;
font-size:18px;
font-weight:bold;
cursor:pointer;
}
#text{
margin-top:20px;
font-size:20px;
line-height:1.8;
white-space:pre-wrap;
}
.heart{
position:absolute;
font-size:22px;
animation:fall linear infinite;
}
@keyframes fall{
0%{transform:translateY(-100px);}
100%{transform:translateY(110vh);}
}
</style>
</head>

<body>

<div class="card">
<h1>❤️ Hey Sumera ❤️</h1>
<p>Ek surprise sirf tumhare liye...</p>

<button onclick="show()">Open ❤️</button>

<div id="text"></div>
</div>

<script>
for(let i=0;i<60;i++){
let h=document.createElement("div");
h.className="heart";
h.innerHTML=["❤️","💕","💖","🌸"][Math.floor(Math.random()*4)];
h.style.left=Math.random()*100+"vw";
h.style.animationDuration=(4+Math.random()*4)+"s";
h.style.animationDelay=Math.random()*5+"s";
document.body.appendChild(h);
}

const msg=`Dear Sumera ❤️

Shayad tumhe kabhi ehsaas na ho...

Lekin tumhari smile meri favourite hai. 😊

Tumhari hasi kisi bhi din ko khoobsurat bana deti hai.

Tum meri life ki sabse special bestie ho. 🌹

Bas ek baat...

Kabhi apni smile mat khona,
kyunki usme kisi ka din khush kar dene ki taqat hai. ✨

Thank you for being you. ❤️

— Ahmad 🌸`;

function show(){
let i=0;
let box=document.getElementById("text");
box.innerHTML="";
let x=setInterval(()=>{
box.innerHTML+=msg.charAt(i);
i++;
if(i>=msg.length){
clearInterval(x);
setTimeout(()=>{
alert("😊 Thank you, Sumera! Stay happy forever ❤️");
},1000);
}
},40);
}
</script>

</body>
</html>
