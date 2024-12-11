<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Radio Neysan Plus </title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: black; /* Fondo negro */
            height: 100vh; /* Altura del body en 100% de la altura de la ventana */
            display: flex;
            flex-direction: column; /* Permite que los elementos se apilen verticalmente */
            justify-content: flex-end; /* Alinea el contenido al final (parte inferior) */
            overflow: hidden; /* Evita el desplazamiento por contenido adicional */
        }

        .background-image {
            position: absolute; /* Asegura que la imagen esté detrás del contenido */
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: url('https://i.ibb.co/vjLC9vJ/10f04b70-ed9f-45bd-8aa6-76e3283b65fe.jpg');
            background-size: contain; /* Mantiene la proporción de la imagen dentro de los límites */
            background-position: center; /* Centra la imagen */
            background-repeat: no-repeat; /* Evita que la imagen se repita */
            z-index: 0; /* Asegura que la imagen esté detrás de todos los elementos */
            animation: spin 10s linear infinite; /* Gira la imagen */
        }

        @keyframes spin {
            0% {
                transform: rotate(0deg);
            }
            50% {
                transform: rotate(360deg); /* Gira 360 grados */
            }
            100% {
                transform: rotate(0deg); /* Vuelve a la posición inicial */
            }
        }

        .footer-player {
            position: fixed; /* Fijo en la parte inferior */
            bottom: 0; /* Alineado a la parte inferior */
            width: 100%; /* Ancho total */
            background-color: rgba(0, 128, 0, 0.8); /* Color verde con un poco de transparencia */
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 10px 0;
            gap: 20px;
            z-index: 2; /* Asegura que el reproductor esté por encima de la imagen */
        }

        .player-container {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .logo {
            width: 40px;
            height: 40px;
        }

        #playPauseBtn {
            background-color: white;
            color: #000000;
            border: none;
            padding: 10px;
            cursor: pointer;
            font-size: 20px;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: background-color 0.3s;
        }

        #playPauseBtn:hover {
            background-color: #00a000;
        }

        .volume-slider {
            appearance: none;
            width: 100px;
            height: 5px;
            background: black;
            outline: none;
            cursor: pointer;
            border-radius: 5px;
        }

        /* Estilos del menú hamburguesa */
        .menu {
            position: fixed;
            top: 20px;
            left: 20px;
            z-index: 10;
        }

        .menu-button {
            background: none;
            border: none;
            cursor: pointer;
            font-size: 30px;
            color: white;
        }

        .menu-content {
            display: none;
            flex-direction: column;
            background-color: rgba(0, 128, 0, 0.8);
            position: absolute;
            top: 50px;
            left: 0;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }

        .menu-content a {
            text-decoration: none;
            color: white;
            margin: 5px 0;
            display: flex;
            align-items: center; /* Centra verticalmente el icono y el texto */
        }

        .menu-content img.logo {
            width: 60px; /* Aumenta el tamaño del logo */
            height: 60px; /* Aumenta el tamaño del logo */
            margin-bottom: 10px; /* Espacio debajo del logo */
        }

        .menu-content img {
            width: 24px; /* Mantiene el tamaño de los iconos de redes sociales */
            height: 24px;
            margin-right: 10px;
            vertical-align: middle; /* Alinea verticalmente el icono */
        }
    </style>
</head>
<body>

    <div class="background-image"></div> <!-- Div para la imagen de fondo -->

    <div class="menu">
        <button class="menu-button" onclick="toggleMenu()">&#9776;</button>
        <div class="menu-content" id="menuContent">
            <a href="#"><img class="logo" src=" https://i.ibb.co/Y2Ygd6f/neysan-plus.png" alt="Logo"></a>
            <a href="https://wa.me/1234567890"><img src="https://img.icons8.com/ios-filled/50/ffffff/whatsapp.png" alt="WhatsApp"> WhatsApp</a>
            <a href="https://t.me/yourchannel"><img src="https://img.icons8.com/ios-filled/50/ffffff/telegram.png" alt="Telegram"> Telegram</a>
            <a href="https://www.youtube.com/yourchannel"><img src="https://img.icons8.com/ios-filled/50/ffffff/youtube.png" alt="YouTube"> YouTube</a>
            <a href="https://www.instagram.com/yourprofile"><img src="https://img.icons8.com/ios-filled/50/ffffff/instagram.png" alt="Instagram"> Instagram</a>
        </div>
    </div>

    <footer class="footer-player">
        <img src="https://i.ibb.co/Y2Ygd6f/neysan-plus.png" alt="Logo" class="logo">
        <div class="player-container">
            <button id="playPauseBtn" onclick="togglePlay()">&#9658;</button>
            <input type="range" id="volumeSlider" class="volume-slider" min="0" max="1" step="0.01" value="0.5">
            <audio id="audioPlayer" src="http://nazca.globalhost1.com:8040/stream"></audio>
        </div>
    </footer>

    <script>
        const audioPlayer = document.getElementById('audioPlayer');
        const playPauseBtn = document.getElementById('playPauseBtn');
        const volumeSlider = document.getElementById('volumeSlider');

        function togglePlay() {
            if (audioPlayer.paused) {
                audioPlayer.play();
                playPauseBtn.innerHTML = '&#10074;&#10074;'; // Cambia a icono de pausa
            } else {
                audioPlayer.pause();
                playPauseBtn.innerHTML = '&#9658;'; // Cambia a icono de play
            }
        }

        volumeSlider.addEventListener('input', function() {
            audioPlayer.volume = volumeSlider.value;
        });

        function toggleMenu() {
            const menuContent = document.getElementById('menuContent');
            menuContent.style.display = menuContent.style.display === 'flex' ? 'none' : 'flex';
        }
    </script>
</body>
</html>
