<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zahlung und Bewertung</title>
    <style>
        body {
            font-family: 'Times New Roman', Times, serif;
            background-image: url('https://www.linkzudeinembild.com/holz.jpg'); /* Ersetze diesen Link durch den Link zu deinem Bild */
            background-size: cover;
            background-repeat: no-repeat;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            text-align: center;
            color: #fff;
        }
        h1 {
            color: #d4af37; /* Goldene Farbe */
            text-shadow: 2px 2px 4px #000;
        }
        p {
            margin: 10px 0;
            font-size: 1.2em;
            color: #f4f4f9;
            text-shadow: 1px 1px 2px #000;
        }
        a {
            display: inline-block;
            margin: 15px 0;
            padding: 15px 30px;
            color: #fff;
            background-color: #8b4513; /* Bräunliche Farbe */
            border: 2px solid #d4af37; /* Goldener Rahmen */
            border-radius: 50px;
            text-decoration: none;
            font-size: 1.2em;
            transition: background-color 0.3s, transform 0.3s;
            box-shadow: 3px 3px 10px #000;
        }
        a:hover {
            background-color: #a0522d; /* Dunklere Bräunliche Farbe */
            transform: scale(1.05);
        }
    </style>
    <script>
        function redirectToPayment() {
            window.location.href = "https://www.paypal.me/DeinFirmenname";
        }
    </script>
</head>
<body>
    <h1>Vielen Dank für Ihre Unterstützung!</h1>
    <p>Bitte bewerten Sie uns, bevor Sie die Zahlung vornehmen:</p>
    <a href="https://www.google.com/maps/place/DeinFirmenname/reviews" target="_blank" onclick="setTimeout(redirectToPayment, 5000)">Bewertung abgeben</a>
    <p>Nach der Bewertung werden Sie automatisch zur Zahlung weitergeleitet.</p>
</body>
</html>

