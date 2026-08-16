# 髙橋亮 Portfolio

シンプルで洗練されたポートフォリオサイト。デザイン、マーケティング、食の領域での経験を紹介します。

## 技術スタック

- HTML5
- CSS3
- Zen Kaku Gothic New（日本語フォント）
- Helvetica（英語フォント）

## デプロイ

### Cloudflare Pages での公開

1. このリポジトリを GitHub にプッシュ
2. Cloudflare Pages ダッシュボードにアクセス
3. 「Connect to Git」を選択
4. このリポジトリを選択
5. 自動デプロイが開始されます

### ビルド設定

- **Framework preset**: None
- **Build command**: （不要）
- **Build output directory**: /

## ファイル構成
cat > .gitignore << 'EOF'
# OS
.DS_Store
Thumbs.db

# IDEs
.vscode/
.idea/
*.swp
*.swo

# Node (不要だが念のため)
node_modules/
npm-debug.log

# Build output
dist/
build/
