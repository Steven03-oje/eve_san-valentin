<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>San Valentín Romántico</title>
    <style>
        /* Estilos generales */
        body {
            font-family: 'Dancing Script', cursive; /* Tipografía romántica */
            background: linear-gradient(135deg, #ff8fab, #ff3b3b);
            color: #ffffff;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            position: relative;
        }

        /* Corazones flotando en el fondo */
        .heart {
            position: absolute;
            color: #b30000;
            font-size: 2rem;
            animation: float 6s ease-in-out infinite;
            opacity: 0.7;
        }
        .heart:nth-child(odd) { animation-delay: -2s; }
        .heart:nth-child(even) { animation-delay: -4s; }
        @keyframes float {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(10deg); }
        }

        /* Contenedor principal */
        .container {
            text-align: center;
            z-index: 1;
            max-width: 90%;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }

        /* Fotos */
        .photos {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 20px;
        }
        .photos img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid #ffffff;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
        }
        .photos img:hover {
            transform: scale(1.1);
        }

        /* Título */
        h1 {
            font-size: 3rem;
            margin-bottom: 30px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        /* Mensaje dinámico */
        #message {
            font-size: 1.5rem;
            margin-bottom: 30px;
            opacity: 0;
            transition: opacity 0.5s ease;
        }
        #message.show {
            opacity: 1;
        }

        /* Botones */
        .buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        button {
            font-family: 'Dancing Script', cursive;
            font-size: 2rem;
            padding: 15px 30px;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }
        #yesBtn {
            background: #ff8fab;
            color: #ffffff;
        }
        #noBtn {
            background: #ff3b3b;
            color: #ffffff;
        }
        button:hover {
            transform: scale(1.05);
        }

        /* Animación de corazones al decir sí */
        .hearts-animation {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            display: none;
        }
        .hearts-animation.show {
            display: block;
        }
        .heart-burst {
            position: absolute;
            font-size: 3rem;
            color: #b30000;
            animation: burst 2s ease-out forwards;
        }
        @keyframes burst {
            0% { transform: scale(0) rotate(0deg); opacity: 1; }
            50% { transform: scale(1.5) rotate(180deg); opacity: 0.8; }
            100% { transform: scale(0) rotate(360deg); opacity: 0; }
        }

        /* Responsive */
        @media (max-width: 768px) {
            h1 { font-size: 2rem; }
            .photos { flex-direction: column; gap: 10px; }
            .photos img { width: 120px; height: 120px; }
            button { font-size: 1.5rem; padding: 10px 20px; }
            .buttons { flex-direction: column; gap: 10px; }
        }
        @media (max-width: 480px) {
            h1 { font-size: 1.5rem; }
            .photos img { width: 100px; height: 100px; }
            button { font-size: 1.2rem; padding: 8px 16px; }
        }
    </style>
</head>
<body>
    <!-- Corazones flotando -->
    <div class="heart" style="top: 10%; left: 10%;">❤️</div>
    <div class="heart" style="top: 20%; right: 15%;">💖</div>
    <div class="heart" style="top: 40%; left: 20%;">💘</div>
    <div class="heart" style="top: 60%; right: 10%;">💕</div>
    <div class="heart" style="top: 80%; left: 15%;">💓</div>
    <div class="heart" style="top: 30%; left: 50%;">💗</div>
    <div class="heart" style="top: 70%; right: 20%;">💞</div>

    <!-- Contenedor principal -->
    <div class="container">
        <!-- Fotos -->
        <div class="imagenes">
            <div class="photos">
                <img src="imagenes/foto8.jpg" alt="A smiling young woman with long dark hair wearing a light-colored shirt and black lace vest, seated at a dining table with food and drinks, warm wooden interior with rustic furniture in background">
                <img src="imagenes/foto5.jpg" alt="foto5">
            </div>

        <!-- Título -->
        <h1>¿Quieres ser mi San Valentín? ❤️</h1>

        <!-- Mensaje dinámico -->
        <div id="message"></div>

        <!-- Botones -->
        <div class="buttons">
            <button id="yesBtn">Sí</button>
            <button id="noBtn">No</button>
        </div>
    </div>

    <!-- Animación de corazones al decir sí -->
    <div class="hearts-animation" id="heartsAnimation">
        <!-- Corazones se generan dinámicamente con JS -->
    </div>

    <!-- Audio opcional (comentado) -->
    <!-- <audio id="romanticSound" src="https://www.soundjay.com/misc/sounds/bell-ringing-05.wav" preload="auto"></audio> -->

    <script>
        // Elementos del DOM
        const message = document.getElementById('message');
        const yesBtn = document.getElementById('yesBtn');
        const noBtn = document.getElementById('noBtn');
        const heartsAnimation = document.getElementById('heartsAnimation');
        // const romanticSound = document.getElementById('romanticSound'); // Opcional

        // Lista de frases románticas
        const phrases = [
            "¿Estás seguro? ❤️",
            "Piénsalo otra vez 🥺",
            "Prometo hacerte feliz 💖",
            "Eres muy especial ✨",
            "Dale una oportunidad al amor 💘",
            "Mi corazón dice que sí ❤️"
        ];

        let noClickCount = 0;
        let yesSize = 1;
        let noSize = 1;

        // Función para el botón "No"
        noBtn.addEventListener('click', () => {
            noClickCount++;
            if (noClickCount < phrases.length) {
                message.textContent = phrases[noClickCount - 1];
                message.classList.add('show');
            } else {
                message.textContent = "Por favor, di que sí 💕";
            }

            // Ajustar tamaños
            yesSize += 0.2;
            noSize = Math.max(0.1, noSize - 0.2); // No se hace más pequeño que 0.1

            yesBtn.style.transform = `scale(${yesSize})`;
            noBtn.style.transform = `scale(${noSize})`;
        });

        // Función para el botón "Sí"
        yesBtn.addEventListener('click', () => {
            // Ocultar botones y mensaje
            document.querySelector('.buttons').style.display = 'none';
            message.textContent = "Sabía que dirías que sí ❤️✨";
            message.classList.add('show');

            // Mostrar animación de corazones
            heartsAnimation.classList.add('show');
            for (let i = 0; i < 20; i++) {
                const heart = document.createElement('div');
                heart.className = 'heart-burst';
                heart.textContent = '💖';
                heart.style.left = Math.random() * 100 + '%';
                heart.style.top = Math.random() * 100 + '%';
                heart.style.animationDelay = Math.random() * 2 + 's';
                heartsAnimation.appendChild(heart);
            }

            // Reproducir sonido opcional
            // romanticSound.play();
        });
    </script>
</body>
</html>
