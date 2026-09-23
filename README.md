# 精神保健福祉Wiki

GitHub Pagesで公開できる、あとから用語を追加・修正できるWiki型サイトです。

## 1. 最初にすること
`index.html` を開き、次の2か所を自分のGitHub情報に変更してください。

- `REPLACE_OWNER` → GitHubユーザー名
- `REPLACE_REPO` → このWikiのリポジトリ名

## 2. GitHub Pages
Repository → Settings → Pages → Deploy from a branch → `main` / `/ (root)` → Save

## 3. 用語を追加・修正
`data/terms.json` をGitHub上で編集します。

1件の形式：
{
  "id": "new-term",
  "name": "新しい用語",
  "category": "カテゴリー名",
  "description": "用語の説明",
  "points": ["ポイント1", "ポイント2"]
}

`id` は重複しない英数字・ハイフンを使ってください。

## 4. 編集ボタン
用語ページの「GitHubで編集する」から `data/terms.json` を直接編集できます。
