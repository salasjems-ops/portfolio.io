# portfolio.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jems Salas | Portfolio</title>

    <!-- Bootstrap 5 -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Bootstrap Icons -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">

    <style>
        body{
            scroll-behavior: smooth;
        }

        .hero{
            min-height:100vh;
            display:flex;
            align-items:center;
            background:linear-gradient(135deg,#0d6efd,#0a58ca);
            color:white;
        }

        .profile-img{
            width:280px;
            height:280px;
            object-fit:cover;
            border-radius:50%;
            border:6px solid white;
            box-shadow:0 10px 30px rgba(0,0,0,.2);
        }

        .skill-badge{
            margin:5px;
            font-size:15px;
        }

        .project-card{
            transition:.3s;
        }

        .project-card:hover{
            transform:translateY(-10px);
        }

        footer{
            background:#212529;
            color:white;
        }
    </style>
</head>
<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
        <a class="navbar-brand fw-bold" href="#">
            Jems Salas
        </a>

        <button class="navbar-toggler" data-bs-toggle="collapse"
            data-bs-target="#navMenu">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navMenu">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#about">About</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#skills">Skills</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#projects">Projects</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#contact">Contact</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- HERO -->
<section class="hero">
    <div class="container">
        <div class="row align-items-center">

            <div class="col-lg-6 text-center text-lg-start">
                <h1 class="display-3 fw-bold">
                    Hi, I'm Jems Salas
                </h1>

                <h3 class="mb-3">
                    Information Technology Student
                </h3>

                <p class="lead">
                    Passionate about Software Development,
                    Artificial Intelligence, Machine Learning,
                    and Web Development.
                </p>

                <a href="#projects" class="btn btn-light btn-lg">
                    View Projects
                </a>
            </div>

            <div class="col-lg-6 text-center mt-5 mt-lg-0">
                <!-- Replace image path -->
                <img src="profile.jpg"
                     class="profile-img"
                     alt="Profile">
            </div>

        </div>
    </div>
</section>

<!-- ABOUT -->
<section id="about" class="py-5">
    <div class="container">

        <h2 class="text-center mb-5 fw-bold">
            About Me
        </h2>

        <div class="row justify-content-center">
            <div class="col-lg-8 text-center">

                <p class="fs-5">
                    I am a first-year Information Technology student
                    with a strong interest in software development,
                    artificial intelligence, and modern web technologies.
                    I enjoy building innovative solutions that solve
                    real-world problems and continuously improving my
                    technical skills through projects and research.
                </p>

            </div>
        </div>
    </div>
</section>

<!-- SKILLS -->
<section id="skills" class="py-5 bg-light">

    <div class="container">

        <h2 class="text-center mb-5 fw-bold">
            Skills
        </h2>

        <div class="text-center">

            <span class="badge bg-primary skill-badge p-3">HTML</span>
            <span class="badge bg-primary skill-badge p-3">CSS</span>
            <span class="badge bg-primary skill-badge p-3">Bootstrap</span>
            <span class="badge bg-primary skill-badge p-3">JavaScript</span>
            <span class="badge bg-primary skill-badge p-3">Python</span>
            <span class="badge bg-primary skill-badge p-3">Java</span>
            <span class="badge bg-primary skill-badge p-3">GitHub</span>
            <span class="badge bg-primary skill-badge p-3">Machine Learning</span>
            <span class="badge bg-primary skill-badge p-3">Deep Learning</span>
            <span class="badge bg-primary skill-badge p-3">Database Management</span>
            <span class="badge bg-primary skill-badge p-3">SDLC</span>

        </div>

    </div>

</section>

<!-- PROJECTS -->
<section id="projects" class="py-5">

    <div class="container">

        <h2 class="text-center mb-5 fw-bold">
            Projects
        </h2>

        <div class="row">

            <div class="col-md-6 mb-4">

                <div class="card shadow project-card h-100">

                    <div class="card-body">

                        <h4>GRAPHISCAN</h4>

                        <p>
                            AI-powered dysgraphia detection system
                            that analyzes handwriting patterns using
                            deep learning techniques to assist teachers
                            and parents.
                        </p>

                        <button class="btn btn-primary">
                            View Project
                        </button>

                    </div>

                </div>

            </div>

            <div class="col-md-6 mb-4">

                <div class="card shadow project-card h-100">

                    <div class="card-body">

                        <h4>SagingAI</h4>

                        <p>
                            An intelligent agricultural solution
                            utilizing AI technology for disease
                            detection and classification.
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

<!-- CONTACT -->
<section id="contact" class="py-5 bg-light">

    <div class="container">

        <h2 class="text-center mb-5 fw-bold">
            Contact Me
        </h2>

        <div class="row justify-content-center">

            <div class="col-lg-6">

                <div class="card shadow">

                    <div class="card-body text-center">

                        <h4>Let's Connect</h4>

                        <p>
                            Feel free to contact me through:
                        </p>

                        <p>
                            <i class="bi bi-envelope-fill"></i>
                            your-email@gmail.com
                        </p>

                        <p>
                            <i class="bi bi-github"></i>
                            github.com/yourusername
                        </p>

                        <p>
                            <i class="bi bi-linkedin"></i>
                            linkedin.com/in/yourusername
                        </p>

                    </div>

                </div>

            </div>

        </div>

    </div>

</section>

<!-- FOOTER -->
<footer class="py-4 text-center">
    <p class="mb-0">
        © 2026 Jems Salas | Portfolio Website
    </p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
