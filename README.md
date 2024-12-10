<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <title>Барселона Легендалары</title>
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }
        nav {
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #9c0404;
            padding: 15px;
        }
        .nav-links {
            display: flex;
            gap: 15px;
        }
        nav a {
            transition: color 0.3s, transform 0.3s;
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 10px 15px;
            font-size: 20px;
        }
        nav a:hover {
            color: #ffcc00;
            transform: scale(1.1);
            text-decoration: underline;
        }

        
        .hamburger-menu {
            display: none;
            font-size: 1.5rem;
            color: white;
            cursor: pointer;
        }

       
        @media (max-width: 768px) {
            .nav-links {
                display: none;
                flex-direction: column;
                background-color: #9c0404;
                position: absolute;
                top: 60px;
                right: 0;
                width: 100%;
                padding: 10px 0;
            }
            .nav-links a {
                padding: 10px;
                text-align: center;
            }
            .hamburger-menu {
                display: block;
            }
            .nav-links.active {
                display: flex;
            }
        }

        header {
            background: #1d3557;
            color: white;
            padding: 15px;
            text-align: center;
            font-size: 2.0rem;
            font-weight: bold;
            text-transform: uppercase;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.3);
        }

        img {
            max-width: 100%;
            height: auto;
        }

        .main-container {
            margin: 20px auto;
            max-width: 1200px;
            padding: 20px;
        }

        .legend-section {
            margin-bottom: 50px;
        }

        .section-title {
            font-size: 2rem;
            color: #1d3557;
            margin-bottom: 20px;
            text-align: center;
        }

        .legends-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .legend-card {
            background-color: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .legend-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
        }

        .legend-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .legend-card .content {
            padding: 15px;
        }

        .legend-card h3 {
            font-size: 1.4rem;
            color: #1d3557;
            margin: 10px 0;
        }

        footer {
            background: #1d3557;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 50px;
        }
       
    </style>
</head>
<body>
    <nav>
        <div class="hamburger-menu" onclick="toggleMenu()">☰</div>
        <div class="nav-links">
            <a href="barcelona.html">Басты бет</a>
            
            <a href="legends.html">Легендалары</a>
            <a href="trophies.html">Трофейлері</a>
            <a href="players.html">Ойыншылары</a>
            <a href="strukture.html">Құрылымы</a>
        </div>
    </nav>

    <header>
        Барселона Легендалары
    </header>
    <div class="fade-in" style="opacity: 0;">
    <div class="main-container">
        <div class="legend-section">
            <div class="section-title">Тарихи Легендалар</div>
            <div class="legends-grid">
             
                <div class="legend-card">
                    <img src="images/messi2009.jpg" alt="Lionel Messi">
                    <img src="images/messi.jpg" alt="Lionel Messi">
                    <div class="content">
                        <h3>Лионель Месси</h3>
                        <p><span class="highlight">Легенда:</span> Барселона үшін 672 гол. Сегіз Алтын доп иегері.</p>
                    </div>
                </div>
                <div class="legend-card">
                    <img src="images/xavi.jpg" alt="Xavi Hernandez">
                    <img src="images/xavi1.jpg" alt="Xavi Hernandez">
                    <div class="content">
                        <h3>Хави Эрнандес</h3>
                        <p><span class="highlight">Рөлі:</span> Ортаңғы алаңның королі.</p>
                    </div>
                </div>
                <div class="legend-card">
                    <img src="images/iniesta.jpg" alt="Andres Iniesta">
                    <img src="images/iniesta1.webp" alt="Andres Iniesta">
                    <div class="content">
                        <h3>Андрес Иньеста</h3>
                        <p><span class="highlight">Жетістігі:</span> Испанияға Әлем чемпионатын жеңуге көмектесті.</p>
                    </div>
                </div>
                <div class="legend-card">
                    <img src="images/ronaldinho.jpg" alt="Ronaldinho">
                    <img src="images/ronaldinho1.jpg" alt="Ronaldinho">
                    <div class="content">
                        <h3>Роналдиньо</h3>
                        <p><span class="highlight">Символ:</span> Футболдың нағыз өнері.</p>
                    </div>
                </div>
                <div class="legend-card">
                    <img src="images/puyol.webp" alt="Carles Puyol">
                    <img src="images/puyol2.jpg" alt="Carles Puyol">
                    <div class="content">
                        <h3>Карлес Пуйоль</h3>
                        <p><span class="highlight">Көшбасшы:</span> Ең сенімді капитан.</p>
                    </div>
                </div>
                <div class="legend-card">
                    <img src="images/eto.webp" alt="Samuel Eto'o">
                    <img src="images/eto1.webp" alt="Samuel Eto'o">
                    <div class="content">
                        <h3>Самуэль Это’О</h3>
                        <p><span class="highlight">Жұлдыз:</span> Чемпиондар Лигасының финалдық голдары авторы.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    </div>

    <footer>
        © 2024 Барселона. Барлық құқықтар қорғалған.
    </footer>

    <script>
        function toggleMenu() {
            const navLinks = document.querySelector('.nav-links');
            navLinks.classList.toggle('active');
        }
      
        const fadeInElement = document.querySelector('.fade-in');
    window.addEventListener('load', () => {
        setTimeout(() => {
            fadeInElement.style.transition = 'opacity 2s ease';
            fadeInElement.style.opacity = 1;
        }, 500); 
    });
</script>
</body>
</html>
