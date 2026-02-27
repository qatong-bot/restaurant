<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>智能餐厅登录</title>
<style>
body{margin:0;font-family:-apple-system,BlinkMacSystemFont,sans-serif;background:#f4f6f9;display:flex;justify-content:center;align-items:center;height:100vh;}
#loginCard{background:white;padding:30px 25px;border-radius:12px;box-shadow:0 6px 15px rgba(0,0,0,0.1);width:320px;display:flex;flex-direction:column;gap:15px;}
h2{text-align:center;color:#ff6b6b;}
input{padding:10px;border-radius:6px;border:1px solid #ccc;width:100%;}
button{padding:10px;border:none;border-radius:6px;background:#ff6b6b;color:white;font-weight:bold;cursor:pointer;transition:0.2s;}
button:hover{background:#e05555;}
.error{color:red;font-size:14px;display:none;}
.register{font-size:14px;text-align:center;color:#555;}
.register a{color:#ff6b6b;text-decoration:none;}
.register a:hover{text-decoration:underline;}
</style>
</head>
<body>
<div id="loginCard">
<h2>智能餐厅登录</h2>
<input type="text" id="username" placeholder="用户名">
<input type="password" id="password" placeholder="密码">
<div class="error" id="errorMsg">用户名或密码错误</div>
<button onclick="login()">登录</button>
<div class="register">还没有账号？<a href="#" onclick="register()">注册</a></div>
</div>

<script>
function generateUUID() {
  return 'xxxx-xxxx-xxxx-xxxx'.replace(/[x]/g,()=>Math.floor(Math.random()*16).toString(16));
}

function login(){
  const u=document.getElementById("username").value.trim();
  const p=document.getElementById("password").value.trim();
  const err=document.getElementById("errorMsg");
  if(!u||!p){err.innerText="请输入用户名和密码"; err.style.display="block"; return;}
  let members=JSON.parse(localStorage.getItem("members"))||{};
  if(members[u] && members[u].password===p){
    localStorage.setItem("currentUser",u);
    window.location.href="index.html";
  }else{
    err.innerText="用户名或密码错误"; err.style.display="block";
  }
}

function register(){
  const u=prompt("请输入新用户名：");
  if(!u) return;
  const p=prompt("请输入密码：");
  if(!p) return;
  let members=JSON.parse(localStorage.getItem("members"))||{};
  if(members[u]){alert("用户名已存在"); return;}
  members[u]={id:generateUUID(),username:u,password:p,orders:[],points:0};
  localStorage.setItem("members",JSON.stringify(members));
  alert("注册成功，请登录");
}
</script>
</body>
</html>
