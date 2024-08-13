# travel
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>complete responsive travel website desgin</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    <link rel="stylesheet" href="style01.css">


</head>
<body>
    <header>
     <a href="#" class="logo">travel <span>.</span></a>

    <nav class="navbar">
        <ul>
            <li><a data-scroll="home"  href="#home" class="active">home</a></li>
            <li><a data="stays"  href="stays.html">stays </a></li> 
            <li><a data="feature"  href="#feature">feature</a></li>
            <li><a data="about"  href="#about">about</a></li>
            <li><a data="galler"  href="#gallery">gallery</a></li>
            <li><a data="review"  href="#review">review</a></li>
            <li><a data="contact"  href="#contact">contact</a></li>
            <li><a data="menu"  href="#menu">Menu </a></li> 

            <div class="dropdown">
                <button ><a class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown button
                  </a>
                </button>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="login.html">user Login</a></li>
                  <li><a class="dropdown-item" href="placeholder.html">Admin login</a></li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
              </div>
            </ul>
    </nav>

    <div class="fas fa-bars"></div>
   </header>   


<section class="home" id="home">
    <div class="video">
    <video src="C:\Users\LENOVO\Downloads\intrnship project\frontvideo.mp4.mp4" loop muted autoplay></video>
</div>
    <div class="content">
        <h1>explore new places <br> adventure awaits.</h1>
        <br>
         <!-- <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fuga ipsum adipisci et magnam voluptas repudiandae 
            sapiente, consequuntur laborum.</p>  -->
    </div> 

<div class="form-container">
    <form action="">

        <h3>search your destination</h3>

        <span>location</span>
        <input type="text" placeholder="place you want to visit">

        <span>guest members</span>
        <input text="number" placeholder="number of peoples">

        <span>arrivals</span>
        <input type="date">

        <span>leaving</span>
        <input type="date">

        <input type="submit" value="search">


    </form>
</div>
</section>

<section class="feature" id="feature">

    <h1 class="heading"><span>f</span>eatured <span>l</span>oactions</h1>

    <div class="card-container">

        <div class="card">
            <span class="discount">-35%</span>
            <img src="dubai.jpg" alt="">
            <div class="content">
                <h3 class="title">dubai</h3>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Reprehenderit dignissimos suscipit nobis, 
                    eligendi dolorum ipsam cumque repellat sequi? Itaque minus a consequatur cum voluptatum reiciendis 
                    animi commodi doloremque amet provident?</p>
                    <div class="starts">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                        </div>
                        <a href="#"><button class="btn">check out!</button></a>
            </div>
        </div>
        <div class="card">
            <span class="discount">-45%</span>
            <img src="egypt.jpg" alt="">
            <div class="content">
                <h3 class="title">egypt</h3>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Reprehenderit dignissimos suscipit nobis, 
                    eligendi dolorum ipsam cumque repellat sequi? Itaque minus a consequatur cum voluptatum reiciendis 
                    animi commodi doloremque amet provident?</p>
                    <div class="starts">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                        </div>
                        <a href="#"><button class="btn">check out!</button></a>
            </div>
        </div>
        <div class="card">
            <span class="discount">-50%</span>
            <img src="hawamehal.jpg" alt="">
            <div class="content">
                <h3 class="title">india</h3>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Reprehenderit dignissimos suscipit nobis, 
                    eligendi dolorum ipsam cumque repellat sequi? Itaque minus a consequatur cum voluptatum reiciendis 
                    animi commodi doloremque amet provident?</p>
                    <div class="starts">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                        </div>
                        <a href="#"><button class="btn">check out!</button></a>
            <!-- </div>

            <div class="card">
                <span class="discount">-50%</span>
                <img src="ladakh.jpg" alt="">
                <div class="content">
                    <h3 class="title">india</h3>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Reprehenderit dignissimos suscipit nobis, 
                        eligendi dolorum ipsam cumque repellat sequi? Itaque minus a consequatur cum voluptatum reiciendis 
                        animi commodi doloremque amet provident?</p>
                        <div class="starts">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                             <i class="fas fa-star"></i> 
                            <i class="fas fa-star-half-alt"></i>
                            </div>
                            <a href="#"><button class="btn">check out!</button></a>
                        </div> -->
                </div>
            </div>
        </div>
    
</section>


<section id="about" class="about">
    <h1 class="heading"><span>a</span>bout <span>u</span>s</h1>

    <div class="row">

       <div class="image">
        <img src="planning.jpg" alt="">
       </div>

       <div class="content">
        <h3>why choose us?</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem nesciunt ut veniam doloribus esse exercitationem cum aliquam laboriosam, 
            illum consequatur quaerat ipsum asperiores sint laudantium architecto omnis eius magni odit.</p><br>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime, maiores?</p>
            <a href="#"><button class="btn btn1">read more</button></a>
            <a href="#"><button class="btn">get started</button></a>
       </div>

    </div>




</section>


<section id="gallery" class="gallery">

    <h1 class="heading"><span>g</span>allery</h1>

    <div class="box-container">

        <div class="box">
            <img src="dubai.jpg" alt="">
        <div class="icons">
            <a href="#" class="fas fa-heart"></a>
            <a href="#" class="fas fa-share"></a>
            <a href="#" class="fas fa-search"></a>
            
        </div>
        </div>

        <div class="box">
            <img src="cave.jpg" alt="">
        <div class="icons">
            <a href="#" class="fas fa-heart"></a>
            <a href="#" class="fas fa-share"></a>
            <a href="#" class="fas fa-search"></a>
           
        </div>
        </div>

        <div class="box">
            <img src="nightview.jpg" alt="">
        <div class="icons">
            <a href="#" class="fas fa-heart"></a>
            <a href="#" class="fas fa-share"></a>
            <a href="#" class="fas fa-search"></a>
            
        </div>
        </div>

        <div class="box">
            <img src="rajatimeperiod.jpg" alt="">
        <div class="icons">
            <a href="#" class="fas fa-heart"></a>
            <a href="#" class="fas fa-share"></a>
            <a href="#" class="fas fa-search"></a>
            
        </div>
        </div>

        <div class="box">
            <img src="kashmir.jpg" alt="">
        <div class="icons">
            <a href="#" class="fas fa-heart"></a>
            <a href="#" class="fas fa-share"></a>
            <a href="#" class="fas fa-search"></a>
            
        </div>
        </div>

        <div class="box">
            <img src="modicrush.jpg" alt="">
        <div class="icons">
            <a href="#" class="fas fa-heart"></a>
            <a href="#" class="fas fa-share"></a>
            <a href="#" class="fas fa-search"></a>
            
        </div>
        </div>
    </div>
</section>





<section id="review" class="review">

    <h1 class="heading"><span>r</span>eview</h1>

    <div class="box-container">

        <div class="box">
        <div class="image">
            <img src="review 3.webp" alt="">
        </div>
        <div class="content">
            <h3>someone's name</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero consequatur minima unde quae ipsa cumque reprehenderit
                 earum quis voluptate libero debitis cupiditate pariatur,  fuga mollitia magnam culpa perspiciatis. Numquam, et.</p>
                 <div class="starts">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                    
                </div>
        </div>
        </div>
        <div class="box-container">

            <div class="box">
            <div class="image">
                <img src="review 4.jpeg" alt="">
            </div>
        
            <div class="content">
                <h3>someone's name</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero consequatur minima unde quae ipsa cumque reprehenderit
                     earum quis voluptate libero debitis cupiditate pariatur,  fuga mollitia magnam culpa perspiciatis. Numquam, et.</p>
                     <div class="starts">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                        
                    </div>
            </div>
            </div>

            <div class="box">
                <div class="image">
                    <img src="review 2.jpeg" alt="">
                </div>
                <div class="content">
                    <h3>someone's name</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero consequatur minima unde quae ipsa cumque reprehenderit
                         earum quis voluptate libero debitis cupiditate pariatur,  fuga mollitia magnam culpa perspiciatis. Numquam, et.</p>
                         <div class="starts">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            
                            <i class="fas fa-star"></i>
                        </div>
                </div>
            </div>
    </div>

</section>


<section id="contact" class="contact">

    <h1 class="heading"><span>c</span>ontact <span>u</span>s</h1>



<!-- <iframe src="https://www.google.com" width="100%" height="300" style="border:0;outline: none;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>" -->
 
 <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3501.870363441081!2d77.42225987422296!3d28.63364718403241!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x390cef014159ed3b%3A0xc39140e03985f716!2sNikki%20tour%20and%20travels!5e0!3m2!1sen!2sin!4v1719932191575!5m2!1sen!2sin" width="100%" height="300" style="border:0;outline: none;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>"
 
<div class="row">
    <div class="contact-info">
        <div class="box">
            <h3> <i class="fas fa-home"></i> address </h3>
            <p>Uttar pradesh,<br>
                Ghaziabad,<br>
            Pin-code - 201009</p>
        </div>
 
        <div class="box">
            <h3> <i class="fas fa-envelope"></i> E-mail </h3>
            <p>chetanpal644@mail.com</p>
        </div>

        <div class="box">
            <h3> <i class="fas fa-phone"></i> Phone </h3>
            <p>+91-8130710338</p>
        </div>
    </div>

    <div class="contact-form-container">
            <form action="">

                <h3>Get in Touch</h3>

                <div class="inputBox">
                    <input type="text" placeholder="full name">
                    <input type="email" placeholder="e-mail">
                </div>
                <textarea name="" id="" cols="10" rows="10" placeholder="message"></textarea>

                <input type="submit" value="message">
            </form>
     </div>
</div>

</section>


<section class="newsletter">

    <h1>sign up 25% discount</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam rerum deserunt dignissimos, ipsam nam repellendus asperiores! Similique facilis sapiente voluptatem?</p>
    <form action="">
        <input type="email" placeholder="enter your email">
        <input type="submit" value="sign up">
    </form>
    
</section>



<section class="footer">
    <h1 class="credit">created by <span>Mr. Chetan  Pal</span>  | all right reserved.</h1>
    <div class="icons">
        <a href="https://www.facebook.com/chetan.pal.58118774" class="fab  fa-facebook-f"></a>
        
        <a href="https://x.com/chetanpal459114?t=IWuiUTh2lzEhOHZRscyUPg&s=08" class="fab  fa-twitter"></a>
        
        <a href="#" class="fab  fa-instagram"></a>
        
        <a href="https://github.com/chetanpal1110" class="fab  fa-github"></a>

        <a href="https://www.linkedin.com/in/chetan-pal-34b372221?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" class="fab fa-linkedin"></a>
     </div>
</section>





<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
<script src="main.js"></script>


</body>
</html>
