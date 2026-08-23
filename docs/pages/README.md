# HTML レビュー成果物

このディレクトリには、人間または AI エージェントが生成した、人間がレビューするための HTML 成果物が含まれます。

例:

- レポート
- UI プロトタイプ
- 図
- 比較ページ
- ステークホルダーレビュー用ページ

これらのファイルは信頼できる情報源（source of truth）ではありません。

## 公開範囲に関する注意

このディレクトリを GitHub Pages などで公開する場合、private リポジトリでも公開 URL になることがあります（Enterprise のアクセス制御を使う場合を除く）。インターネットに公開してよい内容かを確認してからデプロイしてください。

意思決定の後は、長期的に有効な知識を以下に記録してください:

- 意思決定は `docs/adr/`
- ドメイン言語は `CONTEXT.md`
- UI の原則は `DESIGN.md`
- 運用手順は `docs/runbook.md`

## 推奨する命名

日付プレフィックス付きのファイル名を使用してください:

```text
YYYY-MM-DD-topic.html
```

例:

```text
reports/2026-06-10-agent-sdk-comparison.html
prototypes/2026-06-10-run-progress-ui.html
diagrams/2026-06-10-background-execution-flow.html
```
