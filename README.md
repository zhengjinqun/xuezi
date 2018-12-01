# xuezi
学子商场
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Title</title>
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <link rel="stylesheet" href="../css/bootstrap.css">
  <script src="../js/jquery.min.js"></script>
  <script src="../js/popper.min.js"></script>
  <script src="../js/bootstrap.min.js"></script>
  <!--基础样式-->
  <link rel="stylesheet" href="../css/base.css">
  <!--公共样式-->
  <link rel="stylesheet" href="../css/common.css">
  <title>模板</title>
</head>
<body>
<header>
<iframe src="header.HTML" frameborder="0" scrolling="no"></iframe>
</header>
<div class="container">
  <!--轮播图-->
  <div id="mycar" class="carousel" data-ride="carousel">
    <!--大图-->
    <div class="carousel-inner" >
      <div class="carousel-item active">
        <img src="../img/index/banner1.png" alt="">
      </div>
      <div class="carousel-item ">
        <img src="../img/index/banner2.png" alt="">
      </div>
      <div class="carousel-item ">
        <img src="../img/index/banner3.png" alt="">
      </div>
      <div class="carousel-item ">
        <img src="../img/index/banner4.png" alt="">
      </div>
    </div>
    <!--导航栏指示器-->
    <ul class="carousel-indicators list-unstyled">
      <li class="active" data-slide-to="0" data-target="#mycar"></li>
      <li class="" data-slide-to="1" data-target="#mycar"></li>
      <li class="" data-slide-to="2" data-target="#mycar"></li>
      <li class="" data-slide-to="3" data-target="#mycar"></li>
    </ul>
    <!--左右箭头-->
    <a href="#mycar" class="carousel-control-prev" data-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </a>
    <a href="#mycar" class="carousel-control-next"  data-slide="next">
      <span class="carousel-control-next-icon"></span>
    </a>
  </div>
  <!--主体-->
  <!--主体导航栏-->
  <div class="">
  <div id="Nav" class="navbar navbar-light p-0 mt-2">
    <a href="#" class="navbar-brand font-weight-bold text-muted">
      <img class="mr-2 p-0" src="../img/index/computer_icon.png" alt="">
      首页推荐 /1F
    </a>
  </div>
  <!--主体内容-->
  <!--上-->
  <div id="center-img" class="row mt-4">
    <!--上左-->
    <div id="top-left" class="col-lg-7 col-sm-12">
      <!--卡片-->
      <div class="card border-0 flex-row">
        <div class="card-body  d-flex flex-column align-items-start">
          <h5 class="">Apple MacBook </h5>
          <h5 class="">Ari系列</h5>
          <p class="mt-1 text-muted my_small p-0">
          酷睿双核i5处理器|256GB SSD|8GB|内  存英特尔HD显卡620含共享显卡内存
          </p>
          <p class="text-primary p-0">¥6988.00</p>
          <a href="#" class="btn btn-primary">查看详情</a>

        </div>
        <!--大图-->
        <div class="w-75 h-75 mr-5">
        <img class="img-fluid my_img1" src="../img/index/study_computer_img1.png">
        </div>
      </div>
    </div>
    <!--上右-->
    <div class="col-lg-5 col-sm-12">
      <div class="card border-0 flex-md-row">
        <div class="card-body pr-0 ml-4 mr-4 d-flex flex-column align-items-start">
          <h5>小米Air 金属超</h5>
          <h5>轻薄</h5>
          <h6 class="mb-2 my_small">酷睿双核i5处理器|512GB SSD|2GB内存|英特尔HD独立显卡</h6>
          <p class="text-primary mb-3">¥3999.00</p>
          <a href="#" class="btn btn-primary">查看详情</a>
        </div>
        <div class="w-100 h-100 mt-5">
        <img class="img-fluid margin-auto mt-5 my_img2" src="../img/index/study_computer_img2.png" alt="">
      </div>
      </div>
    </div>
  </div>
  <!--下-->
  <div class="row mt-2">
    <!--下左-->
    <div class="col-lg-5 col-sm-12 ">
      <div class="img_width card border-0 flex-md-row">
        <div class="card-body d-flex flex-column align-items-start">
        <h5>联想E480C 轻薄系列</h5>
          <p class="mb-3 text-primary">¥5888.00</p>
          <a href="#" class="btn btn-primary">查看详情</a>
        </div>
        <img class="img-fluid" src="../img/index/study_computer_img3.png" alt="">
      </div>
    </div>
    <!--下右-->
    <div class="col-lg-7 col-sm-12">
      <div class="row">
        <div class="col-lg-4 col-sm-12">
          <div class="card border-0 flex-md-row">
            <div class="card-body d-flex flex-column align-items-start">
              <img class="img-fluid" src="../img/index/study_computer_img4.png" alt="">

              <p class="FontSize">华硕RX310 金属超极本</p>
              <p class="Fontsize1 text-primary">¥4966.00</p>
              <a  href="#" class="btn btn-primary Fontsize1">查看详情</a>
            </div>
          </div>
        </div>
        <!--第二个-->
        <div class="col-lg-4 col-sm-12">
          <div class="card border-0 flex-md-row">
            <div class="card-body d-flex flex-column align-items-start">
              <img class="img-fluid" src="../img/index/study_computer_img5.png" alt="">
              <p class="FontSize">联想小新700 电竞版游戏本</p>
              <p class="Fontsize1 text-primary">¥6299.00</p>
              <a  href="#" class="btn btn-primary Fontsize1">查看详情</a>
            </div>
          </div>
        </div>
        <!--第三个-->
        <div class="col-lg-4 col-sm-12">
          <div class="card border-0 flex-md-row">
            <div class="card-body d-flex flex-column align-items-start">
              <img class="img-fluid" src="../img/index/study_computer_img3.png" alt="">
              <p class="FontSize">戴尔灵越燃7000 轻薄窄边</p>
              <p class="Fontsize1 text-primary">¥5199.00</p>
              <a  href="#" class="btn btn-primary Fontsize1">查看详情</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</div>
<footer>
<iframe src="footer.HTML" frameborder="0" scrolling="no"></iframe>
</footer>
</body>
</html>
