# Banoqabil-website-draft-
assignment class 7 


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    body{
        margin: 0px;
    }
    #header {
        background-color: rgb(209, 211, 210);
        height: 60px;
        padding: 20px;
        width: 100%;
        display: inline-flex;
        padding: 20px;
        align-items: center;


    }

    #header img {
        border-radius: 80px;
        border: 1px solid black;

    }

    #hero {
        background-image: url(img/banner_1.jpeg);
        height: 600px;
        width: 100%;
        background-repeat: no-repeat;
        background-size: cover;

    }

    #footer {
        background-color: rgb(205, 255, 231);
        height: 250px;
        width: 100%;
        display: inline-flex;

    }

    .section-text {
        color: rgb(252, 248, 248);
    }

    .h1-title {
        font-size: 85px;
        text-decoration: underline;
        text-decoration-style: double;
        text-decoration-color: rgb(0, 0, 0);
        text-align: center;

    }

    li {
        font-size: 15px;
        color: rgb(6, 6, 6);
        font-family: 'Times New Roman', Times, serif;
        font-weight: 900;
        padding: 20px;
        text-transform: capitalize;
        text-align: center;
    }

    a {
        text-decoration: none;
    }

    .nav-bar {
        display: inline-flex;
        width: 60%;
    }

    .logo {
        width: 20%;
    }

    .btn {
        width: 30%;
        margin-left: 60px;
    }

    .btn-head {
        background-color: rgb(75, 139, 55);
        color: white;
        padding: 10px 30px;
        border-radius: 10px;
        font-size: 16px;
        text-align: right;
    }

    .main-box {
        display: inline-flex;
        width: 80%;
        
        
    }

    .box {
        width: 33.3%;
        background-color: rgb(255, 255, 255);
        border: 1px solid #000000;
        border-radius: 10px;
        margin: 10px;
      
    }
    .Impact{
        background-color: #1a1a1a;
        text-align: center;
        padding:  80px 0px;
        margin: 0px;
    }
    .imp-h2 , .imp-p{
    color: white;
    line-height: 12px;
    }
    .imp-box{
        width: 80%;
        display: inline-flex;
        padding-top: 20px;
        
        
    }
    .imp-box1{
        width: 20%;
        border: 1px solid wheat ;
        margin: 10px;
        padding: 40px 20px;
        border-radius: 20px;
        background-color: #85808035;

    }
    .imp-num{
        color: #2d8e84;
        font-size: 28px;
    line-height: 2px;    }
    .imp-p{
        color: white;
        font-size: 20px;
        line-height: 25px
    }
    .box-img1{
        background-image: url(img/ittraining.jpeg);
        height: 250px;
        background-position: center;
        background-size: cover;
        border-radius: 10px 10px 0px 0px;
    
    }
    .box-text{
        padding: 20px;
    }
#section-2{

    text-align: center;
}
</style>

<body>
    <div id="header">
        <div class="logo"> <img
                src="data:image/png;base64,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"
                alt="banoqabil logo " width="100" height="100">
        </div>
        <ul style="list-style-type: none;" class="nav-bar">
            <a href="">
                <li>Home</li>
            </a>
            <a href="">
                <li>About us</li>
            </a>
            <a href="">
                <li>Contact us </li>
            </a>
            <a href="">
                <li>Courses</li>
            </a>
            <a href="">
                <li>Contact us </li>
            </a>
            <a href="">
                <li>Campuses </li>
            </a>
            <a href="">
                <li>Students</li>
            </a>
        </ul>
        <div class="btn">
            <button class="btn-head" type="">Register Now </button>

        </div>
    </div>
    <div id="Section">
        <div id="hero"></div>
        <div class="Impact">
            <h2 class="imp-h2">Transforming Lives Through <span style="color: #2d8e84;">Education</span> 
            </h2>
            <p class="imp-p">Join thousands who have already started their journey to success

            </p>
<div class="imp-box">
    <div class="imp-box1">
        <h3 class="imp-num">
            75,000+</h3>
            <p class="imp-p">Students Trained</p>

    </div>
    <div class="imp-box1"> <h3 class="imp-num">
        50+
</h3>
<p class="imp-p">Students Trained</p>

</div>
    <div class="imp-box1"> <h3 class="imp-num">
    06</h3>
    <p class="imp-p"> Students Trained</p>

</div>
    <div class="imp-box1"> <h3 class="imp-num">
       29</h3>
       <p class="imp-p">Students Trained</p>

    </div>
    <div class="imp-box1"> <h3 class="imp-num">

        100K+</h3>
    
        <p class="imp-p">Students Trained</p>

    </div>
</div>
        </div>
        <div id="section-2">
            <div class="main-box">
                <div class="box">
                <div class="box-img1"></div>
                <div class="box-text">
                    <h3>MUHAMMAD ALI </h3>
                    <p>Master the digital landscape with our industry-aligned curriculum. We bridge the gap between academic theory and technical proficiency.</p></div>
                </div>
                <div class="box">
                    <div class="box-img1"></div>
                    <div class="box-text">
                        <h3>MUHAMMAD ALI </h3>
                        <p>Master the digital landscape with our industry-aligned curriculum. We bridge the gap between academic theory and technical proficiency.</p></div>
                    </div>
                    <div class="box">
                        <div class="box-img1"></div>
                        <div class="box-text">
                            <h3>MUHAMMAD ALI </h3>
                            <p>Master the digital landscape with our industry-aligned curriculum. We bridge the gap between academic theory and technical proficiency.</p></div>
                        </div>
            </div>
        </div>
    </div>

    <div id="footer">

        <div class="logo"> <img
            src="data:image/png;base64,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"
            alt="banoqabil logo " width="100" height="100">
    </div>
        <div class="footer-content">
            <div class="footer-links">
                <a href="#home">Home</a> <br>
                <a href="#about">About Us</a><br>
                <a href="#program">Programs</a> <br>
                <a href="#gallery">Gallery</a> <br>
                <a href="#courses">Courses</a><br>
                <a href="#register">Register</a><br>
                <a href="#branches">Branches</a><br>
                <a href="#contact">Contact</a><br>
            </div>
            <p>&copy; 2024 Bano Qabil. All Rights Reserved | Empowering Pakistan's Future</p>
            <p>📧 info@banoqabil.org | 📞 0321-1234567</p>
        </div>
        <div id="Popular courses">
            <a href=" Web Development"> web development</a>
            <a href=" e-commerce "> e-commerce </a>
        </div>
        

</div>

           
</body>

</html>
