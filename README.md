<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>StormTrader Next</title>

<style>
body{
margin:0;
background:#000;
font-family:Arial;
color:white;
text-align:center;
}

header{
padding:20px;
font-size:30px;
font-weight:bold;
color:#ff0033;
background:#111;
}

.hero{
padding:60px 20px;
}

.hero h1{
font-size:38px;
margin-bottom:15px;
}

.hero p{
font-size:18px;
color:#aaa;
}

.btn{
display:inline-block;
margin-top:25px;
padding:16px 35px;
background:#ff0033;
color:white;
text-decoration:none;
border-radius:10px;
font-size:20px;
font-weight:bold;
}

.box{
margin:18px;
padding:22px;
background:#111;
border-radius:14px;
font-size:22px;
}

footer{
padding:40px;
color:#777;
}

/* Floating AI Scanner */
.ai{
position:fixed;
bottom:20px;
right:20px;
width:70px;
height:70px;
border-radius:50%;
background:#00ff99;
box-shadow:0 0 20px #00ff99;
font-size:34px;
display:flex;
justify-content:center;
align-items:center;
animation:pulse 1.2s infinite;
cursor:pointer;
z-index:999;
}

@keyframes pulse{
0%{transform:scale(1);}
50%{transform:scale(1.1);}
100%{transform:scale(1);}
}
</style>
</head>

<body>

<header>⚡ StormTrader Next</header>

<div class="hero">
<h1>Deriv Smart AI Trading</h1>
<p>Connect Deriv account and use AI signals, bot trading & scanner.</p>

<a class="btn" href="#">Sign in with Deriv</a>
</div>

<div class="box">📈 Live Signals</div>
<div class="box">🤖 Auto Bot Trading</div>
<div class="box">💰 Risk Management</div>
<div class="box">📊 Admin Dashboard</div>

<footer>StormTrader Next © 2026</footer>

<div class="ai" onclick="alert('AI Scanner Activated')">🧠</div>

</body>
</html>
