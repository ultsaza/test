# GitHub Pages 静的サイト

このリポジトリは、GitHub Pagesでホスティングされる美しいポートフォリオサイトです。

## 🚀 デプロイ方法

### 1. GitHub Pagesの設定

1. GitHubでリポジトリを作成
2. リポジトリの Settings → Pages に移動
3. Source を「Deploy from a branch」に設定
4. Branch を「main」に設定
5. Folder を「/ (root)」に設定
6. Save をクリック

### 2. ローカルでの確認

```bash
# ローカルサーバーでプレビュー（Python使用）
python -m http.server 8000

# または（Node.js使用）
npx http-server

# ブラウザで http://localhost:8000 を開く
```

## 📁 ファイル構成

```
/
├── index.html       # メインページ
├── style.css        # スタイルシート
├── script.js        # JavaScript機能
└── README.md        # このファイル
```

## 🌟 機能

- **レスポンシブデザイン**: すべてのデバイスで美しく表示
- **モダンなUI/UX**: 最新のデザイントレンドを採用
- **スムーズアニメーション**: 洗練されたトランジション効果
- **インタラクティブな要素**: ユーザーエンゲージメントを高める機能
- **コンタクトフォーム**: バリデーション付きのお問い合わせフォーム
- **SEO最適化**: 検索エンジンに優しい構造

## 🎨 カスタマイズ

### カラーテーマの変更

`style.css`の以下の部分を編集してカラーテーマを変更できます：

```css
/* メインカラー */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* アクセントカラー */
.btn-primary {
    background: linear-gradient(135deg, #667eea, #764ba2);
}
```

### コンテンツの更新

`index.html`を編集して、以下の内容を変更できます：

- 個人情報とプロフィール
- プロジェクトの詳細
- スキルセット
- 連絡先情報

## 📱 ブラウザサポート

- Chrome/Edge (最新版)
- Firefox (最新版)
- Safari (最新版)
- モバイルブラウザ (iOS/Android)

## 🛠️ 開発者向け

### 依存関係

- Font Awesome (CDN)
- Google Fonts (CDN)
- 外部ライブラリは不要

### パフォーマンス最適化

- CSS/JSの最小化
- 画像の最適化
- キャッシュの活用

## 📝 ライセンス

このプロジェクトはMITライセンスの下で公開されています。

## 🤝 貢献

プルリクエストやイシューの報告を歓迎します！

---

**デプロイ後のURL**: `https://yourusername.github.io/repository-name`

> **注意**: GitHub Pagesの設定後、サイトが反映されるまで数分かかる場合があります。 