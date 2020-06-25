<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Brand CSS-->
    <link rel="stylesheet" href="css/styles.css">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">

    <!-- Mapbox -->
    <script src='https://api.mapbox.com/mapbox-gl-js/v1.11.0/mapbox-gl.js'></script>
    <link href='https://api.mapbox.com/mapbox-gl-js/v1.11.0/mapbox-gl.css' rel='stylesheet' />

    <title>Nitro Blend</title>
  </head>
  <body>
    <div class="container">
        <header>
            <nav class="navbar navbar-light" style="background-color: #ffffff;">
                <a class="navbar-brand" href="#">
                    <img src="img/logo.png" width="35" height="35" class="d-inline-block align-top" alt="" loading="lazy">
                    <span class="head">Nitro Blend</span><span class="tail"> Limited</span>
                </a>
                
                <ul class="nav justify-content-end" id="dp">
                    <li class="nav-item">
                        <a href="#about" class="nav-link">About</a>
                    </li>
                    <li class="nav-item">
                        <a href="#products" class="nav-link">Products</a>
                    </li>
                    <li class="nav-item">
                        <a href="#team" class="nav-link">Team</a>
                    </li>
                    <li class="nav-item">
                        <a href="#contact" class="nav-link">Contact</a>
                    </li>
                </ul>
                
            </nav>
        </header>
    
        <section id="about">
    
        </section>
    
        <section id="products">
            <div class="title">
                <h3>Our Products</h3>    
            </div>
            <div class="card-deck">
                <div class="card">
                  <img src="img/dummy.png" class="card-img-top" alt="...">
                  <div class="card-body">
                    <h5 class="card-title">Product Name</h5>
                    <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus id lacus bibendum, semper lectus bibendum, rhoncus tortor. Vestibulum nec enim in ipsum sagittis dapibus non ut ligula.</p>
                  </div>
                </div>
                <div class="card">
                  <img src="img/dummy.png" class="card-img-top" alt="...">
                  <div class="card-body">
                    <h5 class="card-title">Product Name</h5>
                    <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus id lacus bibendum, semper lectus bibendum, rhoncus tortor. Vestibulum nec enim in ipsum sagittis dapibus non ut ligula.</p>
                  </div>
                </div>
                <div class="card">
                  <img src="img/dummy.png" class="card-img-top" alt="...">
                  <div class="card-body">
                    <h5 class="card-title">Product Name</h5>
                    <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus id lacus bibendum, semper lectus bibendum, rhoncus tortor. Vestibulum nec enim in ipsum sagittis dapibus non ut ligula.</p>
                  </div>
                </div>
            </div>
        </section>
        
        <section id="contact">
            <div class="title">
                <h3>Contact us</h3>    
            </div>

            <div class="card-deck">
                <div class="card" id="details">
                    <img src="img/long-logo.png" alt="">
                    <div>
                        <p>+254 7XX XXXXXX</p>
                        <p>info@nitroblends.com</p>
                        <p>Big Building, Road St.</p>
                        <p>Nairobi, Kenya</p>
                    </div>
                </div>
                <div class="card" id="map"></div>
            </div>
        </section>
    
        <footer>
            <p><span class="head">Nitro Blend</span><span class="tail"> Limited</span></span> &copy; 2020</p>
        </footer>
    </div>

    <!-- Mapbox -->
    <script>
        mapboxgl.accessToken = 'pk.eyJ1IjoiYXpyb25icmlhbiIsImEiOiJja2J1c3AxZXAwNTF1MnRxbmxlems1bjZmIn0.IW9vr1molRRLH4JELUvJKg';
        var map = new mapboxgl.Map({
            container: 'map',
            style: 'mapbox://styles/mapbox/streets-v11', // stylesheet location
            center: [36.81667, -1.28333], // starting position [lng, lat]
            zoom: 9 // starting zoom
        });

        var marker = new mapboxgl.Marker()
            .setLngLat([36.81667, -1.28333])
            .addTo(map);
    </script>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
  </body>
</html>