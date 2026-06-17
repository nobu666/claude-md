# claude-md

Claude Code 用のグローバル `CLAUDE.md` テンプレート。

[andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) の CLAUDE.md をベースに、以下の改善を加えたもの。

## オリジナルからの変更点

- 日本語化（コード・変数名は英語を維持）
- 「大前提」セクションの追加（応答言語、簡潔さ）
- 複雑なタスクでの計画提示ルールを追加
- Git 規約の追加（Conventional Commits、自動コミット/push の禁止）
- ファイル削除時のワイルドカード禁止ルールを追加
- AI が解釈しやすい箇条書き主体の構成に変更

## 使い方

`CLAUDE.md` をホームディレクトリまたはプロジェクトルートに配置する。

```bash
# グローバルに適用（全プロジェクト共通）
cp CLAUDE.md ~/CLAUDE.md

# プロジェクト固有の設定がある場合は末尾に追記するか、
# プロジェクトルートに別の CLAUDE.md を置く
```

プロジェクト固有の設定（スコープ、フック、ビルドコマンド等）は各プロジェクトの `CLAUDE.md` に分離することを推奨する。

## ライセンス

MIT License — 詳細は [LICENSE](LICENSE) を参照。

## クレジット

- [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) — オリジナルのコーディングガイドライン
