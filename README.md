# Next-lab-ase-seminar-11
posta electronica 
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <title>Poșta electronică - Acasă</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Poșta electronică</h1>
        <nav>
            <a href="index.html" class="btn">Acasă</a>
            <a href="despre.html" class="btn">Ce este poșta electronică?</a>
            <a href="utilitate.html" class="btn">De ce este utilă?</a>
        </nav>
    </header>
    
    <main>
        <h2>Bine ai venit!</h2>
        <p>Aici vei afla tot ce trebuie să știi despre poșta electronică și avantajele ei.</p>
        <img src="email.jpg" alt="Poșta electronică" class="main-img">
    </main>
    
    <footer>
        <p>&copy; 2026 Poșta electronică. Toate drepturile rezervate.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <title>Ce este poșta electronică?</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Ce este poșta electronică?</h1>
        <nav>
            <a href="index.html" class="btn">Acasă</a>
            <a href="despre.html" class="btn">Ce este poșta electronică?</a>
            <a href="utilitate.html" class="btn">De ce este utilă?</a>
        </nav>
    </header>
    
    <main>
        <p>Poșta electronică (email) este un serviciu care permite trimiterea și primirea de mesaje și fișiere prin internet. Este rapidă, eficientă și folosită pe scară largă în comunicarea personală și profesională.</p>
        <img src="email2.jpg" alt="Email" class="main-img">
    </main>
    
    <footer>
        <p>&copy; 2026 Poșta electronică. Toate drepturile rezervate.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <title>De ce este utilă poșta electronică?</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>De ce este utilă poșta electronică?</h1>
        <nav>
            <a href="index.html" class="btn">Acasă</a>
            <a href="despre.html" class="btn">Ce este poșta electronică?</a>
            <a href="utilitate.html" class="btn">De ce este utilă?</a>
        </nav>
    </header>
    
    <main>
        <ul>
            <li>Trimite mesaje rapid și economic, oriunde în lume.</li>
            <li>Permite trimiterea fișierelor de orice tip și dimensiune.</li>
            <li>Este un instrument indispensabil în muncă și școală.</li>
            <li>Oferă arhivare și organizare a mesajelor.</li>
        </ul>
        <img src="email3.jpg" alt="Avantaje email" class="main-img">
    </main>
    
    <footer>
        <p>&copy; 2026 Poșta electronică. Toate drepturile rezervate.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f8ff;
    color: #333;
}

header {
    background-color: #004080;
    color: white;
    padding: 20px;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav {
    margin-top: 10px;
}

nav .btn {
    text-decoration: none;
    color: white;
    background-color: #0066cc;
    padding: 10px 15px;
    margin: 5px;
    border-radius: 5px;
    transition: background-color 0.3s;
}

nav .btn:hover {
    background-color: #003366;
}

main {
    padding: 20px;
    text-align: center;
}

main ul {
    list-style-type: square;
    text-align: left;
    display: inline-block;
}

.main-img {
    max-width: 300px;
    margin-top: 20px;
}

footer {
    background-color: #004080;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
