# seth
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Valentine's Day</title>
    <style>
        body {
            width: 200%;
            max-width: 1500px;
            margin: 0 auto;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: vh;
            background: linear-gradient(135deg, #ff758c, #ff7eb3);
            font-family: 'Arial', sans-serif;
            text-align: center;
            color: white;
        }
        .container {
            color: white;
        }
        h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }
        p {
            font-size: 1.5rem;
        }
        .button-container {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }
        .nav-button {
            padding: 10px 20px;
            background: white;
            color: #ff758c;
            font-size: 1.2rem;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s;
        }
        .nav-button:hover {
            background: #ffe0e6;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Happy Valentine's Day! ❤️</h1>
        <p>Wishing you love and happiness today and always!</p>
        </p>MY LOVE GOLU </p>
        <div class="button-container">
            <a href="#gallery" class="nav-button">Love Gallery 💕</a>
            <a href="#letter" class="nav-button">Love Letter 💌</a>
        </div>
    </div>

    <section id="gallery" style="margin-top: 50px; text-align: center;">
        <h1>Love Moments 💖</h1>
        <div class="gallery" style="display: flex; gap: 15px; justify-content: center;">
            <img src="https://media-hosting.imagekit.io//b2a8de0cd4644518/WhatsApp%20Image%202025-02-13%20at%2019.33.57_ab672bba.jpg?Expires=1834065005&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=xdG9N438G3za5aLwYlh5bw71Ez7jfyC7GsBrnKOaRS0x6dpiQRi9pztAj8RL2im2Lliit~msUNvELhWl~bhdmIzpzJYZWyz6VHs0rASuWCw-H5gLvdg2yMZtzZa~o9stiJA-tPKwu7t2e8CZAN-rIfRchSrIGy2us5YS7JMQEa4inM5~KWe6RLkB2gL3An1UfJ5QS9VQnHEnhABmxsFINMf2WyWGqbpMqtvcwNxKzVdQgpyqI-TuaAYFUmzCBWeBDXRx7mzdcbG8nN19HSmZZZBNN3-oov5RNU7IRisfG0~uXw2cTJUrfqXz0yvahkWJMIUDOI58q6CXaG1U9duTbA__" alt="Romantic moment 1" style="width: 200px; border-radius: 10px;">
            <img src="https://media-hosting.imagekit.io//4ecaa37fc2f6400f/WhatsApp%20Image%202025-02-13%20at%2019.33.58_4e9de91d.jpg?Expires=1834065089&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=z1XvMM6DFSAdo2WKIiU8gnlbHNGRJ7pAmubmTQnpArapb7chy18mW39Ug4GpFfmTVYh8CZGMXLA-I-2Da8gXULTdzbTsgmcGN7NkKLvhLxJcAbnp-ZNEKYeYPPaeV5496L47PIWH4~L3bshhbXxwt5gDujNMmIGCSXcR7o~SbNouy22HsEgsLjpnfkNawEWkxxCywSPdeSIipysq4FEQD7~E5MZ7SDLmxs9xcvdyYfluvb1htkDl8n18xH0x0XWxfpsp2MXJ8livVpZTXBIzbW6~jsqsIPKYDDjHIGBRPPSzQufG94FAEaBMs4hMhgKvXGWnuXfOu~Nu9ypVYy0H3g__" alt="Romantic moment 2" style="width: 200px; border-radius: 10px;">
            <img src="https://media-hosting.imagekit.io//7dde1460884f42c9/WhatsApp%20Image%202025-02-13%20at%2019.33.57_22540d23.jpg?Expires=1834065005&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=eCE8rYQkP1byLgmhDfwNip~2U4PqZ4PfP19h9meD5h2KzAddGQ7-g4Huk~mroZpZSfAjbkQ8Owsrrj~lv13niuonQLLGxai6j54gPcKG5BqiS7dcMVo70NEw9OhjUlx~fTwcL5OHJIwaSUe1tLz2MZmg6GavDIiBg8s6i56ouc42QN8vbpFz0cTgJJgU5GbBag8AvL7myJaD7QMQAO7h4a2S6tJ43S-X4jj2eaZ6aZ~2Jvf5vw0p64ejgW-StvOGpZK51tcw9XHHzMsk~IjpS69G6mr8a1qn8~yOxYcN9wyzt2l0ma8iScItmlfUJ~yeFNoToq3EezB-cnRn2lpEEQ__" alt="Romantic moment 3" style="width: 200px; border-radius: 10px;">
        </div>
    </section>

    <section id="letter" style="margin-top: 50px; text-align: center;">
        <h1>Write a Love Letter 💌</h1>
        <textarea id="love-letter" style="width: 80%; height: 150px; padding: 10px; border-radius: 10px; border: none; font-size: 1rem;" placeholder="Click the button to generate a love letter..."></textarea>
        <button onclick="generateLetter()" style="margin-top: 10px; padding: 10px 20px; background: white; color: #ff758c; font-size: 1.2rem; border: none; border-radius: 5px; font-weight: bold; cursor: pointer; transition: background 0.3s;">Generate Love Letter</button>
    </section>

    <script>
        function generateLetter() {
            const messages = [
                "MERA BACHU ANI\nFrom the moment you walked into my life, everything changed. Your laughter is my favorite melody, your smile my greatest treasure, and your love my safest place. Every moment with you feels like a dream I never want to wake up from.\n\nYou are my sunshine on the darkest days, my reason to believe in love, and the most beautiful part of my world. I promise to cherish you, to stand by your side through every joy and challenge, and to love you more with every passing day.\n\nI love you, ANI. You are my heart, my soul, and my everything.\n\nForever yours,\n[RUHH] ❤",

                "You are my everything, and I cherish every moment with you.",
                "My love for you grows stronger every day. You are my heart and my soul.",
                "You make my world brighter and my heart happier. I cherish every moment with you.",
                "I am so lucky to have you in my life. You are my greatest love and my best friend."
            ];
            
            document.getElementById('love-letter').value = messages[Math.floor(Math.random() * messages.length)];
        }
    </script>
</body>
</html>
