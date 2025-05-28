# i-Reporter 設定ファイル(.ircf) 生成ツール

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://i-repo-community.github.io/ircf-generator/)

## 概要

**i-Reporter**（アイレポーター）の設定ファイル（`.ircf`）を簡単に生成できる Web ツールです。

i-Reporter アプリの各システム環境設定情報を予めセットした専用の設定ファイルを i-Reporter アプリへ読込ませる事で、システム環境設定項目を自動でセットすることができます。設定ファイルを各ユーザーへ配布する事で、初期設定の簡略化や、大量の端末の配布においてシステム環境設定の内容を容易に統一させることができます。

## 🚀 デモ

**[ツールを使ってみる](https://i-repo-community.github.io/ircf-generator/)**

## ✨ 主な機能

- **サーバー接続設定**（複数サーバー対応）
- **プロキシ・認証設定**
- **PDF 出力・メール送信設定**
- **音声入力・署名タブレット設定**
- **既存の設定ファイル読込・編集・保存**

## 📱 活用メリット

- **初期設定の簡略化**: ユーザーが個別に設定する手間を削減
- **大量端末の統一管理**: システム環境設定の内容を容易に統一
- **簡単配布**: メール添付や HP 公開で各ユーザーへ配布可能
- **端末キッティング最適化**: 導入時の作業効率を大幅向上

## 🔧 配布方法の例

- 📧 **メール添付**: 生成した.ircf ファイルを添付してメール送信
- 🌐 **HP 公開**: Web サイトや Portal サイトで.ircf ファイルを公開
- 📁 **共有フォルダ**: 社内ネットワークの共有フォルダに配置
- 💾 **記録媒体**: USB メモリやクラウドストレージ経由で配布

## 📖 詳細ドキュメント

.ircf ファイルの詳細説明については、公式ドキュメントをご参照ください：

**[専用設定ファイル読込によるシステム環境設定項目の自動設定機能 (PDF)](https://cimtops-support.com/i-Reporter/ir_manuals/jp/ios_app/ConfigurationFileReading_jp.pdf)**

## 🛠️ 技術スタック

- **HTML5** + **CSS3** (Tailwind CSS)
- **Vanilla JavaScript**
- **GitHub Pages** でホスティング

## 📄 ファイル構成

```
ircf-generator/
├── index.html          # メインのWebアプリケーション
├── README.md          # このファイル
└── LICENSE            # MITライセンス
```

## 🚀 ローカル開発

```bash
# リポジトリをクローン
git clone https://github.com/i-repo-community/ircf-generator.git

# ディレクトリに移動
cd ircf-generator

# Webサーバーを起動（例：Python）
python -m http.server 8000

# ブラウザでアクセス
open http://localhost:8000
```

## 🤝 コントリビューション

プルリクエストや Issue の報告を歓迎します！

1. このリポジトリをフォーク
2. フィーチャーブランチを作成 (`git checkout -b feature/amazing-feature`)
3. 変更をコミット (`git commit -m 'Add some amazing feature'`)
4. ブランチにプッシュ (`git push origin feature/amazing-feature`)
5. プルリクエストを作成

## ⚠️ 免責事項

このツールは**コミュニティ有志によるオープンソースソフトウェア**です。

利用により生じたいかなる損害についても、開発者・コミュニティは一切の責任を負いません。自己責任でご利用ください。

## 📝 ライセンス

このプロジェクトは [MIT License](LICENSE) の下で公開されています。
