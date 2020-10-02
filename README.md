# docsify-template
docsify template for quick start

# 初期化
以下の3ファイルが作成される  
- ./docs/index.html
- ./docs/README.md
- ./docs/.nojekyll　（Github Page用）
```javascript
npx docsify-cli init ./docs
```

# ローカルでドキュメントサイト立ち上げ
http://localhost:3000にアクセスすると、README.mdの内容が表示される
```javascript
npx docsify-cli serve docs
```
