<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Carte d'invitation</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }

        h1 {
            color: #4285F4;
        }

        p {
            color: #333;
        }

        .invitation-card {
            max-width: 500px;
            margin: 0 auto;
            padding: 20px;
            border: 2px solid #4285F4;
            border-radius: 10px;
            background-color: #F7F7F7;
            transition: transform 0.3s ease;
        }

        .invitation-card:hover {
            transform: scale(1.05);
        }

        .event-date {
            font-size: 20px;
            font-weight: bold;
        }

        .event-location {
            font-size: 16px;
            font-style: italic;
        }

        .confirmation {
            font-size: 14px;
            color: #777;
        }

        .signature {
            margin-top: 20px;
            text-align: right;
        }
       

    </style>
</head>
<body>
    <div class="invitation-card">
        <h1>Invitation</h1>
        <p>Pour tous les deux, c'est un cap important : le baptême de Martin et les 20 ans de sa marraine Marie, le 30 septembre 2023.</p>
        <p>Nous vous attendons à 12 heures à l'église de Puyricard, puis nous nous retrouverons après la cérémonie pour un buffet champêtre au Jas Lou Rouve à Couteron.</p>
        <p class="event-date">30 septembre 2023</p>
        <p class="event-location">Église de Puyricard<br>Jas Lou Rouve, Couteron</p>
        <p class="confirmation">Merci de confirmer votre présence.</p>
        <div class="signature">
            Cordialement,<br> Sebastien ET Lucia 
        </div>
   <div class="decoration">
             <img src="organiser-soiree.jpeg" alt="Carte d'invitation" style="max-width: 300px; width: 100%; height: auto;">
        </div>
    </div>
</body>
</html>
