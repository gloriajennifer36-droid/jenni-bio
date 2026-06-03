<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata - Jennifer Gloria Wijaya</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .card {
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            padding: 40px;
            max-width: 450px;
            width: 100%;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .avatar {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            margin: 0 auto 25px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 50px;
            color: white;
            font-weight: bold;
        }

        h1 {
            color: #333;
            font-size: 28px;
            margin-bottom: 25px;
            font-weight: 700;
        }

        .info-container {
            text-align: left;
            margin-bottom: 25px;
        }

        .info-item {
            display: flex;
            align-items: center;
            padding: 12px 15px;
            margin-bottom: 10px;
            background: #f8f9fa;
            border-radius: 10px;
            transition: background 0.3s ease;
        }

        .info-item:hover {
            background: #e9ecef;
        }

        .info-icon {
            font-size: 24px;
            margin-right: 15px;
            min-width: 30px;
            text-align: center;
        }

        .info-label {
            font-size: 12px;
            color: #888;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .info-value {
            font-size: 16px;
            color: #333;
            font-weight: 500;
        }

        .motivation-box {
            background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%);
            color: #333;
            padding: 20px;
            border-radius: 12px;
            margin-bottom: 25px;
            font-style: italic;
            font-size: 16px;
            line-height: 1.6;
            border-left: 4px solid #f5576c;
        }

        .motivation-box .label {
            font-weight: bold;
            font-style: normal;
            margin-bottom: 8px;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: #f5576c;
        }

        .btn-project {
            display: inline-block;
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            color: white;
            text-decoration: none;
            padding: 15px 30px;
            border-radius: 50px;
            font-size: 16px;
            font-weight: 600;
            border: none;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(245, 87, 108, 0.4);
        }

        .btn-project:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(245, 87, 108, 0.6);
            background: linear-gradient(135deg, #f5576c 0%, #f093fb 100%);
        }

        .btn-project:active {
            transform: translateY(0);
        }

        .btn-icon {
            margin-right: 8px;
        }

        .footer-note {
            margin-top: 15px;
            font-size: 12px;
            color: #aaa;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="avatar">JW</div>
        <h1>Jennifer Gloria Wijaya</h1>
        
        <div class="info-container">
            <div class="info-item">
                <span class="info-icon">🎂</span>
                <div>
                    <div class="info-label">Umur</div>
                    <div class="info-value">16 Tahun</div>
                </div>
            </div>
            
            <div class="info-item">
                <span class="info-icon">🏫</span>
                <div>
                    <div class="info-label">Sekolah</div>
                    <div class="info-value">SMAN 15 Jakarta Utara</div>
                </div>
            </div>
        </div>

        <div class="motivation-box">
            <div class="label">💪 Motivasi</div>
            "Menjadi yang terbaik untuk masa depan"
        </div>

        <a href="https://gloriajennifer36-droid.github.io/cooking-julie/" target="_blank" class="btn-project">
            <span class="btn-icon">🍳</span> Lihat Proyek Cooking Julie
        </a>

        <div class="footer-note">✨ Klik tombol di atas untuk melihat proyek saya</div>
    </div>
</body>
</html>
