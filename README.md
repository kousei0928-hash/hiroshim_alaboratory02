# 広島大学 廣田研究室 Webサイト

静的サイト（`index.html` + `style.css`）として構成しています。

## 構成

- `index.html`: ページ本体
- `style.css`: デザイン
- `assets/`: 画像など素材置き場

## 素材差し替え

1. 先生から受領した画像を `assets/` に配置
2. まずは `assets/hero-lab.jpg` を配置（トップ画像）
3. 必要に応じて `index.html` 内のメンバー・業績テキストを更新

## Vercel公開（GitHub連携）

1. このフォルダをGitHubリポジトリにpush
2. Vercelで `Add New... > Project` を選択
3. 該当リポジトリをImport
4. Framework Presetは `Other`（静的）
5. Build Commandは空欄、Output Directoryは空欄のままでDeploy
6. デプロイ後、Vercelの `Domains` で管理ドメインを追加

## 備考

- 現行実装は「AIっぽい装飾」を避け、大学研究室サイトとして読みやすさ重視で設計
- モバイル表示に対応（メニューは折りたたみ）
