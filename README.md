<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Retroalimentación</title>
<style>
    body {
        font-family: Arial, sans-serif;
        text-align: center;
    }
    h1 {
        color: #333;
    }
    button {
        background-color: #4CAF50;
        border: none;
        color: white;
        padding: 15px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        cursor: pointer;
    }
</style>
</head>
<body>
    <h1>¡Hola amor!</h1>
    <p>Me gustaría saber cuánto te gusté. ¿Me podrías decir haciendo clic en una de las opciones?</p>
    <button onclick="enviarRetroalimentacion('Mucho')">Me gustaste mucho</button>
    <button onclick="enviarRetroalimentacion('Poco')">Me gustaste poco</button>
    <button onclick="enviarRetroalimentacion('Nada')">No me gustaste en absoluto</button>

    <script>
        function enviarRetroalimentacion(retroalimentacion) {
            alert('¡Gracias por tu retroalimentación! ¡Te quiero mucho!');
            // Aquí podrías enviar la retroalimentación a tu servidor si quisieras registrarla
        }
    </script>
</body>
</html>
