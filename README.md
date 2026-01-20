<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Khushi ❤️ Valentine</title>

<style>
body{
    margin:0;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(135deg,#ff9a9e,#fad0c4);
    text-align:center;
    color:#fff;
}
.container{
    padding:40px 20px;
}
h1{
    font-size:32px;
    margin-bottom:10px;
}
p{
    font-size:18px;
    line-height:1.6;
}
.heart{
    font-size:60px;
    animation: beat 1s infinite;
}
@keyframes beat{
    0%,100%{transform:scale(1);}
    50%{transform:scale(1.2);}
}
.buttons{
    margin-top:30px;
}
button{
    padding:12px 30px;
    font-size:18px;
    border:none;
    border-radius:30px;
    cursor:pointer;
}
#yes{
    background:#ff4d6d;
    color:white;
}
#no{
    background:#fff;
    color:#ff4d6d;
    position:absolute;
}
#message{
    margin-top:30px;
    font-size:22px;
    display:none;
}
</style>
</head>

<body>
<div class="container">
    <div class="heart">❤️</div>
    <h1>Khushi</h1>

    <p>
    तुम मेरी ज़िंदगी का वो हिस्सा हो  
    जिसके बिना हर खुशी अधूरी लगती है।  
    तुम्हारी मुस्कान मेरी ताकत है  
    और तुम्हारी बातें मेरा सुकून 💖
    </p>

    <h2>क्या तुम मेरी Valentine बनोगी? 💌</h2>

    <div class="buttons">
        <button id="yes" onclick="yesClicked()">हाँ 💕</button>
        <button id="no" onmouseover="moveNo()">नहीं 🙈</button>
    </div>

    <div id="message">
        💞 यायyy!  
        Khushi, तुमने मेरी ज़िंदगी को और भी ख़ास बना दिया ❤️  
        I Love You Forever 💖
    </div>
</div>

<script>
function yesClicked(){
    document.getElementById("message").style.display="block";
}
function moveNo(){
    let x = Math.random()*300;
    let y = Math.random()*300;
    let no = document.getElementById("no");
    no.style.left = x+"px";
    no.style.top = y+"px";
}
</script>

</body>
</html>
