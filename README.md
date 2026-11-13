# Niko Lee

Singapore. I build data-collection and survey-operations platforms in Laravel, and the
integrations around them: survey and fieldwork platforms (Nfield, Qualtrics), WeChat, OpenAI, and
Singapore's public APIs.

My production work belongs to my employers and is not public. What is here I maintain myself:

- **[laravel-admin](https://github.com/nikoleesg/laravel-admin)**: a maintained fork of
  `z-song/laravel-admin`, which has had no upstream maintenance since 2023. v3.0 targets PHP 8.3+
  and Laravel 11/12, with CI across PHP 8.3/8.4 × Laravel 11/12 and security fixes. My production
  platforms run on it.
- **[survey](https://github.com/nikoleesg/survey)**: a Laravel package that loads fixed-width survey
  exports (closed answers, verbatims, paradata) and queries them back as typed answers.
- **[laravel-helpers](https://github.com/nikoleesg/laravel-helpers)**: Laravel building blocks,
  several Singapore-specific: a OneMap client, date scopes, base classes for durable workflows, and
  Singapore Faker providers.
- **[onemap-mcp](https://github.com/nikoleesg/onemap-mcp)** and
  **[lta-mcp](https://github.com/nikoleesg/lta-mcp)**: MCP servers on Cloudflare Workers that wrap
  Singapore's OneMap and LTA DataMall APIs for AI agents.
- **[dba-observer](https://github.com/nikoleesg/dba-observer)**: a read-only DBA MCP server for MySQL,
  PostgreSQL and Redis. It runs fixed, reviewed queries and never runs caller-supplied SQL.
