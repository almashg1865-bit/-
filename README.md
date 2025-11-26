<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>يوسف بن إياد - موقعي الشخصي</title>
    <!-- خطوط Google -->
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
    <!-- أيقونات -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        * { margin:0; padding:0; box-sizing:border-box; font-family: 'Cairo', sans-serif; }
        body { background: #f4f4f9; color: #333; scroll-behavior: smooth; }
        a { text-decoration: none; color: inherit; }

        /* رأس الصفحة */
        header {
            background: linear-gradient(135deg, #4CAF50, #2E8B57);
            color: white;
            padding: 80px 20px;
            text-align: center;
        }
        header h1 { font-size: 3em; margin-bottom: 10px; }
        header p { font-size: 1.3em; }

        /* شريط التنقل */
        nav {
            background-color: #333;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav ul {
            display: flex;
            list-style: none;
            justify-content: center;
        }
        nav ul li { margin: 0 15px; }
        nav ul li a {
            display: block;
            padding: 15px 20px;
            color: white;
            transition: 0.3s;
        }
        nav ul li a:hover { background-color: #575757; border-radius: 5px; }

        /* الأقسام */
        section { padding: 80px 20px; max-width: 1200px; margin: auto; }
        section h2 { text-align: center; margin-bottom: 40px; font-size: 2.5em; color: #4CAF50; }
        section p { text-align: center; line-height: 1.6; font-size: 1.1em; }

        /* معرض الأعمال */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }
        .card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 6px 12px rgba(0,0,0,0.1);
            transition: 0.3s;
        }
        .card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        .card-content { padding: 20px; }
        .card h3 { margin-bottom: 10px; color: #2E8B57; }
        .card p { font-size: 0.95em; }
        .card:hover { transform: translateY(-5px); box-shadow: 0 12px 20px rgba(0,0,0,0.2); }

        /* نموذج التواصل */
        form {
            max-width: 600px;
            margin: auto;
            display: flex;
            flex-direction: column;
        }
        input, textarea {
            padding: 15px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 8px;
            font-size: 1em;
        }
        button {
            padding: 15px;
            border: none;
            background-color: #4CAF50;
            color: white;
            font-size: 1.1em;
            cursor: pointer;
            border-radius: 8px;
            transition: 0.3s;
        }
        button:hover { background-color: #45a049; }

        /* أيقونات التواصل */
        .socials {
            text-align: center;
            margin-top: 20px;
        }
        .socials a {
            font-size: 1.8em;
            margin: 0 15px;
            color: #4CAF50;
            transition: 0.3s;
        }
        .socials a:hover { color: #2E8B57; }

        /* تذييل */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 25px 10px;
        }

        /* متجاوب */
        @media (max-width: 600px){
            header h1 { font-size: 2em; }
            nav ul { flex-direction: column; }
            nav ul li { margin: 5px 0; }
        }
    </style>
</head>
<body>

    <!-- رأس الصفحة -->
    <header>
        <h1>يوسف بن إياد</h1>
        <p>مطور ومصمم مواقع وشغوف بالإبداع الرقمي</p>
    </header>

    <!-- شريط التنقل -->
    <nav>
        <ul>
            <li><a href="#about">من أنا</a></li>
            <li><a href="#portfolio">أعمالي</a></li>
            <li><a href="#contact">اتصل بي</a></li>
        </ul>
    </nav>

    <!-- من أنا -->
    <section id="about">
        <h2>من أنا</h2>
        <p>أنا يوسف بن إياد، مطور مواقع ومصمم واجهات مستخدم جذابة وسهلة الاستخدام. أحب بناء مشاريع تفاعلية تجعل تجربة المستخدم مميزة.</p>
    </section>

    <!-- معرض الأعمال -->
    <section id="portfolio">
        <h2>أعمالي</h2>
        <div class="grid">
            <div class="card">
                <img src="https://via.placeholder.com/400x200" alt="مشروع 1">
                <div class="card-content">
                    <h3>مشروع 1</h3>
                    <p>تصميم موقع شخصي تفاعلي باستخدام HTML وCSS وJavaScript.</p>
                </div>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/400x200" alt="مشروع 2">
                <div class="card-content">
                    <h3>مشروع 2</h3>
                    <p>تطبيق ويب ديناميكي لإدارة المهام باستخدام React وNode.js.</p>
                </div>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/400x200" alt="مشروع 3">
                <div class="card-content">
                    <h3>مشروع 3</h3>
                    <p>موقع متجر إلكتروني متكامل مع تصميم متجاوب وتجربة مستخدم سلسة.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- نموذج التواصل -->
    <section id="contact">
        <h2>اتصل بي</h2>
        <form action="https://formspree.io/f/mwkajwzy" method="POST">
            <input type="text" name="name" placeholder="اسمك" required>
            <input type="email" name="email" placeholder="بريدك الإلكتروني" required>
            <textarea name="message" rows="5" placeholder="رسالتك" required></textarea>
            <button type="submit">إرسال</button>
        </form>

        <!-- أيقونات التواصل الاجتماعي -->
        <div class="socials">
            <a href="https://www.instagram.com/yv3pp" target="_blank" title="إنستغرام"><i class="fab fa-instagram"></i></a>
            <a href="https://t.me/yv3pp" target="_blank" title="تيليجرام"><i class="fab fa-telegram"></i></a>
            <a href="#"><i class="fab fa-facebook"></i></a>
            <a href="#"><i class="fab fa-github"></i></a>
        </div>
    </section>

    <!-- التذييل -->
    <footer>
        &copy; 2025 يوسف بن إياد. جميع الحقوق محفوظة.
    </footer>

</body>
</html>
