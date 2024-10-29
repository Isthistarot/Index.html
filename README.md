<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Consultanță Tarot - IsthisTarot</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('https://example.com/tarot-background.jpg'); /* Asigură-te că schimbi URL-ul cu cel al imaginii dorite */
            background-size: cover;
            color: #e0d3d3;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            line-height: 1.6;
            height: 100vh;
        }
        h1, h2 {
            color: #c3a6f9;
        }
        h1 {
            margin-top: 20px;
        }
        .content {
            max-width: 800px;
            padding: 20px;
            text-align: center;
            background-color: rgba(46, 43, 61, 0.8); /* Fundal semi-transparent pentru text */
            border-radius: 10px;
        }
        .service-list {
            margin-top: 20px;
        }
        .service-item {
            margin: 10px 0;
        }
        .social-links {
            margin: 20px 0;
        }
        .social-links a {
            color: #e0d3d3;
            text-decoration: none;
            font-size: 18px;
            margin: 0 10px;
        }
        .social-links a:hover {
            color: #c3a6f9;
        }
        footer {
            margin: 20px 0;
            font-size: 14px;
            color: #c3a6f9;
        }
        .price {
            color: #a087cf;
        }
        .magic-button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #c3a6f9;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            color: white;
            margin: 20px 0;
        }
        .response {
            margin-top: 15px;
            font-size: 18px;
            font-weight: bold;
            color: #e0d3d3;
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>Consultanță Tarot cu IsthisTarot</h1>
        <p>
            Bine ai venit! Sunt pasionată de divinație și tarot de mai bine de 5 ani. Citirile mele sunt 
            autentice și te pot ajuta să obții claritate în diverse aspecte ale vieții. Pentru mai multe detalii, 
            citește mai jos despre ofertele și prețurile mele.
        </p>
        
        <h2>Servicii și Prețuri</h2>
        <div class="service-list">
            <div class="service-item">Analiza birth chart - <span class="price">70 lei</span></div>
            <div class="service-item">Analiza cuplu după zodii - <span class="price">35 lei</span></div>
            <div class="service-item">Citire generală în tarot (iubire sau carieră) - <span class="price">40 lei</span></div>
            <div class="service-item">1 întrebare cu 3 cărți - <span class="price">15 lei</span></div>
            <div class="service-item">2 întrebări - <span class="price">25 lei</span></div>
            <div class="service-item">3 întrebări - <span class="price">40 lei</span></div>
            <div class="service-item">Întrebare despre ce simte persoana iubită - <span class="price">30 lei</span></div>
            <div class="service-item">Mesaj de la îngeri - <span class="price">10 lei</span></div>
            <div class="service-item">Ce trebuie să schimbați pentru a funcționa relația - <span class="price">25 lei</span></div>
            <div class="service-item">Întrebare cu răspuns da/nu - <span class="price">10 lei</span></div>
            <div class="service-item">Orice alt tip de întrebare - Contactează-mă pentru detalii!</div>
            <div class="service-item"><strong>Ofertă: 3 întrebări + o citire generală - <span class="price">55 lei</span></strong></div>
        </div>

        <h2>Conectează-te cu mine</h2>
        <div class="social-links">
            <a href="https://www.tiktok.com/@isthistarot?_t=8qwm3HMaeyE&_r=1" target="_blank">TikTok</a>
            <a href="https://www.instagram.com/isthistarot?igsh=OTN3dWJ4dHBqZzNr" target="_blank">Instagram</a>
        </div>
        
        <button class="magic-button" onclick="getResponse()">Întreabă-mă!</button>
        <div class="response" id="response"></div>
        
        <footer>
            &copy; 2023 IsthisTarot. Toate drepturile rezervate.
        </footer>
    </div>

    <script>
        function getResponse() {
            const responses = ["Da", "Nu"];
            const randomResponse = responses[Math.floor(Math.random() * responses.length)];
            document.getElementById("response").innerText = randomResponse;
        }
    </script>
</body>
</html>
