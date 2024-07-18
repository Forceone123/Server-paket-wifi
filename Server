<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paket WiFi Anda</title>
    <style>
        body {
            background-image: url('background.jpg'); /* Ganti dengan lokasi gambar jaringan internet Anda */
            background-size: cover;
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
            padding-top: 100px;
        }
        .content {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 10px;
        }
        .colorful-text {
            font-size: 24px;
            animation: rainbow 5s infinite;
        }
        @keyframes rainbow {
            0% { color: #FF0000; }
            25% { color: #FF7F00; }
            50% { color: #FFFF00; }
            75% { color: #00FF00; }
            100% { color: #0000FF; }
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>Paket WiFi Anda</h1>
        <p class="colorful-text">Hari ini adalah <span id="currentDateTime"></span></p>
        <p class="colorful-text">Paket WiFi Anda tinggal 25 hari lagi!</p>
    </div>

    <script>
        function updateDateTime() {
            var now = new Date();
            var days = ['Minggu', 'Senin', 'Selasa', 'Rabu', 'Kamis', 'Jumat', 'Sabtu'];
            var months = ['Januari', 'Februari', 'Maret', 'April', 'Mei', 'Juni', 'Juli', 'Agustus', 'September', 'Oktober', 'November', 'Desember'];
            var dayOfWeek = days[now.getDay()];
            var month = months[now.getMonth()];
            var date = now.getDate();
            var year = now.getFullYear();
            var hours = now.getHours();
            var minutes = now.getMinutes();
            var seconds = now.getSeconds();

            document.getElementById('currentDateTime').textContent = dayOfWeek + ', ' + date + ' ' + month + ' ' + year + ' ' + hours + ':' + minutes + ':' + seconds;
        }

        updateDateTime();
        setInterval(updateDateTime, 1000); // Update setiap detik
    </script>
</body>
</html>
