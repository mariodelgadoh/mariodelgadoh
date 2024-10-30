<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil de GitHub - [Tu Nombre]</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background: #1a1a1d;
            color: #f1f1f1;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        header {
            text-align: center;
            padding: 50px 0;
            background: #0d0d0d;
        }

        header h1 {
            font-size: 3.5em;
            color: #00a8ff;
            text-transform: uppercase;
            letter-spacing: 3px;
            margin: 0;
        }

        header h3 {
            font-size: 1.5em;
            color: #ff4757;
            letter-spacing: 2px;
            font-weight: 300;
            margin-top: 10px;
        }

        header img {
            width: 120px;
            margin-top: 20px;
        }

        section {
            padding: 60px 0;
            max-width: 1200px;
            margin: 0 auto;
        }

        section h2 {
            text-align: center;
            font-size: 2.5em;
            color: #00a8ff;
            margin-bottom: 50px;
            text-transform: uppercase;
        }

        section p {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
            font-size: 1.2em;
            line-height: 1.8;
            text-align: justify;
            margin: 0 auto;
            width: 90%;
            max-width: 1000px;
        }

        .skills, .projects {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
        }

        .skill-item {
            width: 200px;
            text-align: center;
        }

        .skill-item img {
            width: 100px;
            filter: drop-shadow(2px 2px 10px #00a8ff);
            transition: transform 0.3s ease;
        }

        .skill-item img:hover {
            transform: scale(1.1);
        }

        .project-card {
            width: 45%;
            background-color: #222;
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.5);
        }

        .project-card h3 {
            font-size: 1.8em;
            color: #1e90ff;
            margin-bottom: 10px;
        }

        .project-card p {
            color: #ddd;
            font-size: 1.1em;
        }

        footer {
            padding: 30px 0;
            text-align: center;
            background: #111;
            color: #aaa;
            font-size: 1.1em;
        }

        footer a {
            text-decoration: none;
            color: #00a8ff;
            margin: 0 10px;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Animaciones */
        @keyframes floating {
            0% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0); }
        }

        .skill-item img {
            animation: floating 3s infinite ease-in-out;
        }
    </style>
</head>
<body>

<header>
    <h1>[Tu Nombre]</h1>
    <h3>Estudiante en la Universidad de Guanajuato</h3>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Escudo_de_la_Universidad_de_Guanajuato.svg/1200px-Escudo_de_la_Universidad_de_Guanajuato.svg.png" alt="Logo UG">
</header>

<!-- Sección Acerca de mí -->
<section>
    <h2>Acerca de mí</h2>
    <p>
        Soy un estudiante apasionado por el desarrollo de software y la tecnología. Actualmente, estoy cursando la carrera de Ingeniería en [Carrera] en la Universidad de Guanajuato. Mi enfoque principal es aprender y mejorar mis habilidades en tecnologías como <strong>JavaScript, Python, Vue.js y Node.js</strong>. Me entusiasma trabajar en proyectos colaborativos y siempre busco nuevas oportunidades para crecer profesionalmente.
    </p>
</section>

<!-- Habilidades Técnicas -->
<section class="skills">
    <h2>Habilidades Técnicas</h2>
    <div class="skills">
        <div class="skill-item">
            <img src="https://img.icons8.com/color/96/000000/javascript.png" alt="JavaScript">
            <p>JavaScript</p>
        </div>
        <div class="skill-item">
            <img src="https://img.icons8.com/color/96/000000/python.png" alt="Python">
            <p>Python</p>
        </div>
        <div class="skill-item">
            <img src="https://img.icons8.com/color/96/000000/vue-js.png" alt="Vue.js">
            <p>Vue.js</p>
        </div>
        <div class="skill-item">
            <img src="https://img.icons8.com/color/96/000000/nodejs.png" alt="Node.js">
            <p>Node.js</p>
        </div>
    </div>
</section>

<!-- Proyectos -->
<section class="projects">
    <h2>Proyectos</h2>
    <div class="project-card">
        <h3><a href="https://github.com/tuUsuario/proyecto1" style="text-decoration: none; color: #1e90ff;">Proyecto 1: App Universitaria</a></h3>
        <p>Desarrollo de una aplicación para la gestión de horarios y tareas. Tecnologías: Vue.js, Firebase.</p>
    </div>
    <div class="project-card">
        <h3><a href="https://github.com/tuUsuario/proyecto2" style="text-decoration: none; color: #1e90ff;">Proyecto 2: Portal de Empleos UG</a></h3>
        <p>Un portal para estudiantes y egresados de la UG que conecta con oportunidades laborales. Tecnologías: React, Node.js.</p>
    </div>
</section>

<!-- Sección de Contacto -->
<footer>
    <p>📫 Contacto:</p>
    <a href="mailto:tuemail@gmail.com">Correo</a> |
    <a href="https://www.linkedin.com/in/tuUsuario">LinkedIn</a> |
    <a href="https://github.com/tuUsuario">GitHub</a>
</footer>

</body>
</html>
