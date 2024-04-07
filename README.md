# Anhtrannt2.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <style>
    body{
      background-color: gray;
    }
    th{
        text-align: center;
    }
    td{

      text-align: center;
    }
    button{
        margin: 0 40px;
    }
    p{
        text-align: center;
        
    }
    .navbar-brand img{
      height: 50px;
    }


</style>
</head>
<body>

<nav class="navbar navbar-expand-sm navbar-dark bg-dark fixed-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="javascript:void(0)"><img src="" alt="">Logo</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mynavbar">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="mynavbar">
      <ul class="navbar-nav me-auto">
        <li class="nav-item">
          <a class="nav-link" href="javascript:void(0)">Trang chu</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="javascript:void(0)">Gio hang</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="javascript:void(0)">Lien he</a>
        </li>
      </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="text" placeholder="Search">
        <button class="btn btn-primary" type="button">Search</button>
      </form>
    </div>
  </div>
</nav>
<!-- Carousel -->
<div id="demo" class="carousel slide" data-bs-ride="carousel">

  <!-- Indicators/dots -->
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
  </div>
  
  <!-- The slideshow/carousel -->
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="img/cach-chup-hinh-san-pham-quan-ao-dep.png" alt="Los Angeles" class="d-block" style="width:100%"  height="400px">
    </div>
    <div class="carousel-item">
      <img src="img/cach-chup-anh-san-pham-dep-bang-dien-thoai_90b9dd1d7ec749709a0f702a198e2a5a_grande.jpg" alt="Chicago" class="d-block" style="width:100%" height="400px">
    </div>
    <div class="carousel-item">
      <img src="img/Chup-quan-ao-treo-tuong.jpg" alt="New York" class="d-block" style="width:100%" height="400px">
    </div>
  </div>
  
  <!-- Left and right controls/icons -->
  <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>
</div>




<div class="container mt5" style="background-color: gray;">
  <p>NEW ADDDDDD</p>
  <div class="row">
      <div class="col-sm-3">
          <div class="card" style="width: 250px">
              <img class="card-img-top" src="img/0daf314d-ef42-4141-ba80-779a1a109ab9.webp" alt="card image" style="position: relative;">
              <div class="card-img-overlay">
                  <div class="container p-1 bg-success text-white" style="width: fit-content; position: absolute; bottom:250px; left: 0;">NEW</div>
                  <div class="container p-1 bg-danger text-white" style="width: fit-content; position: absolute; bottom: 250px; left: 45px;">15% OFF</div>
              </div>
              <div class="card-body">
                  <table class="table">
                      <thead>
                          <tr>
                              <th>T-Shirt</th>
                              
                          </tr>
                      </thead>
                      <tbody>
                          <tr>
                              <td>Áo thun</td>
                            

                          </tr>
                          <tr>
                              <td>x/xl/s</td>
                             
                          </tr>
                          <tr>
                              <td>60,000 đ</td>
                              
                          </tr>
                      </tbody>
                  </table>
                  <div class="container mt-3">
                      <button type="button" class="btn btn-success">Add To Cart</button>
                     
                     
                  </div>





              </div>
          </div>
      </div>
      <div class="col-sm-3">
          <div class="card" style="width: 250px">
              <img class="card-img-top" src="img/ao-thun-in-hinh-theo-yeu-cau.jpg" alt="card image" style="position: relative;">
              <div class="card-img-overlay">
                  <div class="container p-1 bg-success text-white" style="width: fit-content; position: absolute; bottom:250px; left: 0;">NEW</div>
                  <div class="container p-1 bg-danger text-white" style="width: fit-content; position: absolute; bottom: 250px; left: 45px;">15% OFF</div>
              </div>
              <div class="card-body">
                  <table class="table">
                    <thead>
                      <tr>
                          <th>T-Shirt</th>
                          
                      </tr>
                  </thead>
                  <tbody>
                      <tr>
                          <td>Áo thun</td>
                        

                      </tr>
                      <tr>
                          <td>x/xl/s</td>
                         
                      </tr>
                      <tr>
                          <td>60,000 đ</td>
                          
                      </tr>
                      </tbody>
                  </table>
                  <div class="container mt-3">
                      <button type="button" class="btn btn-success">Add To Cart</button>
                     
                     
                  </div>





              </div>
          </div>
      </div>
      <div class="col-sm-3">
          <div class="card" style="width: 250px">
              <img class="card-img-top" src="img/0daf314d-ef42-4141-ba80-779a1a109ab9.webp" alt="card image" style="position: relative;">
              <div class="card-img-overlay">
                  <div class="container p-1 bg-success text-white" style="width: fit-content; position: absolute; bottom:250px; left: 0;">NEW</div>
                  <div class="container p-1 bg-danger text-white" style="width: fit-content; position: absolute; bottom: 250px; left: 45px;">15% OFF</div>
              </div>
              <div class="card-body">
                  <table class="table">
                    <thead>
                      <tr>
                          <th>T-Shirt</th>
                          
                      </tr>
                  </thead>
                  <tbody>
                      <tr>
                          <td>Áo thun</td>
                        

                      </tr>
                      <tr>
                          <td>x/xl/s</td>
                         
                      </tr>
                      <tr>
                          <td>60,000 đ</td>
                          
                      </tr>
                      </tbody>
                  </table>
                  <div class="container mt-3">
                      <button type="button" class="btn btn-success">Add To Cart</button>
                     
                     
                  </div>





              </div>
          </div>
      </div>
      <div class="col-sm-3">
          <div class="card" style="width: 250px">
              <img class="card-img-top" src="img/ao-thun-in-hinh-theo-yeu-cau.jpg" alt="card image" style="position: relative;">
              <div class="card-img-overlay">
                  <div class="container p-1 bg-success text-white" style="width: fit-content; position: absolute; bottom:250px; left: 0;">NEW</div>
                  <div class="container p-1 bg-danger text-white" style="width: fit-content; position: absolute; bottom: 250px; left: 45px;">15% OFF</div>
              </div>
              <div class="card-body">
                  <table class="table">
                    <thead>
                      <tr>
                          <th>T-Shirt</th>
                          
                      </tr>
                  </thead>
                  <tbody>
                      <tr>
                          <td>Áo thun</td>
                        

                      </tr>
                      <tr>
                          <td>x/xl/s</td>
                         
                      </tr>
                      <tr>
                          <td>60,000 đ</td>
                          
                      </tr>
                      </tbody>
                  </table>
                  <div class="container mt-3">
                      <button type="button" class="btn btn-success">Add To Cart</button>
                     
                     
                  </div>





              </div>
          </div>
      </div>
    </div>
</div>
<div class="container-fluid mt-4">
    <img src="img/000aaaaaaaaaaaaaaaaa.jpg" class="img-conheo" width="100%" height="400px" alt="background">
 </div>
 <footer class="bg-dark text-light py-5">
    <div class="container">
      <div class="row">
        <!-- Follow Us -->
        <div class="col-md-4">
          <h5>Follow Us</h5>
          <ul class="list-unstyled">
            <li><a href="#">Facebook</a></li>
            <li><a href="#">Twitter</a></li>
            <li><a href="#">Instagram</a></li>
          </ul>
        </div>
        <!-- Thông Tin -->
        <div class="col-md-4">
          <h5>Thông Tin</h5>
          <p>Cung cấp thông tin về sản phẩm và dịch vụ của chúng tôi.</p>
        </div>
        <!-- Địa chỉ -->
        <div class="col-md-4">
          <h5>Địa chỉ</h5>
          <address>
            123 Đường ABC<br>
            Thành phố XYZ<br>
            Quốc gia ABC<br>
          </address>
        </div>
      </div>
      <!-- Logo -->
      <div class="row mt-3">
        <div class="col text-center">
          <img src="logo.png" alt="Logo" style="max-width: 150px;">
        </div>
      </div>
    </div>
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
