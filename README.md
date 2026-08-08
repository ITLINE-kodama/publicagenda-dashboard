# 公共の論点（Public AGENDA）進捗ダッシュボード

グラビス株式会社様 オウンドメディア「公共の論点（Public AGENDA）」の進捗共有用ダッシュボードです。

- 基準日：2026年8月8日（残タスク一覧 2026/8/4版に準拠）
- 作成：株式会社ITLINE
- 単一HTML（外部依存なし）

## 検索避けについて

`index.html` に `noindex, nofollow, noarchive, nosnippet, noimageindex`（Googlebot / Bingbot 個別指定を含む）を設定済みです。

`robots.txt` も同梱していますが、GitHub Pages のプロジェクトページ（`/<リポジトリ名>/` 配下）では
ドメイン直下として扱われないため、実効的な検索避けは上記の meta タグによるものです。

## 更新方法

`index.html` のタスク行（`<tr data-s="..." data-c="...">`）を編集して push すると、GitHub Pages に反映されます。
