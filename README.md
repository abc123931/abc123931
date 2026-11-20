# abc123931

Software engineer building quality guardrails for AI coding agents.

AI エージェントがコードを書く前提で、品質が落ちない仕組みを設計・運用しています。テスト・レビュー・QA を、人の頑張りではなく仕組みに落とし込むことに取り組んでいます。

## Current focus

- Review pipelines that separate the implementing agent from the reviewing agent
- Automated QA by a separate agent after merge
- CI gates and strict TDD for agent-written code
- Measuring the effect of agent skills with evals

## Projects

- **Neiro** — 自社サービス。上記の仕組みを実際のプロダクト開発で運用しています。
- [**tdd-autoreview-demo**](https://github.com/abc123931/tdd-autoreview-demo) — 厳格な TDD と自動コードレビューで信頼を担保する開発ワークフローの雛形。
- [**slack-context-mcp**](https://github.com/abc123931/slack-context-mcp) — Slack の会話を LLM が読みやすい文脈に整える MCP サーバー。

## Background

- GameHint / assort — 2 人・4 人のチームで、企画・設計・実装・インフラ・運用までを主導。
