# QR on Safari

📱 シンプルで使いやすいQRコードジェネレーター

## 概要

テキストやURLをQRコードに変換するシンプルなWebアプリケーションです。リアルタイムのログ表示機能により、QRコード生成プロセスの各ステップを確認できます。

## 機能

- ✨ **シンプルなUI**: 直感的に使えるインターフェース
- 📝 **テキスト入力**: 任意の文字列をQRコードに変換
- 📊 **ログ表示**: 処理の各ステップをリアルタイムで表示
- 🎨 **レスポンシブデザイン**: スマートフォンからPCまで対応
- 🔒 **セキュア**: すべての処理がブラウザ内で完結（サーバーにデータを送信しません）

## 使い方

1. テキストエリアにQRコードにしたい文字列を入力
2. 「QRコードを生成」ボタンをクリック
3. ログエリアで処理の進行状況を確認
4. 生成されたQRコードが画面下部に表示されます

### ショートカット

- `Ctrl + Enter`: テキストエリア内でQRコード生成を実行

## デモ

![デモスクリーンショット](https://github.com/user-attachments/assets/d1851cc4-0897-4e2d-8995-043f281729b4)

## 技術仕様

- **HTML5** + **CSS3** + **JavaScript**（Vanilla JS）
- **QRコードライブラリ**: [qrcodejs](https://github.com/davidshimjs/qrcodejs)
- **デプロイ**: GitHub Pages

## ローカル開発

1. リポジトリをクローン
```bash
git clone https://github.com/hn770123/QR-on-Safari.git
cd QR-on-Safari
```

2. ローカルサーバーを起動
```bash
python3 -m http.server 8080
```

3. ブラウザで `http://localhost:8080` を開く

## ライセンス

このプロジェクトで使用しているQRコードライブラリ（qrcodejs）は[MIT License](https://github.com/davidshimjs/qrcodejs/blob/master/LICENSE)の下で配布されています。

## 作者

[@hn770123](https://github.com/hn770123)
