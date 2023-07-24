<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Pricing Table</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet" >
  <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" >
  <style>
    @import url('https://fonts.googleapis.com/css?family=Roboto:300');
    body{
      margin: 0;
      padding: 0;
      font-family: 'Roboto', sans-serif !important;
    }
    section{
      width: 100%;
      height: 100vh;
      -webkit-box-sizing: border-box;
              box-sizing: border-box;
      padding: 140px 0;
    }
    .card{
      position: relative;
      max-width: 300px;
      height: auto;
      background: linear-gradient(-45deg,#fe0847,#feae3f);
      border-radius: 15px;
      margin: 0 auto;
      padding: 40px 20px;
      -webkit-box-shadow: 0 10px 15px rgba(0,0,0,.1) ;
              box-shadow: 0 10px 15px rgba(0,0,0,.1) ;
      -webkit-transition: .5s;
      transition: .5s;
    }
    .card:hover{
      -webkit-transform: scale(1.1);
              transform: scale(1.1);
    }
    .col-sm-4:nth-child(1) .card,
    .col-sm-4:nth-child(1) .card .title .fa {
      background: linear-gradient(-45deg, #f53d99, #1d8eff);
    }
    .col-sm-4:nth-child(2) .card,
    .col-sm-4:nth-child(2) .card .title .fa {
      background: linear-gradient(-45deg, #fca51a, #ff27c3);
    }
    .col-sm-4:nth-child(3) .card,
    .col-sm-4:nth-child(3) .card .title .fa {
      background: linear-gradient(-45deg, #14ff87, #8200b7);
    }
    .card::before{
      content: '';
      position: absolute;
      bottom: 0;
      left: 0;
      width: 100%;
      height: 40%;
      background: rgba(255, 255, 255, .1);
      z-index: 1;
      -webkit-transform: skewY(-5deg) scale(1.5);
              transform: skewY(-5deg) scale(1.5);
    }
    .title .fa{
      color: #fff;
      font-size: 60px;
      width: 100px;
      height: 100px;
      border-radius: 50%;
      text-align: center;
      line-height: 100px;
      -webkit-box-shadow: 0 10px 10px rgba(0,0,0,.1) ;
              box-shadow: 0 10px 10px rgba(0,0,0,.1) ;
    }
    .title h2 {
      position: relative;
      margin: 20px  0 0;
      padding: 0;
      color: #fff;
      font-size: 28px;
      z-index: 2;
    }
    .price,.option{
      position: relative;
      z-index: 2;
    }
    .price h4 {
      margin: 0;
      padding: 20px 0 ;
      color: #fff;
      font-size: 60px;
    }
    .option ul {
      margin: 0;
      padding: 0;
    }
    .option ul li {
      margin: 0 0 10px;
      padding: 0;
      list-style: none;
      color: #fff; /* Text color: white */
      font-size: 16px;
      font-weight: bold; /* Make the text bold */
      /* text-shadow: 1px 1px 2px #000; /* Add a black shadow */ */
    }
    .card a {
      position: relative;
      z-index: 2;
      background: #fff;
      color: black;
      width: 150px;
      height: 40px;
      line-height: 40px;
      border-radius: 40px;
      display: block;
      text-align: center;
      margin: 20px auto 0 ;
      font-size: 16px;
      cursor: pointer;
      -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, .1);
              box-shadow: 0 5px 10px rgba(0, 0, 0, .1);
    }
    .card a:hover{
        text-decoration: none;
    }
  </style>
</head>
<body>
  <section>
    <div class="container-fluid">
      <div class="container">
        <div class="row">
          <div class="col-sm-4">
            <div class="card text-center">
              <div class="title">
                <i class="fa fa-paper-plane" aria-hidden="true"></i>
                <h2>Basic</h2>
              </div>
              <div class="price">
                <h4><sup>$</sup>10</h4>
              </div>
              <div class="option">
                <ul>
                  <!-- <li> <i class="fa fa-times" aria-hidden="true"></i> 🚀 Access to All Games </li> -->
                  <li> <i class="fa fa-check" aria-hidden="true"></i> 🎮 Enjoy Simple Games </li>
                  <li> <i class="fa fa-check" aria-hidden="true"></i> 🆘 Fast and Friendly Support </li>
                  <li> <i class="fa fa-check" aria-hidden="true"></i> 💰 All of this for just $10! </li>
                </ul>
              </div>
              <a target="_blank" href="https://discord.gg/Zuu2zVYU">Buy Now </a>
            </div>
          </div>
          <!-- END Col one -->
          <div class="col-sm-4">
            <div class="card text-center">
              <div class="title">
                <i class="fa fa-plane" aria-hidden="true"></i>
                <h2>Standard</h2>
              </div>
              <div class="price">
                <h4><sup>$</sup>20</h4>
              </div>
              <div class="option">
                <ul>
                  <!-- <li> <i class="fa fa-times" aria-hidden="true"></i> 🚀 Access to All Games </li> -->
                  <li> <i class="fa fa-check" aria-hidden="true"></i> 🏅 Get All Standard and Basic Games </li>
                  <li> <i class="fa fa-check" aria-hidden="true"></i> 🆘 Priority Support Included </li>
                  <li> <i class="fa fa-check" aria-hidden="true"></i> 💰 All this for only $20! </li>
                </ul>
              </div>
              <a target="_blank" href="https://discord.gg/Zuu2zVYU">Buy Now </a>
            </div>
          </div>
          <!-- END Col two -->
          <div class="col-sm-4">
            <div class="card text-center">
              <div class="title">
                <i class="fa fa-rocket" aria-hidden="true"></i>
                <h2>Premium</h2>
              </div>
              <div class="price">
                <h4><sup>$</sup>200</h4>
              </div>
              <div class="option">
                <ul>
                  <li> <i class="fa fa-check" aria-hidden="true"></i> 🚀 Unlock All Games - No Restrictions </li>
                  <li> <i class="fa fa-check" aria-hidden="true"></i> 🎮 Exclusive Early Access Privileges </li>
                  <li> <i class="fa fa-check" aria-hidden="true"></i> 🏆 Top-notch Priority Support </li>
                  <li> <i class="fa fa-check" aria-hidden="true"></i> 💰 One-time Payment of $200! </li>
                </ul>
              </div>
              <a target="_blank" href="https://discord.gg/Zuu2zVYU">Buy Now </a>
            </div>
          </div>
          <!-- END Col three -->
        </div>
      </div>
    </div>
  </section>
</body>
</html>
