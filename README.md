# DoenertokenWebsite
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>$DÖNER TOKEN Presale</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header class="header">
        <div class="container">
            <h1>$DÖNER TOKEN</h1>
            <nav>
                <ul>
                    <li><a href="#presale">Jetzt Kaufen</a></li>
                    <li><a href="#roadmap">Roadmap</a></li>
                    <li><a href="#marketing">Marketing</a></li>
                    <li><a href="#join-telegram">Community</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Presale Section -->
    <section id="presale" class="section">
        <div class="container">
            <h2>Jetzt Kaufen</h2>
            <p>Um am $DÖNER TOKEN Presale teilzunehmen, sende bitte deine Zahlung in SOL über das SOL-Netzwerk an die folgende Adresse:</p>
            <div class="address-box">
                <p>AzRd8qdHUZ6byzGjnf1sPG2akovA9Y4URAz5wvT8yG7z</p>
                <button id="copy-address">Adresse Kopieren</button>
            </div>
            <p class="warning">**Wichtig:** Stelle sicher, dass die Einzahlung über das SOL-Netzwerk erfolgt. Zahlungen in anderen Netzwerken können verloren gehen.</p>
        </div>
    </section>

    <!-- Roadmap Section -->
    <section id="roadmap" class="section">
        <div class="container">
            <h2>Roadmap</h2>
            <ul>
                <li><strong>Q3 2024:</strong> Presale-Start</li>
                <li><strong>Q4 2024:</strong> Listung auf den ersten Exchanges (DEX/CEX)</li>
                <li><strong>Q1 2025:</strong> Launch der $DÖNER App</li>
                <li><strong>Q2 2025:</strong> Partnerschaften mit Dönerbuden weltweit</li>
                <li><strong>Zukunft:</strong> Unterstützung gemeinnütziger Organisationen wie die Tafel</li>
            </ul>
        </div>
    </section>

    <!-- Marketing Section -->
    <section id="marketing" class="section">
        <div class="container">
            <h2>Marketing</h2>
            <ul>
                <li>Social Media Kampagnen</li>
                <li>Community-Building</li>
                <li>Zusammenarbeit mit großen Food-Influencern</li>
                <li>Influencer-Engagement</li>
                <li>Events und Sponsoring</li>
            </ul>
            <div class="marketing-visuals">
                <img src="assets/influencer1.jpg" alt="Influencer">
                <iframe src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
            </div>
        </div>
    </section>

    <!-- Join Telegram Section -->
    <section id="join-telegram" class="section">
        <div class="container">
            <h2>Join Our Community</h2>
            <p>Sei Teil der $DÖNER TOKEN Community und erhalte die neuesten Updates direkt auf Telegram!</p>
            <a href="https://t.me/DoenerToken" target="_blank" class="telegram-link">Trete unserem Telegram-Kanal bei</a>
        </div>
    </section>

    <script src="scripts.js"></script>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

.header {
    background: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

.header nav ul {
    list-style: none;
    padding: 0;
}

.header nav ul li {
    display: inline;
    margin: 0 15px;
}

.header nav ul li a {
    color: #fff;
    text-decoration: none;
}

.section {
    padding: 40px;
    text-align: center;
    background: #fff;
    margin: 20px 0;
}

.section h2 {
    color: #333;
}

.container {
    max-width: 1200px;
    margin: auto;
    padding: 0 20px;
}

.address-box {
    background: #ddd;
    padding: 20px;
    margin: 20px auto;
    width: 50%;
    border-radius: 8px;
}

.warning {
    color: #ff0000;
    font-weight: bold;
}

.marketing-visuals img, .marketing-visuals iframe {
    max-width: 100%;
    margin-top: 20px;
}

.telegram-link {
    background: #0088cc;
    color: #fff;
    padding: 15px 30px;
    text-decoration: none;
    border-radius: 8px;
    display: inline-block;
    margin-top: 20px;
}

.telegram-link:hover {
    background: #007bb5;
}
document.getElementById('copy-address').addEventListener('click', function() {
    const address = 'AzRd8qdHUZ6byzGjnf1sPG2akovA9Y4URAz5wvT8yG7z';
    navigator.clipboard.writeText(address).then(function() {
        alert('Adresse wurde in die Zwischenablage kopiert!');
    }, function(err) {
        console.error('Fehler beim Kopieren der Adresse: ', err);
    });
});
