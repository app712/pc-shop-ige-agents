# pc-shop-ige-agents

PC SHOP IGE / 協同組合サイクルブリッジ沖縄のAI社員(サブエージェント)定義集。

`.claude/agents/` 配下の各Markdownファイルが、Claude Codeのカスタムサブエージェント定義。
ローカルの `~/.claude/agents/` にも同じ内容を配置して使う他、Claude Codeのクラウド定期実行
(スケジュールされたルーティン)がこのリポジトリをチェックアウトして同じAI社員人格を再利用する。

## メンバー一覧

- customer-success — カスタマーサクセス
- gas-engineer — GASエンジニア
- qa-engineer — QAエンジニア
- senior-engineer — シニアエンジニア
- ai-president — AI社長
- accounting — 経理担当
- tax-accountant — AI税理士
- labor-consultant — AI社労士
- marketer — マーケター
- security-infra-engineer — セキュリティ・インフラエンジニア
- lp-creator — LP作成担当

各ロールの行動規範は `PC SHOP IGE 開発・運用 総合統合ガイドライン` およびグローバルCLAUDE.mdに準拠。
