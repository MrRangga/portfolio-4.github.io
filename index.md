<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="css/bootstrap.css">
    <link rel="stylesheet" href="style.css">

    <title>Hello, world!</title>
  </head>
  <body>
    <!-- navbar -->

    <nav class="navbar navbar-expand-lg navbar-light">
      <div class="container">
      <div class="navbar-brand">
        <div class="logoA">
          <img src="logoo.png" alt="logo putih">
        </div>
        <div class="logoB">
          <img src="logob.png" alt="logo berwarna">
        </div>
      </div>
      <button class="navbar-toggler" data-toggle="collapse" data-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav" >  
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a href="" class="nav-link">Home</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link">Profil</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link">Artikel</a>
          </li>
        </ul>
      </div>
      </div>
    </nav>

      <div class="jumbotron jumbotron-fluid">
        <div class="container text-white text-header">
        
        <h1 class="display-4">Sparkling Surabaya</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos, inventore?</p>
        <a href="" class="btn btn-primary tombol">Explore</a>
      </div>
      </div>

      <section class="about text-center pb-3">
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-md-6">
              <h1 class="display-4">What's Surabaya ?</h1>
          <p class="text-about">Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero quod id accusantium corporis harum totam consequuntur quia est iste, sint qui pariatur dolore saepe tempore consectetur aut cumque sapiente deserunt!</p>
          <p class="text-about">Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero quod id accusantium corporis harum totam consequuntur quia est iste, sint qui pariatur dolore saepe tempore consectetur aut cumque sapiente deserunt!</p>
        </div>
        <div class="col-md-4">
          <img class="img-about" src="about surabaya.png" alt="gambar surabaya">
        </div>
        </div>
        </div>
      </section>
      <!-- artikel -->
      <section class="artikel bg-light">
        <div class="container">
        <div class="row ">
          <div class="col text-center mt-2">
            <h1>Artikel</h1>
          </div>
        </div>
        <div class="row mt-2 pb-3">
          <div class="col-lg-4 col-md-6">
            <div class="card" style="width: 18rem">
              <img src="GAMBAR 6.jpg" alt="" class="card-img-top">
            <div class="card-body">
              <h5 class="card-title">
                Seni Budaya & Ekplorasi
              </h5>
              <p>
                Lorem ipsum dolor sit amet consectetur....
              </p> 
              <a href="#" class="btn btn-primary">Lanjut Baca...</a> 
            </div>
            </div>  
            </div>
          <div class="col-lg-4 col-md-6">
            <div class="card" style="width: 18rem">
              <img src="GAMBAR 8.jpg" alt="" class="card-img-top">
            <div class="card-body">
              <h5 class="card-title">
                Seni Budaya & Ekplorasi
              </h5>
              <p>
                Lorem ipsum dolor sit amet consectetur....
              </p> 
              <a href="#" class="btn btn-primary">Lanjut Baca...</a> 
            </div>
            </div>  
            </div>
          <div class="col-lg-4 col-md-6">
            <div class="card" style="width: 18rem">
              <img src="GAMBAR 19.jpg" alt="" class="card-img-top">
            <div class="card-body">
              <h5 class="card-title">
                Seni Budaya & Ekplorasi
              </h5>
              <p>
                Lorem ipsum dolor sit amet consectetur....
              </p> 
              <a href="#" class="btn btn-primary">Lanjut Baca...</a> 
            </div>
            </div>  
            </div>
          </div>
          </div>
      </section>
      
      <div class="ballon">
        
      </div>
      <section id="footer">
        <div class="row">
          <div class="col text-center py-4">
        &copy copyright by @Mr.rangga
      </div>
    </div>
      </section>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="js/jquery-3.3.1.slim.min.js" ></script>
    <script src="jquery.min.js"></script>
    <script src="js/popper.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script>
      $(window).scroll(function () {
        var  height = $('html').scrollTop();
        var about = $('.about').offset().top;
        if( height > about) {      
        $('.ballon').css({
                  'display' : 'block'
              });
          }

          else{
            $('.ballon').css({
                  'display' : 'none'
              });
          }
        });
        

        $('.ballon').click(function(){
          
          window.scrollTo({ top: 0, behavior: 'smooth' });
        });
    </script>
  </body>
</html>
