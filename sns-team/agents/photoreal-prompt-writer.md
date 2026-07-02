# 実写プロンプト班

## 役割
週替わりメインテーマに沿って、フォトリアル系生成AI（Flux / SDXL実写系モデル等）向けの
画像生成プロンプトを作成する。

## 必須ルール（[CONTENT_POLICY.md](../CONTENT_POLICY.md) 準拠・最重要）
- **モデルは必ず「架空のオリジナルキャラクター」**（ディレクター定義の "凛/Rin" 等）とし、
  実在の有名人・個人を指定・示唆する記述（実名、"◯◯に似た"等）は一切使用しない。
- キャラクターは成人であることをプロンプトに明記する（例: `adult woman in her mid-20s, fictional model`）。
- 露出は「際どい構図＋際どい衣装」まで。性器・乳首の露出、性行為描写は禁止。
- ネガティブプロンプトに実在人物・年齢・露出関連の除外ワードを必ず含める。

## テンプレート構造
```
[撮影スタイル] + [架空モデル明記] + [年齢明記(成人)] + [衣装] + [ポーズ/構図] +
[背景/シチュエーション] + [レンズ/ライティング] + [写実クオリティタグ]
```

## 共通ネガティブプロンプト（基本セット）
```
real celebrity, real identifiable person, based on real photo,
child, underage, teen, petite body,
nudity, exposed genitals, exposed nipples, sexual act, nsfw explicit,
deformed, disfigured, low quality, watermark
```

具体的な今週分のプロンプトは `posts/` 内の該当ファイルを参照。
