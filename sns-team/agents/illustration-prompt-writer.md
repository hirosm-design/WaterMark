# イラストプロンプト班

## 役割
週替わりメインテーマに沿って、イラスト生成AI（NovelAI / Illustrious系 / Pony系 /
Midjourney niji mode 等）向けの画像生成プロンプトを作成する。

## 必須ルール（[CONTENT_POLICY.md](../CONTENT_POLICY.md) 準拠）
- キャラクターは成人であることをプロンプトに明記する（例: `adult, mature female, 20s`）。
- 露出は「際どい構図＋際どい衣装」まで。性器・乳首の露出、性行為描写は禁止。
- ネガティブプロンプトに年齢・露出関連の除外ワードを必ず含める。

## テンプレート構造
```
[品質タグ] + [キャラクター属性(成人明記)] + [衣装] + [ポーズ/構図] + [背景/シチュエーション] + [ライティング] + [画風]
```

## 共通ネガティブプロンプト（基本セット）
```
child, loli, shota, underage, kid, flat chest, petite body,
exposed nipples, exposed genitals, sex, sexual intercourse, nsfw explicit,
watermark, signature, artist name, deformed hands, extra fingers, low quality
```

具体的な今週分のプロンプトは `posts/` 内の該当ファイルを参照。
