<!DOCTYPE html>
<html dir="rtl" lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>زمن للمعلوميات</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700;900&display=swap');
        
        body {
            font-family: 'Tajawal', sans-serif;
            margin: 0;
            padding: 0;
            min-height: 100vh;
            background: #1a1a1a;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #ffffff;
        }
        
        .container {
            text-align: center;
            padding: 40px;
            max-width: 600px;
            width: 90%;
        }
        
        h1 {
            font-size: 3em;
            margin-bottom: 10px;
            color: #00ff88;
            font-weight: 900;
        }

        h2 {
            font-size: 1.8em;
            color: #00ff88;
            margin: 0 0 30px 0;
            font-weight: 700;
        }
        
        .launch-date {
            font-size: 1.8em;
            color: #ffffff;
            margin: 30px 0;
            padding: 15px;
            border: 2px solid #00ff88;
            display: inline-block;
            border-radius: 8px;
        }
        
        .message {
            line-height: 1.8;
            font-size: 1.2em;
            margin: 20px 0;
            color: #cccccc;
        }
        
        .contact-container {
            margin-top: 50px;
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            max-width: 400px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .contact-item {
            background: #333;
            padding: 20px;
            border-radius: 10px;
            transition: transform 0.3s ease, background 0.3s ease;
            cursor: pointer;
        }
        
        .contact-item:hover {
            background: #00ff88;
            transform: translateY(-5px);
        }
        
        .contact-item:hover .contact-icon {
            color: #1a1a1a;
        }
        
        .contact-item:hover .contact-text {
            color: #1a1a1a;
        }
        
        .contact-icon {
            font-size: 24px;
            margin-bottom: 10px;
            color: #00ff88;
        }
        
        .contact-text {
            font-size: 14px;
            color: #ffffff;
        }
        
        .logo {
            font-size: 40px;
            margin-bottom: 20px;
        }
        
        @media (max-width: 480px) {
            .contact-container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">💻</div>
        <h1>زمن للمعلوميات</h1>
        <h2>قيد التطوير</h2>
        <p class="message">نعمل على تطوير منصة متكاملة لخدمات المعلوميات والتقنية</p>
        <div class="launch-date">27 مارس 2025</div>
        <p class="message">نسعد بتواصلكم معنا</p>
        
        <div class="contact-container">
            <div class="contact-item">
                <div class="contact-icon">📱</div>
                <div class="contact-text">واتساب</div>
            </div>
            <div class="contact-item">
                <div class="contact-icon">📧</div>
                <div class="contact-text">البريد</div>
            </div>
            <div class="contact-item">
                <div class="contact-icon">📞</div>
                <div class="contact-text">اتصال</div>
            </div>
        </div>
    </div>
</body>
</html># -
