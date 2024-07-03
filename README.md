<!DOCTYPE html>
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
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
            text-align: center;
            width: 80%;
            max-width: 600px;
            animation: fadeIn 2s ease-in-out;
        }
        .message-title {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        .message-content {
            font-size: 1.5rem;
            margin: 20px 0;
        }
        .sparkle {
            font-size: 3rem;
            color: #ffd700; /* لون البريق الأصفر */
            animation: sparkles 1s infinite;
        }
        .hearts {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            overflow: hidden;
        }
        .hearts div {
            position: absolute;
            width: 20px;
            height: 20px;
            background: url('https://image.shutterstock.com/image-vector/heart-icon-symbol-love-valentine-260nw-1054917564.jpg') no-repeat center center;
            background-size: contain;
            animation: float 6s infinite;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes sparkles {
            0% { text-shadow: 0 0 5px #ffd700, 0 0 10px #ffd700, 0 0 20px #ffd700, 0 0 40px #ffd700; }
            50% { text-shadow: 0 0 10px #ffd700, 0 0 20px #ffd700, 0 0 40px #ffd700, 0 0 80px #ffd700; }
            100% { text-shadow: 0 0 5px #ffd700, 0 0 10px #ffd700, 0 0 20px #ffd700, 0 0 40px #ffd700; }
        }
        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-100px); }
            100% { transform: translateY(0); }
        }
    </style>
</head>
<body>

    <div class="message-container">
        <div class="message-title">رسالة حب وأخوة</div>
        <div class="message-content">أخي العزيز <span class="sparkle" style="color: #ffd700;">عبد الله جبران</span>،<br>أنا فخور بك للغاية وأحبك من كل قلبي. أنت دائماً مصدر الدعم والقوة لي.<br>أتمنى لك دوام النجاح والسعادة.<br>محبك دائماً،<br><span class="sparkle" style="color: #ffd700;">عبد القادر جبران</span>.</div>
    </div>

    <div class="hearts">
        <div style="left: 10%; animation-delay: 0s;"></div>
        <div style="left: 20%; animation-delay: 1s;"></div>
        <div style="left: 30%; animation-delay: 2s;"></div>
        <div style="left: 40%; animation-delay: 3s;"></div>
        <div style="left: 50%; animation-delay: 4s;"></div>
        <div style="left: 60%; animation-delay: 5s;"></div>
        <div style="left: 70%; animation-delay: 6s;"></div>
        <div style="left: 80%; animation-delay: 7s;"></div>
        <div style="left: 90%; animation-delay: 8s;"></div>
    </div>

</body>
</html>
