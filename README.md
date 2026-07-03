# AINOBI for Education LP

## 1. 概要

- サービス名：AINOBI for Education
- 運営会社：株式会社GeekAca
- 対象：学校、大学、専門学校、日本語学校、学習塾などの教育機関
- 目的：教育機関向けAINOBIサービスを紹介する専用ランディングページ
- 主な内容：AI教材生成、AIアバター講師、テスト生成、学習管理、活用事例、料金、FAQ、お問い合わせ

AINOBI for Educationは、学校・大学・専門学校・日本語学校・学習塾などの教育機関向けに、
AI教材生成、AIアバター講師、テスト生成、学習管理などの機能を紹介するランディングページです。

## 2. 公開URL

公開URL：GitHub Pages設定後に追記

## 3. サービス関連URL

AINOBI公式サイト：
https://biz.ainobi.ai/

お問い合わせ：
https://biz.ainobi.ai/contact.html

## 4. 使用技術

- HTML
- CSS
- JavaScript
- Google Fonts（Noto Sans JP）
- GitHub
- GitHub Pages

## 5. ファイル構成

```
ainobi-for-education-lp/
├─ index.html
├─ logo.svg
└─ README.md
```

## 6. ページ構成

現在のindex.htmlに実装されている、上から順のセクション構成です。

- ヘッダー（ロゴ・ナビゲーション・お問い合わせボタン）
- ファーストビュー（ヒーロー）
- 対象教育機関一覧
- 教育現場の課題（こんなお悩みはありませんか？）
- AINOBIの特徴（4つの機能紹介）
- 導入前・導入後の比較
- 活用シーン
- お問い合わせから利用開始までの流れ
- 導入事例
- 料金プラン
- よくある質問（FAQ）
- お問い合わせCTA
- フッター

## 7. 主な機能・仕様

- PC、タブレット、スマートフォン対応
- 固定ヘッダー
- スクロール時のヘッダー背景変更
- ハンバーガーメニュー
- FAQアコーディオン
- スクロールアニメーション
- ページ内スムーススクロール
- GitHub Pagesで公開可能な静的サイト
- 基本的なSEO設定（titleタグ・meta description）

## 8. 対応画面

- PC
- タブレット
- スマートフォン

主要な最新ブラウザでの表示を想定しています。

## 9. 更新方法

1. index.htmlを修正
2. ローカル環境（ブラウザでindex.htmlを開く）で表示確認
3. Gitへ変更を追加
4. コミット
5. GitHubへpush
6. GitHub Pagesへ自動反映

```
git add .
git commit -m "Update LP"
git push
```

## 10. 主な編集箇所

- 文章変更：index.html内の各section
- 色変更：index.html内のstyleタグにあるCSS変数（`:root`内の`--color-*`）
- お問い合わせURL：aタグのhref
- 会社情報：footer内
- 料金：料金セクション（`id="pricing"`）
- FAQ：FAQセクション（`id="faq"`）
- SEO情報：head内のtitle、meta description
  （OGP・canonicalタグは現時点で未設定です。正式公開時に追加を検討してください）

## 11. 公開方法

1. GitHubリポジトリの Settings を開く
2. 左メニューの Pages を選択
3. Source を「Deploy from a branch」にする
4. Branch を「main」、フォルダを「/ (root)」にして Save
5. 公開後に表示されるURLを、このREADMEの「2. 公開URL」欄へ追記する

## 12. 注意事項

- 正式公開前に文章、料金、会社情報、リンク先を確認する
- canonical、og:url、og:imageなどのOGP設定は、正式な公開URLが決まってから設定する（現時点では未設定）
- 存在しないURLを追加しない
- ロゴや画像ファイル名を変更した場合は、index.html内のパスも変更する
- GitHubへ機密情報、APIキー、個人情報をアップロードしない

## 13. 運営会社

株式会社GeekAca

所在地：
東京都千代田区内幸町2-2-3 日比谷国際ビル3F

## 14. 共有用メモ

- 制作状況：完成
- 公開状況：GitHub Pages設定後に更新
- 確認事項：文章、料金、リンク、SEO情報、OGP画像
- 最終更新日：2026-07-03
