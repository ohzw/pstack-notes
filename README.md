# pstack notes

Cursor プラグイン [pstack](https://github.com/cursor/plugins/tree/main/pstack) の理解を深めるためにまとめた図解資料です。

**公開ページ: https://ohzw.github.io/pstack-notes/**

| ファイル | 内容 |
| --- | --- |
| [`index.html`](index.html) | 目次 |
| [`pstack-skeleton.html`](pstack-skeleton.html) | 全体構成図。ルーター・23 プレイブック・並列ワークフロー・葉スキルと原則・出荷の 5 段。項目を押すと参照関係を表示 |
| [`pstack-playbooks.html`](pstack-playbooks.html) | プレイブック 23 本に共通する 5 つの部品と 7 つの考え方 |
| [`pstack-playbook-fanout.html`](pstack-playbook-fanout.html) | プレイブックと fan out の関係。fan out に共通する 4 段、9 つの型の並列化と集約の方法、orchestrate との違い |
| [`pstack-review.html`](pstack-review.html) | レビュー体制。5 段の検査の起動条件と合格基準、/interrogate、Bugbot の仕分け、独立検証の判定 |

## 見方

ビルド不要の静的 HTML です。ブラウザで直接開いてください。

```sh
open index.html
```

## 出典

- [cursor/plugins/pstack](https://github.com/cursor/plugins/tree/main/pstack)（pstack v0.15.29、2026-10 時点の main）
- 各ページは、出典の本文の要約と、本文を読み比べた解釈を含みます。解釈部分は各ページで「解釈」と表示しています。
