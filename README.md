<!DOCTYPE html><html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>新年快乐</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        * { box-sizing: border-box; }
        body {
            margin: 0;
            font-family: "Noto Sans SC", "Microsoft YaHei", Arial, sans-serif;
            min-height: 100vh;
            background: url('foto.jpg') no-repeat center center fixed;
            background-size: cover;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .overlay {
            background: rgba(0, 0, 0, 0.55);
            width: 100%;
            height: 100%;
            position: absolute;
            top: 0;
            left: 0;
        }
        .card {
            position: relative;
            z-index: 2;
            background: rgba(0, 0, 0, 0.4);
            padding: 36px 30px;
            max-width: 720px;
            border-radius: 22px;
            box-shadow: 0 12px 30px rgba(0,0,0,0.4);
            text-align: center;
            color: #ffffff;
        }
        h1 {
            font-size: 2.8rem;
            margin-bottom: 6px;
            letter-spacing: 2px;
        }
        h2 {
            font-size: 1.3rem;
            font-weight: 400;
            margin-bottom: 20px;
            opacity: 0.95;
        }
        .divider {
            width: 90px;
            height: 3px;
            background: #ffd700;
            margin: 20px auto 24px;
            border-radius: 3px;
        }
        p {
            font-size: 1.05rem;
            line-height: 1.8;
            margin: 12px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 14px;
        }
        th, td {
            padding: 8px;
            border: 1px solid rgba(255,255,255,0.35);
        }
        th { background: rgba(255,255,255,0.15); }
        .footer {
            margin-top: 24px;
            font-size: 0.95rem;
            opacity: 0.85;
        }
        @media (max-width: 480px) {
            h1 { font-size: 2.2rem; }
            h2 { font-size: 1.1rem; }
            .card { padding: 26px 18px; }
        }
    </style>
</head>
<body>
    <!-- Overlay gelap supaya teks jelas -->
    <div class="overlay"></div><div class="card">
    <h1>新年快乐</h1>
    <h2>Xīnnián Kuàilè</h2>
    <div class="divider"></div>

    <p>
        新年快乐，万事如意！<br>
        <span style="color:#ffd700">Xīnnián kuàilè, wànshì rúyì!</span><br>
        <small>Selamat Tahun Baru, semoga semuanya berjalan lancar.</small>
    </p>

    <p>
        新年快乐，学习进步，天天开心！<br>
        <span style="color:#7CFC00">Xīnnián kuàilè, xuéxí jìnbù, tiāntiān kāixīn!</span><br>
        <small>Selamat Tahun Baru, semoga belajar makin maju dan selalu bahagia.</small>
    </p>

    <h2>汉字 · 拼音 · Arti</h2>
    <table>
        <tr>
            <th>汉字</th>
            <th>拼音</th>
            <th>Indonesia</th>
        </tr>
        <tr>
            <td>新年快乐</td>
            <td style="color:#ffd700">Xīnnián kuàilè</td>
            <td>Selamat Tahun Baru</td>
        </tr>
        <tr>
            <td>万事如意</td>
            <td style="color:#ffd700">Wànshì rúyì</td>
            <td>Semoga semua lancar</td>
        </tr>
        <tr>
            <td>学习进步</td>
            <td style="color:#7CFC00">Xuéxí jìnbù</td>
            <td>Belajar semakin maju</td>
        </tr>
    </table>

    <div class="footer">—— 祝您新的一年平安喜乐 ——<br><br>
        <span style="font-size:0.9rem; opacity:0.9;">来自杰森·周（Jason Zhou），致何盛利（He Shengli）</span>
    </div>
</div>

</body>
</html>
