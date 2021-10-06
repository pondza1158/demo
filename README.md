<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="page.css">
</head>
<body>
    
</body>
</html>

<div class="container bg">
  <div class="navBar">
    <div class="logo"></div>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Booking</a></li>
      <li><a href="login.html">Admin</a></li>
      <li><a href="#">Logout</a></li>
    </ul>
  </div>

  <div class="content">
    <div class="khonkaen" style="width:50%;">
      <div class="tnx">
        <h2><i class="fas fa-map-marker-alt"></i> Thailand</h2>
      </div>
      <div class="txt">
        <h3>Welcome To KhonKaen </h3>
      </div>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Libero voluptatem iure sunt praesentium repellat, quaerat, non at quam, saepe fugit labore consequuntur sequi repudiandae ab adipisci quae distinctio dolorem ducimus?</p>
    </div>
    <div class="card" style="width:50%;">
      <div class="box1"> 
      </div>
      <div class="box2">  
      </div>
      <div class="box3">  
      </div>
      <div class="box4">
      </div>
    </div>
  </div>

</div>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: arial;
  }
  * a {
    text-decoration: none;
  }
  * li {
    list-style: none;
  }
  .container {
    min-height: 100vh;
    margin: 0 auto;
    position: relative;
  }
  .bg {
    position: relative;
    width: 100%;
    height: 100%;
  }
  .bg::after {
    content: "";
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    position: absolute;
    z-index: -1;
    filter: brightness(45%);
    background-image: url("https://www.salika.co/wp-content/uploads/2021/07/khonhaen2.jpg");
    background-size: cover;
    background-position: center;
  }
  .navBar {
    display: flex;
    width: 85%;
    justify-content: space-between;
    margin: 0 auto;
    align-items: center;
    height: 15vh;
  }
  .navBar ul {
    display: flex;
    align-items: center;
  }
  .navBar ul li {
    padding: 0 25px;
  }
  .navBar ul li a {
    font-size: 1rem;
    color: #fff;
    font-weight: 400;
    letter-spacing: 1.5px;
  }
  .navBar .logo a {
    font-size: 2.3rem;
    color: #fff;
  }
  .content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 85%;
    position: absolute;
    top: 60%;
    left: 50%;
    transform: translate(-50%, -50%);
    align-items: center;
  }
  .khonkaen {
    color: rgb(255, 255, 255);
    padding: 25px;
  }
  .card {
    display: grid;
    grid-template-columns: auto auto;
    grid-gap: 20px;
  }
  .card h2 {
    color: #fff;
    position: absolute;
    bottom: 15px;
    left: 20px;
    font-size: 1.6rem;
    letter-spacing: 1px;
  }
  .card .box1,
  .box2,
  .box3,
  .box4 {
    width: 90%;
    height: 220px;
    background-position: center;
    background-size: cover;
    position: relative;
    border-radius: 25px;
    cursor: pointer;
  }
  .box1 {
    background-image: url("http://sabaihotel.co.th/cr/wp-content/uploads/2018/02/KingSizeBed.jpg");
  }
  .box2 {
    background-image: url("https://gallerydesignhotel.com/wp-content/gallery/deluxe-double/thumbs/thumbs_4.jpg");
  }
  .box3 {
    background-image: url("https://gallerydesignhotel.com/wp-content/gallery/deluxe-double/1.jpg");
  }
  .box4 {
    background-image: url("http://sabaihotel.co.th/cr/wp-content/uploads/2018/02/sabai.jpg");
  }
  .phuket h2 {
    font-size: 2rem;
    letter-spacing: 2.8px;
  }
  .text {
    display: flex;
    justify-content: flex-start;
    align-items: center;
  }
  .txt  {
    font-size: 3rem;
  }
  .phuket p {
    opacity: 0.4;
  }
  .tnx h2 i {
    color: #fd7e13;
  }
  .card div {
    transition: 0.5s;
  }
  .card div:hover {
    transition: 0.3s;
    transform: translateY(-10px);
    box-shadow: 0 19px 38px rgba(231, 222, 222, 0.3), 0 15px 12px rgba(0, 0, 0, 0.22);
  }
  


 

