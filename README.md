# .............
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Month Anniversary sayanggkuuu! ❤️</title>
    <style>
        body {
            background-color: #fff5f5;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: #4a4a4a;
        }
        .container {
            text-align: center;
            background: white;
            padding: 2rem;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.05);
            max-width: 400px;
            width: 90%;
        }
        h1 { color: #ff4d6d; margin-bottom: 10px; }
        .heart { font-size: 50px; color: #ff4d6d; animation: beat 1s infinite; }
        @keyframes beat {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
        .message {
            font-size: 1.1rem;
            line-height: 1.6;
            min-height: 80px;
        }
        .date {
            font-weight: bold;
            color: #ff758f;
            margin-top: 20px;
            display: block;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="heart">❤️</div>
    <h1>Happy 19 Month!</h1>
    <div class="message" id="typing-text"></div>
    <span class="date">Sejak: [13 Juni 2024]</span>
</div>

<script>
    const text = "Ga terasa yaa sayangg udah 19 bulan kita ngejalanin hubungan ini, siapa sangka kita udah berhasil bertahan melewati badai ini sayangg, kiki bangga kali bisa nemanin proses saa sampe sejauh ini makasihh ya sayangg udah disamping kiki terus, kiki cuman pengen hubungan ini sampe selamanya sayangg, harapan kiki kedepannya kita bisa ngelewatin apapun rintangan kita sayanggg! kikii sayanggg kali sama saa  ✨";
    let i = 0;
    function typeWriter() {
        if (i < text.length) {
            document.getElementById("typing-text").innerHTML += text.charAt(i);
            i++;
            setTimeout(typeWriter, 50);
        }
    }
    window.onload = typeWriter;
</script>


</body>
</html>
