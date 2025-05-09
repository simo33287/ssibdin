# ssibdin
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fiverr Clone</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Fiverr Clone</div>
            <ul class="nav-links">
                <li><a href="#services">الخدمات</a></li>
                <li><a href="#about">من نحن</a></li>
                <li><a href="#contact">اتصل بنا</a></li>
                <li><a href="#login" class="btn">تسجيل الدخول</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>اعثر على أفضل الخدمات بأسعار تنافسية</h1>
        <p>ابدأ الآن واستمتع بخدمات احترافية تقدمها أفضل المستقلين.</p>
        <a href="#services" class="btn">استعرض الخدمات</a>
    </section>

    <section id="services" class="services">
        <h2>الخدمات الشائعة</h2>
        <div class="service-cards">
            <div class="service">
                <img src="service1.jpg" alt="Service 1">
                <h3>تصميم الشعارات</h3>
                <p>ابدأ بـ $5 فقط</p>
            </div>
            <div class="service">
                <img src="service2.jpg" alt="Service 2">
                <h3>كتابة المحتوى</h3>
                <p>ابدأ بـ $10 فقط</p>
            </div>
            <div class="service">
                <img src="service3.jpg" alt="Service 3">
                <h3>تطوير المواقع</h3>
                <p>ابدأ بـ $50 فقط</p>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <h2>من نحن</h2>
        <p>نحن منصة تجمع بين المستقلين والعملاء لتقديم خدمات احترافية بأسعار تنافسية.</p>
    </section>

    <footer>
        <p>&copy; 2025 - Fiverr Clone. جميع الحقوق محفوظة.</p>
    </footer>
</body>
</html>
/* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background: #4caf50;
    color: white;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.header .nav-links {
    list-style: none;
    display: flex;
}

.nav-links li {
    margin: 0 10px;
}

.nav-links a {
    text-decoration: none;
    color: white;
}

.hero {
    text-align: center;
    padding: 50px;
    background: #f4f4f4;
}

.hero h1 {
    font-size: 2.5rem;
}

.hero .btn {
    background: #4caf50;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

.services {
    padding: 50px;
    background: #fff;
}

.services .service-cards {
    display: flex;
    justify-content: space-around;
}

.service {
    text-align: center;
    border: 1px solid #ddd;
    padding: 20px;
    border-radius: 5px;
    width: 30%;
}

.service img {
    max-width: 100%;
    border-radius: 5px;
}

footer {
    text-align: center;
    background: #333;
    color: white;
    padding: 10px 0;
}
// script.js
document.addEventListener("DOMContentLoaded", () => {
    console.log("Welcome to Fiverr Clone");
});
