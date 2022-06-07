


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, shrink-to-fit=no"
    />
    <meta name="description" content="" />
    <meta name="author" content="" />
    <link
      href="https://fonts.googleapis.com/css?family=Lato:100,300,400,700,900"
      rel="stylesheet"
    />

    <title>Katherinne's Personal Portfolio</title>
<!--
Reflux Template
https://templatemo.com/tm-531-reflux
-->
    <script type="text/javascript" src="all.min.js"></script> 
    
    <!-- Bootstrap core CSS -->
    <link href="vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet" />

    <!-- Additional CSS Files -->
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.8/css/all.css" />
    <link rel="stylesheet" href="assets/css/fontawesome.css" />
    <link rel="stylesheet" href="assets/css/templatemo-style.css" />
    <link rel="stylesheet" href="assets/css/owl.css" />
    <link rel="stylesheet" href="assets/css/lightbox.css" />
  </head>

  <body>
    <div id="page-wraper">
      <!-- Sidebar Menu -->
      <div class="responsive-nav">
        <i class="fas fa-ellipsis-h" style="color:#956fb3" id="menu-toggle"></i>
        <div id="menu" class="menu">
          <i class="fas fa-heart" id="menu-close"></i>
          <div class="container">
            <div class="image">
              <a href="#"><img src="assets/images/logo.JPG" alt="" /></a>
            </div>
            <div class="author-content">
              <h4>Katherinne Rivera</h4>
              <span>Data Analyst</span>
            </div>
            <nav class="main-nav" role="navigation">
              <ul class="main-menu">
                <li><a href="#section1">About Me</a></li>
                <li><a href="#section2">My Skills</a></li>
                <li><a href="#section3">Portfolio</a></li>
                <li><a href="#section4">Contact Me</a></li>
              </ul>
            </nav>
            <div class="social-network">
              <ul class="soial-icons">
                <li>
                  <a href="https://www.linkedin.com/in/katherinne-rivera-4a134b1bb/">
                    <i class="fab fa-linkedin"></i>
                  </a>
                </li>                
              </ul>
            </div>
            <div class="copyright-text">
              <p>Copyright 2019 Reflux Design</p>
            </div>
          </div>
        </div>
      </div>

      
     <!-- Main Page -->
      <section class="section about-me" data-section="section1">
        <div class="container">
          
          <!-- Section 1 -->
          <div class="section-heading">
            <h2>About Me</h2>
            <div class="line-dec"></div>
            <span
              > THIS IS A NEW PAGE I THINK!
            </span>
          </div>
          
          <!-- Picture 1 -->
          <div class="left-image-post">
            <div class="row">
              <div class="col-md-6">
                <div class="left-image">
                  <img src="assets/images/flag.png" alt="" />
                </div>
              </div>
              <div class="col-md-6">
                <div class="right-text">
                  <h4>My Life</h4>
                  <p>
                    ITS FINNA BE COOL!
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="right-image-post">
            <div class="row">
              <div class="col-md-6">
                <div class="left-text">
                  <h4>My Education</h4>
                  <p>                    
                    THIS WILL ALL BE DIFFERENT THOUGH
                  </p>
                </div>
              </div>
              <div class="col-md-6">
                <div class="right-image">                  
                  <img src="assets/images/tamu-logo.png" alt="" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="section my-services" data-section="section2">
        <div class="container">
          <div class="section-heading">
            <h2>My Skills</h2>
            <div class="line-dec"></div>
            <span>Throughout my college years I was able to learn some of these skills, and as I graduated I took some 
            self-initiateive and learned some more. I am a fast learner and I enjoy learning. In college, I learned C++, Java, and a bit of HTML/CSS. After college,
              I dedicated time to learn Python, SQL, and I'm currently learning Tableu. Furthermore these are some certifications I've earned along the way:
            </span>
          </div>
          
          <!-- images in Lightbox -->
          <div class="row">
       		  <div class = "column">
              <img src="assets/images/cert1.png" onclick="openModal();currentSlide(1)" class= "hover-shadow">
            </div>
            <div class = "column">
              <img src="assets/images/cert2.png" onclick="openModal();currentSlide(2)" class= "hover-shadow">
            </div>
            <div class = "column">
              <img src="assets/images/cert3.png" onclick="openModal();currentSlide(3)" class= "hover-shadow">
            </div>
            <div class= "column">
              <img src="assets/images/cert4.png" onclick="openModal();currentSlide(4)" class= "hover-shadow">
            </div>
          
     
            <!-- The Lightbox -->
            <div id = "myModal" class="modal">
              <span class = "close cursor" onclick = "closeModal()"> &times;
              </span>
              <div class ="modal-content">

                <!-- The images when they're big -->
                <div class= "mySlides">
                  <div class = "numbertext">1 / 4</div>
                  <img src="assets/images/cert1.png" class= "image-slide style= "width:100%">
                </div>

                <div class= "mySlides">
                  <div class = "numbertext">2 / 4</div>
                  <img src="assets/images/cert2.png" class="image-slide" style= "width:100%">
                </div>

                <div class= "mySlides">
                  <div class = "numbertext">3 / 4</div>
                  <img src="assets/images/cert3.png" class="image-slide" style= "width:100%">
                </div>

                <div class= "mySlides">
                  <div class = "numbertext">4 / 4</div>
                  <img src="assets/images/cert4.png" class="image-slide" style= "width:100%">
                </div>

                <!-- controls -->
                <a class = "prev" onclick="plusSlides(-1)"> &#10094; </a>
                <a class = "next" onclick="plusSlides(1)"> &#10095; </a>

                <!-- thumbnails 
                <div class = "column">
                  <img class = "demo" src="assets/images/cert1.png" onclick = "currentSlide(1)">
                </div>

                <div class = "column">
                  <img class = "demo" src="assets/images/cert2.png" onclick = "currentSlide(2)">
                </div>

                <div class = "column">
                  <img class = "demo" src="assets/images/cert3.png" onclick = "currentSlide(3)">
                </div>

                <div class = "column">
                  <img class = "demo" src="assets/images/cert4.png" onclick = "currentSlide(4)">
                </div>  -->
                                                                                              
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="section my-work" data-section="section3">
        <div class="container">
          <div class="section-heading">
            <h2>Portfolio</h2>
            <div class="line-dec"></div>
            <span>
              I have spent most of my life learning and I don't intend to stop. However, I believe the best way to learn is to put my knowledge into practice.
              Here are some projects I have been working on:
            </span>
          </div>
          <div class="row">
            <p>
              <a href = "https://kathyrivera9.github.io/portfolio"> Click here for an experience!</a>
            </p>
          </div>
        </div>
      </section>

      <section class="section contact-me" data-section="section4">
        <div class="container">
          <div class="section-heading">
            <h2>Contact Me</h2>
            <div class="line-dec"></div>
            <span
              >HERE ILL PUT WAYS TO CONTACT ME INCLUDING MY EMAIL, PHONE NUMBER AND LINKEDIN</span
            >
          </div>
          <div class="row">
            <div class="right-content">
              <div class="container">
                <form id="contact" action="" method="post">
                  <div class="row">
                    <p>
                      THE ACTUAL LINKS 
                    </p>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>

    <!-- Scripts -->
    <!-- Bootstrap core JavaScript -->
    <script src="vendor/jquery/jquery.min.js"></script>
    <script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>

    <script src="assets/js/isotope.min.js"></script>
    <script src="assets/js/owl-carousel.js"></script>
    <script src="assets/js/lightbox.js"></script>
    <script src="assets/js/custom.js"></script>
    <script>
      //according to loftblog tut
      $(".main-menu li:first").addClass("active");

      var showSection = function showSection(section, isAnimate) {
        var direction = section.replace(/#/, ""),
          reqSection = $(".section").filter(
            '[data-section="' + direction + '"]'
          ),
          reqSectionPos = reqSection.offset().top - 0;

        if (isAnimate) {
          $("body, html").animate(
            {
              scrollTop: reqSectionPos
            },
            800
          );
        } else {
          $("body, html").scrollTop(reqSectionPos);
        }
      };

      var checkSection = function checkSection() {
        $(".section").each(function() {
          var $this = $(this),
            topEdge = $this.offset().top - 80,
            bottomEdge = topEdge + $this.height(),
            wScroll = $(window).scrollTop();
          if (topEdge < wScroll && bottomEdge > wScroll) {
            var currentId = $this.data("section"),
              reqLink = $("a").filter("[href*=\\#" + currentId + "]");
            reqLink
              .closest("li")
              .addClass("active")
              .siblings()
              .removeClass("active");
          }
        });
      };

      $(".main-menu").on("click", "a", function(e) {
        e.preventDefault();
        showSection($(this).attr("href"), true);
      });

      $(window).scroll(function() {
        checkSection();
      });
    </script>
  </body>                                   
</html>
