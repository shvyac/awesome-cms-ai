# Awesome CMS & AI

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[日本語版はこちら / Japanese](README.ja.md)

A curated list of open-source **content management systems (CMS)** and the tools to drive them from **AI and MCP** — headless CMS, website CMS, Git-based / flat-file CMS, plus official and community MCP servers and MCP building blocks.

**Discovery list only** — not a ranking. Check each project's license (open source / open core / commercial). ⭐ badges show live GitHub star counts (via shields.io).

## Contents

- [Headless CMS](#headless-cms)
- [Website & publishing CMS](#website--publishing-cms)
- [Git-based & flat-file CMS](#git-based--flat-file-cms)
- [AI & MCP: official CMS integrations](#ai--mcp-official-cms-integrations)
- [AI & MCP: community MCP servers for CMS](#ai--mcp-community-mcp-servers-for-cms)
- [AI & MCP: building blocks](#ai--mcp-building-blocks)
- [Archived / deprecated](#archived--deprecated)
- [Related lists](#related-lists)
- [Contributing](#contributing)
- [shvyac's awesome lists](#shvyacs-awesome-lists)

---

## Headless CMS

Content via REST / GraphQL APIs; bring your own front end.

- [Strapi](https://strapi.io/) ![GitHub stars](https://img.shields.io/github/stars/strapi/strapi?style=flat&label=%E2%AD%90) - The leading open-source headless CMS (MIT), 100% JavaScript / TypeScript; official Strapi MCP server is now GA. ([GitHub](https://github.com/strapi/strapi))
- [Payload](https://payloadcms.com/) ![GitHub stars](https://img.shields.io/github/stars/payloadcms/payload?style=flat&label=%E2%AD%90) - Open-source, fullstack Next.js framework: TypeScript backend and admin panel, usable as a headless CMS. ([GitHub](https://github.com/payloadcms/payload))
- [Directus](https://directus.com/) ![GitHub stars](https://img.shields.io/github/stars/directus/directus?style=flat&label=%E2%AD%90) - Turns any SQL database into a headless CMS with instant REST / GraphQL APIs and an admin app. ([GitHub](https://github.com/directus/directus))
- [Keystone](https://keystonejs.com/) ![GitHub stars](https://img.shields.io/github/stars/keystonejs/keystone?style=flat&label=%E2%AD%90) - Headless CMS for Node.js built with GraphQL and React (by Thinkmill). ([GitHub](https://github.com/keystonejs/keystone))
- [Builder.io](https://www.builder.io/) ![GitHub stars](https://img.shields.io/github/stars/BuilderIO/builder?style=flat&label=%E2%AD%90) - Visual, drag-and-drop headless CMS and page builder for React, Vue, Svelte, Qwik, and more; now positioned around AI agents. ([GitHub](https://github.com/BuilderIO/builder))
- [Webiny](https://www.webiny.com/) ![GitHub stars](https://img.shields.io/github/stars/webiny/webiny-js?style=flat&label=%E2%AD%90) - Self-hosted serverless CMS on AWS (Lambda, DynamoDB, S3) with multi-tenancy and a built-in MCP server ("AI-programmable CMS"). ([GitHub](https://github.com/webiny/webiny-js))
- [Sanity Studio](https://www.sanity.io/) ![GitHub stars](https://img.shields.io/github/stars/sanity-io/sanity?style=flat&label=%E2%AD%90) - Open-source, React-based editing studio for the hosted Sanity Content Lake ("Content Operating System"). ([GitHub](https://github.com/sanity-io/sanity))
- [Squidex](https://squidex.io/) ![GitHub stars](https://img.shields.io/github/stars/Squidex/squidex?style=flat&label=%E2%AD%90) - Open-source (MIT) .NET headless CMS and content hub; supports MongoDB, PostgreSQL, MySQL, and SQL Server. ([GitHub](https://github.com/Squidex/squidex))

---

## Website & publishing CMS

Traditional CMSs that manage and render the site.

- [WordPress](https://wordpress.org/) ![GitHub stars](https://img.shields.io/github/stars/WordPress/WordPress?style=flat&label=%E2%AD%90) - The world's most-used CMS (GitHub repo is a read-only SVN mirror; contribute via wordpress-develop). ([GitHub](https://github.com/WordPress/WordPress))
- [Ghost](https://ghost.org/) ![GitHub stars](https://img.shields.io/github/stars/TryGhost/Ghost?style=flat&label=%E2%AD%90) - Open-source publishing platform for blogs, memberships, subscriptions, and newsletters (Ghost 6). ([GitHub](https://github.com/TryGhost/Ghost))
- [EmDash](https://emdashcms.com/) ![GitHub stars](https://img.shields.io/github/stars/emdash-cms/emdash?style=flat&label=%E2%AD%90) - Full-stack TypeScript CMS built on Astro, pitched as the "spiritual successor to WordPress"; started at Cloudflare, MIT-licensed, 1.0 released Sep 2026. ([GitHub](https://github.com/emdash-cms/emdash))
- [Wagtail](https://wagtail.org/) ![GitHub stars](https://img.shields.io/github/stars/wagtail/wagtail?style=flat&label=%E2%AD%90) - Django CMS focused on flexibility and editor experience (by Torchbox). ([GitHub](https://github.com/wagtail/wagtail))
- [Halo](https://www.halo.run/) ![GitHub stars](https://img.shields.io/github/stars/halo-dev/halo?style=flat&label=%E2%AD%90) - Java-based site builder for blogs, knowledge bases, company sites, and shops (popular in China). ([GitHub](https://github.com/halo-dev/halo))
- [django CMS](https://www.django-cms.org/) ![GitHub stars](https://img.shields.io/github/stars/django-cms/django-cms?style=flat&label=%E2%AD%90) - Enterprise-friendly, BSD-licensed CMS for Django. ([GitHub](https://github.com/django-cms/django-cms))
- [Drupal](https://new.drupal.org/) ![GitHub stars](https://img.shields.io/github/stars/drupal/drupal?style=flat&label=%E2%AD%90) - Enterprise / public-sector CMS; now ships Drupal CMS and Drupal AI (GitHub repo is a mirror). ([GitHub](https://github.com/drupal/drupal))
- [Joomla](https://www.joomla.org/) ![GitHub stars](https://img.shields.io/github/stars/joomla/joomla-cms?style=flat&label=%E2%AD%90) - Long-standing PHP CMS with built-in multilingual support (Joomla 6). ([GitHub](https://github.com/joomla/joomla-cms))
- [Orchard Core](https://orchardcore.net/) ![GitHub stars](https://img.shields.io/github/stars/OrchardCMS/OrchardCore?style=flat&label=%E2%AD%90) - Modular, multi-tenant CMS and application framework on ASP.NET Core (.NET Foundation). ([GitHub](https://github.com/OrchardCMS/OrchardCore))
- [Umbraco](https://umbraco.com/) ![GitHub stars](https://img.shields.io/github/stars/umbraco/Umbraco-CMS?style=flat&label=%E2%AD%90) - Open-source ASP.NET Core CMS, now pitched as "agent-ready". ([GitHub](https://github.com/umbraco/Umbraco-CMS))
- [October CMS](https://octobercms.com/) ![GitHub stars](https://img.shields.io/github/stars/octobercms/october?style=flat&label=%E2%AD%90) - Laravel-based CMS (commercial license since v3). ([GitHub](https://github.com/octobercms/october))
- [Statamic](https://statamic.com/) ![GitHub stars](https://img.shields.io/github/stars/statamic/cms?style=flat&label=%E2%AD%90) - Laravel CMS with flat-file or database storage; free Core, paid Pro. ([GitHub](https://github.com/statamic/cms))
- [ApostropheCMS](https://apostrophecms.com/) ![GitHub stars](https://img.shields.io/github/stars/apostrophecms/apostrophe?style=flat&label=%E2%AD%90) - Node.js CMS with in-context editing plus headless APIs (MIT core). ([GitHub](https://github.com/apostrophecms/apostrophe))
- [Craft CMS](https://craftcms.com/) ![GitHub stars](https://img.shields.io/github/stars/craftcms/cms?style=flat&label=%E2%AD%90) - Flexible content-modeling PHP CMS (commercial license; by Pixel & Tonic). ([GitHub](https://github.com/craftcms/cms))
- [Pimcore](https://pimcore.com/) ![GitHub stars](https://img.shields.io/github/stars/pimcore/pimcore?style=flat&label=%E2%AD%90) - Open-core data & experience platform (PIM, MDM, DAM, CMS, commerce). ([GitHub](https://github.com/pimcore/pimcore))
- [Typecho](https://typecho.org/) ![GitHub stars](https://img.shields.io/github/stars/typecho/typecho?style=flat&label=%E2%AD%90) - Lightweight PHP blogging platform. ([GitHub](https://github.com/typecho/typecho))

---

## Git-based & flat-file CMS

No database: content lives in Markdown / YAML files or your Git repo.

- [Decap CMS](https://decapcms.org/) ![GitHub stars](https://img.shields.io/github/stars/decaporg/decap-cms?style=flat&label=%E2%AD%90) - Git-based CMS for static site generators (formerly Netlify CMS); MIT, independent and EU-maintained. ([GitHub](https://github.com/decaporg/decap-cms))
- [Sveltia CMS](https://sveltiacms.app/) ![GitHub stars](https://img.shields.io/github/stars/sveltia/sveltia-cms?style=flat&label=%E2%AD%90) - Modern successor to Netlify / Decap CMS with better UX, i18n, and mobile support. ([GitHub](https://github.com/sveltia/sveltia-cms))
- [TinaCMS](https://tina.io/) ![GitHub stars](https://img.shields.io/github/stars/tinacms/tinacms?style=flat&label=%E2%AD%90) - Markdown-based headless CMS with visual editing; content stays in your GitHub repo. ([GitHub](https://github.com/tinacms/tinacms))
- [Grav](https://getgrav.org/) ![GitHub stars](https://img.shields.io/github/stars/getgrav/grav?style=flat&label=%E2%AD%90) - Fast flat-file CMS (PHP, Markdown, Twig); recent versions add a first-party REST API and MCP server. ([GitHub](https://github.com/getgrav/grav))
- [Kirby](https://getkirby.com/) ![GitHub stars](https://img.shields.io/github/stars/getkirby/kirby?style=flat&label=%E2%AD%90) - File-based PHP CMS with a polished panel (commercial license). ([GitHub](https://github.com/getkirby/kirby))
- [Bludit](https://www.bludit.com/) ![GitHub stars](https://img.shields.io/github/stars/bludit/bludit?style=flat&label=%E2%AD%90) - Simple, fast flat-file CMS using JSON storage. ([GitHub](https://github.com/bludit/bludit))

---

## AI & MCP: official CMS integrations

Official Model Context Protocol (MCP) servers and AI plugins from CMS vendors — let Claude and other agents read and edit content.

- [WordPress MCP Adapter](https://github.com/WordPress/mcp-adapter) ![GitHub stars](https://img.shields.io/github/stars/WordPress/mcp-adapter?style=flat&label=%E2%AD%90) - Official adapter exposing WordPress core, plugin, and theme abilities (Abilities API) to MCP clients.
- [WordPress AI](https://github.com/WordPress/ai) ![GitHub stars](https://img.shields.io/github/stars/WordPress/ai?style=flat&label=%E2%AD%90) - Official AI features and experiments plugin for WordPress.
- [Directus MCP](https://github.com/directus/mcp) ![GitHub stars](https://img.shields.io/github/stars/directus/mcp?style=flat&label=%E2%AD%90) - Official Directus content MCP server for working with your data in LLMs.
- [Contentful MCP Server](https://github.com/contentful/contentful-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/contentful/contentful-mcp-server?style=flat&label=%E2%AD%90) - Official MCP server for the Contentful Management API.
- [Webflow MCP Server](https://github.com/webflow/mcp-server) ![GitHub stars](https://img.shields.io/github/stars/webflow/mcp-server?style=flat&label=%E2%AD%90) - Official MCP server for the Webflow Data API.
- [Umbraco CMS MCP (Dev)](https://github.com/umbraco/Umbraco-CMS-MCP-Dev) ![GitHub stars](https://img.shields.io/github/stars/umbraco/Umbraco-CMS-MCP-Dev?style=flat&label=%E2%AD%90) - Official Umbraco MCP server for developers working with the back office.
- [Wix MCP](https://github.com/wix/wix-mcp) ![GitHub stars](https://img.shields.io/github/stars/wix/wix-mcp?style=flat&label=%E2%AD%90) - Official Wix MCP server.

---

## AI & MCP: community MCP servers for CMS

Third-party MCP servers — review code and permissions before connecting them to production content.

- [Ghost MCP](https://github.com/MFYDev/ghost-mcp) ![GitHub stars](https://img.shields.io/github/stars/MFYDev/ghost-mcp?style=flat&label=%E2%AD%90) - Manage a Ghost blog (posts, members, newsletters) from Claude and other LLM clients.
- [Payload CMS MCP](https://github.com/disruption-hub/payloadcmsmcp) ![GitHub stars](https://img.shields.io/github/stars/disruption-hub/payloadcmsmcp?style=flat&label=%E2%AD%90) - MCP server for Payload CMS development and content.
- [MCP WordPress](https://github.com/docdyhr/mcp-wordpress) ![GitHub stars](https://img.shields.io/github/stars/docdyhr/mcp-wordpress?style=flat&label=%E2%AD%90) - MCP server for managing WordPress sites via the REST API.
- [Strapi MCP Server](https://github.com/misterboe/strapi-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/misterboe/strapi-mcp-server?style=flat&label=%E2%AD%90) - Community MCP server for Strapi content.
- [Kirby MCP](https://github.com/bnomei/kirby-mcp) ![GitHub stars](https://img.shields.io/github/stars/bnomei/kirby-mcp?style=flat&label=%E2%AD%90) - CLI-first MCP server for Kirby CMS projects (blueprints, templates, runtime, knowledge base).

---

## AI & MCP: building blocks

Specs, SDKs, registries, and directories for building or finding MCP servers.

- [Model Context Protocol](https://modelcontextprotocol.io/) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=flat&label=%E2%AD%90) - Official spec and docs; the linked repo holds the reference server implementations. ([GitHub](https://github.com/modelcontextprotocol/servers))
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/python-sdk?style=flat&label=%E2%AD%90) - Official Python SDK for MCP servers and clients.
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/typescript-sdk?style=flat&label=%E2%AD%90) - Official TypeScript SDK for MCP servers and clients.
- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/inspector?style=flat&label=%E2%AD%90) - Visual testing and debugging tool for MCP servers.
- [MCP Registry](https://github.com/modelcontextprotocol/registry) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/registry?style=flat&label=%E2%AD%90) - Community-driven registry service for MCP servers.
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) ![GitHub stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers?style=flat&label=%E2%AD%90) - The largest curated list of MCP servers.

---

## Archived / deprecated

Kept for reference; no longer maintained or superseded.

- [WordPress MCP (Automattic)](https://github.com/Automattic/wordpress-mcp) ![GitHub stars](https://img.shields.io/github/stars/Automattic/wordpress-mcp?style=flat&label=%E2%AD%90) - Archived; superseded by WordPress MCP Adapter.
- [Sanity MCP Server](https://github.com/sanity-io/sanity-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/sanity-io/sanity-mcp-server?style=flat&label=%E2%AD%90) - Archived; Sanity now offers a hosted remote MCP server instead.
- [Storyblok MCP Server](https://github.com/storyblok/mcp-server) ![GitHub stars](https://img.shields.io/github/stars/storyblok/mcp-server?style=flat&label=%E2%AD%90) - Archived innovation-phase Management MCP server.

---

## Related lists

- [postlight/awesome-cms](https://github.com/postlight/awesome-cms) ![GitHub stars](https://img.shields.io/github/stars/postlight/awesome-cms?style=flat&label=%E2%AD%90) - Open and closed source CMSs.
- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) ![GitHub stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers?style=flat&label=%E2%AD%90) - MCP servers.
- [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) ![GitHub stars](https://img.shields.io/github/stars/awesome-selfhosted/awesome-selfhosted?style=flat&label=%E2%AD%90) - Self-hosted software in general.
- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) ![GitHub stars](https://img.shields.io/github/stars/sindresorhus/awesome?style=flat&label=%E2%AD%90) - The Awesome meta-list.

---

## Contributing

Contributions welcome — open a pull request to add a tool, fix a broken link, or suggest a category.

Prefer **durable official / project URLs**, short blurbs, and actively maintained projects. Add a ⭐ star badge for GitHub projects, and note commercial licenses and archived projects. Update both `README.md` and `README.ja.md` when you can.

---

## shvyac's awesome lists

All curated lists maintained by [shvyac](https://github.com/shvyac):

- [awesome-hamradio](https://github.com/shvyac/awesome-hamradio) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hamradio?style=flat&label=%E2%AD%90)
- [awesome-cad-cae](https://github.com/shvyac/awesome-cad-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cad-cae?style=flat&label=%E2%AD%90)
- [awesome-map-gis](https://github.com/shvyac/awesome-map-gis) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-map-gis?style=flat&label=%E2%AD%90)
- [awesome-ballroom-dance](https://github.com/shvyac/awesome-ballroom-dance) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ballroom-dance?style=flat&label=%E2%AD%90)
- [awesome-ghost-artists](https://github.com/shvyac/awesome-ghost-artists) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ghost-artists?style=flat&label=%E2%AD%90)
- [awesome-audio-softwares](https://github.com/shvyac/awesome-audio-softwares) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-audio-softwares?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-m5stack-arduino](https://github.com/shvyac/awesome-m5stack-arduino) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-m5stack-arduino?style=flat&label=%E2%AD%90)
- [awesome-AI-Powered-Executive-Dashboards](https://github.com/shvyac/awesome-AI-Powered-Executive-Dashboards) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-AI-Powered-Executive-Dashboards?style=flat&label=%E2%AD%90)
- [awesome-ai-tool-for-mechanical-engineering](https://github.com/shvyac/awesome-ai-tool-for-mechanical-engineering) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ai-tool-for-mechanical-engineering?style=flat&label=%E2%AD%90)
- [awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-dashboards-visualization](https://github.com/shvyac/awesome-dashboards-visualization) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-dashboards-visualization?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-cms-ai](https://github.com/shvyac/awesome-cms-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cms-ai?style=flat&label=%E2%AD%90)
