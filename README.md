<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Yihang Chen — Computer Vision Research / LLM Application Development" width="100%">
</picture>

立命館大学大学院 情報理工学研究科の修士課程で、コンピュータビジョンを研究しています。<br>
研究のかたわら、LLM を組み込んだアプリや、生成 AI を使う制作ツールを個人開発で作っています。

<br>

## スキル・使用技術

- **開発で使用**　TypeScript / React / Electron / three.js / LangGraph / Ollama
- **研究で使用**　Python / PyTorch
- **開発ツール**　Claude Code / Codex / GitHub
- **語学**　　　　中国語（母語）/ 日本語

<br>

## 主な開発経験

個人開発を 2 つ公開しています。どちらも、コードは主に Claude Code が書き、Codex がレビューする流れで作りました。自分がやっているのは、何を作るかと仕様の判断、使ってみて見つけた問題のフィードバック、公開前の確認です。

### LLM アプリケーションの開発

- **概要**　　　一文を書くと、遊べる 3D ステージができるブラウザーゲーム
- **内容**　　　ローカルの LLM が、一文をステージの仕様書（構造化出力）に直します。必要なら登場人物の名簿をツールで調べます。配置を作って検査するのはプログラムで、ルールに合わなければ理由をつけて差し戻し、プレビューで確定したものだけを保存します。この流れを LangGraph で組みました。
- **使用技術**　TypeScript / three.js / LangGraph / Ollama
- **リンク**　　[mw-playground](https://github.com/chenyihang98-pixel/mw-playground) · [デモ動画](https://youtu.be/4zSBDaET-JA)

### 生成 AI を使った制作ツールの開発

- **概要**　　　AI で生成した 3D モデルを、Unity で使えるところまで仕上げる Windows アプリ（無料で公開）
- **内容**　　　生成、ポリゴン削減、リギング、モーション付け、Unity への送信を 1 つにまとめました。生成は Tripo・Meshy・Tencent Hunyuan に対応しています。送信前に費用の目安を出し、失敗したタスクは二重課金なしでやり直せます。
- **使用技術**　TypeScript / React / Electron / three.js
- **リンク**　　[Modelwright の紹介](https://github.com/chenyihang98-pixel/Modelwright/blob/main/README.ja.md) · [デモ動画](https://youtu.be/fLYk25TaxHo)

<br>

## 研究経験・論文

### 浮き彫り画像の人物セグメンテーション

- **概要**　　　文化財の浮き彫り（レリーフ）の写真から、人物の領域を切り出す研究
- **内容**　　　浮き彫りは人物と背景の境界が見分けにくいので、画像から得た深度と輪郭の情報を、アダプタを通して SAM に入れる方法を扱いました。
- **使用技術**　Python / PyTorch
- **論文**　　　[ReliefSAM: A Geometry-Augmented Multi-prior Adapter for Bas-Relief Segmentation](https://doi.org/10.1007/978-3-032-37211-6_24)
- **掲載**　　　ECCV 2026（筆頭著者）

<br>

## 最近関心のある分野

LLM やエージェントを、実際に使えるアプリに組み込むところに関心があります。モデルの出力をそのまま信じるのではなく、プログラムで検査して、直させるか、人に確認してもらう。mw-playground で試したこの形を、状態管理や評価のしかたも含めて、もう少し掘り下げたいと思っています。

<br>

## 連絡先

- **メール**　chenyihang98@gmail.com

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/footer-dark.svg">
  <img src="assets/footer-light.svg" alt="" width="100%">
</picture>
