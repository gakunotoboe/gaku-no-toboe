<!DOCTYPE html>
<html lang="ja">
<head>
    <link href="https://fonts.googleapis.com/css2?family=Kaisei+Decol&display=swap" rel="stylesheet">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GAKU NO TOBOE</title>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Kaisei Decol', sans-serif;
            background-color: #000;
            color: #fff;
            background-image: url('https://www.transparenttextures.com/patterns/black-linen.png');
            background-attachment: fixed;
        }
        header, section, footer {
            background-color: rgba(10, 10, 10, 0.9); /* より深い暗さと透明感 */
            border: 1px solid #8b5e3c; /* 暗めのゴールドのアクセント */
        }
        header {
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid #8b5e3c;
        }
        header h1 {
            font-size: 2.8em;
            font-family: 'Pacifico', cursive;
            background: linear-gradient(45deg, #75aadb, #f6d06b);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 2px 2px 10px rgba(139, 94, 60, 0.8);
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 25px;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: #d4af37;
            font-size: 1.3em;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #fff;
        }
        section {
            padding: 50px 20px;
            text-align: center;
            border-bottom: 2px solid #8b5e3c;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.5);
            border-radius: 10px;
            margin: 20px;
        }
        .menu-items {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }
        .menu-items img {
            width: 100%;
            max-width: 200px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(255, 215, 0, 0.3);
            transition: transform 0.3s ease;
        }
        .menu-items img:hover {
            transform: scale(4.5);
            z-index: 1;
        }
        .menu-items div {
            text-align: center;
            max-width: 200px;
        }
        .gallery img {
            width: 100%;
            max-width: 300px;
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(255, 215, 0, 0.3);
            transition: transform 0.3s ease;
        }
        .gallery img:hover {
            transform: scale(2.5);
            z-index: 1;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: rgba(10, 10, 10, 0.9);
            color: #d4af37;
            border-top: 2px solid #8b5e3c;
        }
        h2 {
            color: #d4af37;
        }
    </style>
</head>
<body>

<header>
    <h1>GAKU NO TOBOE</h1>
    <nav>
        <a href="#news">お知らせ</a>
        <a href="#menu">メニュー</a>
        <a href="#history">ヒストリー</a>
        <a href="#sns">SNS</a>
        <a href="#access">アクセス</a>
        <a href="#gallery">ギャラリー</a>
    </nav>
</header>

<section id="news">
    <h2>お知らせ</h2>
    <p>最新情報やイベント情報をこちらでお知らせします。</p>
    <div>
        <img src="img/グレー　カラフル　シック　シンプル　2025　カレンダー　営業日　インスタグラムの投稿.jpg" alt="お知らせ画像" style="width: 200%; max-width: 1250px; border-radius: 10px; margin-top: 20px;">
    </div>
</section>

<section id="menu">
    <h2>メニュー</h2>
    <p>自家製エンパナーダや自家製デザートで非日常を体験できます。</p>
    <div>
        <img src="img/IMG_2159.JPG" alt="メニュー画像" style="width: 100%; aspect-ratio: 16/9; max-width: 500px; border-radius: 10px; margin-top: 20px; object-fit: cover;">
    </div>
    <div class="menu-items">
        <div>
            <img src="img/IMG_2135.jpg" alt="エンパナーダ">
            <p>☝拡大するよ</p>
        </div>
        <div>
            <img src="img/IMG_2136.jpg" alt="スペシャルドリンク">
            <p>☝拡大するよ</p>
        </div>
    </div>
</section>

<section id="history">
    <h2>ヒストリー</h2>
    <p>GAKU NO TOBOEの歴史やこだわりをご紹介します。</p>
    <div>
        <img src="img/スクリーンショット_6-2-2025_145737_.jpg" alt="ヒストリー画像" style="width: 250%; max-width: 1250px; border-radius: 10px; margin-top: 20px;">
    </div>
<div>
        <img src="img/スクリーンショット 2025-02-06 155403.jpg" alt="ヒストリー画像" style="width: 250%; max-width: 1250px; border-radius: 10px; margin-top: 20px;">
    </div>

</section>

<section id="sns">
    <h2>SNS</h2>
    <p>最新情報やカフェの雰囲気をSNSでチェックしましょう！</p>
    <div style="display: flex; justify-content: center; gap: 20px;">
        <a href="https://www.instagram.com/gaku_no_toboe" target="_blank" style="text-decoration: none; color: #d4af37; font-size: 1.5em;">Instagram</a>
        <a href="https://www.tiktok.com/@gaku.no.toboe_empanadas?_t=ZS-8tgKcjiQMnF&_r=1" target="_blank" style="text-decoration: none; color: #d4af37; font-size: 1.5em;">TikTok</a>
    </div>
</section>

<section id="access">
    <h2>アクセス</h2>
    <p>藤沢市亀井野にある隠れ家カフェへようこそ　最寄り駅 六会日大前</p>
    <p>〒251-0813 神奈川県藤沢市亀井野809-13</p>
    <p>駐車場3台　ワンちゃん利用可能なテラス有</p>
</section>

<section id="gallery" class="gallery">
    <h2>ギャラリー</h2>
    <p>カフェの魅力的な写真をお楽しみください。</p>
    <div>
        <img src="img/IMG_2156.jpg" alt="カフェの写真1">
        <img src="img/IMG_2157.jpg" alt="カフェの写真2">
        <img src="img/IMG_2158 (1).jpg" alt="カフェの写真3">
    </div>
</section>

<footer>
    <p>&copy; 2025 GAKU NO TOBOE</p>
</footer>

</body>
</html>
