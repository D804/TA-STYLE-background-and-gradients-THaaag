writeCode

- Create a layout according to the design shown below.

![Backgrounds and gradients level 2](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/background-and-gradients/ex-2.jpg)

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.

- Work on typography in detail.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,300;1,200;1,300&family=Roboto+Slab:wght@500;600;700;900&family=Teko:wght@600&display=swap" rel="stylesheet">
    <title>Document</title>
   
</head>
<body>
    <header class="container">
        <h1>Social media Dashbord</h1>
        <p>Total Followers:23,004</p>
        
        <span>Dark Mode</span>
        <div class="btn">
            <div class="circle">
            </div>
        </div>
    </header>
    <main>
        <section class="container">
            <div class="box facebook">
                <img class="fb-icon" src="facebook-square-brands (1).svg" alt="Loading error">
                <p>@deep</p>
                  <p class="followers"> 2654</p>
                  <p class="status">FOLLOWERS</p>
                   
            </div>
            <div class="box twitter">
            <img class="twitter-icon" src="twitter-brands.svg" alt="Loading error">
            <p>@deep</p>
            <p class="followers"> 2654</p>
            <p class="status">FOLLOWERS</p>
        </div>
            <div class="box instagram ">
                <img  class="insta-icon"src="instagram-brands.svg" alt="Loading error">
                <p>deep</p>
                <p class="followers"> 2654</p>
                <p class="status">FOLLOWERS</p>
            </div>
            <div class="box youtube">
                <img class="youtube-icon"src="youtube-brands.svg" alt="Loading error">
                <p>deep Tech</p>
                <p class="followers"> 2654</p>
                <p class="status"> SUBSCRIBERS </p>
            </div>
        </section>
        <section class="container">
            <div>
            <h2>overview-Today</h2>
            </div>
            <div>
                <div class="profile-details ">
                    <img class="fb-icon1" src="facebook-square-brands (1).svg" alt="Loading error">
                    <p class="para1">page view</p>
                <p class="page-information"> 87</p>

                    </p>
                </div>
               <div class="profile-details ">
                <img class="fb-icon1" src="facebook-square-brands (1).svg" alt="Loading error">
                
               </div>
               <div class="profile-details ">
                <img  class="insta-icon1"src="instagram-brands.svg" alt="Loading error">
               </div>
               <div class="profile-details ">
                <img  class="insta-icon1"src="instagram-brands.svg" alt="Loading error">
               </div>
            </div>
    <div class="profile-details ">
        <img class="twitter-icon1" src="twitter-brands.svg" alt="Loading error">
    </div>
    <div class="profile-details ">
        <img class="twitter-icon1" src="twitter-brands.svg" alt="Loading error">
    </div>
    <div class="profile-details ">
        <img class="youtube-icon1"src="youtube-brands.svg" alt="Loading error">
    </div>
    <div class="profile-details ">
        <img class="youtube-icon1"src="youtube-brands.svg" alt="Loading error">
    </div>
    </div>
        </section>
    </main>
</body>
</html>