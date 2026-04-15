<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tili Ready Chess Club</title>
<script>
window.onload = function() {
    alert("Please use the navigation buttons within the website instead of your device navigation keys.");
};
</script>
<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0f172a;
    color: white;
}

header {
    background: #020617;
    padding: 15px;
    position: sticky;
    top: 0;
}

nav {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

nav a {
    color: white;
    text-decoration: none;
    padding: 8px;
    font-size: 14px;
}

nav a:hover {
    color: #38bdf8;
}

section {
    padding: 40px 20px;
    text-align: center;
}

.hero {
    background: linear-gradient(135deg, #020617, #1e293b);
}

.card {
    background: #1e293b;
    margin: 15px auto;
    padding: 20px;
    border-radius: 12px;
    max-width: 300px;
}

img {
    max-width: 100%;
    border-radius: 10px;
}

footer {
    background: #020617;
    padding: 20px;
    text-align: center;
    font-size: 12px;
}
</style>
</head>

<body>

<header>
    <nav>
        <a href="index.html">Home</a>
        <a href="members.html">Members</a>
        <a href="tournament.html">Tournament</a>
        <a href="rules.html">Rules</a>
        <a href="about.html">About</a>
        <a href="#fame">Wall of Fame</a>
        <a href="#updates">Updates</a>
    </nav>
</header>

<section class="hero">
    <h1>♟️ Tili Ready Chess Club</h1>
    <p>Serious chess. Questionable decisions.</p>
</section>

<section id="fame">
    <h2>Wall of Fame</h2>
    <a href="wall_of_fame.html">
        <img src="https://images.unsplash.com/photo-1586165368502-1bad197a6461">
    </a>
    <p>Click to see legends and people who got lucky once.</p>
</section>

<section id="updates">
    <h2>Updates</h2>
    <div class="card">April 2nd Week tournament in progress. Check tournament card to see more.</div>
</section>

<footer>
    <p>© 2026 Tili Ready|Rael's Lab</p>
</footer>

</body>
</html>
