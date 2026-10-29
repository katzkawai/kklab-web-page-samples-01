# kklab-web-page-samples-01

シンプルな HTML/CSS の静的ウェブページです。

## 使い方

ローカルで表示するには、リポジトリ直下で次を実行します。

```bash
python -m http.server 8000
```

その後、ブラウザで http://localhost:8000 を開いてください。

## GitHub Pages で公開

1. GitHub リポジトリの Settings > Pages を開く
2. Source を "GitHub Actions" に設定
3. main ブランチへの push で自動デプロイされます

このリポジトリには `.github/workflows/deploy-pages.yml` が含まれており、
GitHub Actions で Pages へ静的サイトを公開します。
