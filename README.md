# 📝 Git Markdown Helper

GitのPRやIssueを書く時に便利な、コンパクトなMarkdown記法入力ツール

## 🌐 Web版を試す

**👉 [https://yourusername.github.io/git-markdown-helper/](https://yourusername.github.io/git-markdown-helper/)**

ブラウザで即座に利用可能！ボタンをクリックしてMarkdown記法を入力し、コピー&ペーストで使用できます。

## ✨ 主な機能

- **🎯 コンパクト**: 220px幅の小さなダイアログ
- **⚡ 高速入力**: ワンクリックでMarkdown記法を挿入
- **📱 レスポンシブ**: PC・スマートフォン対応
- **🔧 カスタマイズ可能**: よく使う記法のみを厳選

## 📝 対応記法

| ボタン | 機能 | 出力例 |
|--------|------|--------|
| **H1/H2/H3** | 見出し | `# タイトル` |
| **B/I** | 太字/斜体 | `**太字**` `*斜体*` |
| **☐/☑** | チェックボックス | `- [ ] タスク` `- [x] 完了` |
| **•/1.** | リスト | `- 項目` `1. 項目` |
| **❝** | 引用 | `> 引用文` |
| **&lt;/&gt;** | インラインコード | `` `code` `` |
| **{ }** | コードブロック | `` ```code``` `` |
| **―** | 区切り線 | `---` |

## 💾 デスクトップ版

より高機能なElectronアプリ版も利用可能：

- **グローバルショートカット**: `Ctrl+Shift+M`でどこからでも呼び出し
- **直接入力**: バックグラウンドアプリのカーソル位置に自動入力
- **システムトレイ**: 常駐して邪魔にならない
- **オフライン利用**: インターネット接続不要

### ダウンロード

[📥 最新版をダウンロード](https://github.com/yourusername/git-markdown-helper/releases)

## 🚀 使用例

### PR作成時
```markdown
# 🐛 Bug Fix: ユーザー認証エラーを修正

## 📋 変更内容
- [ ] 認証トークンの有効期限チェックを追加
- [x] エラーハンドリングを改善
- [ ] テストケースを追加

## 🔧 修正方法
> 認証ミドルウェアで有効期限を事前にチェックするように変更

```javascript
if (token.expired) {
  throw new AuthError('Token expired');
}
```

---
Fixes #123
```

## 🛠️ 開発者向け

### セットアップ
```bash
git clone https://github.com/yourusername/git-markdown-helper.git
cd git-markdown-helper
npm install
npm start
```

### ビルド
```bash
npm run build-win  # Windows用exe
npm run build-mac  # macOS用app
```

## 📄 技術スタック

- **フロントエンド**: HTML5, CSS3, Vanilla JavaScript
- **デスクトップ**: Electron
- **自動入力**: robotjs
- **ビルド**: electron-builder

## 🤝 貢献

Issues、Pull Requestsを歓迎します！

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📋 TODO

- [ ] ショートカットキーのカスタマイズ
- [ ] よく使う記法のお気に入り機能
- [ ] カラーテーマの切り替え
- [ ] 記法のプリセット機能

## 📄 ライセンス

MIT License - [LICENSE](LICENSE) ファイルを参照

## 🙏 謝辞

このツールは、日々GitHubでPRやIssueを書く開発者の生産性向上を目指して作成されました。

---

**💡 Tip**: ブラウザから「ホーム画面に追加」でPWAとしてインストールすることも可能です！
