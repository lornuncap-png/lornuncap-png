<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Proyecto Musical - Iván Calderón</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#111;
    color:white;
    line-height:1.6;
}

header{
    background:#000;
    padding:20px;
    text-align:center;
    position:sticky;
    top:0;
    z-index:1000;
}

header h1{
    color:#00d4ff;
    margin-bottom:10px;
}

nav a{
    color:white;
    margin:0 15px;
    text-decoration:none;
    font-weight:bold;
    transition:0.3s;
}

nav a:hover{
    color:#00d4ff;
}

.banner{
    background:url('https://images.unsplash.com/photo-1493225457124-a3eb161ffa5f') center/cover;
    height:400px;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
}

.banner h2{
    background:rgba(0,0,0,0.6);
    padding:20px;
    border-radius:10px;
    font-size:40px;
}

section{
    padding:50px 10%;
}

h2{
    color:#00d4ff;
    margin-bottom:20px;
}

.card{
    background:#1c1c1c;
    padding:25px;
    border-radius:15px;
    margin-bottom:30px;
    box-shadow:0 0 10px rgba(0,0,0,0.5);
}

audio{
    width:100%;
    margin-top:15px;
}

.lyrics{
    white-space:pre-line;
    background:#222;
    padding:20px;
    border-radius:10px;
    margin-top:20px;
}

footer{
    background:#000;
    text-align:center;
    padding:30px;
    margin-top:50px;
}

ul{
    margin-left:20px;
}
</style>
</head>

<body>

<header>
    <h1>Proyecto Musical - Iván Calderón</h1>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#canciones">Canciones</a>
        <a href="#proceso">Proceso Creativo</a>
        <a href="#normas">Normas</a>
    </nav>
</header>

<section class="banner" id="inicio">
    <h2>Iván Calderón</h2>
</section>

<section>
    <h2>Bienvenida</h2>

    <p>
        Bienvenido a la página oficial del proyecto musical de 
        <strong>Iván Calderón</strong>.
    </p>

    <br>

    <p>
        Este proyecto muestra una propuesta artística basada en la música urbana,
        mezclando reggaetón melódico, R&B y pop latino.
    </p>

    <br>

    <p>
        La actividad consiste en crear una canción original utilizando herramientas
        de inteligencia artificial y creatividad musical.
    </p>
</section>

<section>
    <h2>Presentación del Artista</h2>

    <div class="card">

        <h3>Iván Calderón</h3>

        <p><strong>Origen:</strong> Barrio humilde de una gran ciudad</p>

        <p><strong>Estilo:</strong> Reggaetón melódico con influencias de R&B y pop latino</p>

        <br>

        <h3>Historia</h3>

        <p>
            Iván Calderón creció compartiendo habitación con sus dos hermanas,
            cantando bajito por las noches para no despertar a nadie.
            Su madre trabajaba de noche, así que Iván pasaba horas solo,
            grabándose con el móvil y subiendo canciones a internet sin mostrar su cara.
        </p>

        <br>

        <p>
            Durante mucho tiempo nadie lo escuchaba… hasta que un día un video suyo
            cantando en una azotea al amanecer empezó a circular.
            No tenía gran producción, solo su voz, el viento y una ciudad despertando detrás.
        </p>

        <br>

        <p>
            Cuando finalmente mostró su identidad, ya tenía seguidores que sentían
            que lo conocían de siempre.
            Hoy es conocido por sus canciones que mezclan ritmo urbano con emociones reales.
        </p>

    </div>
</section>

<section id="canciones">
    <h2>Canciones</h2>

    <div class="card">

        <h3>Quédate Cerquita</h3>

        <p><strong>Autor:</strong> Iván Calderón</p>

        <p><strong>Género Musical:</strong> Reggaetón melódico / R&B Latino</p>

        <p>
            Una canción emocional sobre el miedo a perder a alguien importante,
            mezclando sonidos urbanos suaves con una letra sentimental.
        </p>

        <!-- AUDIO CORREGIDO -->
        <audio controls>
            <source src="Todavía en Tu Puerta copy.mp3" type="audio/mpeg">
            Tu navegador no soporta el audio.
        </audio>

        <div class="lyrics">

[Verso 1]
Alless va a mí el pulso
Con ese vestido gris
Yo fingiendo eso está bien
pero me tiemblan hasta aquí

Lo perfumas en la camisa
Yo deja otravez así
pegado a lo que no música
Hay lo que puede seguir

[Pre-Coro]
Si te vas, yo quedo
Mirada el lugar mismo
Jura amanecer despacio
Que estamos debajo de mí un subdistancia

¿Ves ese dueles bonito
y eso hash me volver
Porscuido en tus labios pierdo me
como si huirá la prima vendrá

[Coro]
Quedada cerquita
No me suelte así
Quedate cerquita
Yo yo pierdo por ti

Quedada cerquita
Una persona me tenía sufritiva
Quedate cerquita
Si te vas, no hay seir

        </div>

    </div>
</section>

<section id="proceso">
    <h2>Proceso Creativo</h2>

    <div class="card">

        <h3>Idea Inicial</h3>

        <p>
            La canción nació con la idea de expresar una relación emocional
            donde existe miedo a la distancia y al abandono.
        </p>

        <br>

        <h3>Herramientas de IA Utilizadas</h3>

        <ul>
            <li>ChatGPT</li>
            <li>IA musical para generación de letras</li>
            <li>Editor de audio digital</li>
        </ul>

        <br>

        <h3>Prompts Utilizados</h3>

        <p>
            “Crear una canción de reggaetón melódico romántico con emociones reales”.
        </p>

        <br>

        <h3>Creación y Edición</h3>

        <p>
            La letra fue editada manualmente para mantener un estilo urbano,
            emocional y personal.
        </p>

    </div>
</section>

<section id="normas">
    <h2>Aviso Legal</h2>

    <div class="card">

        <h3>Uso Responsable de la IA</h3>

        <p>
            Este proyecto utiliza inteligencia artificial únicamente con fines educativos y creativos.
        </p>

        <br>

        <h3>Privacidad y Protección de Datos</h3>

        <p>
            No se recopilan datos personales. 
            El contenido respeta normas de copyright y creative commons.
        </p>

        <br>

        <h3>Derechos de Autor</h3>

        <p>
            La canción y el contenido del proyecto pertenecen a su autor original.
        </p>

    </div>
</section>

<footer>

    <h3>Proyecto Musical - Lorena Núñez Capitas</h3>

    <p>Curso: 2025 - 2026</p>

    <p>Materia: Tecnología / Música Digital</p>

    <p>Creado con HTML, CSS e Inteligencia Artificial</p>

</footer>

</body>
</html>
