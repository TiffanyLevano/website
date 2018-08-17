# website
#glam html

<!DOCTYPE html>

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>G.L.A.M. - Cosmetics, Beauty, & Bodycare</title>
    <link rel="stylesheet" type="text/css" href="glam.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lobster">
    <script type="text/javascript" src="glam.js"></script>
  </head>
    <body>
      <button onclick="document.getElementById('id01').style.display='block'" style="width:auto;">Sign Up</button>

            <div id="id01" class="modal">

              <form class="modal-content animate" action="/action_page.php">
                <div class="imgcontainer">
                  <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
                  <img src = "glam.png" width="130">
                </div>

                <div class="log">
                  <label for="uname"><b>Username</b></label>
                  <input type="text" placeholder="Enter Username" name="uname" required>

                  <label for="psw"><b>Password</b></label>
                  <input type="password" placeholder="Enter Password" name="psw" required>

                  <button type="submit">Sign Up</button>
                  <label>
                    <input type="checkbox" checked="checked" name="remember"> Remember me
                  </label>
                </div>

                <div class="log" style="background-color:#f1f1f1">
                  <button type="button" onclick="document.getElementById('id01').style.display='none'" class="cancelbtn">Cancel</button>
                  <span class="psw">Forgot <a href="#">password?</a></span>
                </div>
              </form>
            </div>

      <button onclick="document.getElementById('id01').style.display='block'" style="width:auto;">Login</button>

      <div id="id01" class="modal">

        <form class="modal-content animate" action="/action_page.php">
          <div class="imgcontainer">
            <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
            <img src = "glam.png" width="130">
          </div>

          <div class="log">
            <label for="uname"><b>Username</b></label>
            <input type="text" placeholder="Enter Username" name="uname" required>

            <label for="psw"><b>Password</b></label>
            <input type="password" placeholder="Enter Password" name="psw" required>

            <button type="submit">Login</button>
            <label>
              <input type="checkbox" checked="checked" name="remember"> Remember me
            </label>
          </div>

          <div class="log" style="background-color:#f1f1f1">
            <button type="button" onclick="document.getElementById('id01').style.display='none'" class="cancelbtn">Cancel</button>
            <span class="psw">Forgot <a href="#">password?</a></span>
          </div>
        </form>
      </div>


      <a href="file:///C:/Users/GWC2018/Desktop/TestFolder/glamwishlist.html"><i class="fa fa-heart"><img src = "https://www.freeiconspng.com/uploads/pink-heart-png-12.png" width="30"> </img></i></a>
      <a href="#"><i class="fa fa-heart"><img src = "http://pngimg.com/uploads/shopping_cart/shopping_cart_PNG4.png" width="30" ></img></i></a>
      <br>
      <center><a href="file:///C:/Users/GWC2018/Desktop/TestFolder/glam.html"><img src = "glam.png" width="200"> </img></a></center>
      <br>
      <p>(Gorgeous, Lovely, and Magical)</p>
      <ul>
        <li class="dropdown">
          <a href="file:///C:/Users/GWC2018/Desktop/TestFolder/glamface.html#" class="dropbtn">Face</a>
          <div class="dropdown-content">
            <a href="file:///C:/Users/GWC2018/Desktop/TestFolder/glamface.html#">Face Primer</a>
            <a href="file:///C:/Users/GWC2018/Desktop/TestFolder/glamface.html#">Foundation</a>
            <a href="file:///C:/Users/GWC2018/Desktop/TestFolder/glamface.html#">Concealer</a>
            <a href="file:///C:/Users/GWC2018/Desktop/TestFolder/glamface.html#">Highlighter</a>
            <a href="file:///C:/Users/GWC2018/Desktop/TestFolder/glamface.html#">Contour & Bronzer</a>
            <a href="file:///C:/Users/GWC2018/Desktop/TestFolder/glamface.html#">Setting Spray</a>
            <a href="file:///C:/Users/GWC2018/Desktop/TestFolder/glamface.html#">Setting Powder</a>
            <a href="file:///C:/Users/GWC2018/Desktop/TestFolder/glamface.html#">Face Moisturizers</a>
          </div>
        </li>
        <li class="dropdown">
          <a href="file:///C:/Users/GWC2018/Desktop/TestFolder/glameyes.html" class="dropbtn">Eyes</a>
          <div class="dropdown-content">
            <a href="#">Eyeshadow</a>
            <a href="#">Eyeliner</a> width="50%
            <a href="#">Eyelashes</a>
            <a href="#">Eyebrow</a>
            <a href="#">Eye Primer</a>
          </div>
        </li>
        <li class="dropdown">
          <a href="file:///C:/Users/GWC2018/Desktop/TestFolder/glamlips.html" class="dropbtn">Lips</a>
          <div class="dropdown-content">
            <a href="#">Lipstick</a>
            <a href="#">Lip Liner</a>
            <a href="#">Lip Gloss</a>
          </div>
        </li>
        <li class="dropdown">
          <a href="file:///C:/Users/GWC2018/Desktop/TestFolder/glamhair.html" class="dropbtn">Hair</a>
          <div class="dropdown-content">
            <a href="#">Shampoo</a>
            <a href="#">Conditioner</a>
            <a href="#">Hair Oil & Masks</a>
            <a href="#">Hair Spray</a>
            <a href="#">Hair Styling Products</a>
          </div>
        </li>
        <li class="dropdown">
          <a href="javascript:void(0)" class="dropbtn">Bodycare</a>
          <div class="dropdown-content">
            <a href="#">Body Wash</a>
            <a href="#">Lotions</a>
            <a href="#">Self Tanner</a>
            <a href="#">Sunscreen</a>
            <a href="#">Exfoliants</a>
          </div>
        </li>
        <li class="dropdown">
          <a href="javascript:void(0)" class="dropbtn">Nails</a>
          <div class="dropdown-content">
            <a href="#">Nail Polish</a>
            <a href="#">Base & Top Coats</a>
            <a href="#">Press-Ons</a>
            <a href="#">Nail Tools</a>
          </div>
        </li>
        <li class="dropdown">
          <a href="javascript:void(0)" class="dropbtn">Tools</a>
          <div class="dropdown-content">
            <a href="#">Makeup Brushes</a>
            <a href="#">Makeup Bags</a>
            <a href="#">Eyelash Curlers</a>
            <a href="#">Mirrors & Sharpeners</a>
            <a href="#">Face Cleanser Brushes</a>
        </ul>

      <div class="row">
        <div class="column side">
          <h2>Side</h2>
          <center><img src="shade.jpg" width="330" height="1000"></center>
        </div>


        <div class="column middle">
        <br>
        <h2>Check Out What's New!</h2>


        <div class="container">
          <div class="mySlides">
            <div class="numbertext">1 / 6</div>
            <img src="https://gl-images.condecdn.net/image/w8zBJJGvY2Y/crop/1440/0.5235602094240838/f/norvina_palette_glamour_9july18_instagram_l.jpg" style="width:100%">
          </div>

          <div class="mySlides">
            <div class="numbertext">2 / 6</div>
            <img src="https://images-na.ssl-images-amazon.com/images/I/618Cx8BpHiL._SX466_.jpg" style="width:100%">
          </div>

          <div class="mySlides">
            <div class="numbertext">3 / 6</div>
            <img src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/urban-decay-born-to-run-1-1528713451.jpg" style="width:100%">
          </div>

          <div class="mySlides">
            <div class="numbertext">4 / 6</div>
            <img src="https://i2.wp.com/www.pretaeloira.com/wp-content/uploads/2017/04/09d1f65b-e2f8-4449-840d-cf66a0f38021-e1491739272536.jpg?resize=614%2C253&ssl=1" style="width:100%">
          </div>

          <div class="mySlides">
            <div class="numbertext">5 / 6</div>
            <img src="https://mitikala.com/wp-content/uploads/2018/06/huda-highlighter-palette-wk03-1280w.jpg" style="width:100%">
          </div>

          <div class="mySlides">
            <div class="numbertext">6 / 6</div>
            <img src="https://cdn.shopify.com/s/files/1/1168/1214/products/IMG_1798_grande_6e2c27de-0e44-452a-8415-7d3a60591107_large.jpg?v=1482347172" style="width:100%">
          </div>

          <a class="prev" onclick="plusSlides(-1)">❮</a>
          <a class="next" onclick="plusSlides(1)">❯</a>

          <div class="caption-container">
            <p id="caption"></p>
          </div>

          <div class="row">
            <div class="column">
              <img class="demo cursor" src="https://gl-images.condecdn.net/image/w8zBJJGvY2Y/crop/1440/0.5235602094240838/f/norvina_palette_glamour_9july18_instagram_l.jpg" style="width:100%" onclick="currentSlide(1)" alt="Norvina Palette">
            </div>
            <div class="column">
              <img class="demo cursor" src="https://images-na.ssl-images-amazon.com/images/I/618Cx8BpHiL._SX466_.jpg" style="width:100%" onclick="currentSlide(2)" alt="Morphe 39A Palette">
            </div>
            <div class="column">
              <img class="demo cursor" src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/urban-decay-born-to-run-1-1528713451.jpg" style="width:100%" onclick="currentSlide(3)" alt="Mountains and fjords">
            </div>
            <div class="column">
              <img class="demo cursor" src="https://i2.wp.com/www.pretaeloira.com/wp-content/uploads/2017/04/09d1f65b-e2f8-4449-840d-cf66a0f38021-e1491739272536.jpg?resize=614%2C253&ssl=1" style="width:100%" onclick="currentSlide(4)" alt="Northern Lights">
            </div>
            <div class="column">
              <img class="demo cursor" src="https://mitikala.com/wp-content/uploads/2018/06/huda-highlighter-palette-wk03-1280w.jpg" style="width:100%" onclick="currentSlide(5)" alt="Nature and sunrise">
            </div>
            <div class="column">
              <img class="demo cursor" src="https://cdn.shopify.com/s/files/1/1168/1214/products/IMG_1798_grande_6e2c27de-0e44-452a-8415-7d3a60591107_large.jpg?v=1482347172" style="width:100%" onclick="currentSlide(6)" alt="Snowy Mountains">
            </div>
          </div>
        </div>
      </div>

        <div class="column side">
          <h2>Side</h2>
          <center><img src="shades.jpg" width="330" height="1000"></center>
        </div>
        </div>

        <div class="footer">
          <h2>Glam</h2>

          <div class="row">
          	<div class="column side">
              <p>About Us</p>
            	<h3>A makeup website meant to make it easier to find cosmetics to your liking.</h3>
              <br>
              <br>
              <p>Creators</p>
            	<h3>Tiffany Levano</h3>
              <h3>Troi English</h3>
              <h3>Taiya ______</h3>
          	</div>
          	<div class="column middle">
            	<h3>Lorem ipsum dolor sit amet, conse</h3>
            	<h3>Lorem ipsum dolor sit amet, consec</h3>
          	</div>
          	<div class="column side">
            	<h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit..</h3>
          	</div>
          </div>

    </body>
</html>






<div id="myBtnContainer">
          <button class="btn active" onclick="filterSelection('all')"> Show all Face</button>
          <button class="btn" onclick="filterSelection('Face Primer')"> Face Primers</button>
          <button class="btn" onclick="filterSelection('Foundation')"> Foundations</button>
          <button class="btn" onclick="filterSelection('Concealer')"> Concealers</button>
          <button class="btn" onclick="filterSelection('Highlighter')"> Highlighters</button>
          <button class="btn" onclick="filterSelection('Contour & Bronzer')"> Contours & Bronzers</button>
          <button class="btn" onclick="filterSelection('Setting Spray')"> Setting Sprays</button>
          <button class="btn" onclick="filterSelection('Setting Powder')"> Setting Powders</button>
          <button class="btn" onclick="filterSelection('Face Moisturizer')"> Face Moisturizers</button>
        </div>
        <div class="items">
          <div class="filterDiv Face Primer"><img src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/best-face-primer-fenty-beauty-1528126435.jpg?crop=1xw:1xh;center,top&resize=480:*" width="95">Fenty Beauty</img></div>
          <div class="filterDiv Face Primer"><img src="https://www.marionnaud.ch/medias/sys_master/front-prd/front-prd/8811217190942/Smashbox-SB-PHOTO-FINISH-PRIMER-LIGHT-0607710004771-Photo-Finish-Primer.jpg" width="95">Smashbox</img></div>
          <div class="filterDiv Face Primer"><img src="https://cdn.shopify.com/s/files/1/1073/6222/products/Under_Makeup_BAse_2__79707.1433441852.600.600.jpeg?v=1506734607" width="95">Inglot</img></div>
          <div class="filterDiv Foundation"><img src= "https://www.sephora.com/productimages/sku/s1900836-main-hero.jpg" width="95">Tarte</img></div>
          <div class="filterDiv Foundation"><img src= "https://www.sephora.com/productimages/sku/s1711951-main-hero.jpg" width="95">Too Faced</img></div>
          <div class="filterDiv Foundation"><img src= "https://www.sephora.com/productimages/sku/s1925486-main-Lhero.jpg" width="95">Fenty Beauty</img></div>
          <div class="filterDiv Foundation"><img src= "https://i.pinimg.com/originals/c9/46/7d/c9467df7d7874aeb8f59596cf4b64cef.jpg" width="95">  Kat Von D</img></div>
          <div class="filterDiv Foundation"><img src= "https://i2.wp.com/bestlifeonline.com/wp-content/uploads/2017/10/bareminerals-bare-pro-performance-wear-foundation-large.jpg?resize=720%2C720&ssl=1" width="95">Bare Minerals</img></div>
          <div class="filterDiv Foundation"><img src= "https://imgix.bustle.com/uploads/image/2018/4/18/32000f6c-4ece-4ac2-b136-786dd358620a-cclinique.jpg" width="95">Clinique</img></div>
          <div class="filterDiv Foundation"><img src= "https://i.pinimg.com/originals/67/fe/cd/67fecdc62f5c5e9422004bc0875cd89c.jpg" width="95">Girgio Armani</img></div>
          <div class="filterDiv Foundation"><img src= "https://m.sephora.ae/catalog/product/cache/3/image/9df78eab33525d08d6e5fb8d27136e95/u/r/urban_decay_3605971198434_main_parent.jpg" width="95">Urban Decay</img></div>
          <div class="filterDiv Foundation"><img src= "https://images-na.ssl-images-amazon.com/images/I/31F-gUbux8L.jpg" width="95">Marc Jacobs</img></div>
          <div class="filterDiv Foundation"><img src= "https://i.pinimg.com/originals/04/a9/9e/04a99e353679dd4af7d43fc4ef19591f.jpg" width="95">Bobbi Brown</img></div>
          <div class="filterDiv Foundation"><img src= "https://cdn-img.health.com/sites/default/files/styles/300x300/public/1490118191/estee-lauder-stay-in-place-makeup.jpg?itok=rDPeype9" width="95">Estée Lauder</img></div>
          <div class="filterDiv Foundation"><img src= "http://cdn2-www.thefashionspot.com/assets/uploads/gallery/tb-best-foundation-for-oily-skin/07.jpg" width="95">Tarte</img></div>
          <div class="filterDiv Foundation"><img src= "https://weekender.com.sg/entertainment/wp-content/uploads/2018/02/YSL-ALL-HOURS-FOUNDATION.jpg" width="95">YSL Makeup</img></div>
          <div class="filterDiv Foundation"><img src= "http://www.shophudabeauty.com/wp-content/uploads/2017/10/17-Baklava.jpg" width="95">Huda Beauty</img></div>
          <div class="filterDiv Foundation"><img src= "https://images-na.ssl-images-amazon.com/images/I/71LgB-rYDHL._SY355_.jpg" width="95">Milk Makeup</img></div>
          <div class="filterDiv Foundation"><img src= "https://www.mynavyexchange.com/products/images/xlarge/8073279_0.jpg" width="95">Lancome</img></div>
          <div class="filterDiv Foundation"><img src= "https://images-na.ssl-images-amazon.com/images/I/31vnMp-nqzL.jpg" width="95">Smashbox</img></div>
          <div class="filterDiv Face Primer"><img src="https://static.birchbox.com/shop/media/catalog/product/cache/1/small_image/460x460/85e4522595efc69f496374d01ef2bf13/b/e/benefit_pore-fessional_pd_1500x1500.jpg" width="95">Porefessional</img></div>
          <div class="filterDiv Face Primer"><img src="http://www.sephora.fr/media/catalog_ProductCatalog/m12711225_P2413017_princ_medium.jpg" width="95">Too Faced</img></div>
          <div class="filterDiv Face Primer"><img src="https://images-na.ssl-images-amazon.com/images/I/41bkOnOgtaL._SY355_.jpg" width="95">Nars</img></div>
          <div class="filterDiv Face Primer"><img src="https://www.sephora.com/productimages/sku/s1103779-main-zoom.jpg" width="95">Lancome</img></div>
          <div class="filterDiv Face Primer"><img src="https://static.webshopapp.com/shops/086818/files/152344688/huda-beauty-huda-beauty-complexion-perfection-30ml.jpg" width="95">Huda Beauty</img></div>
          <div class="filterDiv Face Primer"><img src="https://www.sephora.com/productimages/sku/s1711076-main-hero-300.jpg" width="95">Marc Jacobs</img></div>
          <div class="filterDiv Face Primer"><img src="https://www.mecca.com.au/on/demandware.static/-/Sites-mecca-online-catalog/default/dwe1b850c5/product/bobbi/hr/i-012557-vitamin-enriched-face-base-1-940.jpg" width="95">Bobbi Brown</img></div>
          <div class="filterDiv Face Primer"><img src="https://www.maccosmetics.com/media/export/cms/products/640x600/mac_sku_M7LA01_640x600_0.jpg" width="95">MAC Makeup</img></div>
          <div class="filterDiv Face Primer"><img src="https://cdn.shopify.com/s/files/1/1824/2901/products/MSFP-01_1024x1024.jpg?v=1517860375" width="95">Milani</img></div>
          <div class="filterDiv Face Primer"><img src="https://images-na.ssl-images-amazon.com/images/I/41yiTFl5laL._SY355_.jpg" width="95">Maybelline</img></div>


          <div class="filterDiv Concealer"><img src="https://media.glamour.com/photos/58d98819594519668d13f478/master/w_1250,c_limit/s135301-main-zoom.jpg" width="95">Lancome</img></div>
          <div class="filterDiv Concealer"><img src="https://www.sephora.com/productimages/sku/s1885631-main-hero.jpg" width="95">Sephora</img></div>
          <div class="filterDiv Concealer"><img src="https://m.sephora.ae/catalog/product/k/a/kat_von_d_811999027943_main_parent.jpg" width="95">  Kat Von D</img></div>
          <div class="filterDiv Concealer"><img src="https://media.glamour.com/photos/58daaaf4594519668d13f489/master/w_1250,c_limit/s1840495-main-zoom.jpg" width="95">Becca</img></div>
          <div class="filterDiv Concealer"><img src="http://www.sephora.fr/media/catalog_ProductCatalog/m10281596_P2095039_princ_la.jpg" width="95">Urban Decay</img></div>
          <div class="filterDiv Concealer"><img src="http://www.journal.hr/wp-content/uploads/2018/03/Estee-Lauder-Double-Wear-Stay-in-Place-Flawless-Wear-Concealer.jpg" width="95">Estée Lauder</img></div>
          <div class="filterDiv Concealer"><img src="https://keyassets-p2.timeincuk.net/wp/prod/wp-content/uploads/sites/31/2017/08/nars-creamy-concealer.jpg" width="95">Nars</img></div>
          <div class="filterDiv Concealer"><img src="https://images.hellogiggles.com/uploads/2017/04/09045334/Tarte.jpg" width="95">Tarte Dead Sea</img></div>
          <div class="filterDiv Concealer"><img src="https://img.makeupalley.com/1/1/8/1/3266598.JPG" width="95">Colourpop</img></div>

          <div class="filterDiv Highlighter"><img src="https://i.pinimg.com/originals/1c/f4/50/1cf4503fa11e5072d84b25cfca2aff16.jpg" width="95">Anastasia BH</img></div>
          <div class="filterDiv Highlighter"><img src="https://beta-m.sephora.com/productimages/sku/s1993948-main-zoom.jpg" width="95">Anastasia BH</img></div>
          <div class="filterDiv Highlighter"><img src="https://s3-us-west-1.amazonaws.com/salla/UxOKC7lHxbkA90pPmESRJbMGwnquk9ChuhcKAZUm.jpeg" width="95">Anastasia BH</img></div>
          <div class="filterDiv Highlighter"><img src="http://www.belanjamimo.net/image-product/img2445-1457001588.jpg" width="95">Becca</img></div>
          <div class="filterDiv Highlighter"><img src="https://www.sephora.com/productimages/sku/s1483502-main-hero.jpg" width="95">Hourglass</img></div>
          <div class="filterDiv Highlighter"><img src="https://i.pinimg.com/originals/94/93/19/949319d9f79f02c61255ae1b0ea0c3be.jpg" width="95">Tarte</img></div>
          <div class="filterDiv Highlighter"><img src="https://beta-m.sephora.com/productimages/sku/s1902014-main-zoom.jpg" width="95">Too Faced</img></div>
          <div class="filterDiv Highlighter"><img src="https://www.sephora.com/productimages/sku/s1845346-main-zoom.jpg" width="95">Cover FX</img></div>
          <div class="filterDiv Highlighter"><img src="https://images-na.ssl-images-amazon.com/images/I/71-jy3wRz%2BL._SL1024_.jpg" width="95">Too Faced</img></div>
          <div class="filterDiv Highlighter"><img src="https://images-na.ssl-images-amazon.com/images/I/91-mWFGcQWL._SY355_.jpg" width="95">Too Faced</img></div>
          <div class="filterDiv Highlighter"><img src="https://www.musingsofamuse.com/wp-content/uploads/2018/04/Smashbox-Vlada-Prismatic-Pearl-Petal-Metal-Highlighter.jpg" width="95">Smashbox</img></div>
          <div class="filterDiv Highlighter"><img src="https://media-at.douglas-shop.com/sgf/at/988067/900_0/BECCA-Highlighter-Shimmering_Skin_Perfector_Pressed.jpg" width="95">Becca</img></div>
          <div class="filterDiv Highlighter"><img src="http://theartisticsoul.com/wp-content/uploads/2015/04/Highlighter-Guerlain-Meteorites-Compact-in-Medium-62-sephora.com_.jpg" width="95">Guerlain</img></div>
          <div class="filterDiv Highlighter"><img src="https://m.sephora.ae/catalog/product/k/a/kat_von_d_816657020915_main.jpg" width="95">  Kat Von D</img></div>
          <div class="filterDiv Highlighter"><img src="https://i.pinimg.com/236x/f6/01/60/f6016042dcc7482ead5a5d91ff080bf5.jpg" width="95">Ciaté</img></div>

          <div class="filterDiv Highlighter"><img src="https://m.sephora.ae/catalog/product/cache/4/image/1800x/040ec09b1e35df139433887a97daa66f/f/e/fenty_816657022452_main.jpg" width="95">Fenty Beauty</img></div>
          <div class="filterDiv Highlighter"><img src="https://cdn1.thehunt.com/app/public/system/note_images/12052204/note_view/8d766ebd36545988f586d4a8a612e966.jpeg" width="95">Sephora</img></div>
          <div class="filterDiv Highlighter"><img src="https://images-na.ssl-images-amazon.com/images/I/41oW5l6iGyL._SY355_.jpg" width="95">Nars</img></div>
          <div class="filterDiv Highlighter"><img src="http://preen.inquirer.net/files/2017/01/stila-e1483346387850.jpg" width="95">Stila</img></div>

          <div class="filterDiv Contour & Bronzer"><img src="https://static-reg.lximg.com/images/pictures/47278/zoom_6c0b24159a72ef68a776a6d8fd4de16f64db2cf8_1493219230_21777_SephoraCollection_Web.jpg" width="95">Sephora</img></div>
          <div class="filterDiv Contour & Bronzer"><img src="https://media.glamour.com/photos/5696711593ef4b095210fb8b/master/w_1280,c_limit/beauty-2015-08-sephora-contour-palette-main.jpg" width="95">Sephora</img></div>
          <div class="filterDiv Contour & Bronzer"><img src="https://images-na.ssl-images-amazon.com/images/I/51LRBKM-z0L._SY355_.jpg" width="95">Too Faced</img></div>
          <div class="filterDiv Contour & Bronzer"><img src="https://static-reg.lximg.com/images/pictures/40759/zoom_d2e09e97159c20de6f61f408d8cacf9912b4b38c_1493199398_17955_BenefitCosmetics_WEB.jpg" width="95">Benefit Cosm.</img></div>
          <div class="filterDiv Contour & Bronzer"><img src="https://cf3.s3.souqcdn.com/item/2016/02/23/10/11/81/06/item_XL_10118106_12515387.jpg" width="95">Guerlain</img></div>
          <div class="filterDiv Contour & Bronzer"><img src="https://www.sephora.com/productimages/sku/s1831346-main-Lhero.jpg" width="95">Kevyn Aucoin</img></div>

          <div class="filterDiv Setting Spray">Blue</div>
          <div class="filterDiv Setting Powder">Cat</div>
          <div class="filterDiv Face Moisturizer">Dog</div>
          <div class="filterDiv Contour & Bronzer">Kiwi</div>
          <div class="filterDiv Highlighter">Banana</div>
          <div class="filterDiv Concealer">Lemon</div>
          <div class="filterDiv Setting Spray">Cow</div>
        </div>
