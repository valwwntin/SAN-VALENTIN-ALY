# SAN-VALENTIN-ALY

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Invitación a San Valentín</title>
    <style>
        body {
            background-color: #fef5e7;
            font-family: 'Arial', sans-serif;
            color: #4a4e69;
            margin: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            overflow: hidden;
        }
        .container {
            text-align: center;
        }
        h1 {
            font-size: 2.5rem;
            color: #ff6f61;
        }
        button {
            background-color: #ff9a8d;
            border: none;
            border-radius: 15px;
            color: white;
            padding: 10px 20px;
            font-size: 1.2rem;
            cursor: pointer;
            margin: 10px;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #f8a5c2;
        }
        #gifContainer img,
        #happyGifContainer img,
        #happyGifContainer2 img,
        #happyGifContainer3 img,
        #happyGifContainer4 img,
        #sadGifContainer img,
        #sadGifContainer1 img,
        #sadGifContainer2 img {
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <div id="gifContainer">
            <img id="gifContainerImg" src="https://encoded.pe/codepen/mocha.gif" alt="Ositos Iniciales">
        </div>
        <div id="happyGifContainer" style="display: none;">
            <img src="https://encoded.pe/codepen/mocha.gif" alt="Ositos Felices" style="width: 100%; height: 100%;">
        </div>
        <div id="happyGifContainer2" style="display: none;">
            <img src="https://encoded.pe/codepen/mocha6final.gif" alt="Ositos Felices" style="width: 100%; height: 100%;">
        </div>
        <div id="happyGifContainer3" style="display: none;">
            <img src="https://encoded.pe/codepen/mocha7final.gif" alt="Ositos Felices" style="width: 100%; height: 100%;">
        </div>
        <div id="happyGifContainer4" style="display: none;">
            <img src="https://encoded.pe/codepen/mocha9final.gif" alt="Ositos Felices" style="width: 100%; height: 100%;">
        </div>
        <div id="sadGifContainer" style="display: none;">
            <img src="https://encoded.pe/codepen/mocha2.gif" alt="Osito Triste" style="width: 80%; height: 80%;">
        </div>
        <div id="sadGifContainer1" style="display: none;">
            <img src="https://encoded.pe/codepen/mocha3.gif" alt="Osito Triste" style="width: 80%; height: 80%;">
        </div>
        <div id="sadGifContainer2" style="display: none;">
            <img src="https://encoded.pe/codepen/mocha4.gif" alt="Osito Triste" style="width: 80%; height: 80%;">
        </div>
        <h1 id="question">¿Quieres ser mi San Valentín?</h1>
        <div id="messageContainer" style="display: none;"></div>
        <button id="siBtn">Sí</button>
        <button id="noBtn">No</button>
    </div>
    <script src="script.js"></script>
</body>
</html>
