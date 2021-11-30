<!DOCTYPE html>
 <html lang="en">
<head>
    <meta charset="UTF-8">-
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="./putti.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/icon?family=Material+Icons"rel="stylesheet">
<title>Online Shoping</title> 
</head> 
 <!------------------------------------header------------------------------------------------->
    <body>
    <div class="social-menu">
        <ul>
            <li><a href="#"><i class="fa fa-facebook"></i></a></li>
            <li><a href="#"><i class="fa fa-twitter"></i></a></li>
            <li><a href="#"><i class="fa fa-instgram"></i></a></li>
            <li><a href="#"><i class="fa fa-linkedin"></i></a></li>
        </ul>
    </div>
  
 

                 
      <!-- ------------------------------------------------------------------------------- -->
<div class="container">
 <div class="navbar">
        <div class="logo">
           <a href="product homepage.html"><img src="/images1/images/logo.png" width="100px" height="50px"></a>
    </div>
    <nav>
    <ul id="menuItems">
              <li><a  href="product homepage.html">Home</a></li>
               <li><a  href="product1.html">Products</a></li>
               <!-- <li><a  href="">Menu</a></li> -->
               <li><a  href="product detail.html">About</a></li>
               <li><a  href="contact.html">Contact</a></li>
             <li><a  href="account.html">Account</a></li>
        
    </ul>
        </nav>
        <a href="cart.html"><img src="images1/images/cart.png" width="30px" height="30px"></a>
        <img src="images1/images/menu.png" class="menu-icon" onclick="menutoggle()">

 </div>
<!-- </div> -->
 
 <!--------------------------------------------------------------------------------->
 <!-- <div class="row">
     <div class="col-2">
         <h1>Give Your workout<br> A New Style!</h1>
         <p>Success isn't always about greatness. It's about consisteny. Consistent hard<br> work gains
             success.  greatness will come.</p>
         <a href="" class="btn">Explore Now &#8594;</a>
</div>
<div class="col-2">
     <img src="images1/images/image1.png" alt="onepic"/> 
</div>
</div>
</div>
</div> -->

<div id="carouselExampleControlsNoTouching" class="carousel slide" data-bs-touch="false" data-bs-interval="false">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="images1/images/category-3.jpg" class="d-block w-100" alt="..." height="550px">
      </div>
      <div class="carousel-item">
        <img src="images1/images/category-2.jpg" class="d-block w-100" alt="..." height="550px">
      </div>
      <div class="carousel-item">
        <img src="images1/images/category-1.jpg" class="d-block w-100" alt="..." height="550px">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
<!------------------------ featured categories --------------------------->

<div class="categories">
    <div class="small-container">
        <h2 class="title"> Products</h2>
    <div class="row">
        <div class="col-3">
            <img src="images1/images/category-1.jpg">
        </div>
        <div class="col-3">
            <img src="images1/images/category-2.jpg">
        </div>
        <div class="col-3">
            <img src="images1/images/category-3.jpg">
        </div>
    </div>
    </div>
</div>
<!---------------------- featured products ---------------------------->
 <div class="small-container">
     <h2 class="title">Featured Products</h2>
     <div class="row">
        <div class="col-4">
            <a href="product detail.html"><img src="images1/images/product-1.jpg"></a>
            <a href="product-detail.html"><h4>Red Printed T-Shirt</h4></a>
            <div class="rating">
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_half</span>
               
           </div>
            <p>$50.00</p>
        </div>
        <div class="col-4">
            <img src="images1/images/product-2.jpg">
            <h4>Hemquen Shoes</h4>
            <div class="rating">
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_half</span>
           </div>
            <p>$70.00</p>
        </div>
        <div class="col-4">
            <img src="images1/images/product-3.jpg">
            <h4>Vantar Track Pant</h4>
            <div class="rating">
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
           </div>
            <p>$60.00</p>
        <!-- </div><div class="col-4">
            <img src="images1/images/product-4.jpg">
            <h4>Fabshio Navy Blue T-shirt</h4>
            <div class="rating">
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_half</span>
           </div>
            <p>$50.00</p> -->
        </div>
     </div>
     <h2 class="title">Latest Products</h2>
     <div class="row">
        <div class="col-4">
            <img src="images1/images/product-5.jpg">
            <h4>Bride Combo Shoes</h4>
            <div class="rating">
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_half</span>
               
           </div>
            <p>$90.00</p>
        </div>
        <div class="col-4">
            <img src="images1/images/product-6.jpg">
            <h4>Black Printed T-Shirt</h4>
            <div class="rating">
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_half</span>
           </div>
            <p>$60.00</p>
        <!-- </div><div class="col-4">
            <img src="images1/images/product-7.jpg">
            <h4>Royal Son Multicolor Cotton Socks</h4>
            <div class="rating">
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
           </div>
            <p>$50.00</p> -->
        </div><div class="col-4">
            <img src="images1/images/product-8.jpg">
            <h4>Smart Watch</h4>
            <div class="rating">
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_half</span>
           </div>
            <p>$80.00</p>
        </div>
     </div>
     <div class="row">
        <div class="col-4">
            <img src="images1/images/product-9.jpg">
            <h4>Fossil Watch</h4>
            <div class="rating">
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_half</span>
               
           </div>
            <p>$90.00</p>
        </div>
        <div class="col-4">
            <img src="images1/images/product-10.jpg">
            <h4>Boy lace Canvas Shoes</h4>
            <div class="rating">
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_half</span>
           </div>
            <p>$70.00</p>
        </div><div class="col-4">
            <img src="images1/images/product-11.jpg">
            <h4>Sparx Mens Running Shoes </h4>
            <div class="rating">
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
           </div>
            <p>$90.00</p>
        <!-- </div><div class="col-4">
            <img src="images1/images/product-12.jpg">
            <h4>Basis Track Pant</h4>
            <div class="rating">
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_rate</span>
                <span class="material-icons">star_half</span>
           </div>
            <p>$50.00</p> -->
        </div>
     </div>
    </div>
    <!----------------------------Offer------------------------->
    <div class="offer">
        <div class="small-container">
            <div class="row">
                <div class="col-2">
                <img src="images1/images/exclusive.png" class="offer-img">
                </div>
                <div class="col-2">
                    <p>Exclusively Available on RedStore</p>
                    <h1>Smart Band 4</h1>
                    <small>The Mi Smart Band  4 features a 39.9% larger (than Mi Band 3)
                     AMOLED color full-touch display with adjustable brightness, so 
                     everything is clear as can be.</small><br>
                     <a href=""class="btn"> Buy Now &#8594;</a>
                </div>
            </div>
        </div>
    </div>
    <!--------------------- testimonial------------------------>
    <div class="testimonial">
        <div class="small-container">
            <div class="row">
                <!-- <div class="row"> -->
                    <div class="col-3">
                        <div class="fa">
                        <!-- <span>&#8220;</span> -->
                    </div>

                        <p>Lorem Ipsum is simply dummy text of the printing and typesetting
                    industry. Lorem Ipsum has been the industry's standard dummy text ever.
                        </p>
                        <div class="rating">
                            <span class="material-icons">star_rate</span>
                            <span class="material-icons">star_rate</span>
                            <span class="material-icons">star_rate</span>
                            <span class="material-icons">star_rate</span>
                            <span class="material-icons">star_half</span>
                           
                       </div>
                       <img src="images1/images/user-1.png">
                       <h3>Sean Parker</h3>
                    </div>
                    <div class="col-3">
                        <div class="fa">
                        <!-- <span>&#8220;</span> -->
                    </div>
                        <p>Lorem Ipsum is simply dummy text of the printing and typesetting
                    industry. Lorem Ipsum has been the industry's standard dummy text ever.
                        </p>
                        <div class="rating">
                            <span class="material-icons">star_rate</span>
                            <span class="material-icons">star_rate</span>
                            <span class="material-icons">star_rate</span>
                            <span class="material-icons">star_rate</span>
                            <span class="material-icons">star_half</span>
                           
                       </div>
                       <img src="images1/images/user-2.png">
                       <h3>Mike Smith</h3>
                    </div>
                    <div class="col-3">
                        <div class="fa">
                        <!-- <span>&#8220; </span> -->
                        </div>
                        <p>Lorem Ipsum is simply dummy text of the printing and typesetting
                    industry. Lorem Ipsum has been the industry's standard dummy text ever.
                        </p>
                        <div class="rating">
                            <span class="material-icons">star_rate</span>
                            <span class="material-icons">star_rate</span>
                            <span class="material-icons">star_rate</span>
                            <span class="material-icons">star_rate</span>
                            <span class="material-icons">star_half</span>
                           
                       </div>
                       <img src="images1/images/user-3.png">
                       <h3>Mobel Joe</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>
<!------------------------------------brands------------------------------>
     <div class="brands">
         <div class="small-container">
             <div class="row">
                 <div class="col-5">
                 <img src="images1/images/logo-godrej.png" alt="">
             </div>
             <div class="col-5">
                <img src="images1/images/logo-oppo.png" alt="">
            </div>
            <div class="col-5">
                <img src="images1/images/logo-coca-cola.png" alt="">
            </div>
            <div class="col-5">
                <img src="images1/images/logo-paypal.png" alt="">
            </div>
            <div class="col-5">
                <img src="images1/images/logo-philips.png" alt="">
            </div>
         </div>
     </div>
     <!-----------------------------footer------------------------------>
    <div class="footer">
        <div class="container">
            <div class="row">
                <div class="footer-col-1">
                    <h3>Download App</h3>
                    <p>Download App for Android and ios mobile phone.</p>
                    <div class="app-logo">
                        <img src="images1/images/play-store.png">
                        <img src="images1/images/app-store.png">
                    </div>
                </div>
                <div class="footer-col-2">
                     <img src="images1/images/logo-white.png">
                    <p>Our Purpose Is To Sustainably Make Pleasure and Benefits of Sports Accessible
                         to the Many.</p>
                </div>
                  <div class="footer-col-3">
                    <h3>Useful Links</h3>
                    <ul>
                        <li>Coupons</li>
                        <li>blog Post</li>
                        <li>Return Policy</li>
                        <li>Join Affiliate</li>
                    </ul>
                     </div>
                     <div class="footer-col-4">
                        <h3> Follow us</h3>
                        <ul>
                            <li>Facebook</li>
                            <li>TwItter</li>
                            <li>Instagram</li>
                            <li>YouTube</li>
                        </ul>
                    </div>
             </div>
             <hr>
             <p class="copyright">Copyright 2021-Easy Tutorials</p>
        </div>
    </div>
    <!-- ----------------------js for toggle menu --------------------------------
    <script>
        var MenuItems = document.getElementId("menuItems");
        Menuitems.style.maxHeight="0px";
        function menutoggle(){
            if(MenuItems.style.maxHeight =="0px")
            {
                MenuItems.style.maxHeight="200px";
            }
            else{
                MenuItem.style.maxHeight ="0px";
            }
        }
    </script> -->
</body>
</html>
