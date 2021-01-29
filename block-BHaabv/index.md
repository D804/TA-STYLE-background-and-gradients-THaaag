writeCode

- Create a layout according to the design shown below.

![Backgrounds and gradients level 2](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/background-and-gradients/ex-2.jpg)

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.

- Work on typography in detail.

<!----HTML--->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
      
       <title>Assignment2</title>
    <!--Font Awesome-->
    <script src="https://kit.fontawesome.com/f98f63fd9d.js" crossorigin="anonymous"></script>
    <!--Google Fonts--->
      <link rel="preconnect" href="https://fonts.gstatic.com">
      <link href="https://fonts.googleapis.com/css2?family=Yusei+Magic&display=swap" rel="stylesheet">

      <link rel="stylesheet" href="assets/stylesheet/style.css">
  </head>
  <body>
    <header class="header padding">
        <div class="container flex">
            <div>
              <h1> social media dashboard</h1>
            
              <h5> total followers:23,004 </h5>
               
            </div>
            <div class=" btn-container flex">
                <span>Dark Mode</span>
                <div class="btn">
                   <div class="circle"></div>
                </div>
            </div>
        </div>
    </header>
    <main class="main">
        <section class="hero-section">
            <div class="container flex">
                <div class="box fb-border ">
                    <div class="flex center padding facebook">
                       <i class="fab fa-facebook-square"></i>
                       <p class="id">@nathanf</p>
                    </div>
                    <div>
                        <h2>1987</h2>
                        <p class="details">FOLLOWERS</p>
    
                    </div>
                    <div class="daily-details">
                      <i class="fas fa-caret-up"></i>
                      <span>12 Today<span>
                    </div>
                </div>
                <div class="box twitter-border">
                  <div class="flex center padding twitter">
                    <i class="fab fa-twitter"></i>
                    <p class="id">@nathanf</p>
                  </div>
                  <div>
                    <h2>1987</h2>
                    <p class="details">FOLLOWERS</p>
                  </div>
                  <div class="daily-details">
                      <i class="fas fa-caret-up"></i>
                      <span>99 Today<span>
                  </div>
                </div>
                <div class="box insta-border">
                    <div class="flex center padding insta">
                       <i class="fab fa-instagram"></i>
                       <p class="id">@nathanf</p>
                    </div>
                    <div>
                      <h2>11K</h2>
                      <p class="details">FOLLOWERS</p>
                    </div>
                    <div class="daily-details">
                       <i class="fas fa-caret-up"></i>
                       <span>1099 Today<span>
                    </div>
                </div>
                <div class="box youtube-border">
                  <div class="flex center padding you-tube">
                    <i class="fab fa-youtube"></i>
                    <p class="id">@nathanf</p>
                  </div>
                  <div>
                    <h2>8239</h2>
                    <p class="details">FOLLOWERS</p>
                  </div>
                  <div class="daily-details down-caret">
                      <i class="fas fa-caret-down"></i>
                      <span class="span"> 144 Today<span>
                        
                  </div>
                </div>
            </div>
            
        </section>
        <section>
            <div class="container padding ">
          
                <h4>Overview-Today</h4>
                <div class=" flex wrap">
                    <div class=" cart-container small-box  ">
                        <div class="flex facebook ">
                           <p class="information">page views</p>
                           <i class="fab fa-facebook-square"></i>
                        </div>
                        <div class="flex ">
                            <h6>87</h6>
                            <div class="daily-details">
                               <i class="fas fa-caret-up"></i>
                               <span>3%<span>
                            </div>
                        </div>
                    </div>
                    <div class=" cart-container small-box  ">
                        <div class="flex facebook ">
                            <p class="information">Likes</p>
                            <i class="fab fa-facebook-square"></i>
                        </div>
                        <div class="flex ">
                           <h6>52</h6>
                               <div class="daily-details down-caret">
                                 <i class="fas fa-caret-down"></i>
                                 <span class="span">2%<span>
                               </div>
                        </div>
                    </div>
                    <div class=" cart-container small-box  ">
                        <div class="flex insta ">
                           <p class="information">Likes</p>
                           <i class="fab fa-instagram"></i>
                        </div>
                        <div class="flex ">
                            <h6>5462</h6>
                            <div class="daily-details">
                               <i class="fas fa-caret-up"></i>
                               <span>2257%<span>
                            </div>
                        </div>
                    </div>
                    <div class=" cart-container small-box  ">
                        <div class="flex insta ">
                           <p class="information">profile views</p>
                           <i class="fab fa-instagram"></i>
                        </div>
                        <div class="flex ">
                           <h6>52k</h6>
                           <div class="daily-details">
                              <i class="fas fa-caret-up"></i>
                              <span>1375%<span>
                           </div>
                        </div>
                    </div>
                    <div class=" cart-container small-box  ">
                        <div class="flex twitter ">
                           <p class="information">Retweets</p>
                           <i class="fab fa-twitter"></i>
                        </div>
                        <div class="flex ">
                            <h6>117</h6>
                            <div class="daily-details">
                              <i class="fas fa-caret-up"></i>
                              <span>303%<span>
                            </div>
                        </div>
                    </div>
                    <div class=" cart-container small-box  ">
                        <div class="flex twitter ">
                           <p class="information">Likes</p>
                           <i class="fab fa-twitter"></i>
                        </div>
                        <div class="flex ">
                            <h6>507</h6>
                            <div class="daily-details">
                               <i class="fas fa-caret-up"></i>
                               <span>553%<span>
                            </div>
                        </div>
                    </div>
                    <div class=" cart-container small-box  ">
                        <div class="flex you-tube ">
                           <p class="information">Likes</p>
                           <i class="fab fa-youtube"></i>
                        </div>
                        <div class="flex ">
                           <h6>107</h6>
                            <div class="daily-details down-caret">
                              <i class="fas fa-caret-down"></i>
                              <span class="span">19%<span>
                            </div>
                        </div>
                    </div>
                    <div class=" cart-container small-box  ">
                        <div class="flex you-tube ">
                           <p class="information">Total views</p>
                           <i class="fab fa-youtube"></i>
                        </div>
                        <div class="flex ">
                            <h6>1407</h6>
                            <div class="daily-details down-caret">
                               <i class="fas fa-caret-down"></i>
                               <span class="span">12%<span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>
   </body>
</html>