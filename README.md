# Awesome MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> A curated list of awesome Model Context Protocol (MCP) servers, clients, SDKs, and resources.

The [Model Context Protocol](https://modelcontextprotocol.io/) (MCP) is an open standard by Anthropic that enables AI assistants to connect to external data sources, tools, and services through a unified interface. Think of it as USB-C for AI — one protocol to connect them all.

## Contents

- [Official Resources](#official-resources)
- [SDKs & Libraries](#sdks--libraries)
- [Server Frameworks](#server-frameworks)
- [Database Servers](#database-servers)
- [Cloud & Infrastructure](#cloud--infrastructure)
- [Developer Tools](#developer-tools)
- [Communication](#communication)
- [Search & Web](#search--web)
- [AI & LLM](#ai--llm)
- [Memory & Knowledge](#memory--knowledge)
- [Data & Analytics](#data--analytics)
- [Productivity](#productivity)
- [Media & Files](#media--files)
- [Design & 3D](#design--3d)
- [Finance & Payments](#finance--payments)
- [Monitoring & Observability](#monitoring--observability)
- [Smart Home & IoT](#smart-home--iot)
- [Clients & Hosts](#clients--hosts)
- [Gateways & Registries](#gateways--registries)
- [Testing & Debugging](#testing--debugging)
- [Tutorials & Guides](#tutorials--guides)
- [Community](#community)
- [Support](#support)

## Official Resources

- [MCP Specification](https://modelcontextprotocol.io/specification/latest) - The official protocol specification.
- [MCP Documentation](https://modelcontextprotocol.io/introduction) - Official getting started guide and documentation.
- [MCP GitHub Organization](https://github.com/modelcontextprotocol) - Official repos including SDKs, servers, and spec.
- [MCP Servers Repository](https://github.com/modelcontextprotocol/servers) - Official reference server implementations by Anthropic.
- [Introducing MCP (Blog)](https://www.anthropic.com/news/model-context-protocol) - Anthropic's announcement blog post.

## SDKs & Libraries

- [C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) - .NET SDK for building MCP servers and clients.
- [Go SDK (mark3labs)](https://github.com/mark3labs/mcp-go) - Community Go SDK for the Model Context Protocol.
- [Java SDK (quarkiverse)](https://github.com/quarkiverse/quarkus-mcp-server) - Quarkus extension for building MCP servers in Java.
- [Kotlin SDK](https://github.com/modelcontextprotocol/kotlin-sdk) - Official SDK for building MCP servers and clients in Kotlin on the JVM.
- [Python SDK](https://github.com/modelcontextprotocol/python-sdk) - Official Python SDK for building MCP servers and clients.
- [Ruby SDK](https://github.com/modelcontextprotocol/ruby-sdk) - Official Ruby SDK for building MCP servers and clients.
- [Rust SDK](https://github.com/modelcontextprotocol/rust-sdk) - Official SDK for building high-performance MCP servers in Rust.
- [Swift SDK](https://github.com/modelcontextprotocol/swift-sdk) - Official SDK for building MCP servers on Apple platforms.
- [TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - Official TypeScript/Node.js SDK for building MCP servers and clients.

## Server Frameworks

- [FastMCP](https://github.com/jlowin/fastmcp) - High-level Python framework for building MCP servers with minimal boilerplate.
- [mcp-framework](https://github.com/QuantGeekDev/mcp-framework) - TypeScript framework for building MCP servers with decorators.
- [Spring AI MCP](https://docs.spring.io/spring-ai/reference/api/mcp/mcp-overview.html) - Spring Boot integration for building MCP servers and clients in Java.

## Database Servers

- [ClickHouse MCP](https://github.com/ClickHouse/mcp-clickhouse) - MCP server for ClickHouse analytical queries.
- [DuckDB MCP](https://github.com/motherduckdb/mcp-server-motherduck) - MCP server for DuckDB and MotherDuck queries.
- [MongoDB MCP](https://github.com/kiliczsh/mcp-mongo-server) - MCP server for MongoDB operations and queries.
- [MySQL MCP](https://github.com/benborla/mcp-server-mysql) - MCP server for MySQL database interactions.
- [Neon MCP](https://github.com/neondatabase/mcp-server-neon) - MCP server for Neon serverless PostgreSQL — branches, queries, and management.
- [Postgres MCP Pro](https://github.com/crystaldba/postgres-mcp) - MCP server for PostgreSQL with querying, schema inspection, and performance analysis.
- [Redis MCP](https://github.com/redis/mcp-redis) - Official Redis MCP server for managing and searching data in Redis.
- [Supabase MCP](https://github.com/supabase-community/supabase-mcp) - MCP server for Supabase — database, auth, storage, and edge functions.

## Cloud & Infrastructure

- [AWS MCP](https://github.com/awslabs/mcp) - Official AWS MCP servers for interacting with AWS services.
- [Azure MCP](https://github.com/Azure/azure-mcp) - MCP server for Azure cloud services.
- [Cloudflare MCP](https://github.com/cloudflare/mcp-server-cloudflare) - MCP server for Cloudflare Workers, KV, R2, and D1.
- [DigitalOcean MCP](https://github.com/digitalocean-labs/mcp-digitalocean) - MCP server for DigitalOcean infrastructure management.
- [Docker MCP](https://github.com/ckreiling/mcp-server-docker) - MCP server for Docker container management.
- [Kubernetes MCP](https://github.com/strowk/mcp-k8s-go) - MCP server for Kubernetes cluster management and operations.
- [Terraform MCP](https://github.com/hashicorp/terraform-mcp-server) - MCP server for Terraform infrastructure management.
- [Vercel MCP Handler](https://github.com/vercel-labs/mcp-handler) - Adapter for deploying MCP servers on Vercel and Next.js.

## Developer Tools

- [Agent QA](https://github.com/vostride/agent-qa) - MCP tools to author, run, and inspect natural-language web, Android, and iOS tests, with source available under FSL-1.1-ALv2.
- [Filesystem MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) - Official MCP server for local filesystem operations.
- [Git MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - Official MCP server for Git repository operations.
- [GitHub MCP](https://github.com/github/github-mcp-server) - GitHub's official MCP server for repos, issues, PRs, and code search.
- [GitLab MCP](https://docs.gitlab.com/user/model_context_protocol/mcp_server/) - GitLab's official MCP server for working with GitLab projects.
- [Linear MCP](https://linear.app/docs/mcp) - Linear's official hosted MCP server for issue tracking and project management.
- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - Microsoft's MCP server for browser automation with Playwright.
- [Postman MCP](https://github.com/postmanlabs/postman-mcp-server) - MCP server for Postman API testing and collections.

## Communication

- [BulkPublish MCP](https://github.com/azeemkafridi/bulkpublish-api) - MCP server for AI agents to plan, review, schedule, publish, and analyze social media content through BulkPublish.
- [Discord MCP](https://github.com/v-3/discordmcp) - MCP server for Discord bot operations and messaging.
- [Microsoft Teams MCP](https://github.com/InditexTech/mcp-teams-server) - MCP server for reading, posting, and replying to Microsoft Teams messages.
- [Slack MCP](https://github.com/korotovsky/slack-mcp-server) - MCP server for Slack workspaces, including channels, DMs, threads, and search.
- [Twilio MCP](https://github.com/twilio-labs/mcp) - MCP server for Twilio SMS and communication APIs.

## Search & Web

- [Brave Search MCP](https://github.com/brave/brave-search-mcp-server) - Official MCP server for the Brave Search API.
- [Browserbase MCP](https://github.com/browserbase/mcp-server-browserbase) - MCP server for cloud browser sessions and web automation.
- [Exa MCP](https://github.com/exa-labs/exa-mcp-server) - MCP server for Exa neural search — semantic web search for AI.
- [Fetch MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) - Official MCP server for fetching and parsing web content.
- [Firecrawl MCP](https://github.com/mendableai/firecrawl-mcp-server) - MCP server for Firecrawl web scraping and crawling.
- [Perplexity MCP](https://github.com/ppl-ai/modelcontextprotocol) - MCP server for Perplexity AI search.
- [Pocket Drives](https://github.com/RevList/pocket-drives-mcp) - Search peer-to-peer luxury, exotic, and EV rentals from independent hosts over Streamable HTTP at https://pocketdrives.ai/mcp with no auth.
- [Tavily MCP](https://github.com/tavily-ai/tavily-mcp) - MCP server for Tavily AI-optimized search.

## AI & LLM

- [LangChain MCP](https://github.com/langchain-ai/langchain-mcp-adapters) - Adapters for using MCP tools with LangChain agents.
- [RunAPI MCP](https://github.com/runapi-ai/mcp) - MCP server for running AI image, video, music, speech, and LLM jobs through RunAPI.
- [Sequential Thinking MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking) - Official reference server for structured, step-by-step problem solving.

## Memory & Knowledge

- [Chroma MCP](https://github.com/chroma-core/chroma-mcp) - MCP server for Chroma vector database.
- [Hyperconsciousness](https://github.com/louis030195/hyperconsciousness) - Developer-alpha encrypted knowledge store with lexical search and scoped, expiring grants over MCP.
- [Memory MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) - Official reference server for persistent memory using a local knowledge graph.
- [Obsidian MCP](https://github.com/MarkusPfundstein/mcp-obsidian) - MCP server for Obsidian vaults via the Local REST API plugin.
- [Pinecone MCP](https://github.com/pinecone-io/pinecone-mcp) - MCP server for Pinecone vector search.
- [Qdrant MCP](https://github.com/qdrant/mcp-server-qdrant) - MCP server for Qdrant vector database operations.
- [Weaviate MCP](https://github.com/weaviate/mcp-server-weaviate) - MCP server for Weaviate vector search engine.

## Data & Analytics

- [BigQuery MCP](https://github.com/LucasHild/mcp-server-bigquery) - MCP server for Google BigQuery queries and dataset management.
- [Databricks MCP](https://github.com/databrickslabs/mcp) - MCP servers from Databricks Labs for working with Databricks workspaces.
- [Invokely MCP connector](https://github.com/estevecastells/invokely-mcp-connector) - Local stdio MCP connector for querying official statistics through Invokely's hosted service.
- [Jupyter MCP](https://github.com/datalayer/jupyter-mcp-server) - MCP server for Jupyter notebook execution.
- [Snowflake MCP](https://github.com/datawiz168/mcp-snowflake-service) - MCP server for Snowflake data warehouse operations.

## Productivity

- [Apple Notes MCP](https://github.com/sirmews/apple-notes-mcp) - MCP server for reading and searching Apple Notes.
- [Google Calendar MCP](https://github.com/nspady/google-calendar-mcp) - MCP server for Google Calendar events and scheduling.
- [NotFair Google Ads MCP](https://github.com/nowork-studio/toprank) - Google Ads MCP server. Connect Claude and AI agents to a Google Ads account: diagnose performance, recommend optimizations, and execute approved changes via the Google Ads API with a built-in human-approval gate.
- [Notion MCP](https://github.com/makenotion/notion-mcp-server) - Notion's official MCP server for pages, databases, and search.
- [Orbit by Noveum](https://orbit.noveum.ai/mcp) - Hosted MCP server for issues, projects, sprints, docs and files with workspace-scoped OAuth.
- [Time MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/time) - Official reference server for time and timezone conversions.
- [Todoist MCP](https://github.com/abhiz123/todoist-mcp-server) - MCP server for Todoist task management.

## Media & Files

- [Cloudinary MCP](https://github.com/cloudinary/mcp-servers) - MCP servers for Cloudinary image and video management.
- [OrkasVideoStudio](https://github.com/Orkas-AI/Orkas-VideoStudio) - Local-first CLI and MCP toolkit for composing, editing, generating, transcribing, and assembling videos from editable timelines.

## Design & 3D

- [Blender MCP](https://github.com/ahujasid/mcp-for-blender) - Community plugin for controlling Blender 3D with any LLM.
- [Figma Context MCP](https://github.com/GLips/Figma-Context-MCP) - Provides Figma layout information to AI coding agents.
- [Figma MCP](https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server) - Figma's official MCP server for bringing design context into coding agents.

## Finance & Payments

- [Agent Payment Node](https://github.com/nuanu-ai/agent-payment-node) - Local CLI and stdio MCP payment runtime for AI agents (macOS Apple Silicon); direct transfers wait for owner approval in a terminal, x402 purchases run within an owner-set spending policy.
- [Alpha Vantage MCP](https://github.com/alphavantage/alpha_vantage_mcp) - Official Alpha Vantage MCP server for stock, forex, crypto, and economic data.
- [Coinbase MCP](https://github.com/coinbase/agentkit) - Coinbase AgentKit with MCP server for crypto operations.
- [FilingFirehose MCP](https://filingfirehose.com/mcp) - Hosted SEC EDGAR MCP for any US ticker: 8-K / 10-K / 10-Q / S-3 / 13D filings plus forensic risk scoring (LOW/MODERATE/ELEVATED/HIGH) and cyber-incident tracking.
- [Statsnet](https://github.com/usenetstate/statsnet-mcp) - Background check any company in the world: registration, executives, courts and finances. Remote: `https://statsnet.co/mcp` · Registry: `io.github.usenetstate/statsnet`.
- [Stripe MCP](https://github.com/stripe/agent-toolkit) - Stripe's AI agent toolkit with MCP server for payments.

## Monitoring & Observability

- [Datadog MCP](https://github.com/datadog-labs/mcp-server) - Datadog Labs MCP server for querying Datadog observability data.
- [Grafana MCP](https://github.com/grafana/mcp-grafana) - MCP server for Grafana monitoring and visualization.
- [Kilobat CLI](https://github.com/seifip/kilobat-cli) - Local macOS 14+ network diagnostics and per-app traffic monitoring exposed through stdio MCP and JSON.
- [Noveum](https://noveum.ai/en/mcp) - Hosted MCP server for AI traces, evaluation datasets, and model comparisons, with OAuth or Bearer API key authentication.
- [Sentry MCP](https://mcp.sentry.dev/) - Sentry's official MCP server for error tracking and issue investigation.

## Smart Home & IoT

- [ha-mcp](https://github.com/homeassistant-ai/ha-mcp) - MCP server for configuring and automating Home Assistant with AI assistants.
- [Home Assistant MCP Server](https://www.home-assistant.io/integrations/mcp_server/) - Built-in Home Assistant integration that exposes your smart home to MCP clients.

## Clients & Hosts

- [Amazon Q Developer](https://aws.amazon.com/q/developer/) - AWS AI assistant with MCP client capabilities.
- [Claude Code](https://code.claude.com/docs/en/overview) - Anthropic's agentic coding tool with built-in MCP support.
- [Claude Desktop](https://claude.ai/download) - Anthropic's desktop app with native MCP client support.
- [Cline](https://github.com/cline/cline) - Autonomous coding agent for VS Code with MCP support.
- [Codex CLI](https://github.com/openai/codex) - OpenAI's lightweight coding agent for the terminal with MCP support.
- [Continue.dev](https://continue.dev/) - Open-source AI code assistant with MCP support for VS Code and JetBrains.
- [Cursor](https://www.cursor.com/) - AI code editor with MCP client integration.
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - Google's open-source AI agent for the terminal with MCP support.
- [Genkit (Google)](https://github.com/firebase/genkit) - Google's AI framework with MCP plugin support.
- [Sourcegraph Cody](https://sourcegraph.com/cody) - AI coding assistant with MCP support for code understanding.
- [VS Code](https://code.visualstudio.com/docs/agent-customization/mcp-servers) - Visual Studio Code's agent mode with GitHub Copilot supports MCP servers.
- [Windsurf](https://windsurf.com/) - AI IDE with MCP support for enhanced coding.
- [Zed](https://zed.dev/) - High-performance code editor with MCP integration.

## Gateways & Registries

- [API.market MCP Gateway](https://api.market/api/mcp/gateway) - Hosted API discovery and execution with five tools over Streamable HTTP, OAuth or API keys, and per-API free tiers and paid plans.
- [Glama MCP Directory](https://glama.ai/mcp/servers) - Curated directory of MCP servers with categories.
- [MCP.so](https://mcp.so/) - Directory and registry for discovering MCP servers.
- [Official MCP Registry](https://registry.modelcontextprotocol.io/) - Community-driven registry service for publicly available MCP servers.
- [Smithery](https://smithery.ai/) - Registry for discovering and installing MCP servers.

## Testing & Debugging

- [Everything MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/everything) - Official reference server that exercises every MCP feature, for testing clients.
- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) - Official visual debugging tool for MCP servers.
- [mcp-cli](https://github.com/wong2/mcp-cli) - CLI tool for testing and interacting with MCP servers.
- [mcpx](https://github.com/punkpeye/mcp-proxy) - MCP proxy for debugging and logging server communications.
- [Supergateway](https://github.com/supercorp-ai/supergateway) - Runs stdio MCP servers over SSE or Streamable HTTP.

## Tutorials & Guides

- [Awesome MCP Servers (punkpeye)](https://github.com/punkpeye/awesome-mcp-servers) - Another comprehensive collection of MCP servers.
- [Claude Code MCP Docs](https://code.claude.com/docs/en/mcp) - Guide to connecting Claude Code to MCP servers.
- [Hugging Face MCP Course](https://github.com/huggingface/mcp-course) - Free course on building and using MCP servers.
- [MCP Quickstart Guide](https://modelcontextprotocol.io/quickstart) - Official getting started tutorial for building your first MCP server.

## Community

- [MCP Discord](https://discord.gg/anthropic) - Anthropic's Discord with MCP-focused channels.
- [MCP GitHub Discussions](https://github.com/modelcontextprotocol/modelcontextprotocol/discussions) - Official discussion forum for MCP development.
- [MCP Servers GitHub Topic](https://github.com/topics/mcp-server) - Discover MCP servers on GitHub by topic.
- [MCP Tools GitHub Topic](https://github.com/topics/mcp) - Broader MCP ecosystem on GitHub.
- [r/ClaudeAI](https://www.reddit.com/r/ClaudeAI/) - Reddit community with active MCP discussions.

---

## Support

If you find this list useful, consider supporting its maintenance:

[![Patreon](https://img.shields.io/badge/Patreon-Support%20this%20list-F96854?logo=patreon&logoColor=white)](https://patreon.com/Rohianon)

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.
