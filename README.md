<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil de GitHub - [Tu Nombre]</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(135deg, #1a1a1d, #2b2b2e);
            color: #f1f1f1;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        header {
            text-align: center;
            padding: 60px 0;
            background: #101010;
            position: relative;
        }

        header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://cdn.pixabay.com/photo/2017/08/30/12/45/circuit-board-2692640_1280.png') no-repeat center/cover;
            opacity: 0.1;
            z-index: 1;
        }

        header h1 {
            font-size: 3.5em;
            color: #00a8ff;
            letter-spacing: 3px;
            z-index: 2;
            position: relative;
        }

        header h3 {
            font-size: 1.7em;
            color: #ff4757;
            letter-spacing: 2px;
            font-weight: 300;
            margin-top: 10px;
            z-index: 2;
            position: relative;
        }

        header img {
            width: 150px;
            margin-top: 20px;
            position: relative;
            z-index: 2;
        }

        section {
            padding: 60px 0;
            max-width: 1200px;
            margin: 0 auto;
            position: relative;
            z-index: 2;
        }

        section h2 {
            text-align: center;
            font-size: 2.5em;
            color: #00a8ff;
            margin-bottom: 50px;
            text-transform: uppercase;
            position: relative;
        }

        section p {
            background: rgba(255, 255, 255, 0.05);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.7);
            font-size: 1.2em;
            line-height: 1.8;
            text-align: justify;
            margin: 0 auto;
            width: 90%;
            max-width: 1000px;
        }

        .skills {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
        }

        .skill-item {
            width: 200px;
            text-align: center;
            transition: transform 0.3s ease;
            perspective: 1000px;
        }

        .skill-item img {
            width: 120px;
            height: 120px;
            filter: drop-shadow(2px 2px 10px #00a8ff);
            transition: transform 0.6s ease;
            transform: rotateY(0deg);
            perspective: 1000px;
        }

        .skill-item:hover img {
            transform: rotateY(360deg);
        }

        .skill-item p {
            margin-top: 10px;
            font-size: 1.2em;
            color: #ddd;
        }

        .projects {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 30px;
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
            transition: color 0.3s;
        }

        footer a:hover {
            color: #ff4757;
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
        Soy estudiante de la Universidad de Guanajuato, donde actualmente curso la carrera de [tu carrera]. Mi enfoque es el desarrollo de software, especialmente tecnologías como <strong>JavaScript, Python, Vue.js y Node.js</strong>. Me apasiona resolver problemas mediante la programación y crear soluciones innovadoras.
    </p>
</section>

<!-- Habilidades Técnicas -->
<section>
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
<section>
    <h2>Proyectos</h2>
    <div class="projects">
        <div class="project-card">
            <h3><a href="https://github.com/tuUsuario/proyecto1" style="text-decoration: none; color: #1e90ff;">Proyecto 1: App Universitaria</a></h3>
            <p>Desarrollo de una aplicación para gestión de tareas y horarios. Tecnologías: Vue.js, Firebase.</p>
        </div>
        <div class="project-card">
            <h3><a href="https://github.com/tuUsuario/proyecto2" style="text-decoration: none; color: #1e90ff;">Proyecto 2: Portal de Empleos UG</a></h3>
            <p>Plataforma para conectar estudiantes con oportunidades laborales. Tecnologías: React, Node.js.</p>
        </div>
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
