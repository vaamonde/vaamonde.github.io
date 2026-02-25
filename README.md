<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QRCode - SENAC Tito</title>

    <!-- Estilo Responsivo -->
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: linear-gradient(135deg, #0f172a, #1e293b);
            color: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            text-align: center;
            padding: 20px;
        }

        .container {
            background: #111827;
            padding: 40px 30px;
            border-radius: 12px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.4);
            max-width: 400px;
            width: 100%;
        }

        h1 {
            font-size: 1.8rem;
            margin-bottom: 15px;
        }

        p {
            font-size: 1rem;
            margin-bottom: 25px;
            color: #cbd5e1;
        }

        #qrcode {
            display: flex;
            justify-content: center;
            margin-bottom: 15px;
        }

        .link {
            font-size: 0.9rem;
            color: #38bdf8;
            word-break: break-all;
        }

        @media (max-width: 480px) {
            h1 {
                font-size: 1.5rem;
            }

            p {
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Projeto SENAC Tito</h1>
        <p>Escaneie o QR Code abaixo para acessar a documentação oficial no GitHub.</p>

        <div id="qrcode"></div>

        <div class="link">
            https://github.com/vaamonde/netacad/wiki/senactito
        </div>
    </div>

    <!-- Biblioteca QRCode.js (Open Source) -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>

    <script>
        const url = "https://github.com/vaamonde/netacad/wiki/senactito";

        new QRCode(document.getElementById("qrcode"), {
            text: url,
            width: 200,
            height: 200,
            colorDark: "#000000",
            colorLight: "#ffffff",
            correctLevel: QRCode.CorrectLevel.H
        });
    </script>

</body>
</html><!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QRCode - SENAC Tito</title>

    <!-- Estilo Responsivo -->
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: linear-gradient(135deg, #0f172a, #1e293b);
            color: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            text-align: center;
            padding: 20px;
        }

        .container {
            background: #111827;
            padding: 40px 30px;
            border-radius: 12px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.4);
            max-width: 400px;
            width: 100%;
        }

        h1 {
            font-size: 1.8rem;
            margin-bottom: 15px;
        }

        p {
            font-size: 1rem;
            margin-bottom: 25px;
            color: #cbd5e1;
        }

        #qrcode {
            display: flex;
            justify-content: center;
            margin-bottom: 15px;
        }

        .link {
            font-size: 0.9rem;
            color: #38bdf8;
            word-break: break-all;
        }

        @media (max-width: 480px) {
            h1 {
                font-size: 1.5rem;
            }

            p {
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Projeto SENAC Tito</h1>
        <p>Escaneie o QR Code abaixo para acessar a documentação oficial no GitHub.</p>

        <div id="qrcode"></div>

        <div class="link">
            https://github.com/vaamonde/netacad/wiki/senactito
        </div>
    </div>

    <!-- Biblioteca QRCode.js (Open Source) -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>

    <script>
        const url = "https://github.com/vaamonde/netacad/wiki/senactito";

        new QRCode(document.getElementById("qrcode"), {
            text: url,
            width: 200,
            height: 200,
            colorDark: "#000000",
            colorLight: "#ffffff",
            correctLevel: QRCode.CorrectLevel.H
        });
    </script>

</body>
</html>
