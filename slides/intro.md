---
marp: true

style: |
    @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@400;700&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=DotGothic16&display=swap');

    body, section {
        font-family: 'Noto Sans JP', sans-serif;
        font-size: 1.5em;
    }
    .dotgothic-slide {
        font-family: 'DotGothic16', 
        sans-serif;
        font-size: 2.5em;
        text-align: center;
    }

    .title-band {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 64px;
        color: gray;
        font-weight: bold;
        line-height: 64px;
        z-index: 10;
        padding: 0.5em;
        padding-left: 1em;
    }

    .card-row {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 1em;
        height: 400px;
    }
    .card {
        flex: 1;
        margin: 0 0.5em;
        display: flex;
        height: 320px;
        flex-direction: column;
        justify-content: flex-start;
        align-items: center;
        text-align: center;
        padding: 1em;
        overflow: auto;
        border: 1px solid #ddd;
        border-radius: 16px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
        transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    .card.circle {
        border-radius: 50%;
        height: 300px;
        aspect-ratio: 1 / 1;
        justify-content: center;
    }
    .bottom-center {
        position: absolute;
        bottom: 50px;
        left: 50%;
        transform: translateX(-50%);
        text-align: center;
        font-size: 1.2em;
        color: #333;
    }


---

<section class="dotgothic-slide">
<h1>ChatGPTは人間になれたのか</h1>
<p>テキスト生成の進化により、人間は計算機と自然な対話ができるようになった。  
人間と計算機、どちらとテキストをやり取りしているかはもはや判別ができなくないだろう。
では「本来の人間の会話」とは何でしょうか？</p>
</section>

---

# 🧠 1. 人間の「推論」とは？
## → 推論とは、前提から論理的に結論を導くプロセス（演繹・帰納・仮説形成などを含む）
人間の推論は：
- 自分自身で問いを立てる
- 目的や価値観に照らして判断する
- 矛盾を検出・修正できる
- 経験・感情・意志と深く関わっている

よって、“自我”と“内省”を伴った思考活動として、推論は人間的特性に強く根ざしている

---

<div class="title-band">
    <h1>AIの特徴</h1>
</div>
<div class="card-row">
    <div class="card">
        <h1>検索機能</h1>
        <p>人類社会のすべて人類社会のすべて人類社会のすべて人類社会のすべて人類社会のすべて</p>
    </div>
  <div class="card">
    <p>Column2</p>
  </div>
  <div class="card">
    <p>Column2</p>
  </div>
</div>
<div class="bottom-center">
    <h1>→結論をここに示す</h1>
</div>

---

<div class="title-band">
    <h1>AIの特徴（丸型）</h1>
</div>
<div class="card-row">
    <div class="card circle">
        <h1>検索機能</h1>
        <p>人類社会のすべて人類社会のすべて人類社会のすべて人類社会のすべて人類社会のすべて</p>
    </div>
  <div class="card circle">
    <p>Column2</p>
  </div>
  <div class="card circle">
    <p>Column2</p>
  </div>
</div>
<div class="bottom-center">
    <h1>→結論をここに示す（丸）</h1>
</div>


---

