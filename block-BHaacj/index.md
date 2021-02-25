- Create a page according to the layout shown below.

![Building HTML forms Assignment level 2](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/building-html-forms/ex-2.png)

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="assets/stylesheet/style.css">
<!----Google Font---->
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
<!--Font Awesome-->
<script src="https://kit.fontawesome.com/f98f63fd9d.js" crossorigin="anonymous"></script>
</head>
<body>
    <main>
        <header class="header">
            <div class="container flex">
                <div class="flex">
                   <img src="assets/media/logo.png" alt="Loading error">
                   <h1 class="heading">journey</h1>
                </div>
                <nav class="nav">
                    <ul class="flex">
                        <li><a class="home" href="#">Home</a></li>
                        <li><a href="#">Top Destinations</a></li>
                        <li><a href="#">Recommended Places</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </nav>
            </div>
        </header>
        <section class="hero">
            <div class="container">
                <div class="img">
                    <img class="banner-img" src="assets/media/banner.jpg" alt="Loading error">
                </div>
                <div class="bg-content">
                  <h2 class="bg-heading">LET'S BEGIN</h2>
                  <img class="dot"src="assets/media/dots-3.png" alt="Loading error">
                  <p class="bg-para">We assist you to choose the best</p>
                  <div class="hero-icon">
                    <i class="fas fa-angle-down"></i>
                  </div>
                  <div class="form">
                      <form class="hero-form" action="index.html" method="post">
                           <fieldset>
                              <div class="flex justify">
                              <label>Choose Your Destination 
                                 <input class="form-control" type="text" name="destination"  placeholder="Type your destination..."/>
                              </label>
                              <label>How many rooms? 
                                <input class="form-control" type="number" name="rooms?"  placeholder="1 Room"/>
                             </label>
                             <label>Adult
                                <input class="form-control-1 " type="number" name="person"  placeholder="1 "/>
                             </label>
                             <label>Childreen
                                <input class="form-control-1 " type="number" name="person"  placeholder="0"/>
                             </label>
                            </div>
                            <div class="flex justify">
                             <label>Check in Date
                                <input  class="form-control" type="text" name="date"  placeholder="Check in"/>
                             </label>
                             <label>Check Out Date
                                <input class="form-control" type="text" name="date"  placeholder="Check out"/>
                             </label>
                             <button class="btn">CHECK AVAILABILITY</button>
                            </div>
                          </fieldset>
                      </form>
                  </div>

                </div>
            </div>

        </section>
        <section class="utility margin-bottom">
            <div class="container">
                <h3 class= "section-heading">
                    YOUR <span class="header-design"> JOURNEY</span> IS OUR PRIORITY
                </h3>
               <p class="para utility-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium ipsum corrupti cumque ex accusamus sequi eius labore, quia eos! Quam optio eveniet deleniti cupiditate delectus </p>
               <button class="primary-btn button" >CONTINUE EXPLORE</button>
            
            </div>
        </section>
        <section class="">
            <div class="container travel flex">
                <div class="col-1">
                    <img class="travel-img" src="assets/media/tm-img-01.jpg" alt="Loading error">
                </div>
                <div class="travel-content content col">
                  <h4 class="travel-heading ">Europe's most visited places</h4>
                  <p class=" para travel-para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae molestiae facilis, tempore doloremque assumenda sed unde quia accusamus eligendi, quae numquam blanditiis quaerat beatae in minima qui et enim id? Lorem ipsum </p>
                  <button class="primary-btn travel-btn" >CONTINUE READING</button>
                </div>
            </div>
        </section>
        <section>
            <div class="container travel flex">
                <div class="travel-content col">
                    <h4 class="travel-heading ">Europe's most visited places</h4>
                    <p class=" para travel-para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae molestiae facilis, tempore doloremque assumenda sed unde quia accusamus eligendi, quae numquam blanditiis quaerat beatae in minima qui et enim id? Lorem ipsum </p>
                    <button class="primary-btn travel-btn" >CONTINUE READING</button>
                  </div>
                  <div class="col-1">
                    <img class="travel-img" src="assets/media/tm-img-02.jpg" alt="Loading error">
                </div>
        </section>
      
           
      
    </main>
</body>
</html>