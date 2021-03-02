<html>
<head>
<title>HTML CSS</title>
<link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Aldrich" />
<style>
body
{
background-color:#D3D3D3;
}
h1
{
border: 4px solid black;
text-align:center;
}
h2
{
color:purple
}
input
{
border: 5px solid darkblue
}
#textblock
{
border:5px solid gray;
width:800px;
height:400px;
}
a
{
color: red
}
* 
{
font-family:Aldrich, sans-serif;
}
</style>
</head>
<body>
<h1>Welcome to Puppy Blog!</h1>
<p>Thanks so much for visiting this site!</p>
<h2>What is this site for?</h2>
<p>This site can do three things:</p>
<ol>
<li>Take in text input</li>
<li>Take in Log In Information</li>
<li><a href="https://www.google.com/">Take you to Google so you can search for pups!</a></li>
</ol>
<h2>Please log in to save your blog post</h2>
<form>
Email:<input type='email'>
Password:<input type='password'>
<input type='submit' value="Log In">
</form>
<p>Questions or Comments? Send us feedback here:</p>
<textarea id='textblock'></textarea>
</body>
</html>
