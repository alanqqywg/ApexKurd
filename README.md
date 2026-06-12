<!DOCTYPE html>
<html lang="ckb">
<head>
    <meta charset="UTF-8">
    <title>ApexKurdstan</title>
    <style>
        body { 
            font-family: sans-serif; text-align: center; 
            background: linear-gradient(to bottom, #d21034 33%, #ffffff 33%, #ffffff 66%, #266b3c 66%);
            min-height: 100vh; margin: 0; padding: 20px;
        }
        @keyframes wave {
            0%, 100% { transform: skewX(-5deg); }
            50% { transform: skewX(5deg); }
        }
        h1 { animation: wave 3s infinite ease-in-out; color: #ffce00; font-size: 3em; text-shadow: 2px 2px 5px black; }
        @keyframes scrollAndFade {
            0% { transform: translateX(100%); color: blue; }
            50% { transform: translateX(0%); color: blue; }
            100% { transform: translateX(-100%); color: black; }
        }
        .designer { font-size: 1.5em; font-weight: bold; animation: scrollAndFade 5s infinite; overflow: hidden; margin-bottom: 30px; }
        .btn { display: block; margin: 15px auto; padding: 15px; width: 250px; background: rgba(255,255,255,0.8); color: #333; text-decoration: none; border-radius: 10px; border: 2px solid #266b3c; font-weight: bold; transition: 0.3s; }
        .btn:hover { background: #ffce00; }
    </style>
</head>
<body>
    <h1>ApexKurdstan</h1>
    <div class="designer">دیزاینەر: ئەلان گۆڵسەر</div>
    
    <a class="btn" href="#">یاری موبایل</a>
    <a class="btn" href="#">ئەپەکانی موبایل</a>
    <a class="btn" href="#">یاری کۆمپیوتەر</a>
    <a class="btn" href="#">بەرنامەی کۆمپیوتەر</a>
</body>
</html>
