<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>語学マニアのガジェ部屋</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>語学マニアのガジェ部屋</h1>
    <nav>
      <ul>
        <li><a href="#">ホーム</a></li>
        <li><a href="#">英語学習</a></li>
        <li><a href="#">ガジェット</a></li>
        <li><a href="#">プロフィール</a></li>
        <li><a href="#">お問い合わせ</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="hero">
      <h2>英語とガジェットで日常をアップグレード。</h2>
      <p>TOEIC・IELTS対策と、学習を支えるアイテムレビューをお届けします。</p>
    </section>

    <section class="latest-posts">
      <h3>最新記事</h3>
      <div class="posts">
        <article>
          <h4>【TOEIC】リスニング満点を取るための習慣</h4>
          <p>毎日10分でできる練習方法を紹介。</p>
          <a href="#">続きを読む</a>
        </article>
        <article>
          <h4>【レビュー】ノイキャン最強イヤホンTOP3</h4>
          <p>英語学習にも最適なガジェットを徹底比較！</p>
          <a href="#">続きを読む</a>
        </article>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 語学マニアのガジェ部屋</p>
  </footer>
</body>
</html>/* 全体共通スタイル */
body {
  margin: 0;
  font-family: 'Helvetica Neue', sans-serif;
  background-color: #f0f4ff;
  color: #222;
  line-height: 1.6;
}

/* ヘッダー */
header {
  background: linear-gradient(to right, #1e3a8a, #2563eb);
  color: white;
  padding: 30px 20px;
  text-align: center;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

header h1 {
  margin: 0;
  font-size: 2.5rem;
  letter-spacing: 2px;
}

/* ナビゲーション */
nav ul {
  list-style: none;
  padding: 0;
  margin: 15px 0 0;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s;
}

nav a:hover {
  color: #c7d2fe;
}

/* ヒーローセクション */
.hero {
  background-color: #3b82f6;
  color: white;
  text-align: center;
  padding: 60px 20px;
  border-bottom: 6px solid #1e3a8a;
}

.hero h2 {
  font-size: 2rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
  opacity: 0.9;
}

/* 記事一覧 */
.latest-posts {
  padding: 50px 20px;
  max-width: 1000px;
  margin: auto;
}

.latest-posts h3 {
  text-align: center;
  color: #1e3a8a;
  margin-bottom: 40px;
}

.posts {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 30px;
}

article {
  background: white;
  padding: 25px;
  border-radius: 12px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.08);
  transition: transform 0.3s;
}

article:hover {
  transform: translateY(-5px);
}

article h4 {
  color: #2563eb;
  margin-top: 0;
}

article p {
  font-size: 0.95rem;
}

article a {
  display: inline-block;
  margin-top: 10px;
  color: #1d4ed8;
  text-decoration: underline;
  font-weight: bold;
}

/* フッター */
footer {
  text-align: center;
  padding: 20px;
  background-color: #1e3a8a;
  color: white;
  font-size: 0.9rem;
}
