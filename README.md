<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bárbara Puyol - Desarrolladora Full-Stack</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            background-color: #121212;
            color: #e0e0e0;
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            text-align: center;
            margin-bottom: 20px;
        }

        header h1 {
            font-size: 2.5em;
            margin-bottom: 0.2em;
        }

        header h2 {
            font-size: 1.5em;
            color: #00e676;
            margin-bottom: 1em;
        }

        header .description {
            font-size: 1.1em;
            color: #b0bec5;
        }

        section {
            margin-bottom: 30px;
        }

        section h3 {
            font-size: 1.8em;
            border-bottom: 2px solid #00e676;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        section .skills,
        section .experience,
        section .education,
        section .projects,
        section .contact {
            list-style-type: none;
            padding: 0;
        }

        section .skills li {
            background-color: #1e1e1e;
            display: inline-block;
            margin: 5px;
            padding: 10px 20px;
            border-radius: 5px;
            font-size: 1em;
            color: #00e676;
        }

        section .experience div,
        section .education div,
        section .projects div,
        section .contact p {
            background-color: #1e1e1e;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 15px;
        }

        section .experience div h4,
        section .education div h4,
        section .projects div h4 {
            font-size: 1.3em;
            color: #00e676;
            margin-bottom: 10px;
        }

        section .experience div p,
        section .education div p,
        section .projects div p,
        section .contact p {
            font-size: 1em;
            color: #b0bec5;
        }

        section .projects div a {
            color: #00e676;
            text-decoration: none;
        }

        section .projects div a:hover {
            text-decoration: underline;
        }

        .contact a {
            color: #00e676;
            text-decoration: none;
        }

        .contact a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Bárbara Puyol</h1>
            <h2>Desarrolladora Full-Stack</h2>
            <p class="description">
                Apasionada técnica de producción audiovisual y recién graduada en Desarrollo Full-Stack. Capaz de ofrecer un apoyo integral en todas las etapas de producción, desde el rodaje hasta la postproducción. Con habilidades técnicas sólidas y una pasión por la calidad visual y sonora, me enorgullezco de colaborar estrechamente con los equipos para superar cualquier desafío.
            </p>
        </header>
        <section>
            <h3><i class="fas fa-laptop-code"></i> Habilidades</h3>
            <ul class="skills">
                <li>JavaScript</li>
                <li>ReactJS</li>
                <li>Python</li>
                <li>Flask</li>
                <li>HTML5/CSS3</li>
                <li>SQL</li>
                <li>GIT/GitHub</li>
            </ul>
        </section>
        <section>
            <h3><i class="fas fa-briefcase"></i> Experiencia</h3>
            <div class="experience">
                <div>
                    <h4>Director de Producción en Kahuna Films</h4>
                    <p>Dirigí proyectos audiovisuales para marcas reconocidas, gestionando todas las etapas desde la planificación hasta la postproducción.</p>
                </div>
                <div>
                    <h4>Marketing y Redes Sociales en Platea Gym</h4>
                    <p>Gestioné la página web, diseñé campañas publicitarias y materiales gráficos, y manejé redes sociales, implementando estrategias que incrementaron la visibilidad y captación de leads.</p>
                </div>
                <div>
                    <h4>Gestión Web en Camaleon Rental</h4>
                    <p>Encargada del mantenimiento y actualización de la página web, asegurando una presencia en línea efectiva.</p>
                </div>
            </div>
        </section>
        <section>
            <h3><i class="fas fa-graduation-cap"></i> Formación</h3>
            <div class="education">
                <div>
                    <h4>4Geeks Academy España</h4>
                    <p>Desarrollo Full Stack, Desarrollo de Software (nov. 2023 - may. 2024)
                        <br> Durante este bootcamp intensivo, adquirí habilidades en tecnologías front-end y back-end como HTML, CSS, JavaScript, React, Node.js, Python y bases de datos.
                    </p>
                </div>
            </div>
        </section>
        <section>
            <h3><i class="fas fa-project-diagram"></i> Proyectos</h3>
            <div class="projects">
                <div>
                    <h4>My Mood</h4>
                    <p>Proyecto Final 4Geeks Academy (abr. 2024 - may. 2024)
                        <br> My Mood - Red Social para Personas y Profesionales: Conecta a personas y profesionales en un entorno seguro donde poder compartir emociones y brindar ayuda profesional.
                        <a href="https://github.com/bpuyol/My-Mood-Final-Project" target="_blank">Ver proyecto en GitHub</a>
                    </p>
                </div>
            </div>
        </section>
        <section>
            <h3><i class="fas fa-envelope"></i> Contacto</h3>
            <div class="contact">
                <p>Email: <a href="mailto:b.puyolfont@gmail.com">b.puyolfont@gmail.com</a></p>
                <p>LinkedIn: <a href="https://www.linkedin.com/in/barbara-puyol-font/" target="_blank">linkedin.com/in/bpuyol</a></p>
                <p>GitHub: <a href="https://github.com/bpuyol" target="_blank">github.com/bpuyol</a></p>
                <p>Codepen: <a href="https://codepen.io/bpuyol" target="_blank">codepen.io/bpuyol</a></p>
            </div>
        </section>
    </div>
</body>
</html>
