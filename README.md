<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zahlung und Bewertung</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            text-align: center;
            color: #333;
        }
        h1 {
            color: #007bff;
        }
        p {
            margin: 10px 0;
            font-size: 1.2em;
        }
        a {
            display: inline-block;
            margin: 15px 0;
            padding: 10px 20px;
            color: #fff;
            background-color: #007bff;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            font-size: 1.2em;
            transition: background-color 0.3s;
        }
        a:hover {
            background-color: #0056b3;
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
