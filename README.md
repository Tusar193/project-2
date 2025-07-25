<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Create Account</title>
<style>
body {
font-family: Arial, sans-serif;
background-color: #f3f4f6;
display: flex;
justify-content: center;
align-items: center;
height: 100vh;
margin: 0;
}
.form-container {
background-color: #dbe9d8;
padding: 30px;
border-radius: 10px;
box-shadow: 0 4px 8px rgba(0,0,0,0.1);
width: 300px;
}
.form-container h2 {
text-align: center;
margin-bottom: 20px;
}
.social-buttons {
display: flex;
justify-content: center;
gap: 15px;
margin-bottom: 10px;
}
.social-buttons button {
background: white;
border: none;
padding: 10px;
border-radius: 50%;
font-size: 18px;
cursor: pointer;
box-shadow: 0 2px 4px rgba(0,0,0,0.2);
width: 44px;
height: 44px;
display: flex;
align-items: center;
justify-content: center;
}
.social-buttons img {
width: 24px;
height: 24px;
}
.form-container p {
text-align: center;
margin: 10px 0;
color: #333;
font-size: 14px;
}
.form-container input {
width: 100%;
padding: 10px;
margin: 10px 0;
border: none;
border-radius: 6px;
box-sizing: border-box;
font-size: 14px;
}
.form-container button.signup {
width: 100%;
padding: 10px;
background-color: #7f977b;
color: white;
border: none;
border-radius: 6px;
font-weight: bold;
font-size: 14px;
cursor: pointer;
}
.form-container button.signup:hover {
background-color: #6b836c;
}
</style>
</head>
<body>
<div class="form-container">
<h2>CREATE ACCOUNT</h2>
<div class="social-buttons">
<button title="Sign up with Google">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg"
alt="Google" />
</button>
<button title="Sign up with Facebook">
<img
src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/facebook/facebook-original.svg"
alt="Facebook" />
</button>
</div>
<p>or use your email for registration</p>
<form>
<input type="text" placeholder="Username" required />
<input type="email" placeholder="Email" required />
<input type="password" placeholder="Password" required />
<button type="submit" class="signup">SIGN UP</button>
</form>
</div>
</body>
</html>
