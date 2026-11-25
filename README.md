# kazuneet-style

呉和仁 (Kazuhito Go, [@kazuneet](https://twitter.com/kazuneet)) の公開技術記事の構成と文体を分析し、記事執筆用のスキルにまとめたものです。

- 分析対象: Qiita 40 本、Zenn 4 本、AWS builders.flash 12 本 (いずれも公開記事)
- 内容: 文体ルール、記事構成、媒体別テンプレート、チェックリスト
- 元記事の本文は、このリポジトリに含めていません。

本人とは無関係の非公式な有志の分析です。文体の模倣を目的としており、本人の記事の転載ではありません。

## 構成

```
.kiro/skills/kazuneet-style/
├── SKILL.md                  # 文体ルールと手順
└── references/
    ├── templates.md          # 媒体別テンプレート
    └── examples.md           # 短い実例
```

## 使い方

Kiro のワークスペースでは、このリポジトリの `.kiro/skills/kazuneet-style/` をコピーします。全ワークスペースで使う場合は `~/.kiro/skills/` に置きます。

```bash
git clone https://github.com/kazuhitogo/kazuneet-style-skill.git
cp -R kazuneet-style-skill/.kiro/skills/kazuneet-style ~/.kiro/skills/
```

その後、「kazuneet 風で、〜について記事を書いて」と依頼します。コードや実行結果などの検証内容は、利用者が用意してください。

## 注意

- スキルは、検証していない結果や数値を書かないよう指示しています。
- 本人の名前を使った記事の公開では、本人が書いたと誤認される書き方を避けてください。

## ライセンス

MIT。ただし `references/examples.md` の引用は、呉和仁本人の記事からの短い抜粋で、各記事の権利は本人に帰属します。
