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
