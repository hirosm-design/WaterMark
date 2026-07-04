# X SNS運用チーム「おセンシの時間」

25〜50歳のAIイラストレーター・クリエーター層をターゲットに、X（旧Twitter）で
毎週金曜（目安）に投稿する画像生成企画「おセンシの時間」用の運用チーム構成。

毎回、以下の役割（プロンプト定義）が連携して1本分の投稿素材一式を作る。

| 班 | ファイル | 役割 |
|---|---|---|
| ディレクター | [agents/director.md](agents/director.md) | 依頼者へのヒアリング進行、週替わりテーマの決定、全体統括 |
| リサーチ班 | [agents/researcher.md](agents/researcher.md) | Xで話題の記事・イベント・トレンドの調査 |
| イラストプロンプト班 | [agents/illustration-prompt-writer.md](agents/illustration-prompt-writer.md) | イラスト生成AI（NovelAI/Illustrious系/Midjourney niji等）向けプロンプト作成 |
| 実写プロンプト班 | [agents/photoreal-prompt-writer.md](agents/photoreal-prompt-writer.md) | フォトリアル生成AI（Flux/SDXL実写系等）向けプロンプト作成 |
| コピー班 | [agents/copywriter.md](agents/copywriter.md) | X投稿文・ハッシュタグ作成 |

表現の上限やガードレールは [CONTENT_POLICY.md](CONTENT_POLICY.md) に固定で定義している。
実際の投稿ごとの成果物は `posts/` 以下に日付・回次で保存する。

## 今回の成果物

- [posts/2026-07-02-vol1-tanabata-yukata.md](posts/2026-07-02-vol1-tanabata-yukata.md)
- [posts/2026-07-02-event-kickoff-kunoichi-assassin.md](posts/2026-07-02-event-kickoff-kunoichi-assassin.md)（1,000フォロワー達成記念イベント キックオフ）
- [posts/2026-07-04-bijinga-natsu-genshoku-reijin-vol1.md](posts/2026-07-04-bijinga-natsu-genshoku-reijin-vol1.md)（美人画企画「AI夏幻極彩色の麗人」Vol.1）
- [posts/2026-07-04-prisoner-uniform-dark-fantasy.md](posts/2026-07-04-prisoner-uniform-dark-fantasy.md)（囚人服の意匠を取り入れたイラスト企画・ダークファンタジー版）
