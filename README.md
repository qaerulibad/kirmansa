body {
    margin: 0;
    padding: 0;
    font-family: 'Arial', sans-serif;
    background-image: url(WhatsApp\ Image\ 2024-09-05\ at\ 12.49.44.jpeg); /* Ganti dengan URL gambar latar belakang */
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    background-repeat: no-repeat;
    color: #ffffff;
}

/* Loading Screen */
#loading {
    position: fixed;
    width: 100%;
    height: 100vh;
    background-color: #000;
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 9999;
}

#loading img {
    width: 150px; /* Sesuaikan ukuran logo */
    height: auto;
    animation: bounce 2s ; /* Animasi pergerakan naik-turun */
}

@keyframes bounce {
    0%, 100% {
        transform: translateY(0);
    }
    50% {
        transform: translateY(-20px);
    }
}

.overlay {
    background-color: rgba(7, 0, 0, 0.402); /* Overlay gelap untuk membuat teks lebih jelas */
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1; /* Pastikan overlay berada di belakang konten */
}

header {
    text-align: center;
    padding: 50px 0;
    background-color: rgba(0, 0, 128, 0.7);
    border-bottom: 3px solid #ffffff;
}

header h1 {
    font-size: 48px;
    margin: 0;
    color: #ffffff;
}

.content {
    text-align: center;
    padding: 50px 20px;
    min-height: 100vh;
}

.content h2 {
    font-size: 36px;
    margin-bottom: 20px;
}

.content p {
    font-size: 18px;
    max-width: 800px;
    margin: 0 auto 30px;
    line-height: 1.6;
}

.sections {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
}

.section {
    background-color: rgba(255, 255, 255, 0.8);
    padding: 20px;
    border-radius: 10px;
    width: 250px;
    text-align: center;
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.5);
}

.section h3 {
    font-size: 24px;
    color: #003366;
    margin-bottom: 15px;
}

.section p {
    color: #2e2e2e;
    font-size: 16px;
}

.section a {
    text-decoration: none;
    color: #003366;
    font-weight: bold;
}

.section a:hover {
    color: #0056b3;
}

footer {
    background-color: rgba(0, 0, 128, 0.9);
    color: white;
    text-align: center;
    padding: 15px 0;
    margin-top: 50px;
}

footer {
    background-image: url(DSC_5537.JPG); /* Ganti dengan URL gambar latar belakang footer */
}

footer p {
    margin: 0;
}

