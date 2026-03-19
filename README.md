<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CGM SF TANZANIA</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        /* General Styles */
body {
    font-family: 'Inter', sans-serif;
    margin: 0;
    padding: 0;
    background: linear-gradient(to right, #8f1818,#8929a1,#2b1591);
    color: #333;
}
@keyframes bgSlide {
    0% { background-image: url('image1.jpg'); }
    33% { background-image: url('#'); }
    66% { background-image: url('image3.jpg'); }
}
@keyframes wave {
    0%, 100% { transform: skewX(0deg); }
    50% { transform: skewX(10deg); }
}

/* Header and Navigation */
header {
    background: #2C3E50;
    padding: 15px 20px;
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 100;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1100px;
    margin: 0 auto;
}

.logo {
    font-size: 24px;
    font-weight: bold;
    color: #fff;
}

.nav-links {
    list-style: none;
    display: flex;
}

.nav-links li {
    margin: 0 15px;
}

.nav-links a {
    text-decoration: none;
    color: #fff;
    font-weight: 500;
    transition: color 0.3s;
}

.nav-links a:hover {
    color: #1abc9c;
}

/* Hero Section */
.hero {
    text-align: center;
    padding: 120px 20px;
    color: white;
    height: 30vh;
    background-size: cover;
    background-position: center;
    animation: bgSlide 10s infinite alternate;
}

.hero h1 {
    font-size: 40px;
    margin-bottom: 10px;
}

.hero p {
    font-size: 18px;
    margin-bottom: 20px;
}

.btn {
    display: inline-block;
    padding: 12px 30px;
    background: #fff;
    color: #1abc9c;
    text-decoration: none;
    font-size: 18px;
    font-weight: bold;
    border-radius: 5px;
    transition: 0.3s;
}

.btn:hover {
    background: #16a085;
    color: #fff;
}

/* Features Section */
.features {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 50px 20px;
}

.feature-card {
    background: rgb(203, 233, 33);
    padding: 20px;
    text-align: center;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    width: 250px;
    animation: alternate;
}

.feature-card i {
    font-size: 40px;
    color: #1abc9c;
    margin-bottom: 10px;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background: #2C3E50;
    color: white;
}
@media (max-width: 768px) {
    nav {
        flex-direction: column;
        text-align: center;
    }

    .nav-links {
        flex-direction: column;
        padding: 10px 0;
    }

    .features {
        flex-direction: column;
        align-items: center;
        animation: wave 5s infinite alternate
    }
}


    </style>
</head>
<body>

    <header>
        <nav>
            <div class="logo">CGM SF</div>
            <ul class="nav-links">
                <li><a href="VITABU.html" width="100%" height="600px">
                    NUKUU
                </a></li>
                <li><a href="MIKAKATI.html">KUHUSU SISI</a></li>
                <li><a href="sample.html">sample</a></li>
            </ul>
        

        </nav>
    </header>

    <section class="hero">
        <h1>Welcome to our website for CGM SF TANZANIA</h1>
        <p>We provide top-notch solutions for your SPIRITUAL and ACADEMIC needs.</p>
        <a href="CGM SF.html" class="btn">Get Started</a>
    </section>

    <section class="features">
        <div class="feature-card">
            <i class="fas fa-rocket"></i>
            <a href="MBELE.html">
            <h2>DAIMA MBELE </h2></a>
            <p>Ni marufuku kwetu kukata tamaa.</p>
            
        </div>
        <div class="feature-card">
            <i class="fas fa-mobile-alt"></i>
            <a href="WOKOVU.html">
            <h2>WOKOVU </h2></a>
            <p>MUNGU ni kila kitu kwetu</p>
           
        </div>
        <div class="feature-card">
            <i class="fas fa-shield-alt"></i>
            <a href="ELIMU.html">
            <h2>ELIMU</h2></a>
            <p>Mkamate sana elimu wala usimuache aende zake.</p>
        </div>
    </section>

    <footer>
        <a href="#" class="fa" ><image src="pinterest_1742540670067.jpg" width="40" length="40"></a>
            <a href="https://www.facebook.com/groups/316098503006933/" class="fa"><image src="pinterest_1742540710258.jpg" width="40" length="40"></a>
            <a href="https://www.instagram.com/cgmsftanzania/" class="fa"><image src="Instagram_icon_for_social_media_in_3D_design_psd._25_MAY_2022_-_BANGKOK,_THAILAND___free_image_by_rawpixel.com___Sakarin_Sukmanatham.jpg" width="40" length="40"></a>
            <a href="https://chat.whatsapp.com/EtMm4PKfAyOKvq6ofjIdyC" class="fa"><image src="pinterest_1742541070549.jpg" width="40" length="40"></a>
        <p>&copy; 2025 CGM SF. All rights reserved.</p>
    </footer>

</body>
</html>

