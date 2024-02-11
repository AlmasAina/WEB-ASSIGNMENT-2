# WEB-ASSIGNMENT-2

Menu.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pizza-landng-page</title>
    <link rel="stylesheet" href="ass2.css">
</head>

<body class="background">
    <nav id="navbarr">
        <h3 id="intro">Pizza Delight</h3>

        <div class="fire"> </div>

        <ul class="n">
            <li><a href="/contact.html">Contact</a></li>
            <li><a href="/order.html">Order Online</a></li>
            <li><a href="/special.html">Special</a></li>
            <li><a href="/ass2.html">Menu</a></li>
        </ul>
        <div class="cart"> </div>
    </nav>

</body>

</html>


Special.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pizza-landng-page</title>
    <link rel="stylesheet" href="ass2.css">

</head>

<body>
    <nav id="navbarr">
        <h3 id="intro">Pizza Delight</h3>

        <div class="fire"> </div>

        <ul class="n">
            <li><a href="/contact.html">Contact</a></li>
            <li><a href="/order.html">Order Online</a></li>
            <li><a href="/special.html">Special</a></li>
            <li><a href="/ass2.html">Menu</a></li>
        </ul>
        <div class="cart"> </div>
    </nav>
    <h1 class="pg2_heading">Today's Specials</h1>
    <div>
        <div class="pg2_imgs img1">
            <img src="pizza-recipe-1.jpg" alt="not found" width="300px" height="250px">
        </div>
        <div class="pg2_imgs img2">
            <img src="pizza-recipe-1.jpg" alt="not found" width="300px" height="250px">
        </div>
        <div class="pg2_imgs img3">
            <img src="pizza-recipe-1.jpg" alt="not found" width="300px" height="250px">
        </div>
        <div id="title_2">
            <h2 class="pg2_title">Supreme Pizza</h2>
            <h2 class="pg2_title mar">Margherita Pizza</h2>
            <h2 class="pg2_title mar1">Vegetarian Pizza</h2>
        </div>
    </div>

    <h1 class="pg2_heading">What Our Customers Say</h1>
    <p class="para_pg2">"Pizza is the circle. Pizza is my life. Pizza is the circle of life."</p>
    <h4 class="author_pg2"><i>--ED Sheeran--</i></h4>
    <p class="para_pg2">"There is no better feeling in the world than a warm pizza box in your lap."</p>
    <h4 class="author_pg2"><i>--Bteve Hartin--</i></h4>
</body>

</html>

Order.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pizza-landng-page</title>
    <link rel="stylesheet" href="ass2.css">
</head>

<body>
    <nav id="navbarr">
        <h3 id="intro">Pizza Delight</h3>

        <div class="fire"> </div>

        <ul class="n">
            <li><a href="/contact.html">Contact</a></li>
            <li><a href="/order.html">Order Online</a></li>
            <li><a href="/special.html">Special</a></li>
            <li><a href="/ass2.html">Menu</a></li>
        </ul>
        <div class="cart"> </div>
    </nav>
    <h1 class="pg3_heading">Ready to order?</h1>
    <p class="para_pg3">Experience the taste of Perfection. Order now and enjoy a delightful experience!</p>
    <input type="button" value="Order Now" class="btn">
    <div class="head_div">
        <div class="divisions">
            <h3 class="heading_pg3">Quality Ingredients</h3>
            <p>We use only the finest and freshest ingredients to craft our delicious pizzas.</p>
        </div>
        <div class="divisions">
            <h3 class="heading_pg3">Customization Options</h3>
            <p>Customize your pizza with a variety of toppings, sauces, and crust options to suit your taste.</p>
        </div>
        <div class="divisions">
            <h3 class="heading_pg3">Fast Delivery</h3>
            <p>Enjoy quick and reliable delivery services to savor your pizza at its best.</p>
        </div>
    </div>
</body>

</html>

Contact.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pizza-landng-page</title>
    <link rel="stylesheet" href="ass2.css">
</head>

<body>
    <nav id="navbarr">
        <h3 id="intro">Pizza Delight</h3>

        <div class="fire"> </div>

        <ul class="n">
            <li><a href="/contact.html">Contact</a></li>
            <li><a href="/order.html">Order Online</a></li>
            <li><a href="/special.html">Special</a></li>
            <li><a href="/ass2.html">Menu</a></li>
        </ul>
        <div class="cart"> </div>
    </nav>

    <h1 class="pg4_heading">Contact Us</h1>

    <form action="backend.php" class="form">
        <label for="name">Your Name: </label>
        <input type="text" name="name" class="in" id="name" placeholder="Almas Aina" required>

        <label for="email">Your Email: </label>
        <input type="email" name="email" class="in" id="email" placeholder="almasaina@example.com" required>

        <label for="phone">Your Phone Number: </label>
        <input type="text" name="phone" class="in" id="phone" placeholder="Format: 123-456-7890" required>

        <label for="msg">Your Message: </label>
        <textarea name="msg" id="msg" class="in" cols="30" rows="7" placeholder="Type your message here...."></textarea>
        <div class="sbm">
            <input type="submit" value="Submit" class="submit">

            <input type="reset" value="Reset" class="submit">
        </div>
    </form>

    <footer class="foot">
        <p>&copy; 2024 Pizza Delight All rights reserved.</p>
    </footer>
</body>

</html>

Style.css
/*--------------------------------------- MENU --------------------------------- */
* {
    background-repeat: no-repeat;
    background-size: 100%;
    margin: 0px;
    background-size: cover; 
    padding: 0px;
}

/* first page background   */
.background {
    background-image: url('pizza-recipe-1.jpg');
}

/* navbar  */

#intro {
    float: left;
    font-weight: bolder;
    font-size: 25px;
    margin-top: 7px;
    margin-right: 2px;

}

.fire {
    margin-top: 5px;
    background-repeat: no-repeat;
    float:left;
    margin-left: 30px;
    width: 30px;
    height: 30px;
    background-image: url('fire.png');
    background-size: contain;
}

.cart {
    margin-top: 5px;
    margin-right: 4px;
    background-repeat: no-repeat;
    width: 30px;
    height: 30px;
    background-image: url('cart.jpg');
    background-size: contain;
    float: right;
}

#navbarr {
    background-color: rgb(184, 50, 2);
}

#navbarr ul {
    list-style: none;
    padding: 0px;
    margin: 0px;
    margin-left: 720px;
}

#navbarr ul li {
    float: right;
    list-style: none;
    text-align: center;
    font-size: 15px;
    font-weight: bolder;
}

#navbarr ul li a {
    display: block;
    padding: 10px 15px;
    margin-top: 2px;
    color: black;
    text-decoration: none;
}

#navbarr ul li a:hover, #navbarr ul li a:active{
    background-color: rgb(221, 51, 9);
    border-radius: 30px;
    color: rgb(255, 255, 255);
}

.n {
    display: inline-block;
}

/* -------------------------------------------Specials--------------------------------- */

.pg2_heading{
    margin: 8px;
    font-size: 40px;
    text-align: center;
}

.pg2_imgs{
    display: inline-block;
    margin:45px;
    margin-top: 30px;
    margin-bottom: 0px;
    padding:15px;
    background-size: contain;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
    
}
.img1:hover{
    transition: transform 3s ease;
    transform: rotate(-359deg);
}
.img2:hover{
    transform:scaleX(-1) translateY(0);
    
    transition: transform 2s ease;
}
.img3:hover{
    transition: transform 3s ease;
    transform: rotate(359deg);
}
.pg2_title{
    display:inline-block;
    margin:115px;
    margin-top: 5px;
    margin-bottom: 0px;
    padding:10px;
}
.mar{
    margin-left: 140px;
}
.mar1{
    margin-left: 110px;
}
.para_pg2{
    margin-top:15px;
    text-align: center;
    font-size: larger;
}
.author_pg2{
    text-align: center;
    font-size: larger;
    font-weight: 1000px;
}

/* ------------------------------------Order----------------------------------------- */
.pg3_heading{
    margin: 8px;
    font-size: 40px;
    text-align: center;
}
.para_pg3{
    margin-top:15px;
    text-align: center;
    font-size: larger;
}
.btn{
    background-color: green;
    color:white;
    font-size: 15px;
    width: 100px;
    height:35px;
    border-radius: 10px;
    text-align: center;
    display: block;
    margin: 15px auto 0;
    transition: background-color 0.7s ease;
}
.btn:hover{
    background-color: rgb(250, 70, 5);
}
.divisions{
    margin:20px auto;
    background-color:rgb(250, 236, 236);
    border-radius: 23px;
    height: 80px;
    padding:20px;
    padding-top: 25px;
    padding-left: 30px;
    width:1000px;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
}
.heading_pg3{
    padding-bottom: 15px;
}

/* -------------------------------------Contact Us-------------------------------- */
.pg4_heading{
    margin-top: 15px;
    font-size: 40px;
    text-align: center;
}
.form{
    background-color:rgb(250, 236, 236);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
    margin: 50px auto;
    margin-top: 0px;
    width: 450px; 
    padding: 20px;
}
.form label{
    display:block;
    font-size:25px;
    font-weight: bolder;
    margin-left: 12px;
}
.in{
    width:95%;
    margin:10px;
}
.submit{
    background-color: green;
    color:white;
    font-size: 15px;
    width: 100px;
    height:35px;
    border-radius: 10px;
    text-align: center;
    display: inline-block;
    margin-right: 10px;
    transition: background-color 0.7s ease;
}
.sbm{
    margin-left: 120px;
}
.submit:hover{
    background-color: rgb(250, 70, 5);
}
.foot {
    width: 100%;
    height: 68px;
    color: white;
    text-align: center;
    font-size: 20px;
    font-weight: bolder;
    background-color: rgb(246, 85, 26);
}

.foot p {
    margin-top: 45px; 
}

Screen shots
