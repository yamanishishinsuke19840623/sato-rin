# 佐藤凛 スポンサーLP

## フォルダ構成

```
佐藤凛/
  index.html     ← LP本体
  photos/        ← 写真を入れるフォルダ
    hero.jpg     ← ヒーロー丸アイコン写真
    profile.jpg  ← プロフィールセクション写真
  README.md      ← このファイル
```

---

## 写真の入れ方

1. Instagram (@sato_rin60) から写真を保存
2. `photos/` フォルダに以下の名前で入れる
   - `hero.jpg` — 顔がわかるアクション写真（正方形推奨）
   - `profile.jpg` — 全身か上半身の縦長写真

写真がなくても 🎾 のアイコンが表示されるので問題ありません。

---

## 問い合わせフォームの設定（Formspree）

### 現在の動作
フォームを送信すると **メールアプリが開く** 形式で動作します（設定ゼロで使えます）。
送信先: naorinbon310@icloud.com（CC: yamanishishinsuke19840623@gmail.com）

### より確実に受け取るには（Formspree 推奨）

1. **https://formspree.io** でアカウントを無料作成
2. 「New Form」を作成 → 受信メールに `naorinbon310@icloud.com` を入力
3. 表示されたフォームID（例: `xyzabcde`）をコピー
4. `index.html` を開き、以下の1行を変更:

```javascript
// 変更前
var FORM_ENDPOINT = '';

// 変更後（ID部分を置き換え）
var FORM_ENDPOINT = 'https://formspree.io/f/xyzabcde';
```

---

## 公開方法（どこかに載せる場合）

### 一番かんたん: GitHub Pages（無料）
1. GitHub アカウントを作成
2. 新しいリポジトリを作成
3. `index.html` と `photos/` フォルダをアップロード
4. Settings → Pages → Source を「main」に設定
5. `https://ユーザー名.github.io/リポジトリ名/` で公開完了

### その他の選択肢
- **Netlify** (https://app.netlify.com) → フォルダごとドラッグ&ドロップで公開
- **WordPress** → かんもんノートと同じ方法で固定ページに埋め込み

---

## 金額の変更

`index.html` 内で「50,000」「100,000」「200,000」を検索して書き換えてください。

---

## お問い合わせ情報
- 受信メール: naorinbon310@icloud.com
- CC: yamanishishinsuke19840623@gmail.com
