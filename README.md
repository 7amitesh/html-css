# html-css
product with hovering effects
<!doctype html>
<html>
<head>
    <title>Product</title>
    <link rel="stylesheet" href="https://dhbhdrzi4tiry.cloudfront.net/cdn/sites/foundation.min.css">
    <style>

    </style>
</head>
<body>
<!-- Preloader -->
<div class="spinner-wrapper" id="loading">
      <div class="spinner"></div>
      <div class="spinner">
         <div class="rect1"></div>
         <div class="rect2"></div>
         <div class="rect3"></div>
         <div class="rect4"></div>
         <div class="rect5"></div>
      </div>
   </div>
   <br>
   <br>
   <br>
   <br>
    <div class="grid-container">
        <div class="grid-x grid-margin-x small-up-1 medium-up-2 large-up-4 grid-x-wrapper">
            <div class="product-box column">
                <a href="#" class="product-item">
                    <div class="product-item-image">
                        <img src="https://modernaweb.net/__data/img/products/apple-watch.png" alt="Stadium Full Exterior">
                        <div class="product-item-image-hover">
                        </div>
                    </div>
                    <div class="product-item-content">
                        <div class="product-item-category">
                            Base Item
                        </div>
                        <div class="product-item-title">
                            Name of Product 1
                        </div>
                        <div class="product-item-price">
                            $57.00
                        </div>
                        <div class="button-pill">
                            <span>Shop Now</span>
                        </div>
                    </div>
                </a>
            </div>
            <div class="product-box column">
                <a href="#" class="product-item">
                    <div class="product-item-image">
                        <img src="https://modernaweb.net/__data/img/products/apple-watch.png" alt="Stadium Full Exterior">
                        <div class="product-item-image-hover">
                        </div>
                    </div>
                    <div class="product-item-content">
                        <div class="product-item-category">
                            Base Item
                        </div>
                        <div class="product-item-title">
                            Name of Product 2
                        </div>
                        <div class="product-item-price">
                            $89.00
                        </div>
                        <div class="button-pill">
                            <span>Shop Now</span>
                        </div>
                    </div>
                </a>
            </div>
            <div class="product-box column">
                <a href="#" class="product-item">
                    <div class="product-item-image">
                        <img src="https://modernaweb.net/__data/img/products/apple-watch.png" alt="Stadium Full Exterior">
                        <div class="product-item-image-hover">
                        </div>
                    </div>
                    <div class="product-item-content">
                        <div class="product-item-category">
                            Base Item
                        </div>
                        <div class="product-item-title">
                            Name of Product 3
                        </div>
                        <div class="product-item-price">
                            $89.00
                        </div>
                        <div class="button-pill">
                            <span>Shop Now</span>
                        </div>
                    </div>
                </a>
            </div>
            <div class="product-box column">
                <a href="#" class="product-item">
                    <div class="product-item-image">
                        <img src="https://modernaweb.net/__data/img/products/apple-watch.png" alt="Stadium Full Exterior">
                        <div class="product-item-image-hover">
                        </div>
                    </div>
                    <div class="product-item-content">
                        <div class="product-item-category">
                            Base Item
                        </div>
                        <div class="product-item-title">
                            Name of Product 4
                        </div>
                        <div class="product-item-price">
                            $89.00
                        </div>
                        <div class="button-pill">
                            <span>Shop Now</span>
                        </div>
                    </div>
                </a>
            </div>
        </div>
    </div>
    <div class="grid-container">
         <div class="grid-x grid-margin-x small-up-1 medium-up-1 large-up-1 grid-x-wrapper">
             <div class="product-box column" style="text-align: center;  margin: 50px 0 50px;">
              
            </div>
         </div>
      </div>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
</body>
</html>
css:
/*
 * modernaweb.net
 * * * * * * * * * */

@import url('https://fonts.googleapis.com/css?family=Rubik:400,700');
body { background: #f4f6f9; }
a:focus,
a:hover {color: #000;}

/* Preloader
************************** */
.spinner-wrapper { position: fixed; top: 0; left: 0; right: 0; bottom: 0; background: rgba(255,255,255,0.95); z-index: 999999; background: #c5d0e2; }
.spinner { position: absolute; margin: 100px auto; width: 50px; height: 40px; text-align: center; font-size: 10px; top: 40%; left: 50%; transform: translate(-50%, -60%); -moz-transform: translate(-50%, -60%); -webkit-transform: translate(-50%, -60%); -webkit-transition: all .37s ease; -moz-transition: all .37s ease;  -ms-transition: all .37s ease; -o-transition: all .37s ease; transition: all .37s ease;}
.spinner > div { background-color: #000; height: 100%; width: 6px; display: inline-block; -webkit-animation: sk-stretchdelay 1.2s infinite ease-in-out; animation: sk-stretchdelay 1.2s infinite ease-in-out; }
.spinner .rect2 { -webkit-animation-delay: -1.1s; animation-delay: -1.1s; }
.spinner .rect3 { -webkit-animation-delay: -1.0s; animation-delay: -1.0s; }
.spinner .rect4 { -webkit-animation-delay: -0.9s; animation-delay: -0.9s; }
.spinner .rect5 { -webkit-animation-delay: -0.8s; animation-delay: -0.8s; }
@-webkit-keyframes sk-stretchdelay {
    0%, 40%, 100% { -webkit-transform: scaleY(0.4) }  
    20% { -webkit-transform: scaleY(1.0) }
}
@keyframes sk-stretchdelay {
    0%, 40%, 100% { 
        transform: scaleY(0.4);
        -webkit-transform: scaleY(0.4);
    }  20% { 
        transform: scaleY(1.0);
        -webkit-transform: scaleY(1.0);
    }
}
.none {transition: all 1.7s ease;opacity: 0; display: none; z-index: -9999;}

/* Products
************************** */
.grid-x-wrapper {max-width: 85%; margin: 0 auto;}
.product-item .product-item-content { display: block; position: relative; transition: all .3s cubic-bezier(.785,.135,.15,.86); }
.product-item {display: block;text-align: center;color: #000;padding: 2rem;overflow: hidden;margin-bottom: 1rem;font-family: 'Rubik', sans-serif;margin: 20px 0;background: #fff;box-shadow: 0 10px 40px -3px rgba(0,0,0,0.1);border-radius: 7px;transform:scale(0.97,0.97);transition: all .17s cubic-bezier(0.24, 0.71, 0.58, 0.57);}
.product-item:hover {box-shadow: 0 0px 50px -10px rgba(0,0,0,0.3); transform:scale(1,1);}
.product-item:hover .product-item-image { transition-delay: .2s; -ms-transform: scale(.8) translateY(-15%); transform: scale(.8) translateY(-15%);}
.product-item .product-item-image { display: block; position: relative; margin-bottom: 2rem; transform: translate3d(0,0,0); transition: all .5s cubic-bezier(.68,-.55,.265,1.55); }
.product-item .product-item-image img { border-radius: 100%; position: relative; z-index: 3; }
.product-item:hover .product-item-image-hover { transition-delay: .1s; -ms-transform: translate(-50%,-42%) scale(.85); transform: translate(-50%,-42%) scale(.85); }
.product-item .product-item-image-hover { position: relative; z-index: 2; width: 100%; height: 100%; background: #97e7a2; background: -moz-linear-gradient(135deg,  #97e7a2 0%,#d8ff7e    100%); background: -webkit-linear-gradient(135deg,  #97e7a2 0%,#d8ff7e    100%); background: linear-gradient(135deg,  #97e7a2 0%,#d8ff7e    100%); border-radius: 100%; -ms-transform: translate(-50%,-120%) scale(0); transform: translate(-50%,-120%) scale(0); position: absolute; top: 50%; left: 50%; transition: all .6s cubic-bezier(.68,-.55,.265,1.55); opacity: 0; visibility: hidden;}
.product-item:hover .product-item-image-hover { opacity: 1; visibility: visible;}
.product-item:hover .product-item-category { transition-delay: .3s; }
.product-item:hover .product-item-category,
.product-item:hover .product-item-price,
.product-item:hover .product-item-title { -ms-transform: translateY(-50px); transform: translateY(-50px); }
.product-item .product-item-category,
.product-item .product-item-price,
.product-item .product-item-title { transition: all .3s cubic-bezier(.785,.135,.15,.86); }
.product-item .product-item-category { font-size: .875rem; }
.product-item:hover .product-item-title { transition-delay: .4s; }
.product-item:hover .product-item-category,
.product-item:hover .product-item-price,
.product-item:hover .product-item-title { -ms-transform: translateY(-50px); transform: translateY(-50px); }
.product-item .product-item-category,
.product-item .product-item-price,
.product-item .product-item-title { transition: all .3s cubic-bezier(.785,.135,.15,.86); }
.product-item .product-item-title { font-size: 1.125rem; font-weight: 600; }
.product-item:hover .product-item-price { transition-delay: .5s; }
.product-item:hover .product-item-category,
.product-item:hover .product-item-price,
.product-item:hover .product-item-title { -ms-transform: translateY(-50px); transform: translateY(-50px); }
.product-item .product-item-category,
.product-item .product-item-price,
.product-item .product-item-title { transition: all .3s cubic-bezier(.785,.135,.15,.86); }
.product-item .product-item-price { font-size: 1.0625rem; }
.product-item:hover .button-pill { transition-delay: .6s;}
.product-item:hover .button-pill {opacity: 1;-ms-transform: translateY(5px) translateX(-50%);transform: translateY(5px) translateX(-50%);}
.product-item .button-pill { position: absolute; bottom: 0; left: 50%; -ms-transform: translateY(30px) translateX(-50%); transform: translateY(30px) translateX(-50%); opacity: 0; transition: all .3s cubic-bezier(.785,.135,.15,.86); }
.button-pill span {display: inline-block;position: relative;font-size: .75rem;font-weight: 600;letter-spacing: .09em;text-transform: uppercase;  background: #97e7a2; background: -moz-linear-gradient(135deg,  #97e7a2 0%,#d8ff7e    100%); background: -webkit-linear-gradient(135deg,  #97e7a2 0%,#d8ff7e    100%); background: linear-gradient(135deg,  #97e7a2 0%,#d8ff7e    100%); color: #000;border-radius: 1.5rem;padding-top: .6rem;padding-bottom: .6rem;padding-left: 2.1rem;padding-right: 2.1rem;box-shadow: 0 14px 25px 0px rgba(75,204,140,0.1); transition: all .37s ease;}
.button-pill:hover span {display: inline-block;position: relative;font-size: .75rem;font-weight: 600;letter-spacing: .09em;text-transform: uppercase;  background: #5f5f5f; background: -moz-linear-gradient(135deg,  #5f5f5f 0%,#000    100%); background: -webkit-linear-gradient(135deg,  #5f5f5f 0%,#000    100%); background: linear-gradient(135deg,  #5f5f5f 0%,#000    100%); color: #fff;border-radius: 1.5rem;padding-top: .6rem;padding-bottom: .6rem;padding-left: 2.1rem;padding-right: 2.1rem; box-shadow: 0 14px 25px 0px rgba(0,0,0,0.1);}
@media(min-width:1200px) and (max-width:1366px) {
    .button-pill {width: 100%;}
    .product-box {padding: 0 10px;}
}
@media(min-width:1024px) and (max-width:1200px) {
    .product-item .product-item-title {font-size: 0.888rem;}
    .product-item .product-item-price {font-size: 0.788rem; padding: 7px 0 0;}
    .product-box {padding: 0 7px;}
}

