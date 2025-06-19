> **リポジトリ名推奨**: `se-career-agent-comparison-tool`

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-blue)](https://[your-username].github.io/se-career-agent-comparison-tool/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 🎯 概要

システムエンジニア向けの転職エージェント比較ツールです。  
**経験年数・希望年収・対応地域・専門性**で絞り込み検索ができ、各エージェントの特徴を視覚的に比較できます。

## ✨ 主な機能

### 🔍 インタラクティブな絞り込み機能
- **経験年数別**: 未経験〜2年 / 3〜5年 / 6年以上
- **希望年収別**: 〜400万 / 400〜600万 / 600〜1000万 / 1000万〜
- **対応地域別**: 全国対応 / 都市部中心 / 首都圏のみ
- **専門性別**: 総合型 / IT専門 / ハイクラス

### ⭐ 視覚的評価システム
- 求人数・年収レンジ・サポート品質・IT専門性を5段階で評価
- 星表示で一目で特徴を把握

### 🏷️ エージェント分類
- **総合型** (青): リクルート、doda等の大手総合エージェント
- **IT専門** (緑): レバテック、マイナビIT等の業界特化型
- **ハイクラス** (赤): ビズリーチ、JAC等の高年収特化型

### 📱 レスポンシブデザイン
- PC・タブレット・スマートフォンに対応
- モダンなグラデーションとカードデザイン

## 🚀 デモサイト

**👉 [ライブデモを見る](https://[your-username].github.io/se-career-agent-comparison-tool/)**

## 📦 使い方

### ローカルで実行する場合

```bash
# リポジトリをクローン
git clone https://github.com/[your-username]/se-career-agent-comparison-tool.git

# ディレクトリに移動
cd se-career-agent-comparison-tool

# ブラウザでindex.htmlを開く
open index.html
```

### GitHub Pagesで公開する場合

1. GitHubリポジトリを作成
2. `index.html`をアップロード
3. Settings → Pages → Source で `Deploy from a branch` を選択
4. Branch を `main` に設定
5. `https://[your-username].github.io/se-career-agent-comparison-tool/` でアクセス可能

## 📊 掲載エージェント一覧

### 🏢 大手総合型
- **リクルートエージェント** - 業界最大級の求人数
- **doda** - 転職フェア・セミナー充実
- **マイナビITエージェント** - 20代・第二新卒に強い

### 💻 IT専門型
- **レバテックキャリア** - エンジニア出身アドバイザー
- **ワークポート** - IT業界特化の老舗
- **TechClipsエージェント** - 高年収・自社開発特化

### 👑 ハイクラス向け
- **ビズリーチ** - スカウト機能充実
- **JACリクルートメント** - 外資系・グローバル企業

## 🛠️ 技術仕様

- **HTML5**: セマンティックなマークアップ
- **CSS3**: Flexbox・Grid・アニメーション
- **JavaScript (ES6+)**: 動的フィルタリング・DOM操作
- **レスポンシブデザイン**: モバイルファースト

## 📝 ファイル構成

```
se-career-agent-comparison-tool/
├── index.html          # メインページ（HTML + CSS + JS）
├── README.md           # このファイル
└── LICENSE             # MITライセンス
```

## 🔧 カスタマイズ

### エージェント情報の追加・編集

`index.html`内の`agents`配列を編集することで、エージェント情報をカスタマイズできます：

```javascript
const agents = [
    {
        name: "エージェント名",
        type: "comprehensive", // comprehensive | specialized | premium
        typeLabel: "総合型",
        featured: true, // 注目エージェントかどうか
        ratings: {
            jobCount: 5,    // 求人数 (1-5)
            salary: 4,      // 年収レンジ (1-5)
            support: 4,     // サポート品質 (1-5)
            specialty: 3    // IT専門性 (1-5)
        },
        // ... 他の設定
    }
];
```

### スタイルのカスタマイズ

CSS変数を使用してテーマカラーを簡単に変更できます：

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f6ad55;
}
```

## 🤝 コントリビューション

プルリクエストやイシューの作成を歓迎します！

### 改善アイデア
- [ ] エージェント情報のJSON外部ファイル化
- [ ] ダークモード対応
- [ ] 検索機能の追加
- [ ] お気に入り機能
- [ ] 比較表示機能

## 📄 ライセンス

このプロジェクトは [MIT License](LICENSE) の下で公開されています。

## 📞 関連リンク

- **ブログ記事**: [SEがつらい理由と対策完全ガイド](https://example.com/blog/se-tsurai)
- **作者Twitter**: [@your_twitter_handle](https://twitter.com/your_twitter_handle)
- **Issue報告**: [GitHub Issues](https://github.com/[your-username]/se-career-agent-comparison-tool/issues)

## 🙏 謝辞

このツールは、現役SE・管理職としての現場経験と、多くの転職経験者からの情報提供をもとに作成されました。

転職を検討中の全てのエンジニアの皆さんのキャリア形成に少しでもお役に立てれば幸いです。

---

**⭐ このツールが役に立ったら、ぜひスターをお願いします！**
