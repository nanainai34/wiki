<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>世界防衛国連邦架空国家 Wiki</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="header-content">
            <h1>世界防衛国連邦架空国家 Wiki</h1>
            <p>歴史・政府・文化・ギャラリーなど</p>
        </div>
    </header>
    <nav>
        <ul>
            <li><a href="#about">国家概要</a></li>
            <li><a href="#history">歴史</a></li>
            <li><a href="#government">政府</a></li>
            <li><a href="#culture">文化</a></li>
            <li><a href="#gallery">ギャラリー</a></li>
            <li><a href="#comments">コメント</a></li> <!-- コメントセクションへのリンクを追加 -->
        </ul>
    </nav>
    <main>
        <section id="about">
            <h2>国家概要</h2>
            <p>ここに国家の基本的な情報や特徴を記述します。</p>
        </section>
        <section id="history">
            <h2>歴史</h2>
            <div id="history-content">
                <!-- JavaScriptで動的に歴史を表示 -->
            </div>
            <form id="history-form">
                <h3>歴史を記述する</h3>
                <label for="history-name">名前:</label><br>
                <input type="text" id="history-name" name="history-name" required><br>
                <label for="history-content">内容:</label><br>
                <textarea id="history-content" name="history-content" rows="4" cols="50" required></textarea><br>
                <button type="submit">投稿する</button>
            </form>
        </section>
        <section id="government">
            <h2>政府</h2>
            <div id="government-content">
                <!-- JavaScriptで動的に政府を表示 -->
            </div>
            <form id="government-form">
                <h3>政府を記述する</h3>
                <label for="government-name">名前:</label><br>
                <input type="text" id="government-name" name="government-name" required><br>
                <label for="government-content">内容:</label><br>
                <textarea id="government-content" name="government-content" rows="4" cols="50" required></textarea><br>
                <button type="submit">投稿する</button>
            </form>
        </section>
        <section id="culture">
            <h2>文化</h2>
            <p>国家の文化や伝統について紹介します。</p>
            <form id="culture-form">
                <h3>文化を記述する</h3>
                <label for="culture-name">タイトル:</label><br>
                <input type="text" id="culture-name" name="culture-name" required><br>
                <label for="culture-content">内容:</label><br>
                <textarea id="culture-content" name="culture-content" rows="4" cols="50" required></textarea><br>
                <button type="submit">投稿する</button>
            </form>
            <div id="culture-content"></div>
        </section>
        <section id="gallery">
            <h2>ギャラリー</h2>
            <p>国家の写真やイラストなどを掲載します。</p>
            <form id="photo-form">
                <h3>写真をアップロードする</h3>
                <label for="photo-name">タイトル:</label><br>
                <input type="text" id="photo-name" name="photo-name" required><br>
                <label for="photo-file">ファイルを選択:</label><br>
                <input type="file" id="photo-file" name="photo-file" accept="image/*" required><br>
                <button type="submit">アップロードする</button>
            </form>
            <div id="photo-gallery"></div>
        </section>

        <section id="comments">
            <h2>コメントを投稿する</h2>
            <form id="comment-form">
                <label for="comment-name">名前:</label><br>
                <input type="text" id="comment-name" name="comment-name" required><br>
                <label for="comment-content">コメント:</label><br>
                <textarea id="comment-content" name="comment-content" rows="4" cols="50" required></textarea><br>
                <button type="submit">投稿する</button>
            </form>
        </section>

        <section id="display-comments">
            <h2>投稿されたコメント</h2>
            <ul id="comments-list">
                <!-- JavaScriptで動的にコメントが表示される -->
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 世界防衛国連邦架空国家. All rights reserved.</p>
    </footer>

    <script src="scripts.js"></script> <!-- JavaScriptファイルの読み込み -->
</body>
</html>
