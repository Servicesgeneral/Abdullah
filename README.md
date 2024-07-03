<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>رسالة حب وأخوة</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Amiri&display=swap');
        body {
            font-family: 'Amiri', serif;
            text-align: center;
            background: #0d1b2a; /* لون خلفية الكحلي */
            color: #fff;
            direction: rtl;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
            position: relative;
        }
        .message-container {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
            text-align: center;
            width: 90%;
            max-width: 400px;
            animation: fadeIn 2s ease-in-out;
            margin: auto; /* يوسط الرسالة على الشاشة */
        }
        .message-title {
            font-size: 1.8rem;
            margin-bottom: 10px;
        }
        .message-content {
            font-size: 1.2rem;
            margin: 10px 0;
        }
        .sparkle {
            font-size: 2rem;
            color: #ffd700; /* لون البريق الأصفر */
            animation: sparkles 1s infinite;
        }
        .hearts {
            display: none; /* لن يظهر البريق على الأجهزة الصغيرة */
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes sparkles {
            0% { text-shadow: 0 0 3px #ffd700, 0 0 6px #ffd700, 0 0 12px #ffd700, 0 0 24px #ffd700; }
            50% { text-shadow: 0 0 6px #ffd700, 0 0 12px #ffd700, 0 0 24px #ffd700, 0 0 48px #ffd700; }
            100% { text-shadow: 0 0 3px #ffd700, 0 0 6px #ffd700, 0 0 12px #ffd700, 0 0 24px #ffd700; }
        }
    </style>
</head>
<body>

    <div class="message-container">
        <div class="message-title">رسالة حب وأخوة</div>
        <div class="message-content">أخي العزيز <span class="sparkle" style="color: #ffd700;">عبد الله جبران</span>،<br>أنا فخور بك للغاية وأحبك من كل قلبي. أنت دائماً مصدر الدعم والقوة لي.<br>أتمنى لك دوام النجاح والسعادة.<br>محبك دائماً،<br><span class="sparkle" style="color: #ffd700;">عبد القادر جبران</span>.</div>
    </div>

</body>
</html>
