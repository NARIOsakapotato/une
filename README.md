# 畝立て設計（オオサカポテト）

圃場をGoogleマップの航空写真でなぞって登録し、本畝・枕畝・明渠を置いて数量を出すアプリ。

- 画面：この index.html（GitHub Pages で公開）
- API：Apps Script「畝立て設計」（~/gas-projects/畝立て設計）、データは「畝立て設計DB」スプレッドシート
- 地図：Google Maps JavaScript API（キーは nariosakapotato.github.io からのみ有効）

## 更新のしかた
画面：`cd ~/gas-projects/une-web && git add -A && git commit -m "update" && git push`
API：`cd ~/gas-projects/畝立て設計 && clasp push -f` → エディタで「デプロイを管理」→ 新バージョン
