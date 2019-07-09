<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.2/css/all.css" integrity="sha384-fnmOCqbTlWIlj8LyTjo7mOUStjsKC4pOpQbqyi7RrhN7udi9RwhKkMHpvLbHG9Sr" crossorigin="anonymous">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/ekko-lightbox/5.3.0/ekko-lightbox.css" />
    <link rel="stylesheet" href="css/style.css">
    <title>Bootstrap Theme</title>
</head>
<body >
  
    <!--start here-->
<nav class="navbar navbar-expand-sm  py-2"  style="background-color:Violet;">
    <div class="container">
        <a href="index.html" class="navbar-brand">professional dresses</a>
        <button class="navbar-toggler" data-toggle="collapse"
        data-target="#navbarcollapse">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarcollapse">
        <ul class="navbar-nav">
            <li class="nav-item px-2">
                <a href="index.html" class="nav-link ">about us </a>
            </li>
            <li class="nav-item px-2">
                <a href="posts.html" class="nav-link ">contact</a>
            </li>
           
        </ul>
        <ul class="navbar-nav ml-auto">
            <li class="nav-item dropdown mr-3">
                <a href="#" class="nav-link dropdown-toggle" data-toggle="dropdown">
                    <i class="fas fa-user-friend"></i>sign up
                </a>
                <div class="dropdown-menu">
                    <a href="profile.html" class="dropdown-item">
                     <i class="fas fa-user-circle"></i> tailor sign up
                    </a>
                    <a href="setting.html" class="dropdown-item">
                        <i class="fas fa-user-circle"></i> user sign up 
                       </a>
                </div>
            </li>
            <li class="nav-item">
             <a href="login.html" class="nav-link">
                 <i class="fas fa-user-timmes"></i>login
             </a>
            </li>
            <li class="nav-item">
             <a href="login.html" class="nav-link">
                 <i class="fas fa-user-circle"></i>
             </a>
            </li>
        </ul>
    </div>
    </div>
</nav>

<!--showcase slider-->
<section id="showcase">
    <div id="mycarousel" class="carousel slide" data-ride="carousel" >
<ol class="carousel-indicators">
   <li data-target="#mycarousel" data-slide-to="1" class="active"></li> 
   <li data-target="#mycarousel" data-slide-to="2" ></li> 
   <li data-target="#mycarousel" data-slide-to="3" ></li> 
   <li data-target="#mycarousel" data-slide-to="4" ></li> 
</ol>


<div class="carousel-inner">
    <div class="carousel-item carousel-image-1 active">
        <div class="container">
        <div class="carousel-caption d-none d-sm-block text-right mb-5">
            <h1 class="display-3">designing</h1>
            <p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt laudantium obcaecati autem! Ratione odit sunt quas aspernatur laboriosam quisquam saepe.</p>
            <a href="#" class="btn btn-danger btn-lg">learn more</a>
        </div>    
        </div>
    </div>

    <div class="carousel-item carousel-image-2 ">
        <div class="container">
        <div class="carousel-caption d-none d-sm-block  mb-5">
            <h1 class="display-3">sewing</h1>
            <p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt laudantium obcaecati autem! Ratione odit sunt quas aspernatur laboriosam quisquam saepe.</p>
            <a href="#" class="btn btn-primary btn-lg">learn more</a>
        </div>    
        </div>
    </div>

    <div class="carousel-item carousel-image-3 ">
        <div class="container">
        <div class="carousel-caption d-none d-sm-block text-right mb-5">
            <h1 class="display-3">tournament</h1>
            <p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt laudantium obcaecati autem! Ratione odit sunt quas aspernatur laboriosam quisquam saepe.</p>
            <a href="#" class="btn btn-success btn-lg">learn more</a>
        </div>    
        </div>
    </div>

    <div class="carousel-item carousel-image-4 ">
        <div class="container">
        <div class="carousel-caption d-none d-sm-block  mb-5">
            <h1 class="display-3">store</h1>
            <p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt laudantium obcaecati autem! Ratione odit sunt quas aspernatur laboriosam quisquam saepe.</p>
            <a href="#" class="btn btn-primary btn-lg">learn more</a>
        </div>    
        </div>
    </div>





</div>
<a href="#mycarousel" data-slide="prev" class="carousel-control-prev">
    <span class="carousel-control-prev-icon"></span>
</a>
<a href="#mycarousel" data-slide="next" class="carousel-control-next">
    <span class="carousel-control-next-icon"></span>
</a>
</div>
</section>
<!--footer-->
<footer id="main-footer" class=" text-white mt-5 p-5" style="background-color:Violet;">
    <div class="container">
        <div class="row">
            <div class="col">
                <p class="lead text-center">
                    copyright &copy; <span id="year"></span>
                    professional dresses
                </p>
            </div>
        </div>
    </div>
    </footer>

    <script
    src="http://code.jquery.com/jquery-3.3.1.min.js"
    integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8="
    crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/ekko-lightbox/5.3.0/ekko-lightbox.min.js"></script>

<script>
// get the current year for the copyright
$('#year').text(new Data().getFullYear());
//configure slider
$('.carousel').carousel({
interval:6000,
pause:'hover'
});
//lightbox init
$(document).on('click', '[data-toggle="lightbox"]', function(event) {
                event.preventDefault();
                $(this).ekkoLightbox();
            });

</script>
</body>
</html>
