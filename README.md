<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <link rel="icon" href="%PUBLIC_URL%/favicon.ico" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="theme-color" content="#000000" />
    <meta
      name="description"
      content="Web site created using create-react-app"/>
    <link rel="apple-touch-icon" href="%PUBLIC_URL%/logo192.png" />
    <link rel="manifest" href="%PUBLIC_URL%/manifest.json" />
    <title>React App</title>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://kit.fontawesome.com/a076d05399.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.1/js/bootstrap.min.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
       
    <style>

      *{
          padding:0;
          margin: 0;
          text-decoration: none;
          list-style: none;
          box-sizing: border-box;
         
         
  
      }
      body{
          background: #000;
          
      }
      nav div{ 
          display: flex;
          justify-content: space-between;
          align-items: center;
  
          
      }
     .search-box{
         position: relative;
         background: #2f3640;
         height: 40px;
         border-radius: 10px;
         padding: 10px;
         left: 10%;
         margin-top: 1%;
         font-family: 'Poppins', sans-serif;
         
  
     }
     .search-box:hover>.search-txt{
          width:300px;
          font-family: 'Poppins', sans-serif;
     }
     
     .search-btn{
         color: rgb(245, 237, 237);
         float: right;
         height: 20px;
         width: 25px;
         border-radius: 50%;
         display: flex;
         justify-content: center;
         align-items: center ;
         transition: 0.4s ease-in-out;
         background: #2f3640;
         font-family: 'Poppins', sans-serif;
     }
     .search-box:hover>.search-btn{
        color: #fff;
        font-size: 1.5rem;
     }
     .search-txt{
         height: 20px;
         float: right;
         display: flex;
         justify-content: center;
         align-items: center;
         background: transparent;
         border: none;
         outline: none;
         padding: 0;
         color: #fff;
         transition: 0.4s ease-in-out;
         width: 50px;
         font-family: 'Poppins', sans-serif;
     }
     .logo{
         position:relative;
         left: 5%;
         margin-top: 1%;
         font-family: 'Poppins', sans-serif;
     }
     .nav-right{
       margin-top: 1%;
       margin-right: 3%;
     }
     .nav-right>.globe{
         margin: 10px;
         padding: 3%;
         display: flex;
         justify-content: center;
         align-items: center;
         height: 35px;
         width: 70px;
         border-radius: 10px;
         background: #0f1318;
         color: #2f3640;
     }
     .nav-right>.globe>i:hover{
       color: #fff;
       font-size: 20px;
      
     }
     .nav-right>.login{
         color:#1565c0;
         background: #0f1318;
         font-family: 'Poppins', sans-serif;
     }
     .nav-right>.login:hover{
         background-color:#1565c0;
         color: #fff;
     }
     .nav-right>.login,.nav-right>.try-now{
         margin: 10px;
         display: flex;
         justify-content: center;
         align-items: center;
         height: 35px;
         width: 90px;
         border-radius: 10px;
         font-weight: 600;
         
     }
     .nav-right>.try-now{
         color: #fff;
         background-color: #1565c0;
         font-family: 'Poppins', sans-serif;
     }
     .nav-right>.try-now:hover{
         background-color: #fff;
         color: #1565c0;
     }
    .wrap{
      display: flex;
      position: relative;
      height: 65vh;
    }
    .wrap .menu{
      position: relative;
      width: 300px;
      height: 100%;
      left: 3%;
      padding: 30px 0;
      border-radius: 10px;
      font-family: 'Poppins', sans-serif;
      
      

    }
    .wrap .menu h4{
      color: #2f3640;
    }
    .wrap .menu ul li{
      padding: 5px;
      margin-top:6px ;
      transition: 0.2s ease;
    

    }
    .wrap .menu ul li a{
      color: #fff;
      text-decoration: none;
    }
    .wrap .menu ul li:hover{
      background-color:#0f1318;
      border-radius: 8px;
      transform: scale(1.1);
    }
    
     .active-li{
      background-color:#0f1318;
      border-radius: 8px;

    }
    .wrap .menu ul li a i{
      padding: 0px 10px;
    }
    .wrap .main-content{
      width: 100%;
      margin-left:20%;
      margin-top: 3%;
      margin-right: 5%;
  
    }
    .carousel-item img{
      border-radius:10px;
      height: 300px;
    }
    .grid-box{
     margin-left: 25%;
     margin-bottom: 5%;
     width: 70%;
     display: grid;
     grid-template-rows: 20px 150px 20px 150px;
     grid-template-columns: repeat(4,1fr);
     grid-gap: 20px;
     overflow: visible;
    }
    .grid-box .title-collection{
      grid-column: 1/-1;
    }
    .grid-box .title-new{
      grid-column: 1/-1;
    }
    .grid-box .movie-collection{
      width: 100px;
      display: grid;
      grid-template-rows: 150px;
      grid-template-columns: repeat(6,1fr);
      grid-gap: 10px;
      box-sizing: border-box;
      cursor: pointer;
      
    }
    .grid-box .new-collection{
      width: 100px;
      display: grid;
      grid-template-rows: 150px;
      grid-template-columns: repeat(6,1fr);
      grid-gap: 10px;
      cursor: pointer;
    }
    .title-collection,.title-new{
      color: #fff;
    }
    
    .type{
      position: absolute;
      left: 0%;
      top:-33%;
      font-weight: 500;
      font-size: .8rem;
      color:#fff;
      opacity: 0.8;
      font-family: 'Poppins', sans-serif;
    }
    .name{
      position: absolute;
      left: 0%;
      top:-25%;
      font-weight: 700;
      color: #fff;
      font-family: 'Poppins', sans-serif;
    }
    .trailer{
      position: absolute;
      left: 0%;
      top:-5% ;
      padding: 5px 8px;
      color: #fff;
      background: #0f1318;
      border-radius: 10px;
      opacity: .8;
      
      
    }
    .trailer>i,.fav>i{
      color: #fff;
      margin: 5px;
    }
    .fav{
      position: absolute;
      left: 23%;
      top:-5% ;
      padding: 5px 8px;
      color: #fff;
      background: #0f1318;
      border-radius: 10px;
      opacity: .8;
    }
    .trailer:hover,.fav:hover{
      color: #fff;
      opacity: 1;
    }
    .des{
     
      margin-top:3%;
      padding-top: 3%;
      margin-left: -10%;
      text-align: left;
      width: 600px;
      position: absolute;
      top: 170px;
    }
    .rating{
      position: absolute;
      left: 117%;
      top: -70%;
      font-size: 14px;
      font-weight: 700;
      color:rgb(241, 229, 229);
      opacity: 1;
      font-family: 'Poppins', sans-serif;
    }
    .rating a{
      text-decoration:none;
      margin: 5px;
      font-size: 12px;
      background-color: #fff;
      color:#000;
      font-weight: 700;
      letter-spacing: 1.5px;
      border-radius: 3px;
      opacity: 0.4;
    }
    .right-arrow{
      position: absolute;
      left:90%
    }
    .left-arrow{
      position: absolute;
      left:-5%
    }
    .fit-img{
      object-fit: cover;
    }
    .movie-collection>.box>img,.new-collection>.box>img{
      border-radius: 15px 15px 0 0;
      
      
    }
    .movie-collection>.box,.new-collection>.box{
      transition: 0.2s ease-in;
      border-radius: 15px;
    }
    .movie-collection>.box:hover,.new-collection>.box:hover{
      transform: scale(1.1);
      box-shadow:  0 4px 8px 0 rgba(66, 65, 65, 0.637), 0 6px 15px 0 rgba(58, 57, 57, 0.76);
      border-radius: 15px;
    }
    .movie-collection>.box>p,.new-collection>.box>p{
      border-radius:0 0 10px 10px;
      color: #fff;
      padding: 3px 0px 5px 3px;
      line-height: 20px;
      font-weight: 600;
      
    }
    .play-store{
      position: absolute;
      bottom: -40%;
      font-family: 'Poppins', sans-serif;
    }
    .a{
                animation: navbar 0.20s ease-in;
            }
             .b{
                animation: navbar 0.40s ease-in;
            }
             .c{
                animation: navbar 0.600s ease-in;
            }
             .d{
                animation: navbar 0.75s ease-in;
            }
            .e{
                animation: navbar 0.80s ease-in;
            }
            .f{
                animation: navbar 0.85s ease-in;
            }
            .g{
                animation: navbar 0.90s ease-in;
            }
            .i{
                animation: navbar 0.95s ease-in;
            }
        @keyframes navbar{
            0%{
              transform: translateX(-290px);
              opacity: 0.3;
            }
            100%{
                transform: translateX(0px);
                opacity: 1;
              
            }
        }
 

            .j{
                animation: navbar1 0.40s ease-in;
            }
             .k{
                animation: navbar1 0.50s ease-in;
            }
            .l{
                animation: navbar1 0.55s ease-in;
            }
             .m{
                animation: navbar1 0.65s ease-in;
            }
            .n{
                animation: navbar1 0.70s ease-in;
            }
             .o{
                animation: navbar1 0.75s ease-in;
            }
            .p{
                animation: navbar1 0.850s ease-in;
            }
             .q{
                animation: navbar1 0.90s ease-in;
            }
            .r{
                animation: navbar1 0.95s ease-in;
            }
        @keyframes navbar1{
            0%{
              transform: translateX(-290px);
              opacity: 0.3;
            }
            100%{
                transform: translateX(0px);
                opacity: 1;
              
            }
        }
        .main-content{
          overflow: hidden;
        }
        .title-img>img{
          height: 100%;
          opacity: .7;
          
        }
             	 
        .slide-show{
          height: 50vh;
          overflow: hidden;
          border-radius: 0 0 10px 10px;
        }
        .slide{
           height: 50vh;
        }
        .des{
          position: absolute;
          top: 170px;
          
        }
        
        
      </style>
  </head>
  <body>
    <nav>
      <div>
          <div class="logo">
            <i style="color: rgb(25, 0, 255); margin: 3px;" class="fab fa-affiliatetheme fa-2x"></i>
              <h2 style="color: #fff;"> Cinemeye</h2>
          </div>
       
          <div class="search-box">
              <input class="search-txt" type="text" name="" placeholder="Search here">
              <a class="search-btn" href="#" style="text-decoration:none">
              <i class="fas fa-search fa-1x"></i>
              </a>
          </div>
          <div class="nav-right">
              <a class="globe" href="#" style="text-decoration:none"><i class="fas fa-globe-asia " > </i>&nbsp EN</a>
              <a class="login"href="#" style="text-decoration:none">Login</a>
              <a class="try-now" href="#" style="text-decoration:none">Try Now</a> 
          </div>
      </div>
  </nav>
  <div class="wrap">
    <div class="menu">
      <ul>
        <h4>Catagories</h4>
        <li class="active-li a j"><a href="#"><i class="fas fa-home"></i>Main page</a></li>
        <li class="b k"> <a href="#"><i class="fas fa-tv"></i>TV-channels</a></li>
        <li class="c l"><a href="#"><i class="fas fa-film"></i>Movies</a></li>
        <li class="d m"><a href="tv.html"><i class="fas fa-compact-disc"></i>TV series</a></li>
        <li class="e n"><a href="#"><i class="fas fa-drum-steelpan"></i>Concerts</a></li>
        <li class="f o"><a href="#"><i class="fas fa-volleyball-ball"></i>Sport</a></li>
        <li class="g p"><a href="#"><i class="fas fa-baby"></i>For Kids</a></li>
        <li class="h q"><a href="#"><i class="fas fa-star"></i>Favourites</a></li>
        <li class="i r"><a href="#"><i class="fas fa-user"></i>Personal data</a></li>
    </ul>
    </div>
    <div class="main-content" style="color: #fff;">
       <div class="slide-show">
        <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
          <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
          </ol>
          <div class="carousel-inner">
            <div class="carousel-item active title-img">
              <img  src="https://wallpapercave.com/wp/wp1817971.jpg" class="d-block w-100" alt="...">
              <div class="carousel-caption d-none d-md-block  des">
                <p class="type">Action | Drama |Movie | Adventures</p>
                <h2 class="name">Interstellar</h2>
                <a class="trailer" href="#" style="text-decoration: none;"><i class="fas fa-play-circle"></i>Watch trailer</a>
                <a href="#" style="text-decoration: none;" class="fav"><i class="fas fa-star"></i>Add to Favourites</a>
                <p style="margin-top:10px;">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rem voluptatum itaque dolorem molestias earum id culpa dignissimos magni pariatu.</p>
                <p class="rating"><a  href="#">IMDB</a>9.1</p>
              </div>

            </div>
            <div class="carousel-item   title-img">
              <img  src="https://woodsidepawprint.com/wp-content/uploads/2019/04/avengers_endgame_poster_wallpaper_hdoficial_byandrew_vm-e1552652545172.png" class="d-block w-100" alt="...">
              <div class="carousel-caption d-none d-md-block des">
                <p class="type">Action | Drama |Movie | Adventures</p>
                <h2 class="name">Avengers Endgame</h2>
                <a class="trailer" href="#" style="text-decoration: none;"><i class="fas fa-play-circle"></i>Watch trailer</a>
                <a href="#" style="text-decoration: none;" class="fav"><i class="fas fa-star"></i>Add to Favourites</a>
                <p style="margin-top:10px;">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rem voluptatum itaque dolorem molestias earum id culpa dignissimos magni pariatu.</p>
                <p class="rating"><a href="#">IMDB</a>8.5</p>
              </div>
            </div>
            <div class="carousel-item title-img">
              <img  src="https://c4.wallpaperflare.com/wallpaper/784/678/343/movies-inception-leonardo-dicaprio-wallpaper-preview.jpg" class="d-block w-100" alt="...">
              <div class="carousel-caption d-none d-md-block des">
                <p class="type">Action | Drama |Movie | Adventures</p>
                <h2 class="name">Inception</h2>
                <a class="trailer" href="#" style="text-decoration: none;"><i class="fas fa-play-circle"></i>Watch trailer</a>
                <a href="#" style="text-decoration: none;" class="fav"><i class="fas fa-star"></i>Add to Favourites</a>
                <p style="margin-top:10px;">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rem voluptatum itaque dolorem molestias earum id culpa dignissimos magni pariatu.</p>
                <p class="rating" ><a style="opacity: 1;" href="#">IMDB</a>9.5</p>
              </div>
            </div>
          </div>
          <a class="carousel-control-prev left-arrow" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon left" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next right-arrow" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon right" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
       </div>
      </div>
  </div>
  <div class="grid-box">
    <div class="title-collection"><h5>Movie Collections</h5></div>
    <div class="movie-collection">
         <div class="box"><img class="fit-img" src="https://api.time.com/wp-content/uploads/2014/06/844558_full.jpg?w=600&quality=85"  height="100px" width="150px"/><p style=" background-color: #0f1318">Action</br><span style="font-size: 10px;">collection of films that amaze</span</p></div>
         <div class="box"><img class="fit-img" src="https://townsquare.media/site/442/files/2017/05/baywatch-2017-movie-4k-qhd.jpg?w=980&q=75" height="100px" width="150px"/><p style=" background-color: #0f1318">Comedy<br><span style="font-size: 10px;">collection of films that amaze</span</p></div>
         <div class="box"><img class="fit-img" src="https://movieposters2.com/images/1603486-b.jpg" height="100px" width="150px"/><p style=" background-color: #0f1318">Drama<br><span style="font-size: 10px;">collection of films that amaze</span</p></div>
         <div class="box"><img class="fit-img" src="https://images-na.ssl-images-amazon.com/images/I/81fvNfPZBsL._RI_.jpg" height="100px" width="150px"/><p style=" background-color: #0f1318">Sceince<br><span style="font-size: 10px;">collection of films that amaze</span</p></div>
         <div class="box"><img class="fit-img" src="https://upload.wikimedia.org/wikipedia/en/3/3c/JumanjiTheNextLevelTeaserPoster.jpg" height="100px" width="150px"/><p style=" background-color: #0f1318">Adventures<br><span style="font-size: 10px;">collection of films that amaze</span</p></div>
         <div class="box"><img class="fit-img" src="https://bronaghdoc10.files.wordpress.com/2014/12/img_2419.jpg" height="100px" width="150px"/><p style= " background-color: #0f1318">Animation<br><span style="font-size: 10px;">collection of films that amaze</span</p></div>
    </div>
    <div class="title-new"><h5>New</h5></div>
    <div class="new-collection">
        <div class="box"><img class="fit-img" src="https://m.media-amazon.com/images/M/MV5BZDZlMjc0MTItZWY2YS00ZDJhLWI2M2MtODVjNWFmYTQxYmJjXkEyXkFqcGdeQXVyMjMxOTE0ODA@._V1_UY1200_CR64,0,630,1200_AL_.jpg" height="100px" width="150px"/><p style= " background-color: #0f1318">Fast and Furious<br><span style="font-size: 10px;">Action, Drama</span</p></div>
        <div class="box"><img class="fit-img" src="https://i.ytimg.com/vi/lo9nEwHyvt4/movieposter.jpg" height="100px" width="150px"/><p style= " background-color: #0f1318">Martian<br><span style="font-size: 10px;">Action, Drama,Animation</span</p></div>
         <div class="box"><img class="fit-img" src="https://resizing.flixster.com/V4AjAI-3nolBM2DNyt7goOo0qtk=/206x305/v1.bTsxMTE3MjcwMDtqOzE4NjI0OzEyMDA7MTQwMDsyMTAw" height="100px" width="150px"/><p style= " background-color: #0f1318">Olympus Has Fallen<br><span style="font-size: 10px;">Action, Drama</span</p></div>
        <div class="box"><img class="fit-img" src="https://images-na.ssl-images-amazon.com/images/I/71y%2BE9MaURL._AC_SL1260_.jpg" height="100px" width="150px"/><p style= " background-color: #0f1318">Aquaman<br><span style="font-size: 10px;">Action, Drama,Adventures</span</p></div>
        <div class="box"><img class="fit-img" src="https://contentserver.com.au/assets/511728_p10989225_p_v8_ak.jpg" height="100px" width="150px"/><p style= " background-color: #0f1318">Civil War<br><span style="font-size: 10px;">Action, Drama,Adventures</span</p></div>
        <div class="box"><img class="fit-img" src="https://upload.wikimedia.org/wikipedia/en/thumb/e/e1/Joker_%282019_film%29_poster.jpg/220px-Joker_%282019_film%29_poster.jpg" height="100px" width="150px"/><p style= " background-color: #0f1318">Joker<br><span style="font-size: 10px;">Action, Drama,</span</p></div>
    </div>
   </div>
   <div class="play-store">
      <p style="width: 300px;">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quia minima recusandae tenetur.</p>
      <a href="#">
         <img  style="border: 1px solid #0f1318;border-radius: 5px;" src="https://www.pngmart.com/files/10/Get-It-On-Google-Play-Transparent-Background.png" height="40px" width="130px">
      </a>
      <a href="#">
          <img style="border: 1px solid #0f1318;border-radius: 5px;"src="https://p7.hiclipart.com/preview/316/826/489/etazhi-app-store-logo-brand-font-google-play-apple-store.jpg" height="40px" width="130px">
      </a>
   </div>
  </body>
</html>
