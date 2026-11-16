<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Yihang Chen" width="100%">
</picture>

立命館大学大学院 情報理工学研究科の Yihang Chen です。

生成 AI が出したものは、そのままでは使えないことがよくあります。<br>
3D モデルはポリゴンが多すぎてゲームに入らないし、LLM の出力はルールに合わないことがあります。<br>
そこから実際に使えるところまで持っていく道具を、個人開発で作っています。

**「生成できた」で終わらせず、検査して、直して、人が安心して使えるところまで作る。そういうエンジニアを目指しています。**

<br>

## スキル・語学

- **使用技術**　Python / TypeScript / PyTorch / React / Electron / three.js / LangGraph
- **ツール**　　GitHub / PyCharm / VS Code / Unity / Ollama / Claude Code / Codex
- **語学**　　　中国語（母語）/ 日本語

<br>

## 主な開発経験

### LLM アプリケーションの開発

- **内容**　　　一文を書くと、遊べる 3D ステージができるブラウザーゲーム。ローカルの LLM と LangGraph で、一文からステージを生成します。Modelwright で作ったキャラクターを読み込んで、主人公や仲間にできます。
- **使用技術**　TypeScript / three.js / LangGraph / Ollama
- **リンク**　　[mw-playground](https://github.com/chenyihang98-pixel/mw-playground) · [デモ動画](https://youtu.be/4zSBDaET-JA)

### 生成 AI を使った制作ツールの開発

- **内容**　　　AI で生成した 3D モデルを、Unity で使えるところまで仕上げる Windows アプリ。生成、ポリゴン削減、リギング、モーション付け、Unity への送信を 1 つにまとめました。無料で公開し、更新を続けています。
- **使用技術**　TypeScript / React / Electron / three.js
- **リンク**　　[Modelwright の紹介](https://github.com/chenyihang98-pixel/Modelwright/blob/main/README.ja.md) · [デモ動画](https://youtu.be/fLYk25TaxHo)

<br>

## 研究経験・論文

### 浮き彫り画像の人物セグメンテーション

- **内容**　　　文化財の浮き彫り（レリーフ）の写真から、人物の領域を切り出す研究。人物と背景の境界が見分けにくいので、画像から得た深度と輪郭の情報を、アダプタを通して SAM に入れる方法を扱いました。
- **使用技術**　Python / PyTorch
- **論文**　　　[ReliefSAM: A Geometry-Augmented Multi-prior Adapter for Bas-Relief Segmentation](https://doi.org/10.1007/978-3-032-37211-6_24)
- **掲載**　　　ECCV 2026（筆頭著者）

<br>

## 最近関心のある分野・取り組み

いま関心があるのは、**LLM やエージェントを、実際に使えるアプリケーションに組み込むこと**です。

モデルの出力は、いつも頼んだとおりになるとは限りません。出力をプログラムで検査して、だめなら理由をつけて直させ、最後は人が確認する。この形をどう作るかを、mw-playground の「レベル工房」で試しました。

### これまでに試したこと

1. **構造化出力**<br>
   LLM に書かせるのはステージの仕様書だけ。座標は書かせず、配置はプログラムが作って検査する
2. **ツール呼び出し**<br>
   登場人物の名簿を、モデルが必要なときだけ読みに行く（読み取り専用）
3. **差し戻しと人の確認**<br>
   ルールに合わなければ理由をつけて差し戻す（2 回まで）。プレビューで確定したものだけを保存する
4. **結果の数え方**<br>
   「検査に通った」と「頼んだとおりになった」を分けて記録する

詳しくは [レベル工房のしくみ](https://github.com/chenyihang98-pixel/mw-playground/blob/main/docs/how-it-works.md) に書きました。

<br>

## 連絡先

- **メール**　chenyihang98@gmail.com

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/footer-dark.svg">
  <img src="assets/footer-light.svg" alt="" width="100%">
</picture>
