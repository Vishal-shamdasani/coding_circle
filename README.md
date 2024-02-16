<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous"/>
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Coading Circle</title>
<style>
    /* Reset styles */
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        font-family: Arial, sans-serif;
        background-color: #010002;
        margin: 0;
    }

    /* Header styles */
    header {
        background-color: #333;
        color: white;
        text-align: center;
        padding: 20px;
    }

    /* Navigation styles */
    nav {
        background-color: #444;
        padding: 10px;
        text-align: center;
    }

    nav ul {
        list-style-type: none;
        padding: 0;
        margin: 0;
    }

    nav ul li {
        display: inline;
        margin: 0 10px;
    }

    nav ul li a {
        color: white;
        text-decoration: none;
        padding: 10px 20px;
        border-radius: 5px;
    }

    nav ul li a:hover {
        background-color: #666;
    }

    /* Main content styles */
    .container {
        max-width: 1200px;
        margin: 20px auto;
        padding: 0 20px;
    }
    .cour{
        color: white;
    }

    .course {
        background-color: #fff;
        border-radius: 5px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        padding: 20px;
        margin-bottom: 20px;
    }

    .course h2 {
        color: #333;
    }

    .course p {
        color: #666;
    }

    /* Footer styles */
    footer {
        background-color: #333;
        color: white;
        text-align: center;
        padding: 20px;
    }
    .marg {
        margin:15px;
        border-radius:2px;
    }
  
</style>
</head>
<body>
<header>
    <h1>Coading Circle</h1>
</header>

<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#courses">Courses</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<div class="container">
    <h1 class="cour"> Courses </h1>
    <!--<div class="course">
        <h2>Course Title 1</h2>
        <p>Description of the course...</p>
        <a href="#">Enroll Now</a>
    </div>
    <div class="course">
        <h2>Course Title 2</h2>
        <p>Description of the course...</p>
        <a href="#">Enroll Now</a>
    </div>
    Add more courses here -->
    <div class = "d-flex flex-row justify-content-center">
        <div class = "marg">
        <div class="card" style="width: 18rem;">
            <img src="https://topviecit.vn/blog/wp-content/uploads/2021/11/thumb-5.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Html Basics To Advance</h5>
              <p class="card-text">Html is required in Basic web Developenment.</p>
              <a href="#" class="btn btn-primary">Enroll Now</a>
            </div>
          </div>
        </div>
        <div class = "marg">
          <div class="card" style="width: 18rem;">
            <img src="https://www.ntuclearninghub.com/documents/39367/4216797/Python-Symbol.png/369e410e-a90f-f887-c2dc-61f7ef761476/" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Python </h5>
              <p class="card-text">Python is a high-level, interpreted programming language known for its simplicity, versatility.</p>
              <a href="#" class="btn btn-primary">Enroll Now</a>
            </div>
          </div>
        </div>
        <div class = "marg">
          <div class="card" style="width: 18rem;">
            <img src="https://miro.medium.com/v2/resize:fit:2000/1*y6C4nSvy2Woe0m7bWEn4BA.png" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">React js</h5>
              <p class="card-text">React.js is a JavaScript library for building user interfaces, focusing on component-based development and efficient rendering.              </p>
              <a href="#" class="btn btn-primary">Enroll Now</a>
            </div></div>
          </div><div class = "marg">
          <div class="card" style="width: 18rem;">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLBP_TgL_b88N68OQ8Vv9OKhWsnWw-yj5K2GaZ8blLIL7Yz0JBzEY1SnrBcvSkWSf0pBg&usqp=CAU" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Java Fundamentals</h5>
              <p class="card-text">Java is a versatile, object-oriented programming language known for its portability, robustness, security features</p>
              <a href="#" class="btn btn-primary">Enroll Now</a>
            </div>
          </div>
    </div></div>
</div>

<div class="container">
    <h1 class="cour"> Events </h1>
    <!--<div class="course">
        <h2>Course Title 1</h2>
        <p>Description of the course...</p>
        <a href="#">Enroll Now</a>
    </div>
    <div class="course">
        <h2>Course Title 2</h2>
        <p>Description of the course...</p>
        <a href="#">Enroll Now</a>
    </div>
    Add more courses here -->
    <div class = "d-flex flex-row justify-content-center">
        <div class="card" style="width: 18rem;">
            <img src="..." class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary"></a>
            </div>
          </div>
          <div class="card" style="width: 18rem;">
            <img src="..." class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary"></a>
            </div>
          </div>
          <div class="card" style="width: 18rem;">
            <img src="..." class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary"></a>
            </div>
          </div>
          <div class="card" style="width: 18rem;">
            <img src="..." class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary"></a>
            </div>
          </div>
    </div>
</div>
</div>
<footer>
    <p>&copy; 2024 Educational Learning Website. All rights reserved.</p>
</footer>

</body>
</html>
