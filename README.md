<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Bootstrap Icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">

    <style>
        body{
            font-family: Arial, sans-serif;
        }

        .hero{
            background: linear-gradient(135deg,#0d6efd,#6610f2);
            color:#fff;
            padding:120px 0;
        }

        .profile-img{
            width:250px;
            height:250px;
            object-fit:cover;
            border-radius:50%;
            border:8px solid rgba(255,255,255,.2);
        }

        .section-title{
            font-weight:bold;
            margin-bottom:30px;
        }

        .skill-box{
            background:#f8f9fa;
            padding:20px;
            border-radius:10px;
            text-align:center;
            transition:.3s;
        }

        .skill-box:hover{
            background:#0d6efd;
            color:white;
            transform:translateY(-5px);
        }

        .project-card img{
            height:220px;
            object-fit:cover;
        }

        footer{
            background:#212529;
            color:white;
            padding:20px;
        }
    </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
    <div class="container">
        <a class="navbar-brand fw-bold" href="#">My Portfolio</a>

        <button class="navbar-toggler"
                data-bs-toggle="collapse"
                data-bs-target="#menu">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="menu">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a href="#home" class="nav-link">Home</a>
                </li>

                <li class="nav-item">
                    <a href="#about" class="nav-link">About</a>
                </li>

                <li class="nav-item">
                    <a href="#skills" class="nav-link">Skills</a>
                </li>

                <li class="nav-item">
                    <a href="#projects" class="nav-link">Projects</a>
                </li>

                <li class="nav-item">
                    <a href="#contact" class="nav-link">Contact</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- Hero -->
<section class="hero" id="home">
    <div class="container">
        <div class="row align-items-center">

            <div class="col-lg-6">
                <h1 class="display-4 fw-bold">
                    Hello, I'm John Doe
                </h1>

                <p class="lead mt-3">
                    Web Developer | UI Designer | Freelancer
                </p>

                <p>
                    I build responsive websites using HTML, CSS,
                    Bootstrap, JavaScript and modern technologies.
                </p>

                <a href="#projects" class="btn btn-light btn-lg me-2">
                    View Work
                </a>

                <a href="#contact" class="btn btn-outline-light btn-lg">
                    Contact Me
                </a>
            </div>

            <div class="col-lg-6 text-center mt-5 mt-lg-0">
                <img src="https://via.placeholder.com/300"
                     class="profile-img"
                     alt="Profile">
            </div>

        </div>
    </div>
</section>

<!-- About -->
<section class="py-5" id="about">
    <div class="container">

        <h2 class="text-center section-title">
            About Me
        </h2>

        <div class="row">

            <div class="col-lg-6">
                <img src="https://via.placeholder.com/600x400"
                     class="img-fluid rounded shadow"
                     alt="">
            </div>

            <div class="col-lg-6">

                <h3>Professional Web Developer</h3>

                <p>
                    I create responsive websites and web applications
                    with clean UI and optimized performance.
                </p>

                <p>
                    I enjoy learning new technologies and building
                    creative digital experiences.
                </p>

                <button class="btn btn-primary">
                    Download Resume
                </button>

            </div>

        </div>

    </div>
</section>

<!-- Skills -->
<section class="py-5 bg-light" id="skills">

    <div class="container">

        <h2 class="text-center section-title">
            Skills
        </h2>

        <div class="row g-4">

            <div class="col-md-3">
                <div class="skill-box">
                    <i class="bi bi-filetype-html display-5"></i>
                    <h5 class="mt-3">HTML5</h5>
                </div>
            </div>

            <div class="col-md-3">
                <div class="skill-box">
                    <i class="bi bi-filetype-css display-5"></i>
                    <h5 class="mt-3">CSS3</h5>
                </div>
            </div>

            <div class="col-md-3">
                <div class="skill-box">
                    <i class="bi bi-bootstrap display-5"></i>
                    <h5 class="mt-3">Bootstrap</h5>
                </div>
            </div>

            <div class="col-md-3">
                <div class="skill-box">
                    <i class="bi bi-filetype-js display-5"></i>
                    <h5 class="mt-3">JavaScript</h5>
                </div>
            </div>

        </div>

    </div>

</section>

<!-- Projects -->
<section class="py-5" id="projects">

    <div class="container">

        <h2 class="text-center section-title">
            My Projects
        </h2>

        <div class="row g-4">

            <div class="col-md-4">

                <div class="card project-card shadow">

                    <img src="https://via.placeholder.com/500x300"
                         class="card-img-top">

                    <div class="card-body">

                        <h5>Portfolio Website</h5>

                        <p>
                            Responsive personal portfolio using
                            Bootstrap 5.
                        </p>

                        <button class="btn btn-primary">
                            View Project
                        </button>

                    </div>

                </div>

            </div>

            <div class="col-md-4">

                <div class="card project-card shadow">

                    <img src="https://via.placeholder.com/500x300"
                         class="card-img-top">

                    <div class="card-body">

                        <h5>E-Commerce</h5>

                        <p>
                            Modern shopping website with responsive UI.
                        </p>

                        <button class="btn btn-primary">
                            View Project
                        </button>

                    </div>

                </div>

            </div>

            <div class="col-md-4">

                <div class="card project-card shadow">

                    <img src="https://via.placeholder.com/500x300"
                         class="card-img-top">

                    <div class="card-body">

                        <h5>Dashboard</h5>

                        <p>
                            Bootstrap Admin Dashboard with charts and tables.
                        </p>

                        <button class="btn btn-primary">
                            View Project
                        </button>

                    </div>

                </div>

            </div>

        </div>

    </div>

</section>

<!-- Contact -->
<section class="py-5 bg-light" id="contact">

    <div class="container">

        <h2 class="text-center section-title">
            Contact Me
        </h2>

        <div class="row justify-content-center">

            <div class="col-lg-8">

                <form>

                    <div class="row">

                        <div class="col-md-6 mb-3">
                            <input
                                type="text"
                                class="form-control"
                                placeholder="Your Name">
                        </div>

                        <div class="col-md-6 mb-3">
                            <input
                                type="email"
                                class="form-control"
                                placeholder="Email">
                        </div>

                    </div>

                    <div class="mb-3">
                        <input
                            type="text"
                            class="form-control"
                            placeholder="Subject">
                    </div>

                    <div class="mb-3">
                        <textarea
                            rows="5"
                            class="form-control"
                            placeholder="Message"></textarea>
                    </div>

                    <button class="btn btn-primary">
                        Send Message
                    </button>

                </form>

            </div>

        </div>

    </div>

</section>

<!-- Footer -->
<footer class="text-center">

    <div class="container">

        <p class="mb-2">
            © 2026 My Portfolio. All Rights Reserved.
        </p>

        <div>
            <i class="bi bi-facebook fs-4 me-3"></i>
            <i class="bi bi-twitter-x fs-4 me-3"></i>
            <i class="bi bi-linkedin fs-4 me-3"></i>
            <i class="bi bi-github fs-4"></i>
        </div>

    </div>

</footer>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
