# pstack notes

Cursor プラグイン [pstack](https://github.com/cursor/plugins/tree/main/pstack) の理解を深めるためにまとめた図解資料です。

**公開ページ: https://ohzw.github.io/pstack-notes/**

| ファイル | 内容 |
| --- | --- |
| [`index.html`](index.html) | 目次 |
| [`pstack-skeleton.html`](pstack-skeleton.html) | 全体構成図。ルーター・23 プレイブック・並列起動スキル・葉スキルと原則・出荷の 5 段。項目を押すと参照関係を表示 |
| [`pstack-playbook-fanout.html`](pstack-playbook-fanout.html) | プレイブックと fan out（サブエージェントの並列起動）の関係。並列起動スキルに共通する 4 段、9 スキルの並列化と集約の方法、orchestrate との違い |
| [`pstack-playbooks.html`](pstack-playbooks.html) | プレイブック 23 本に共通する 5 つの部品と 7 つの考え方 |
| [`pstack-review.html`](pstack-review.html) | レビュー体制。5 段の検査の起動条件と合格基準、/interrogate、Bugbot の仕分け、独立検証の判定 |
| [`pstack-models.html`](pstack-models.html) | モデル割り当て。/setup-pstack の 17 の役割と既定モデル、混成パネル、推論予算、Claude Code での読み替え、割り当て例 |
| [`pstack-guide.html`](pstack-guide.html) | 作者による pstack ガイド。X の連載 Pt. 1・Pt. 2 の要約を 1 章にまとめたもの。検証スキル、自分の言葉で言い直させる頼み方、README・試作・/architect による設計、計画と実践例 |
| [`articles/pstack-guide-pt1.md`](articles/pstack-guide-pt1.md) | 「The Complete Guide to pstack Pt. 1」の日本語要約（Markdown） |
| [`articles/pstack-guide-pt2.md`](articles/pstack-guide-pt2.md) | 「The Complete Guide to pstack Pt. 2」の日本語要約（Markdown） |

## 見方

ビルド不要の静的 HTML です。ブラウザで直接開いてください。

```sh
open index.html
```

## 出典

- [cursor/plugins/pstack](https://github.com/cursor/plugins/tree/main/pstack)（pstack v0.15.29、2026-10 時点の main）
- lauren（[@poteto](https://x.com/poteto)）の X 記事「The Complete Guide to pstack」[Pt. 1](https://x.com/poteto/status/2094457600259842065)（2026-08-31）、[Pt. 2](https://x.com/poteto/status/2097732320606507506)（2026-09-09）。`pstack-guide.html` と `articles/` はその要約で、全文訳ではありません
- 各ページは、出典の本文の要約と、本文を読み比べた解釈を含みます。解釈部分は各ページで「解釈」と表示しています。
