<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sole - Smaki i Cennik</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            color: #333;
            animation: gradientBackground 10s ease infinite;
        }
        @keyframes gradientBackground {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        h1 {
            text-align: center;
            font-size: 3rem;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
            margin: 20px 0;
            padding: 20px;
            background: linear-gradient(135deg, #ff6f61, #ffcc00);
            border-radius: 10px;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            background: rgba(255, 255, 255, 0.9);
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }
        .flavors, .pricing, .why-us {
            margin-bottom: 30px;
        }
        .flavors h2, .pricing h2, .why-us h2 {
            font-size: 2rem;
            color: #555;
            border-bottom: 2px solid #ddd;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        .flavors ul {
            list-style-type: none;
            padding: 0;
        }
        .flavors li {
            padding: 12px;
            margin: 8px 0;
            background: #f8f8f8;
            border-radius: 8px;
            transition: background 0.3s, transform 0.2s;
            cursor: pointer;
        }
        .flavors li:hover {
            background: #ff6f61;
            color: #fff;
            transform: translateX(10px);
        }
        .pricing table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
            background: #fff;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        .pricing th, .pricing td {
            padding: 12px;
            text-align: center;
            border-bottom: 1px solid #ddd;
        }
        .pricing th {
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            color: #fff;
            font-weight: bold;
        }
        .pricing tr:hover {
            background: #f8f8f8;
        }
        .pricing td {
            color: #555;
        }
        .why-us {
            text-align: center;
        }
        .why-us p {
            font-size: 1.1rem;
            color: #555;
            line-height: 1.6;
        }
        .footer {
            text-align: center;
            margin-top: 30px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        .footer p {
            margin: 0;
            color: #555;
        }
        .social-icons {
            margin-top: 10px;
        }
        .social-icons a {
            color: #ff6f61;
            font-size: 1.5rem;
            margin: 0 10px;
            transition: color 0.3s;
        }
        .social-icons a:hover {
            color: #ffcc00;
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <h1>Sole - Smaki i Cennik</h1>
    <div class="container">
        <div class="flavors">
            <h2>Nasze Smaki</h2>
            <ul>
                <li>1. Cukierek jabłkowy, chłodzik</li>
                <li>2. Czarna porzeczka, jeżyna, truskawka, malina, jagoda, czerwona porzeczka, ananas, chłodzik, słodzik</li>
                <li>3. Truskawka, słodzik, chłodzik</li>
                <li>4. Cola z chłodzikiem</li>
                <li>5. Czerwone owoce, cytrusy, chłodzik</li>
                <li>6. Niebieska malina, chłodzik</li>
                <li>7. Brzoskwinia, kiwi, słodka malina</li>
                <li>8. Kwaśna cytryna, limonka, chłodzik, słodzik</li>
                <li>9. Mieszanka świeżej mięty, miętowe cukierki</li>
                <li>10. Arbuz, sok cytrynowy, chłodzik, słodzik</li>
                <li>11. Granat, kiwi, poziomka, ice</li>
                <li>12. Wiśnia, smoczy owoc, ice</li>
                <li>13. Owoce leśne, ice</li>
                <li>14. Gruszka, melon, granat, ice</li>
                <li>15. Ananas, grejpfrut</li>
                <li>16. Słodki kaktus, limonka</li>
                <li>17. Słodkie żółte mango</li>
                <li>18. Owoce tropikalne</li>
                <li>19. Winogrono, jeżyna, anyż, ice</li>
                <li>20. Czarna porzeczka, truskawka, malina, jagody, czerwona porzeczka, ice</li>
                <li>21. Zielone jabłko z nutą zielonych żelków</li>
                <li>22. Czerwona porzeczka, jagoda, malina</li>
                <li>23. Truskawka, czerwona porzeczka, malina</li>
            </ul>
        </div>
        <div class="pricing">
            <h2>Cennik</h2>
            <table>
                <thead>
                    <tr>
                        <th>Pojemność</th>
                        <th>24mg</th>
                        <th>18mg</th>
                        <th>12mg</th>
                        <th>9,6,3,0mg</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>60ml</td>
                        <td>70zł</td>
                        <td>68zł</td>
                        <td>67zł</td>
                        <td>66zł</td>
                    </tr>
                    <tr>
                        <td>30ml</td>
                        <td>40zł</td>
                        <td>38zł</td>
                        <td>37zł</td>
                        <td>36zł</td>
                    </tr>
                    <tr>
                        <td>10ml</td>
                        <td>16zł</td>
                        <td>15zł</td>
                        <td>14zł</td>
                        <td>13zł</td>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="why-us">
            <h2>Dlaczego my?</h2>
            <p>
                Oferujemy najwyższą jakość produktów, szeroki wybór smaków oraz konkurencyjne ceny.
                Nasze sole są tworzone z myślą o Twojej przyjemności i satysfakcji.
            </p>
        </div>
    </div>
    <div class="footer">
        <p>© 2023 Sole. Wszystkie prawa zastrzeżone.</p>
    </div>
</body>
</html>
