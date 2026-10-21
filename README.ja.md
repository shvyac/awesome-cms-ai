# Awesome CMS & AI（日本語）

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English README](README.md)

オープンソースの **CMS（コンテンツ管理システム）** と、それを **AI・MCP** から操作するためのツールを集めたキュレーションリスト。ヘッドレス CMS、Web サイト向け CMS、Git ベース／フラットファイル CMS、そして CMS 公式・コミュニティ製の MCP サーバーと MCP 基盤ツールを紹介します。

**発見用のリストです**（ランキングではありません）。ライセンス（オープンソース／オープンコア／商用）は各プロジェクトで確認してください。⭐ バッジは GitHub のスター数をリアルタイム表示します(shields.io)。

## 目次

- [ヘッドレス CMS](#ヘッドレス-cms)
- [Web サイト・パブリッシング向け CMS](#web-サイトパブリッシング向け-cms)
- [Git ベース・フラットファイル CMS](#git-ベースフラットファイル-cms)
- [AI・MCP：CMS 公式の連携](#aimcpcms-公式の連携)
- [AI・MCP：コミュニティ製の CMS 用 MCP サーバー](#aimcpコミュニティ製の-cms-用-mcp-サーバー)
- [AI・MCP：基盤ツール](#aimcp基盤ツール)
- [アーカイブ・非推奨](#アーカイブ非推奨)
- [関連リスト](#関連リスト)
- [コントリビュート](#コントリビュート)
- [shvyac の awesome リスト](#shvyac-の-awesome-リスト)

---

## ヘッドレス CMS

REST／GraphQL API でコンテンツを配信し、フロントエンドは自由に選べる CMS。

- [Strapi](https://strapi.io/) ![GitHub stars](https://img.shields.io/github/stars/strapi/strapi?style=flat&label=%E2%AD%90) - 代表的なオープンソースのヘッドレス CMS（MIT）。JavaScript／TypeScript 製。公式の Strapi MCP サーバーが正式リリース（GA）済み。 ([GitHub](https://github.com/strapi/strapi))
- [Payload](https://payloadcms.com/) ![GitHub stars](https://img.shields.io/github/stars/payloadcms/payload?style=flat&label=%E2%AD%90) - オープンソースのフルスタック Next.js フレームワーク。TypeScript のバックエンドと管理画面を備え、ヘッドレス CMS として使える。 ([GitHub](https://github.com/payloadcms/payload))
- [Directus](https://directus.com/) ![GitHub stars](https://img.shields.io/github/stars/directus/directus?style=flat&label=%E2%AD%90) - 既存の SQL データベースをそのままヘッドレス CMS にし、REST／GraphQL API と管理画面を提供。 ([GitHub](https://github.com/directus/directus))
- [Keystone](https://keystonejs.com/) ![GitHub stars](https://img.shields.io/github/stars/keystonejs/keystone?style=flat&label=%E2%AD%90) - GraphQL と React で作られた Node.js 向けヘッドレス CMS（Thinkmill 製）。 ([GitHub](https://github.com/keystonejs/keystone))
- [Builder.io](https://www.builder.io/) ![GitHub stars](https://img.shields.io/github/stars/BuilderIO/builder?style=flat&label=%E2%AD%90) - React、Vue、Svelte、Qwik などに対応した、ドラッグ＆ドロップのビジュアル型ヘッドレス CMS・ページビルダー。現在は AI エージェントを前面に打ち出している。 ([GitHub](https://github.com/BuilderIO/builder))
- [Webiny](https://www.webiny.com/) ![GitHub stars](https://img.shields.io/github/stars/webiny/webiny-js?style=flat&label=%E2%AD%90) - AWS 上で動くセルフホスト型サーバーレス CMS（Lambda、DynamoDB、S3）。マルチテナント対応で MCP サーバーを内蔵（「AI でプログラムできる CMS」）。 ([GitHub](https://github.com/webiny/webiny-js))
- [Sanity Studio](https://www.sanity.io/) ![GitHub stars](https://img.shields.io/github/stars/sanity-io/sanity?style=flat&label=%E2%AD%90) - クラウド型の Sanity Content Lake 向けの、React ベースでオープンソースの編集画面（Sanity は「Content Operating System」を標榜）。 ([GitHub](https://github.com/sanity-io/sanity))
- [Squidex](https://squidex.io/) ![GitHub stars](https://img.shields.io/github/stars/Squidex/squidex?style=flat&label=%E2%AD%90) - オープンソース（MIT）の .NET 製ヘッドレス CMS・コンテンツハブ。MongoDB、PostgreSQL、MySQL、SQL Server に対応。 ([GitHub](https://github.com/Squidex/squidex))

---

## Web サイト・パブリッシング向け CMS

サイトの管理と表示を一体で行う従来型の CMS。

- [WordPress](https://wordpress.org/) ![GitHub stars](https://img.shields.io/github/stars/WordPress/WordPress?style=flat&label=%E2%AD%90) - 世界で最も使われている CMS（GitHub のリポジトリは SVN の読み取り専用ミラー。開発参加は wordpress-develop から）。 ([GitHub](https://github.com/WordPress/WordPress))
- [Ghost](https://ghost.org/) ![GitHub stars](https://img.shields.io/github/stars/TryGhost/Ghost?style=flat&label=%E2%AD%90) - ブログ、会員制、サブスクリプション、ニュースレター向けのオープンソース出版プラットフォーム（Ghost 6）。 ([GitHub](https://github.com/TryGhost/Ghost))
- [EmDash](https://emdashcms.com/) ![GitHub stars](https://img.shields.io/github/stars/emdash-cms/emdash?style=flat&label=%E2%AD%90) - Astro ベースのフルスタック TypeScript CMS。「WordPress の精神的後継」を掲げる。Cloudflare 発、MIT ライセンス。2026 年 9 月に 1.0 をリリース。 ([GitHub](https://github.com/emdash-cms/emdash))
- [Wagtail](https://wagtail.org/) ![GitHub stars](https://img.shields.io/github/stars/wagtail/wagtail?style=flat&label=%E2%AD%90) - 柔軟性と編集体験を重視した Django ベースの CMS（Torchbox 製）。 ([GitHub](https://github.com/wagtail/wagtail))
- [Halo](https://www.halo.run/) ![GitHub stars](https://img.shields.io/github/stars/halo-dev/halo?style=flat&label=%E2%AD%90) - ブログ、ナレッジベース、企業サイト、EC サイトまで作れる Java 製のサイト構築ツール（中国で人気）。 ([GitHub](https://github.com/halo-dev/halo))
- [django CMS](https://www.django-cms.org/) ![GitHub stars](https://img.shields.io/github/stars/django-cms/django-cms?style=flat&label=%E2%AD%90) - エンタープライズでも使いやすい、BSD ライセンスの Django 用 CMS。 ([GitHub](https://github.com/django-cms/django-cms))
- [Drupal](https://new.drupal.org/) ![GitHub stars](https://img.shields.io/github/stars/drupal/drupal?style=flat&label=%E2%AD%90) - 大規模サイトや公共機関向けの CMS。現在は Drupal CMS と Drupal AI を提供（GitHub のリポジトリはミラー）。 ([GitHub](https://github.com/drupal/drupal))
- [Joomla](https://www.joomla.org/) ![GitHub stars](https://img.shields.io/github/stars/joomla/joomla-cms?style=flat&label=%E2%AD%90) - 多言語対応を標準で備えた老舗の PHP 製 CMS（Joomla 6）。 ([GitHub](https://github.com/joomla/joomla-cms))
- [Orchard Core](https://orchardcore.net/) ![GitHub stars](https://img.shields.io/github/stars/OrchardCMS/OrchardCore?style=flat&label=%E2%AD%90) - ASP.NET Core 上のモジュール式・マルチテナント対応 CMS 兼アプリケーションフレームワーク（.NET Foundation）。 ([GitHub](https://github.com/OrchardCMS/OrchardCore))
- [Umbraco](https://umbraco.com/) ![GitHub stars](https://img.shields.io/github/stars/umbraco/Umbraco-CMS?style=flat&label=%E2%AD%90) - ASP.NET Core 製のオープンソース CMS。現在は「AI エージェント対応」を打ち出している。 ([GitHub](https://github.com/umbraco/Umbraco-CMS))
- [October CMS](https://octobercms.com/) ![GitHub stars](https://img.shields.io/github/stars/octobercms/october?style=flat&label=%E2%AD%90) - Laravel ベースの CMS（v3 から商用ライセンス）。 ([GitHub](https://github.com/octobercms/october))
- [Statamic](https://statamic.com/) ![GitHub stars](https://img.shields.io/github/stars/statamic/cms?style=flat&label=%E2%AD%90) - フラットファイルとデータベースのどちらでも保存できる Laravel 製 CMS。Core は無料、Pro は有料。 ([GitHub](https://github.com/statamic/cms))
- [ApostropheCMS](https://apostrophecms.com/) ![GitHub stars](https://img.shields.io/github/stars/apostrophecms/apostrophe?style=flat&label=%E2%AD%90) - ページ上で直接編集でき、ヘッドレス API も備えた Node.js 製 CMS（コア部分は MIT）。 ([GitHub](https://github.com/apostrophecms/apostrophe))
- [Craft CMS](https://craftcms.com/) ![GitHub stars](https://img.shields.io/github/stars/craftcms/cms?style=flat&label=%E2%AD%90) - コンテンツ構造を柔軟に設計できる PHP 製 CMS（商用ライセンス、Pixel & Tonic 製）。 ([GitHub](https://github.com/craftcms/cms))
- [Pimcore](https://pimcore.com/) ![GitHub stars](https://img.shields.io/github/stars/pimcore/pimcore?style=flat&label=%E2%AD%90) - オープンコアのデータ・体験管理基盤（PIM、MDM、DAM、CMS、EC）。 ([GitHub](https://github.com/pimcore/pimcore))
- [Typecho](https://typecho.org/) ![GitHub stars](https://img.shields.io/github/stars/typecho/typecho?style=flat&label=%E2%AD%90) - 軽量な PHP 製ブログ。 ([GitHub](https://github.com/typecho/typecho))

---

## Git ベース・フラットファイル CMS

データベース不要。コンテンツは Markdown／YAML ファイルや Git リポジトリに保存。

- [Decap CMS](https://decapcms.org/) ![GitHub stars](https://img.shields.io/github/stars/decaporg/decap-cms?style=flat&label=%E2%AD%90) - 静的サイトジェネレーター向けの Git ベース CMS（旧 Netlify CMS）。MIT ライセンスで、独立した EU のチームが保守。 ([GitHub](https://github.com/decaporg/decap-cms))
- [Sveltia CMS](https://sveltiacms.app/) ![GitHub stars](https://img.shields.io/github/stars/sveltia/sveltia-cms?style=flat&label=%E2%AD%90) - Netlify／Decap CMS のモダンな後継。UX、多言語対応、モバイル対応を改善。 ([GitHub](https://github.com/sveltia/sveltia-cms))
- [TinaCMS](https://tina.io/) ![GitHub stars](https://img.shields.io/github/stars/tinacms/tinacms?style=flat&label=%E2%AD%90) - ビジュアル編集ができる Markdown ベースのヘッドレス CMS。コンテンツは自分の GitHub リポジトリに保存される。 ([GitHub](https://github.com/tinacms/tinacms))
- [Grav](https://getgrav.org/) ![GitHub stars](https://img.shields.io/github/stars/getgrav/grav?style=flat&label=%E2%AD%90) - 高速なフラットファイル CMS（PHP、Markdown、Twig）。最近のバージョンで公式の REST API と MCP サーバーを追加。 ([GitHub](https://github.com/getgrav/grav))
- [Kirby](https://getkirby.com/) ![GitHub stars](https://img.shields.io/github/stars/getkirby/kirby?style=flat&label=%E2%AD%90) - 洗練された管理画面を持つファイルベースの PHP 製 CMS（商用ライセンス）。 ([GitHub](https://github.com/getkirby/kirby))
- [Bludit](https://www.bludit.com/) ![GitHub stars](https://img.shields.io/github/stars/bludit/bludit?style=flat&label=%E2%AD%90) - JSON で保存する、シンプルで高速なフラットファイル CMS。 ([GitHub](https://github.com/bludit/bludit))

---

## AI・MCP：CMS 公式の連携

CMS ベンダー公式の MCP（Model Context Protocol）サーバーと AI プラグイン。Claude などのエージェントからコンテンツを読み書きできる。

- [WordPress MCP Adapter](https://github.com/WordPress/mcp-adapter) ![GitHub stars](https://img.shields.io/github/stars/WordPress/mcp-adapter?style=flat&label=%E2%AD%90) - WordPress 公式。コア・プラグイン・テーマの機能（Abilities API）を MCP クライアントから呼び出せるようにするアダプター。
- [WordPress AI](https://github.com/WordPress/ai) ![GitHub stars](https://img.shields.io/github/stars/WordPress/ai?style=flat&label=%E2%AD%90) - WordPress 公式の AI 機能・実験用プラグイン。
- [Directus MCP](https://github.com/directus/mcp) ![GitHub stars](https://img.shields.io/github/stars/directus/mcp?style=flat&label=%E2%AD%90) - Directus 公式のコンテンツ MCP サーバー。LLM からデータを扱える。
- [Contentful MCP Server](https://github.com/contentful/contentful-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/contentful/contentful-mcp-server?style=flat&label=%E2%AD%90) - Contentful 公式。Management API 用の MCP サーバー。
- [Webflow MCP Server](https://github.com/webflow/mcp-server) ![GitHub stars](https://img.shields.io/github/stars/webflow/mcp-server?style=flat&label=%E2%AD%90) - Webflow 公式。Data API 用の MCP サーバー。
- [Umbraco CMS MCP (Dev)](https://github.com/umbraco/Umbraco-CMS-MCP-Dev) ![GitHub stars](https://img.shields.io/github/stars/umbraco/Umbraco-CMS-MCP-Dev?style=flat&label=%E2%AD%90) - Umbraco 公式の開発者向け MCP サーバー（バックオフィス操作用）。
- [Wix MCP](https://github.com/wix/wix-mcp) ![GitHub stars](https://img.shields.io/github/stars/wix/wix-mcp?style=flat&label=%E2%AD%90) - Wix 公式の MCP サーバー。

---

## AI・MCP：コミュニティ製の CMS 用 MCP サーバー

サードパーティ製の MCP サーバー。本番コンテンツに接続する前にコードと権限を確認すること。

- [Ghost MCP](https://github.com/MFYDev/ghost-mcp) ![GitHub stars](https://img.shields.io/github/stars/MFYDev/ghost-mcp?style=flat&label=%E2%AD%90) - Claude などの LLM クライアントから Ghost ブログ（記事、会員、ニュースレター）を管理。
- [Payload CMS MCP](https://github.com/disruption-hub/payloadcmsmcp) ![GitHub stars](https://img.shields.io/github/stars/disruption-hub/payloadcmsmcp?style=flat&label=%E2%AD%90) - Payload CMS の開発とコンテンツ操作用の MCP サーバー。
- [MCP WordPress](https://github.com/docdyhr/mcp-wordpress) ![GitHub stars](https://img.shields.io/github/stars/docdyhr/mcp-wordpress?style=flat&label=%E2%AD%90) - REST API 経由で WordPress サイトを管理する MCP サーバー。
- [Strapi MCP Server](https://github.com/misterboe/strapi-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/misterboe/strapi-mcp-server?style=flat&label=%E2%AD%90) - Strapi のコンテンツを扱うコミュニティ製 MCP サーバー。
- [Kirby MCP](https://github.com/bnomei/kirby-mcp) ![GitHub stars](https://img.shields.io/github/stars/bnomei/kirby-mcp?style=flat&label=%E2%AD%90) - Kirby CMS プロジェクト向けの CLI 中心の MCP サーバー（ブループリント、テンプレート、実行環境、ナレッジベース）。

---

## AI・MCP：基盤ツール

MCP サーバーを作ったり探したりするための仕様、SDK、レジストリ、一覧。

- [Model Context Protocol](https://modelcontextprotocol.io/) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=flat&label=%E2%AD%90) - 公式の仕様とドキュメント。リンク先のリポジトリにはリファレンス実装のサーバー群がある。 ([GitHub](https://github.com/modelcontextprotocol/servers))
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/python-sdk?style=flat&label=%E2%AD%90) - MCP サーバー・クライアント用の公式 Python SDK。
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/typescript-sdk?style=flat&label=%E2%AD%90) - MCP サーバー・クライアント用の公式 TypeScript SDK。
- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/inspector?style=flat&label=%E2%AD%90) - MCP サーバーの動作確認・デバッグ用ツール。
- [MCP Registry](https://github.com/modelcontextprotocol/registry) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/registry?style=flat&label=%E2%AD%90) - コミュニティ主導の MCP サーバーレジストリ。
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) ![GitHub stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers?style=flat&label=%E2%AD%90) - 最大級の MCP サーバー一覧。

---

## アーカイブ・非推奨

参考として残しているが、メンテナンスは終了または後継に移行。

- [WordPress MCP (Automattic)](https://github.com/Automattic/wordpress-mcp) ![GitHub stars](https://img.shields.io/github/stars/Automattic/wordpress-mcp?style=flat&label=%E2%AD%90) - アーカイブ済み。WordPress MCP Adapter に置き換え。
- [Sanity MCP Server](https://github.com/sanity-io/sanity-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/sanity-io/sanity-mcp-server?style=flat&label=%E2%AD%90) - アーカイブ済み。現在はクラウドのリモート MCP サーバーが提供されている。
- [Storyblok MCP Server](https://github.com/storyblok/mcp-server) ![GitHub stars](https://img.shields.io/github/stars/storyblok/mcp-server?style=flat&label=%E2%AD%90) - アーカイブ済み（試験段階だった Management 用 MCP サーバー）。

---

## 関連リスト

- [postlight/awesome-cms](https://github.com/postlight/awesome-cms) ![GitHub stars](https://img.shields.io/github/stars/postlight/awesome-cms?style=flat&label=%E2%AD%90) - オープンソースと商用の CMS 一覧。
- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) ![GitHub stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers?style=flat&label=%E2%AD%90) - MCP サーバー。
- [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) ![GitHub stars](https://img.shields.io/github/stars/awesome-selfhosted/awesome-selfhosted?style=flat&label=%E2%AD%90) - セルフホスト可能なソフトウェア全般。
- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) ![GitHub stars](https://img.shields.io/github/stars/sindresorhus/awesome?style=flat&label=%E2%AD%90) - Awesome リストのメタリスト。

---

## コントリビュート

追加・リンク切れ修正・カテゴリ提案などのプルリクエストを歓迎します。

**公式／プロジェクトの恒久的な URL**、短い説明、活発にメンテナンスされているプロジェクトを優先してください。GitHub プロジェクトには ⭐ バッジを付け、商用ライセンスやアーカイブ済みのものは注記してください。可能なら `README.md` と `README.ja.md` の両方を更新してください。

---

## shvyac の awesome リスト

[shvyac](https://github.com/shvyac) が管理しているキュレーションリストの一覧:

- [awesome-AI-Powered-Executive-Dashboards](https://github.com/shvyac/awesome-AI-Powered-Executive-Dashboards) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-AI-Powered-Executive-Dashboards?style=flat&label=%E2%AD%90)
- [awesome-ai-tool-for-mechanical-engineering](https://github.com/shvyac/awesome-ai-tool-for-mechanical-engineering) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ai-tool-for-mechanical-engineering?style=flat&label=%E2%AD%90)
- [awesome-audio-softwares](https://github.com/shvyac/awesome-audio-softwares) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-audio-softwares?style=flat&label=%E2%AD%90)
- [awesome-azure-ai-dynamics365-security](https://github.com/shvyac/awesome-azure-ai-dynamics365-security) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-azure-ai-dynamics365-security?style=flat&label=%E2%AD%90)
- [awesome-ballroom-dance](https://github.com/shvyac/awesome-ballroom-dance) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ballroom-dance?style=flat&label=%E2%AD%90)
- [awesome-cad-cae](https://github.com/shvyac/awesome-cad-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cad-cae?style=flat&label=%E2%AD%90)
- [awesome-cms-ai](https://github.com/shvyac/awesome-cms-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cms-ai?style=flat&label=%E2%AD%90)
- [awesome-dashboards-visualization](https://github.com/shvyac/awesome-dashboards-visualization) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-dashboards-visualization?style=flat&label=%E2%AD%90)
- [awesome-ghost-artists](https://github.com/shvyac/awesome-ghost-artists) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ghost-artists?style=flat&label=%E2%AD%90)
- [awesome-hamradio](https://github.com/shvyac/awesome-hamradio) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hamradio?style=flat&label=%E2%AD%90)
- [awesome-hpc](https://github.com/shvyac/awesome-hpc) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hpc?style=flat&label=%E2%AD%90)
- [awesome-iso27001-isms-tools](https://github.com/shvyac/awesome-iso27001-isms-tools) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-iso27001-isms-tools?style=flat&label=%E2%AD%90)
- [awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90)
- [awesome-m5stack-arduino](https://github.com/shvyac/awesome-m5stack-arduino) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-m5stack-arduino?style=flat&label=%E2%AD%90)
- [awesome-map-gis](https://github.com/shvyac/awesome-map-gis) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-map-gis?style=flat&label=%E2%AD%90)
- [awesome-meshless-cae](https://github.com/shvyac/awesome-meshless-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-meshless-cae?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-requirements-system-ai](https://github.com/shvyac/awesome-requirements-system-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-requirements-system-ai?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
