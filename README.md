<!DOCTYPE html>
<html lang="en">
  <head>
    <style>
        .navbar {
            display: flex;
            flex-direction: row;
            position: relative;
            align-items: center;
            width: 100%;
            height: 50px;
            min-height: 100px;
            align-items: center;
            justify-content: space-between;
            background-color: transparent;
            align-self: center;
          }
          
          .navbar li {
            margin: 0 50px;
            list-style-type: none;
            display: flex;
            flex-direction: row;
          }
          .navbar li:nth-child(2) {
            margin-top: -10px;
            margin-right: 70px;
          }
          .logo img {
            width: 180px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            align-self: center;
          }
          
          .logo {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            align-self: center;
          }
          .buttons {
            background-color: #e50914;
            padding: 7px 17px;
            color: white;
            display: flex;
            flex-direction: row;
            border-radius: 3px;
          }
          .main {
            width: 100%;
            margin-top: -100px;
            background-size: cover;
            align-items: center;
            overflow-x: hidden;
            justify-content: center;
            display: flex;
            background-position: center;
            min-height: 710px;
            background-image: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)),
              url(https://assets.nflxext.com/ffe/siteui/vlv3/a1dc92ca-091d-4ca9-a05b-8cd44bbfce6a/f9368347-e982-4856-a5a4-396796381f28/RS-en-20191230-popsignuptwoweeks-perspective_alpha_website_large.jpg);
          }
          .area {
            color: white;
            display: inline-flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            margin-top: 70px;
          }
          
          .area h1 {
            font-size: 60px;
            word-spacing: 15px;
            line-height: 75px;
          }
          
          .area h3 {
            margin-top: -30px;
            font-size: 27px;
            font-weight: normal;
          }
          .search {
            width: 150%;
            background-color: none;
            min-height: 80px;
            display: flex;
            flex-direction: row;
            align-items: center;
            justify-content: center;
            text-align: left;
            margin-top: 10px;
          }
          .box {
            width: 100%;
            min-height: 65px;
          }          
          .try {
            display: inline-flex;
            flex-direction: row;
            align-items: center;
            justify-content: center;
            background-color: #e50914;
            min-height: 70px;
            width: 70%;
            font-size: 30px;
            text-transform: uppercase;
          }
          
          
    </style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Netflix</title>
    
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="mediaquery.css">
    <link rel="stylesheet" href="https://maxst.icons8.com/vue-static/landings/line-awesome/line-awesome/1.3.0/css/line-awesome.min.css">
    <script src="https://kit.fontawesome.com/bc3a1796c2.js" crossorigin="anonymous"></script>
    <link rel="shortcut icon" href="https://image.flaticon.com/icons/png/512/870/870910.ico'/> 
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.css" />
  </head>
  <body>


    <div class="navbar">
    <li class="logo"><img src="logo.png"></li>
    <li class="buttons">Sign In</a>

    </div>
    <div class="main">
    <div class="area">
    <h1>Unlimited movies, TV <br>shows, and more.</h1>
    <h3>Watch anywhere. Cancel anytime.</h3>

    <div class="search">
      <input type="text" class="box" placeholder="Email">
      <span class="try">
Try 30 days free <i class="fas fa-chevron-right"></i>


      </span>
</div>
<h4>Ready to watch? Enter your email to create or access your account
  </h4>
    </div>
   
    
  </body>
</html>
