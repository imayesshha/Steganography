<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Steganography – Hidden Communication</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
    color: white;
    text-align: center;
}

.hero {
    padding: 80px 20px;
}

h1 {
    font-size: 3.5em;
    background: linear-gradient(to right, #00f2fe, #4facfe);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

.badges img {
    margin: 10px;
}

.section {
    padding: 50px 10%;
}

.card {
    background: rgba(255,255,255,0.1);
    border-radius: 15px;
    padding: 25px;
    margin: 20px;
    backdrop-filter: blur(10px);
    box-shadow: 0 0 30px rgba(0,255,255,0.3);
}

.features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px,1fr));
    gap: 30px;
}

.team {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px,1fr));
    gap: 30px;
}

.member {
    background: rgba(0,0,0,0.4);
    border-radius: 15px;
    padding: 20px;
}

.stats {
    display: flex;
    justify-content: center;
    gap: 50px;
    flex-wrap: wrap;
    margin-top: 40px;
}

.stat {
    background: rgba(255,255,255,0.1);
    padding: 25px 40px;
    border-radius: 15px;
    font-size: 1.3em;
}

footer {
    padding: 40px;
    background: rgba(0,0,0,0.4);
    margin-top: 60px;
}
</style>
</head>

<body>

<div class="hero">
    <h1>🔐 Steganography</h1>
    <p><b>The Art of Hidden Communication</b></p>

    <div class="badges">
        <img src="https://img.shields.io/badge/Security-SHA256-green">
        <img src="https://img.shields.io/badge/Encryption-Advanced-blue">
        <img src="https://img.shields.io/badge/Formats-Images%20%7C%20Audio%20%7C%20Video-orange">
        <img src="https://img.shields.io/badge/Status-Active-brightgreen">
    </div>
</div>

<div class="section">
    <h2>🔒 Secure Your Data</h2>
    <p>
        Steganography is the practice of concealing secret messages inside other media files.
        This system ensures **covert communication** by hiding data so that no one even knows it exists.
    </p>
</div>

<div class="section features">

    <div class="card">
        <h2>🔒 Encode Data</h2>
        <p>
            Hide secret messages inside:
            <br><b>PNG, JPG, JPEG, MP3, MP4</b><br><br>
            Uses advanced <b>LSB (Least Significant Bit)</b> encoding
        </p>
    </div>

    <div class="card">
        <h2>🔓 Decode Data</h2>
        <p>
            Extract hidden messages securely with:
            <br><b>Password Authentication</b><br>
            <b>SHA-256 Hash Verification</b>
        </p>
    </div>

</div>

<div class="section">
    <h2>👥 Meet Our Team</h2>

    <div class="team">
        <div class="member">
            <h3>👩🏻‍💻 Javeria Faisal</h3>
            <p>F24605017</p>
        </div>
        <div class="member">
            <h3>👩🏻‍💻 Bisma Fatima</h3>
            <p>F24605036</p>
        </div>
        <div class="member">
            <h3>👩🏻‍💻 Ayesha Imran</h3>
            <p>F24605019</p>
        </div>
        <div class="member">
            <h3>👩🏻‍💻 Sawaira Anwar</h3>
            <p>F24605041</p>
        </div>
    </div>
</div>

<div class="section">
    <h2>📊 Project Stats</h2>

    <div class="stats">
        <div class="stat">📁 Supported Formats<br><b>5</b></div>
        <div class="stat">🔐 Security Level<br><b>SHA-256</b></div>
        <div class="stat">📦 Max File Size<br><b>50MB</b></div>
    </div>
</div>

<footer>
    <p>© 2026 – Steganography System | Secure Hidden Communication</p>
</footer>

</body>
</html>

