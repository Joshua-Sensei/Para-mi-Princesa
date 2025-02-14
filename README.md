<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Feliz Día Amor❤</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh; /* Cambiado de height a min-height para permitir scroll */
      background: linear-gradient(135deg, #8BC34A, #2196F3); /* Fondo verde cálido a azul cálido */
      font-family: 'Arial', sans-serif;
      color: white;
      text-align: center;
      /* overflow: hidden; */ /* Eliminado para permitir scroll */
    }

    .container {
      background: rgba(0, 0, 0, 0.5); /* Fondo semi-transparente para el texto */
      padding: 20px;
      border-radius: 15px;
      max-width: 600px;
      position: relative;
      margin-top: 20px; /* Margen superior reducido para bajar el contenido */
      z-index: 1; /* Asegura que el contenido esté sobre los efectos */
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
      color: #ff0000; /* Color rojo para el título */
    }

    p {
      font-size: 1.2rem;
      line-height: 1.6;
    }

    .date {
      font-size: 1.5rem;
      color: #00ff00; /* Color verde para la fecha */
      margin-top: 20px;
    }

    .photos {
      display: flex;
      justify-content: space-around;
      margin-top: 20px;
    }

    .photos img {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      border: 3px solid white;
      object-fit: cover;
    }

    /* Estilos para las imágenes en los costados */
    .heart-left, .heart-right {
      position: absolute;
      width: 150px; /* Tamaño mediano */
      height: auto;
    }

    .heart-left {
      left: -180px; /* Posición a la izquierda del contenedor */
      top: 50%;
      transform: translateY(-50%);
    }

    .heart-right {
      right: -180px; /* Posición a la derecha del contenedor */
      top: 50%;
      transform: translateY(-50%);
    }

    /* Efectos de corazones y rosas */
    .effect {
      position: absolute;
      pointer-events: none; /* Para que no interfieran con el contenido */
      animation: float 5s infinite ease-in-out;
    }

    .heart-effect {
      width: 30px;
      height: 30px;
      background: url('https://i.imgur.com/p9P7PN8.png') no-repeat center/cover; /* Imagen de corazón */
      animation: heartFloat 3s infinite ease-in-out;
    }

    .rose-effect {
      width: 40px;
      height: 40px;
      background: url('https://i.imgur.com/ME7lxPF.png') no-repeat center/cover; /* Imagen de rosa */
      animation: roseFloat 4s infinite ease-in-out;
    }

    /* Animaciones */
    @keyframes float {
      0% { transform: translateY(0) rotate(0deg); }
      50% { transform: translateY(-20px) rotate(180deg); }
      100% { transform: translateY(0) rotate(360deg); }
    }

    @keyframes heartFloat {
      0% { opacity: 0; transform: translateY(0) scale(0.5); }
      50% { opacity: 1; transform: translateY(-100px) scale(1); }
      100% { opacity: 0; transform: translateY(-200px) scale(0.5); }
    }

    @keyframes roseFloat {
      0% { opacity: 0; transform: translateY(0) rotate(0deg); }
      50% { opacity: 1; transform: translateY(-150px) rotate(180deg); }
      100% { opacity: 0; transform: translateY(-300px) rotate(360deg); }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Imagen en forma de corazón a la izquierda (fija) -->
    <img class="heart-left" src="https://i.imgur.com/EvwfAj6.jpeg" alt="Corazón izquierdo">
    
    <h1>❤️Feliz Día Amor❤️</h1>
    <p>
      Mi princesa, Feliz dia de San Valentin, estoy haciendo este detalle el 15 de Diciembre para poder enviartelo el dia 14/02, se que es 2 meses antes pero pienso hacer este mensaje web y tambien seguro te estare entregando un cuaderno en la noche cuando nos veamos, que tambien estoy comenzando hacerlo, espero que cuando lo veas te guste, porque lo hago con todo mi amor para ti Merly mi 👸❤️.
      <br><br> <!-- Separación después de "para ti Merly 👸❤️" -->
      Cada día a tu lado es un regalo🥰, una nueva razón para sonreír y un motivo más para creer en lo hermoso de la vida. Eres mi refugio, mi inspiración✨ y la luz que ilumina hasta mis días más grises. Sé que peleamos mucho, pero siempre tratamos de arreglarlo, aunque nos cueste lo intentamos. Siempre luchamos, nos reímos, lloramos, sonreímos, pero a pesar de eso aún nos seguimos amando, ya que eres lo unico que quiero en esta vida y perdon por cometer algunos fallos, pero no soy perfecto, pero cuando te dig oque te amo es porque te amo, creeme amor que yo te quiero solo a ti, pero gracias a ti ahora tengo muchas ganas y mucha felicidad.
      <br><br> <!-- Separación después de "tengo muchas ganas y mucha felicidad" -->
      No me imagino estar sin ti, ya que me doleria mucho si algun dia rompemos, ten por seguro que estaria extrañandote todos los dias y pensandote, pero se que no pasara porque por mi parte ya que te amo un monton, mucho mas de lo que te imaginas, espero que este dia podamos pasarlo juntos😍, quizas ya hallamos planeado como pásarlo , ya sea en casa o ya sea en la calle o sabes quizas te proponga ir a la playa y hacer como un picnic , bueno ya tu tambien me diras opciones.
      <br><br>
      Gracias por estar a mi lado amor💋, porfavor no me dejes, que enverdad tu eres la unica que quiero en mi futuro, te amo mucho con amor tu querido principe Joshua Antony.
    </p>
    <div class="photos">
      <img src="https://i.imgur.com/Hw3H9Uj.jpeg" alt="Foto 1">
      <img src="https://i.imgur.com/9B4qF49.jpeg" alt="Foto 2">
      <img src="https://i.imgur.com/OBNq4wS.jpeg" alt="Foto 3">
    </div>
    <div class="date">01/01/2024 - 14/02/2025</div>

    <!-- Imagen en forma de corazón a la derecha (fija) -->
    <img class="heart-right" src="https://i.imgur.com/4oyRX8j.jpeg" alt="Corazón derecho">
  </div>

  <!-- Efectos de corazones y rosas -->
  <script>
    function createEffect(type) {
      const effect = document.createElement('div');
      effect.className = `effect ${type}-effect`;
      effect.style.left = `${Math.random() * 100}vw`;
      effect.style.animationDuration = `${Math.random() * 3 + 2}s`;
      document.body.appendChild(effect);

      setTimeout(() => {
        effect.remove();
      }, 5000); // Elimina el efecto después de 5 segundos
    }

    setInterval(() => {
      createEffect('heart');
      createEffect('rose');
    }, 1000); // Crea un nuevo efecto cada segundo
  </script>
</body>
</html>
