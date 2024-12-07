---
title: "1D 歯科医療プラットフォームの技術スタック及び選定理由"
emoji: "🦷"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["技術選定"]
published: false
---

こんににちわ。ワンディー株式会社のSoftware Engineerをしております上村です。

歯科医療プラットフォーム[1D](https://oned.jp/)は動画で歯科医療技術が学べるサブスクリプションサービスです。

Laravelで構築されたレガシーコードをGoにリプレイスしてきて、ようやく開発チームとしての技術基盤も固まってきたのと、採用活動の一環として弊社の技術スタックとその選定背景をご紹介したいと思います。

# 主な技術スタック

- バックエンド
  - Go
  - AWS
  - GraphQL
  - gqlgen
  - .ent
- フロントエンド
  - React / TypeScript
  - Next.js
  - Apollo Client