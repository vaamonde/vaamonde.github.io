<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>QRCode Maratona Cisco - SENAC Tito</title>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        font-family: Arial, sans-serif;
        background: #0f172a;
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
        padding: 20px;
    }

    .container {
        background: #ffffff;
        padding: 40px;
        border-radius: 12px;
        text-align: center;
        max-width: 420px;
        width: 100%;
    }

    h1 {
        margin-bottom: 15px;
        color: #111;
    }

    p {
        margin-bottom: 25px;
        color: #333;
    }

    #qrcode {
        display: flex;
        justify-content: center;
        padding: 20px; /* Quiet Zone */
        background: #ffffff;
    }

    canvas {
        image-rendering: pixelated; /* evita suavização */
    }
</style>
</head>
<body>

<div class="container">
    <h1>Maratona Cisco - SENAC Lapa Tito</h1>
    <p>Escaneie o QR Code abaixo para acessar a página</p>
    <div id="qrcode"></div>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>

<script>
    const url = "https://github.com/vaamonde/netacad/wiki/senactito";

    new QRCode(document.getElementById("qrcode"), {
        text: url,
        width: 300,
        height: 300,
        colorDark: "#000000",
        colorLight: "#ffffff",
        correctLevel: QRCode.CorrectLevel.H
    });
</script>

</body>
</html>
