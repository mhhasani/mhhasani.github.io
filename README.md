<html lang="en">
<head>
<title>صفحه اصلي</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
box-sizing: border-box;
}
body {
font-family: Arial, Helvetica, sans-serif;
margin: 0;
}
.header {
padding: 80px;
text-align: center;
background: #1abc9c;
color: white;
}
.header h1 {
font-size: 40px;
}
.navbar {
overflow: hidden;
background-color: #333;
position: sticky;
position: -webkit-sticky;
top: 0;
}
.navbar a {
float: left;
display: block;
color: white;
text-align: center;
padding: 14px 20px;
text-decoration: none;
}
.navbar a.right {
float: right;
}
.navbar a:hover {
background-color: #ddd;
color: black;
}
.navbar a.active {
background-color: #666;
color: white;
}
.row {
display: -ms-flexbox; /* IE10 */
display: flex;
-ms-flex-wrap: wrap; /* IE10 */
flex-wrap: wrap;
}
.side {
-ms-flex: 30%; /* IE10 */
flex: 30%;
background-color: #f1f1f1;
padding: 20px;
}
.main {
-ms-flex: 70%; /* IE10 */
flex: 70%;
background-color: white;
padding: 20px;
}
.fakeimg {
background-color: #aaa;
width: 100%;
padding: 20px;
}
.footer {
padding: 20px;
text-align: center;
background: #ddd;
}
@media screen and (max-width: 700px) {
.row {
flex-direction: column;
}
}
@media screen and (max-width: 400px) {
.navbar a {
float: none;
width: 100%;
}
}
</style>
</head>
<body>

<div class="header">
<h1>mhhasani</h1>
<p style="font-weight: bold">Iran University of science & Technology</p>
</div>

<div class="row">
<div class="side">
<h2>About Me</h2>

<img src="https://s17.picofile.com/file/8424221892/my_photo_png.jpg" width="320px" height="410px">

<h3>my name is mohammad hosein hasani</h3>
<p>I am one of the entrants of the Faculty of Computer Engineering of Iran University of Science and Technology in 1399</p>
<h5>My ID in Telegram:</h5>
<h2> <img src="https://farsgraphic.com/wp-content/uploads/2020/07/%D9%85%D8%AC%D9%85%D9%88%D8%B9%D9%87-%D9%84%D9%88%DA%AF%D9%88-%D8%AA%D9%84%DA%AF%D8%B1%D8%A7%D9%85-7.png" width="30px" height="30px">@MHHASANI</h2>

</div>
<div class="main">
<h2>My Github Page</h2>
<p>Hi...</p>
<p>Welcome to my page at GitHub</p>
<br>
<h2>About my city</h2>
<h5>Tehran in Iran</h5>
<img src="https://s16.picofile.com/file/8424233968/tehran.jpg" width=200px" height="200px">
<p>introduction</p>
<p>Tehran is the most populous city and capital of Iran, the capital of Tehran province and the city of Tehran. With a population of 8,693,706, it is the 24th most populous city in the world and the most populous city in West Asia. The metropolis of Tehran is the third most populous metropolis in the Middle East.</p>
</div>
</div>

<div class="footer">
<p style="font-weight: bold"> 
   <font face='Tahoma, Arial,"Times New Roman"' size='+4' color='#ff0000'>Iran University of Science and Technology</font> 
</p>
</div>

</body>
</html>
