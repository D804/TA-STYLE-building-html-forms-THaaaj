<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Journey Assignment-2</title>
    <link rel="stylesheet" href="assets/stylesheet/style.css">


    <!--Font Awesome-->
     <script src="https://kit.fontawesome.com/f98f63fd9d.js" crossorigin="anonymous"></script><link rel="preconnect" href="https://fonts.gstatic.com">
     <link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap" rel="stylesheet">
  </head>
  <body>
    <header class="header">
        <div class="container  shadow flex">
          <div class="flex">
            <a class="flex" href="#"><img src="assets/media/logo.png" alt="Loadong error"><strong>JOURNEY</strong></a>
            </div>
            <nav class="nav">
              <ul class="flex">
                <li><a class="active" href="#">Home</a></li>
                <li><a href="#">Top Destinations</a></li>
                <li><a href="#">Recommended Places</a></li>
                <li><a href="#">Contact Us</a></li>
              </ul>
            </nav>
        </div>
    </header>
     <!--Hero Section-->
    <main>
        <div class="container">
            <section class="hero text-center padding-top">
                <div class="bg-content">
                    <h1 class="hero-heading">LET'S BEGIN</h1>
                    <img class="dot"src="assets/media/dots-3.png" alt="Loading error">
                    <h2 class="hero-subheading">We assist you to choose the best</h2>
                    <div class="hero-icon">
                       <i class="fas fa-angle-down"></i>
                    </div>
                </div>
                <div class="form padding-top text-align">
                    <form class="form-container flex align" action="index.html" method="post">
                        <fieldset class="flex-45">
                            <label>Choose Your Destination 
                                <input class="form-control" type="text" name="destination"  placeholder="Type your destination..."/>
                            </label>
                            <div class="flex">
                                <label>Check in Date
                                    <input  class="form-control" type="date" name="date"  placeholder="Check in"/>
                                 </label>
                                 <label>Check Out Date
                                    <input class="form-control" type="date" name="date"  placeholder="Check out"/>
                                 </label>
                            </div>
                        </fieldset>
                        <fieldset class="flex-45">
                            <div class="flex">
                                <label>How many rooms? 
                                    <select class="form-control ">
                                        <option value="">1 Room</option>
                                        <option value="">2 Room</option>
                                        <option value="">3 Room</option>
                                        <option value="">4 Room</option>
                                    </select>
                                </label>
                                <label>Adult 
                                    <select class="form-control">
                                        <option value="">1 </option>
                                        <option value="">2 </option>
                                        <option value="">3 </option>
                                        <option value="">4 </option>
                                    </select>
                                </label>
                                <label>childreen
                                    <select class="form-control">
                                        <option value="">0 </option>
                                        <option value="">1 </option>
                                        <option value="">2 </option>
                                        <option value="">3 </option>
                                    </select>
                                </label>
                                    
                            </div>
                                <input class="btn primary-btn hero-btn " type="submit" value="CHECK AVAILABILITY"/>
                        </fieldset>
                    </form>
                </div>
            </section>
            <!--About-Section-->
            <section class="">
                <div class=" about padding-bottom">
                    <h3 class= "section-heading">
                       YOUR <strong> JOURNEY</strong> IS OUR PRIORITY
                    </h3>
                    <p class="para about-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium ipsum corrupti cumque ex accusamus sequi eius labore, quia eos! Quam optio eveniet deleniti cupiditate delectus </p>
                    <a class="btn primary-btn " href="#">CONTINUE EXPLORE</a>
                </div>
            </section>
            <!--Blog-->
            <section class="blog">
                <article class="flex alignment article">
                    <div class=" flex-50 font-0 article-col-left ">
                       <img src="assets/media/tm-img-01.jpg" alt="Loading error">
                       <div>
                          <div class="nav-btn-container right flex justify-end ">
                            <div class="nav-btn center">
                                <div class="nav-btn-icon">
                                    <i class="fas fa-angle-left"></i>   
                                </div>
                            </div>
                            <div class="nav-btn center">
                                <div class="nav-btn-icon">
                                    <i class="fas fa-angle-left"></i>
                                </div>
                            </div>
                          </div>
                       </div>
                    </div>
                    <div class="flex-50 article-col-right article-left">
                      <h3 class="blog-heading">Europe's most visited places</h3>
                      <p class="blog-para">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rerum repellat vel libero ea pariatur id. Totam quidem laboriosam voluptatibus qui, aperiam, reiciendis incidunt ab blanditiis sit provident minima corporis aspernatur?</p>
                      <input class="btn secondary-btn " type="submit" value="CHECK AVAILABILITY"/>
                    </div>
                </article>
                <article class="flex alignment article">
                   <div class="flex-50 article-col-right article-right artical-background">
                      <h3 class="blog-heading">Asia's most popular places</h3>
                      <p class="blog-para">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rerum repellat vel libero ea pariatur id. Totam quidem laboriosam voluptatibus qui, aperiam, reiciendis incidunt ab blanditiis sit provident minima corporis aspernatur?</p>
                      <input class="btn secondary-btn blog-btn " type="submit" value="CHECK AVAILABILITY"/>
                  </div>
                  <div class=" flex-50 font-0 article-col-left">
                     <img src="assets/media/tm-img-02.jpg" alt="Loading error">
                       <div>
                          <div class="nav-btn-container left flex justify-end ">
                            <div class="nav-btn center">
                                <div class="nav-btn-icon">
                                    <i class="fas fa-angle-left"></i>
                                </div>
                            </div>
                            <div class="nav-btn center">
                                <div class="nav-btn-icon">
                                    <i class="fas fa-angle-left"></i>
                                </div>
                            </div>
                          </div>
                      </div>
                 </div>
                </article>
                <article class="flex alignment article">
                   <div class=" flex-50 font-0 article-col-left ">
                      <img src="assets/media/tm-img-03.jpg" alt="Loading error">
                      <div>
                        <div class="nav-btn-container right flex justify-end ">
                            <div class="nav-btn center">
                                <div class="nav-btn-icon">
                                    <i class="fas fa-angle-left"></i>
                                </div>
                            </div>
                            <div class="nav-btn center">
                                <div class="nav-btn-icon">
                                    <i class="fas fa-angle-left"></i>
                                </div>
                            </div>
                        </div>
                      </div>
                   </div>
                   <div class="flex-50 article-col-right article-left">
                      <h3 class=" blog-heading">America's most famous place </h3>
                      <p class="blog-para">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rerum repellat vel libero ea pariatur id. Totam quidem laboriosam voluptatibus qui, aperiam, reiciendis incidunt ab blanditiis sit provident minima corporis aspernatur?</p>
                      <input class="btn secondary-btn " type="submit" value="CHECK AVAILABILITY"/>
                   </div>
                </article>
            </section>
            <!--Maps-->
            <section class="map flex text-align font-0 justify">
              <div class="grow">
                  <img src="assets/media/north-america.png" alt="loading error">
                  <p class="map-details">NORTH AMERICA</p>
              </div>
              <div class="grow">
                 <img src="assets/media/south-america.png" alt="loading error">
                 <p class="map-details">SOUTH AMERICA</p>
              </div>
              <div class=" grow active">
                 <img src="assets/media/europe.png" alt="loading error">
                 <p  class="map-details">EUROPE</p>
              </div>
              <div class="grow">
                <img src="assets/media/asia.png" alt="loading error">
                <p  class="map-details">ASIA</p>
              </div>
              <div class="grow">
                <img src="assets/media/africa.png" alt="loading error">
                <p  class="map-details">AFRICA</p>
              </div>
              <div class="grow">
                <img src="assets/media/australia.png" alt="loading error">
                <p  class="map-details">AUSTRALIA</p>
              </div>
            </section>
            <!--Recomended places-->
            <section class="recomended recomended-padding ">
                <article class="flex recomended-wraper alignment recomended-item ">
                   <div class="flex-30 font-0">
                     <img src="assets/media/tm-img-06.jpg" alt="loading error">
                   </div>
                   <div class="flex-45 place-padding ">
                      <h4>asia resort hotel </h4>
                      <strong class="recomended-place">singapore</strong>
                      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius accusamus doloribus at</p>
                   </div>
                   <div class="pricing flex-23">
                       <div class="recom-img">
                         <img src="assets/media/button-curve.png" alt="loading error">
                         <div class=" center column text-align">
                            <h5>$440</h5>
                            <a href="#">continue reading</a>
                         </div>
                       </div>
                   </div>
                </article>
                <article class="flex recomended-wraper alignment recomended-item ">
                   <div class="flex-30 font-0">
                      <img src="assets/media/tm-img-07.jpg" alt="loading error">
                  </div>
                  <div class="flex-45 place-padding ">
                      <h4>nullam eget est a nisl</h4>
                      <strong>Yangon,Myanmar</strong>
                      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius accusamus doloribus at</p>
                  </div>
                  <div class="pricing flex-23">
                     <div class="recom-img">
                       <img src="assets/media/button-curve.png" alt="loading error">
                       <div class=" center column text-align">
                          <h5>$440</h5>
                          <a href="#">continue reading</a>
                       </div>
                     </div>
                  </div>
                </article>
                <article class="flex recomended-wraper alignment recomended-item  ">
                   <div class="flex-30 font-0">
                      <img src="assets/media/tm-img-05.jpg" alt="loading error">
                  </div>
                  <div class="flex-45 place-padding ">
                    <h4>proint interdum ullamcorper</h4>
                    <strong>Bangkok,Thailand</strong>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius accusamus doloribus at</p>
                  </div>
                  <div class="pricing flex-23">
                     <div class="recom-img">
                       <img src="assets/media/button-curve.png" alt="loading error">
                       <div class=" center column text-align">
                          <h5>$440</h5>
                          <a href="#">continue reading</a>
                       </div>
                     </div>
                  </div>
                </article>
                <article class="flex recomended-wraper alignment  recomended-item">
                   <div class="flex-30 font-0">
                      <img src="assets/media/tm-img-04.jpg" alt="loading error">
                   </div>
                   <div class="flex-45 place-padding  ">
                      <h4>lorem ipsum dolor sit</h4>
                      <strong>Vientiane ,Laos</strong>
                      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius accusamus doloribus at</p>
                   </div>
                   <div class="pricing flex-23">
                      <div class="recom-img">
                        <img src="assets/media/button-curve.png" alt="loading error">
                        <div class=" center column text-align">
                          <h5>$440</h5>
                          <a href="#">continue reading</a>
                        </div>
                      </div>
                   </div>
                </article>
                <div class="text-align">
                   <a class="btn primary-btn " href="#">SHOW MORE PLACES</a>
                </div>
            </section>
            <!--contact-->
            <section class="font-0 contact">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3375.919515571293!2d76.35140991450203!3d32.206399320168714!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x391b530e24726e0d%3A0x71ff0cae0784712d!2sAltCampus%20Services%20Pvt.%20Ltd!5e0!3m2!1sen!2sin!4v1615630903564!5m2!1sen!2sin" width="100%" height="500" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                <div class="overlay"></div> 
                    <form>
                       <fieldset>
                           <div class="flex flex-45">
                               <input class="form-control " name="name" type="text" placeholder="Name"/>
                               <input class="form-control email " name="email" type="email" placeholder="Email"/>
                           </div>
                           <input class="form-control" name="subject" type="text" placeholder="Subject"/>
                           <textarea class="form-control" name="message" rows="6" placeholder="Message"></textarea>
                           <input class=" btn primary-btn hero-btn" type="submit" value="SEND MESSAGE NOW"/>
                      </fieldset>
                    </form> 
            </section>
    </main>
    <footer>
        <div class="container footer text-align">
            <small>copyright &copy;2020 your company designed by template mo</small>
        </div>
    </footer>
  </body>
</html>