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
<!--header-->
<header id="main-header" class="py-2 bg-primary text-white">
    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <h1><i class="fas fa-user"></i>
                    edit profile</h1>
            </div>
        </div>
    </div>
</header>
<!--actions-->>
<section id="actions" class="py-4 mb-4 bg-light">
    <div class="container">
        <div class="row">
            <div class="col-md-3">
                <a href="index.html" class="btn btn-light btn-block" >
                <i class="fas fa-arrow-left"></i>back to dashboard
                </a>
            </div>
            <div class="col-md-3">
                <a href="#" class="btn btn-success btn-block">
                <i class="fas fa-lock"></i>change password
                </a>
            </div>
            <div class="col-md-3">
                <a href="#" class="btn btn-danger btn-block">
                <i class="fas fa-trash"></i>delete account
                </a>
            </div>
        </div>
    </div>
</section>
<!--profile-->
<section id="profile">
   <div class="container">
       <div class="row">
           <div class="col-md-9">
            <div class="card" style="opacity:0.8;">
                <div class="card-header">
                    <h4>edit profile</h4>
                </div>
              <div class="card-body">
                  <form >
                      <div class="form-group">
                      <label for=" password"> password</label>
                      <input type="text" class="form-control" value="new password">
                    </div>
                    <div class="form-group">
                            <label for=" new password"> new password</label>
                            <input type="text" class="form-control" value="confirm new password">
                          </div>
                          <div class="form-group">
                                <label for=" phonenumber"> phonenumber</label>
                                <input type="text" class="form-control" value="new phonenumber">
                              </div>
                    <div class="form-group">
                            <label for=" email"> email</label>
                            <input type="email" class="form-control" value="new email">
                          </div>
                          <div class="form-group">
                                <label for=" address"> address</label>
                                <textarea class="form-control" name="editor1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur obcaecati temporibus ipsa assumenda laborum vitae excepturi! Alias unde accusamus sapiente amet, impedit temporibus aut recusandae eum et, aperiam quia ducimus aliquid voluptatem accusantium sed! Accusantium eligendi aperiam dicta esse quibusdam?</textarea>
                              </div>
                              
                  </form>
              </div>
            </div>
           </div>
           <div class="col-md-3">
           <h3>new avatar</h3>
           <img src="img/avatar.png" alt="" class="d-block img-fluid mb-3">
           <button class="btn btn-primary btn-block">edit image</button>
           <button class="btn btn-danger btn-block">delete image</button>
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
                    blogen
                </p>
            </div>
        </div>
    </div>
    </footer>
<!--modals-->
<!--add post modal-->
<div class="modal fade" id="addpostmodal">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header bg-primary text-white">
                <h5 class="modal-title">add post</h5>
                <button class="close" data-dismiss="modal">
                    <span>&times;</span>
                </button>
            </div>
            <div class="modal-body">
                <form>
                 <div class="form-group">
                    <label for="title">title</label> 
                    <input type="text" class="form-control">
                 </div>
                 <div class="form-group">
                     <label for="category">category</label>
                     <select  class="form-control">
                         <option value="">web development </option>
                         <option value="">tech gadgets</option>
                         <option value="">business</option>
                         <option value="">health & wellness</option>
                     </select>
                 </div>
                 <div class="form-group">
                     <label for="image">upload image</label>
                     <div class="custom-file">
                         <input type="file" class="custom-file input" id="image">
                         <label for="image" class="custom-file-label">choose file</label>
                     </div>
                     <small class="form-text text-muted">max size 3mb</small>
                 </div>
                 <div class="form-group">
                     <label for="body">body</label>
                     <textarea name="editor1" class="form-control" ></textarea>
                 </div>
                </form>
            </div>
            <div class="modal-footer">
                <button class="btn btn-primary" data-dismiss="modal">save changes</button>
            </div>
        </div>
    </div>
</div>
<!--add category modal-->
<div class="modal fade" id="addcategorymodal">
        <div class="modal-dialog modal-lg">
            <div class="modal-content">
                <div class="modal-header bg-success text-white">
                    <h5 class="modal-title">add category</h5>
                    <button class="close" data-dismiss="modal">
                        <span>&times;</span>
                    </button>
                </div>
                <div class="modal-body">
                    <form>
                     <div class="form-group">
                        <label for="title">title</label> 
                        <input type="text" class="form-control">
                     </div>
                     
                    </form>
                </div>
                <div class="modal-footer">
                    <button class="btn btn-success" data-dismiss="modal">save changes</button>
                </div>
            </div>
        </div>
    </div>
    
<!--add user modal-->
<div class="modal fade" id="addusermodal">
        <div class="modal-dialog modal-lg">
            <div class="modal-content">
                <div class="modal-header bg-warning text-white">
                    <h5 class="modal-title">add user</h5>
                    <button class="close" data-dismiss="modal">
                        <span>&times;</span>
                    </button>
                </div>
                <div class="modal-body">
                    <form>
                     <div class="form-group">
                        <label for="name">name</label> 
                        <input type="text" class="form-control">
                     </div>
                     <div class="form-group">
                            <label for="email">email</label> 
                            <input type="email" class="form-control">
                         </div>
                         <div class="form-group">
                                <label for="password">password</label> 
                                <input type="password" class="form-control">
                             </div>
                             <div class="form-group">
                                    <label for="password2">confirm password</label> 
                                    <input type="password" class="form-control">
                                 </div>
                    </form>
                </div>
                <div class="modal-footer">
                    <button class="btn btn-warning" data-dismiss="modal">save changes</button>
                </div>
            </div>
        </div>
    </div>

<!-- <span id="year"></span> -->
    <script
    src="http://code.jquery.com/jquery-3.3.1.min.js"
    integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8="
    crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
<script src="https://cdn.ckeditor.com/4.11.3/standard/ckeditor.js"></script>

<script>
// get the current year for the copyright
$('#year').text(new Data().getFullYear());

CKEDITOR.replace( 'editor1' );//not work
</script>
</body>
</html>
