
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Empleo con Apoyo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: linear-gradient(to right, #ff9966, #ff5e62);
            color: white;
        }
        @keyframes moverTitulo {
            0% { transform: translateX(0); }
            50% { transform: translateX(20px); }
            100% { transform: translateX(0); }
        }
        h1 {
            font-size: 3em;
            animation: moverTitulo 2s infinite;
        }
        .botones {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            margin: 20px;
        }
        .boton {
            background-color: #ffcc00;
            color: black;
            padding: 15px 25px;
            margin: 10px;
            border: none;
            cursor: pointer;
            font-size: 1.2em;
            border-radius: 10px;
            text-decoration: none;
            display: inline-block;
        }
        .boton:hover {
            background-color: #ff9900;
        }
        .seccion {
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.6);
            margin: 20px auto;
            border-radius: 10px;
            width: 80%;
        }
    </style>
</head>
<body>
    <h1>Empleo con Apoyo</h1>
    <p>Un modelo de inserción laboral diseñado para personas con discapacidad u otras dificultades de acceso al empleo.</p>
    
    <div class="botones">
        <a href="#evaluacion" class="boton">Evaluación Individualizada</a>
        <a href="#busqueda" class="boton">Búsqueda de Empleo</a>
        <a href="#intermediacion" class="boton">Intermediación Laboral</a>
        <a href="#formacion" class="boton">Formación y Capacitación</a>
        <a href="#acompanamiento" class="boton">Acompañamiento Inicial</a>
        <a href="#adaptaciones" class="boton">Adaptaciones Laborales</a>
        <a href="#seguimiento" class="boton">Apoyo Continuo</a>
        <a href="#autonomia" class="boton">Fomento de Autonomía</a>
        <a href="#sensibilizacion" class="boton">Sensibilización Empresarial</a>
        <a href="#coordinacion" class="boton">Coordinación Familiar</a>
    </div>

    <div id="evaluacion" class="seccion">
        <h2>Evaluación Individualizada</h2>
        <p>Se analizará el perfil de la persona, habilidades, intereses y necesidades para buscar un empleo adecuado.</p>
    </div>
    <div id="busqueda" class="seccion">
        <h2>Búsqueda de Empleo</h2>
        <p>Se identificarán oportunidades laborales accesibles y compatibles con las capacidades del trabajador.</p>
    </div>
    <div id="intermediacion" class="seccion">
        <h2>Intermediación Laboral</h2>
        <p>Se facilitará el contacto entre la persona y los empleadores, asegurando una comunicación sobre los apoyos necesarios.</p>
    </div>
    <div id="formacion" class="seccion">
        <h2>Formación y Capacitación</h2>
        <p>Se brindarán entrenamientos de habilidades técnicas, sociales y laborales para la adaptación al puesto de trabajo.</p>
    </div>
    <div id="acompanamiento" class="seccion">
        <h2>Acompañamiento Inicial</h2>
        <p>Un preparador laboral ayudará a la persona en sus primeras semanas de trabajo, asegurando la integración correcta.</p>
    </div>
    <div id="adaptaciones" class="seccion">
        <h2>Adaptaciones Laborales</h2>
        <p>Se pueden realizar modificaciones en el espacio de trabajo, herramientas o tareas para mejorar la accesibilidad y productividad.</p>
    </div>
    <div id="seguimiento" class="seccion">
        <h2>Apoyo Continuo</h2>
        <p>Se realizarán reuniones periódicas con el trabajador y el empleador para evaluar el progreso y realizar ajustes si fuera necesario.</p>
    </div>
    <div id="autonomia" class="seccion">
        <h2>Fomento de Autonomía</h2>
        <p>Se buscará reducir el apoyo hasta que la persona pueda desempeñar su independencia.</p>
    </div>
    <div id="sensibilizacion" class="seccion">
        <h2>Sensibilización Empresarial</h2>
        <p>Se trabajará con empresas para promover la inclusión, eliminar prejuicios y garantizar un entorno laboral respetuoso.</p>
    </div>
    <div id="coordinacion" class="seccion">
        <h2>Coordinación Familiar</h2>
        <p>Se mantendrá una comunicación constante con la red de apoyo del trabajador para reforzar su bienestar y estabilidad laboral.</p>
    </div>
