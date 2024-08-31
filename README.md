<!doctype html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rohan Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link
    href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
    rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link
    href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
    rel="stylesheet">
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="css/responsive.css">
</head>

<body>
  <nav class="navbar navbar-expand-lg ">
    <div class="container">
      <a class="navbar-brand text-dark" href="#">
        <img src="images/logo.svg" alt="Bootstrap" width="129" height="">
      </a>
      <button class="navbar-toggler shadow-none border-0" type="button" data-bs-toggle="offcanvas"
        data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="sidebar offcanvas offcanvas-start" tabindex="-1" id="offcanvasNavbar"
        aria-labelledby="offcanvasNavbarLabel">
        <div class="offcanvas-header">
          <h5 class="offcanvas-title" id="offcanvasNavbarLabel">
            <img src="images/logo.svg" alt="Bootstrap" width="100" height="">
          </h5>
          <button type="button" class="btn-close btn-close-black border-0 shadow-none" data-bs-dismiss="offcanvas"
            aria-label="Close"></button>
        </div>
        <div class="offcanvas-body">
          <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
            <li class="nav-item">
              <a class="nav-link active text-dark" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item text-dark">
              <a class="nav-link text-secondary" href="#scrollspyHeading1">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-secondary" href="#scrollspyHeading2">Services</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-secondary" href="#scrollspyHeading3">Skills</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-secondary" href="#">Portfoilio</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-secondary" href="#">Contact Us</a>
            </li>
            <!-- <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                aria-expanded="false">
                Dropdown
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li>
                  <hr class="dropdown-divider">
                </li>
                <li><a class="dropdown-item" href="#">Something else here</a></li>
              </ul>
            </li> -->
          </ul>
          <!-- <form class="d-flex mt-3" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form> -->
        </div>
      </div>
    </div>
  </nav>
  <div class="background-vectors">
    <img id="vector-1" src="images/background-vector.svg" alt="">
  </div>
  <!--hero-->
  <div class="container text-center hero">
    <div class="row align-items-start hero-row">
      <div class="col-6 hero-first-col">
        <div class="box">
          <div class="my-image">
            <img src="images/Mask group.png" alt="my-img">
          </div>
        </div>
      </div>
      <div class="col hero-second-col">
        <h1>Hi There !</h1>
        <div class="scrolling-words-container">
          <span class="title" style="color: #000000">I’M A </span>
          <div class="scrolling-words-box">
            <ul>
              <li style="color: #8B44C4">Web Designer</li>
              <li style="color: #8B44C4">UI/UX Designer</li>
              <li style="color: #8B44C4">Web Developer</li>
              <li style="color: #8B44C4">Web Designer</li>
              <li style="color: #8B44C4">UI/UX Designer</li>
            </ul>
          </div>
        </div>
        <p class="subtitle">I’m a UI Designer and Developer based in Kolkata,Hooghly. I Strives to build immersive and
          beautiful Web application throughcarefully crafted code and user-centric design.</p>
        <div class="d-grid gap-2 d-md-block button-flex">
          <button class="btn btn-primary hero-buttons about-btn" type="button">About Me</button>
          <button class="btn btn-primary hero-buttons portfolio-btn" type="button">Portfolio</button>
        </div>
      </div>
    </div>
  </div>
  <!-- /hero-->

  <!--About Us-->
  <div class="about-us bg" id="scrollspyHeading1">
    <!-- <div class="background-vectors">
      <img id="vector-2" src="images/background-vector2.svg" alt="">
    </div> -->
    <div class="container">
      <h1 class="main-title">About Us</h1>
      <h2 class="sub-heading">Hi, I’m <span class="rr" style="color: #101010">Rohan De</span></h2>
      <p class="subtitle">I’m a designer & developer with a passion for web design. I enjoy developing
        simple, clean and slick websites that provide real value to the end user.
        Thousands of clients have procured exceptional results while working with me.
        Delivering work within time and budget which meets client’s requirements is our
        moto.</p>
      <div class="text-first">
        <div class="row align-items-start detail-container">
          <div class="col my-detail">
            <span>Name:</span>
            <p>Rohan De</p>
          </div>
          <div class="col my-detail">
            <span>Email:</span>
            <p>rohande2402@gmail.com</p>
          </div>
          <div class="col my-detail">
            <span>Date of birth:</span>
            <p>24 February 2002</p>
          </div>
          <div class="col my-detail">
            <span>From:</span>
            <p>Dhaniakhali, Hooghly</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- /About US-->

  <!--services-->
  <div class="services" id="scrollspyHeading2">
    <div class="container">
      <h1 class="main-title">Services</h1>
      <p class="subtitle">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris
        ipsum sit nibh amet egestas tell us.</p>
      <div class="vector-3">
        <img id="vector-3" src="images/background-vector2.svg" alt="">
      </div>
      <div class="row align-items-start detail-container service">
        <div class="col my-services">
          <span>Web Developer</span>
          <p>Lorem Ipsum is simply dummy text of the
            printing and typesetting industry. Lorem
            Ipsum has been the industry’s standard
            dummy text.</p>
        </div>
        <div class="col my-services">
          <span>Web Design</span>
          <p>Lorem Ipsum is simply dummy text of the
            printing and typesetting industry. Lorem
            Ipsum has been the industry’s standard
            dummy text.</p>
        </div>
        <div class="col my-services">
          <span>UI/UX Design</span>
          <p>Lorem Ipsum is simply dummy text of the
            printing and typesetting industry. Lorem
            Ipsum has been the industry’s standard
            dummy text.</p>
        </div>
        <div class="col my-services">
          <span>PSD to HTML</span>
          <p>Lorem Ipsum is simply dummy text of the
            printing and typesetting industry. Lorem
            Ipsum has been the industry’s standard
            dummy text.</p>
        </div>
        <div class="col my-services">
          <span>Figma Design</span>
          <p>Lorem Ipsum is simply dummy text of the
            printing and typesetting industry. Lorem
            Ipsum has been the industry’s standard
            dummy text.</p>
        </div>
      </div>
    </div>
  </div>
  <!--/ services-->

  <!--skills-->
  <div class="skills bg" id="scrollspyHeading3">
    <div class="container">
      <h1 class="main-title">My Skills</h1>
      <div class="container text-center skills-g mt-4 mb-3">
        <div class="row align-items-start sr-vc">
          <div class="col skills-container">
            <img src="images/ux.svg" alt="" width="59" height="59">
            <p>UI/UX Design</p>
          </div>
          <div class="col skills-container">
            <img src="images/html-icon.svg" alt="" width="59" height="59">
            <p>HTML5</p>
          </div>
          <div class="col skills-container">
            <img src="images/css-icon.svg" alt="" width="59" height="59">
            <p>CSS3</p>
          </div>
          <div class="col skills-container">
            <img src="images/logos_javascript.svg" alt="" width="59" height="59">
            <p>JavaScript</p>
          </div>
          <div class="col skills-container">
            <img src="images/Bootstrap-logo.svg" alt="" width="59" height="59">
            <p>Bootstrap</p>
          </div>
          <div class="col skills-container">
            <img src="images/jquery-logo.svg" alt="" width="59" height="59">
            <p>JQuery</p>
          </div>
          <div class="col skills-container">
            <img src="images/figma-icon.svg" alt="" width="59" height="59">
            <p>Figma</p>
          </div>
          <div class="col skills-container">
            <img src="images/photoshop-icon.svg" alt="" width="59" height="59">
            <p>Photoshop</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!--/ Skills-->
  <script src="js/script.js"></script>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
    crossorigin="anonymous"></script>
</body>

</html>
