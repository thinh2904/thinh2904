### TAU LÀ THỊNH 🖕👌
### 🖕🖕🖕TAU CÓ 1 CÁI THƯ VIỆN CHƠI CHỨNG KHOÁN AUTO WIN🖕🖕🖕
### 🖕🖕🖕MÀY TẢI ĐƯỢC THÌ CHO MÀY XÀI LUÔN🖕🖕🖕
<!--
**thinh2904/thinh2904** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

#🔭 I’m currently working on ...
#🌱 I’m currently learning ...
#👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Document</title>
</head>
<body>
<style>
.back {
position: fixed;
padding: 0;
margin: 0;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: white;
animation-name: backdiv;
animation-duration: 1s;
animation-iteration-count:infinite;
}
.heart {
position: absolute;
margin: auto;
top: 0;
right: 0;
bottom: 0;
left: 0;
background-color: pink;
height: 50px;
width: 50px;
transform: rotate(-45deg);
animation-name: beat;
animation-duration: 1s;
animation-iteration-count:infinite;
}
.heart:after {
background-color: pink;
content: "";
border-radius: 50%;
position: absolute;
width: 50px;
height: 50px;
top: 0px;
left: 25px;
}
.heart:before {
background-color: pink;
content: "";
border-radius: 50%;
position: absolute;
width: 50px;
height: 50px;
top: -25px;
left: 0px;
}
@keyframes backdiv {
50% {
background: #ffe6f2;
}
}
@keyframes beat {
0% {
transform: scale(1) rotate(-45deg);
}
50% {
transform: scale(0.6) rotate(-45deg);
}
}
</style>
<div class="back"></div>
<div class="heart"></div>
</body>
</html>
