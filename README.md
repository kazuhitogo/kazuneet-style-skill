# kazuneet-style

自分の技術記事の構成と文体を、記事執筆用の Kiro スキルにまとめたものです。

- 分析対象: 公開済みの技術記事 56 本
- 内容: 文体ルール、記事構成、種類別テンプレート、チェックリスト

## 構成

```
.kiro/skills/kazuneet-style/
├── SKILL.md                  # 文体ルールと手順
└── references/
    ├── templates.md          # 記事の種類別テンプレート
    └── examples.md           # 短い実例
```

## 使い方

ワークスペースで使うときは、`.kiro/skills/kazuneet-style/` をコピーします。全ワークスペースで使う場合は `~/.kiro/skills/` に置きます。

```bash
git clone https://github.com/kazuhitogo/kazuneet-style-skill.git
cp -R kazuneet-style-skill/.kiro/skills/kazuneet-style ~/.kiro/skills/
```

その後、「kazuneet 風で、〜について記事を書いて」と依頼します。コードや実行結果などの検証内容は、利用者が用意してください。スキルは、検証していない結果や数値を書かないよう指示しています。

## ライセンス

MIT
