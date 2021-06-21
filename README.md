### Hi there 👋

<canvas id="myCanvasMatrix" width="500" height="200" style="border:1px solid #c3c3c3;">
Please Upgrade your browser
</canvas>
var c1=document.getElementById("myCanvasMatrix");
var ctx1=c1.getContext("2d");
var Matrix=function(){
ctx1.fillStyle='rgba(0,0,0,.05)';
ctx1.fillRect(0,0,500,500);
ctx1.fillStyle="#0f0";
ctx1.fillText('Matrix', Math.random()*(500), Math.random()*(500));
};
setInterval(Matrix,30);

<!--
**AndreMyszko/AndreMyszko** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
