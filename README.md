<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.2/css/all.css" integrity="sha384-fnmOCqbTlWIlj8LyTjo7mOUStjsKC4pOpQbqyi7RrhN7udi9RwhKkMHpvLbHG9Sr" crossorigin="anonymous">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="css/style.css">
    <title>Bootstrap Theme</title>
</head>
<body style="background-image: url(https://source.unsplash.com/random/562x562); ">
    <!--start here-->
    <nav class="navbar navbar-expand-sm  py-2" style="background-color:Violet;">
        <div class="container">
            <a href="professionalDresses.html" class="navbar-brand">professional Dresses</a>
         
       
        </div>
    </nav>
<!--header-->
<header id="main-header" class="py-2 bg-primary text-white">
    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <h1><i class="fas fa-user"></i>
                 blogen user</h1>
            </div>
        </div>
    </div>
</header>
<!--actions-->
<section id="actions" class="py-4 mb-4 bg-light">
    <div class="container">
        <div class="row">
          
        </div>
    </div>
</section>
<!--login-->
<section id="login">
   <div class="container">
       <div class="row">
           <div class="col-md-6 mx-auto">
            <div class="card" style="opacity:0.8;">
                <div class="card-header">
                    <h4>account login</h4>
                </div>
                <div class="card-body">
                    <form action="index.html">
                        <div class="form-group">
                            <label for="email">email</label>
                            <input type="text" class="form-control">
                        </div>
                        <div class="form-group">
                                <label for="password">password</label>
                                <input type="password" class="form-control">
                            </div>
                            <input type="submit" value="login" class="btn btn-primary btn-block">
                    </form>
                </div>
            </div>
           </div>
    
       </div>
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

<!-- <span id="year"></span> -->
    <script
    src="http://code.jquery.com/jquery-3.3.1.min.js"
    integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8="
    crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>


<script>
// get the current year for the copyright
$('#year').text(new Data().getFullYear());


</script>
</body>
</html>
