<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <script src="https://kit.fontawesome.com/2417d95f95.js" crossorigin="anonymous"></script>
<style>
* {
    box-sizing: border-box;
}
.nav{
    overflow: auto;
    background-color: rgb(32, 36, 32);
    text-align: center;
    width: 100%;
    position: fixed;
    top: 0;
    width: 100%;
}
.nav a {
    float: left;
    display: block;
    padding: 16px 16px;
    text-decoration: none;
    color: white;
}
.header {
    float:left;
    padding: 70px;
    width: 100%;
    text-align: center;
    font-size: 20px;
    background-color: rgb(238, 238, 238);
    font-family: 'Times New Roman', Times, serif;
}
.border{    
    border-style: dotted;
    border-width: 3px;
    border-color:  rgb(84, 84, 84); 
}
.body {
    float: left;
    padding: 50px;
    background-color:rgb(32, 36, 32) ;
    text-align: center;
    color: white;
    font-family: 'Courier New', Courier, monospace;
    width: 100%;
}
.container{
        padding: 8px 10px;
        background-color: white;
        color: black;
}
.picture{
    float: left;
    height: auto;
    width: 100%;
    padding: 20px;
    background-color: white;
    font-family: 'Courier New', Courier, monospace  ;
}
.contact{
    float:left;
    padding:30px;
    background-color: rgb(32, 36, 32);
    width:100%;
    color: white;
    font-family: 'Courier New', Courier, monospace;
}
.icons {
    font-size: medium;
    font-family: 'Courier New', Courier, monospace;
}
.footer{
    float: left;
    padding:1px;
    background-color:rgb(32, 36, 32) ;
    width: 100%;
    text-align: center;
    color: white;
}

</style>
</head>
<body>

<div class="nav">
    <a href="#Home"><i class="fa-solid fa-house"></i> Home</a>
    <a href="#about"><i class="fa-solid fa-user"></i> About me</a>
    <a href="#pic"><i class="fa-solid fa-camera"></i> Photos</a>
    <a href="#contact"><i class="fa-solid fa-phone"></i> Contacts</a>
</div>

<div class="header" id="Home">
    <div class="border">
        <h1> PORTFOLIO</h1>
        <p> Welcome!</p>
    </div>
</div>
<!-- background image-->

<div class="body" id="about">
    <h1>VALERIE P. BUTAC</h1>
        <hr><br>
    <h2>About Me</h2>
    <p>Hi! I am Valerie Butac. I am a Grade 12 student who is pursuing her dream career. I am motivated by my passion to study computer programming and create my own programs. I became interested in this area because I've always wondered how people develop the applications and software with which we interact on a daily basis. Despite understanding that this field is difficult, it motivates me to learn and take on the challenge. There is still a long road ahead of me until I achieve this dream, but with the help of my family and friends as pillars of support and sources of strength, I will continue to strive and be the best version of myself. </p>
<div> <br>
    <h2>Skills</h2>
    <p> Mag-Overthink</p>
    <div class="container" style="width: 100%">100%</div>
    <p> Mag-panic </p>
    <div class="container" style="width: 80%">80%</div>
    <p> Gaslighter</p>
    <div class="container" style="width:10%">10%</div>
</div>
</div>

<div class="picture" id="pic">
    <h2>My Photos</h2>
    <hr>
        <img src="D:\Users\valerie.butac\Pictures\OIP (1).jpg" width="200" height="200">
        <img src="D:\Users\valerie.butac\Documents\Portfolio_VB\98.jpg" width="200" height="200"><br>
        <img src="D:\Users\valerie.butac\Documents\Portfolio_VB\R.jpg" width="200" height="200">
        <img src="D:\Users\valerie.butac\Documents\Portfolio_VB\t.jpg" width="200" height="200"> 
    <!-- lagyan ng code kung saan pwede siyang ma-click and load more button-->
    <!-- Can add pagination-->
</div>

<div class="contact" id="contact">
    <h2> Contacts</h2><hr>
        <div class="icons">
            <p><i class="fa-solid fa-location-dot"></i> Metro Manila, Philippines</p>
            <p><i class="fa-solid fa-phone"></i> Phone: +63 9154374900</p> 
            <p><i class="fa-solid fa-envelope"></i> butacvalerie14@gmail.com</p>
            <p><i class="fa-brands fa-facebook"></i> Valerie Butac</p>
            <p><i class="fa-brands fa-instagram"></i> val_butac</p>
        </div>
</div>

<div class="footer">
    <div class="icons">
    <i class="fa-brands fa-square-facebook"></i>
    <i class="fa-brands fa-instagram"></i>
    <i class="fa-brands fa-github"></i>
    </div>
</div>
    
</div>
</body>
</html>
