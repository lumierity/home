<style>
{
    box-sizing: border-box;
}

body {
    font-family: Montserrat, Lato, sans-serif;
    margin: 0;
}

.header {
    padding: 20px;
    text-align: center;
    background: #ffffff;
    color: black;
}

.header h1 {
    font-size: 40px;
}

.navbar {
    overflow: hidden;
    background-color: #333;
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

.vertical-menu {
    width: 200px;
}

.vertical-menu a {
    background-color: #fff; 
    color: black;
    display: block; 
    padding: 5px; 
    text-decoration: none; 
}

.vertical-menu a:hover {
    background-color: #ccc; 
}

.vertical-menu a.active {
    background-color: #fff;
    color: black;
}

.row {  
    display: -ms-flexbox; 
    display: flex;
    -ms-flex-wrap: wrap; 
    flex-wrap: wrap;
}

.side {
    -ms-flex: 30%;
    flex: 30%;
    background-color: #f1f1f1;
    padding: 20px;
}

.main {   
    -ms-flex: 70%; 
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
    
<div class="vertical-menu">
  <a href="#">Home</a>
  <a href="#">About</a>
  <a href="#">Blog</a>
  <a href="#">What we're reading/craving</a>
  <a href="#">Contact</a>
</div>

<div class="header">
  <h1>Lumierity</h1>
  <p>Local &  on-budget marketing solutions.</p>
</div>

<div class="row">
  <div class="side">
      <h2>About Me</h2>
      <h5>Photo of me:</h5>
      <div class="fakeimg" style="height:200px;">Image</div>
      <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      <h3>More Text</h3>
      <p>Lorem ipsum dolor sit ame.</p>
      <div class="fakeimg" style="height:60px;">Image</div><br>
      <div class="fakeimg" style="height:60px;">Image</div><br>
      <div class="fakeimg" style="height:60px;">Image</div>
  </div>
 
 <div class="main">
      <h2>TITLE HEADING</h2>
      <h5>Title description, Dec 7, 2017</h5>
      <div class="fakeimg" style="height:200px;">Image</div>
      <p>Some text..</p>
      <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
      <br>
      <h2>TITLE HEADING</h2>
      <h5>Title description, Sep 2, 2017</h5>
      <div class="fakeimg" style="height:200px;">Image</div>
      <p>Some text..</p>
      <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
  </div>
</div>

<div class="footer">
  <h2>Footer</h2>
</div>

</body>
</html>
