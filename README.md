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
- [Data & Analytics](#data--analytics)
- [Productivity](#productivity)
- [Media & Files](#media--files)
- [Finance & Payments](#finance--payments)
- [Monitoring & Observability](#monitoring--observability)
- [Clients & Hosts](#clients--hosts)
- [Testing & Debugging](#testing--debugging)
- [Tutorials & Guides](#tutorials--guides)
- [Community](#community)

## Official Resources

- [MCP Specification](https://spec.modelcontextprotocol.io/) - The official protocol specification.
- [MCP Documentation](https://modelcontextprotocol.io/introduction) - Official getting started guide and documentation.
- [MCP GitHub Organization](https://github.com/modelcontextprotocol) - Official repos including SDKs, servers, and spec.
- [MCP Servers Repository](https://github.com/modelcontextprotocol/servers) - Official reference server implementations by Anthropic.
- [Introducing MCP (Blog)](https://www.anthropic.com/news/model-context-protocol) - Anthropic's announcement blog post.

## SDKs & Libraries

- [TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - Official TypeScript/Node.js SDK for building MCP servers and clients.
- [Python SDK](https://github.com/modelcontextprotocol/python-sdk) - Official Python SDK for building MCP servers and clients.
- [Go SDK (mark3labs)](https://github.com/mark3labs/mcp-go) - Community Go SDK for the Model Context Protocol.
- [Rust SDK](https://github.com/modelcontextprotocol/rust-sdk) - Rust SDK for building high-performance MCP servers.
- [Java SDK (quarkiverse)](https://github.com/quarkiverse/quarkus-mcp-server) - Quarkus extension for building MCP servers in Java.
- [C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) - .NET SDK for building MCP servers and clients.
- [Kotlin SDK](https://github.com/modelcontextprotocol/kotlin-sdk) - Kotlin SDK for JVM-based MCP implementations.
- [Swift SDK](https://github.com/modelcontextprotocol/swift-sdk) - Swift SDK for building MCP servers on Apple platforms.
- [Ruby SDK (funwarioisii)](https://github.com/funwarioisii/mcp-ruby-sdk) - Community Ruby SDK for building MCP servers.

## Server Frameworks

- [FastMCP](https://github.com/jlowin/fastmcp) - High-level Python framework for building MCP servers with minimal boilerplate.
- [mcp-framework](https://github.com/QuantGeekDev/mcp-framework) - TypeScript framework for building MCP servers with decorators.
- [EasyMCP](https://github.com/zueai/EasyMCP) - Simplified MCP server creation with automatic tool registration.
- [Spring AI MCP](https://docs.spring.io/spring-ai/reference/api/mcp.html) - Spring Boot integration for building MCP servers in Java.
- [mcp-server-go (mark3labs)](https://github.com/mark3labs/mcp-go) - Go framework for creating MCP servers with the Go SDK.

## Database Servers

- [PostgreSQL MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - Official MCP server for PostgreSQL — query, schema inspection, and analysis.
- [SQLite MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) - Official MCP server for SQLite databases.
- [MySQL MCP](https://github.com/benborla/mcp-server-mysql) - MCP server for MySQL database interactions.
- [MongoDB MCP](https://github.com/kiliczsh/mcp-mongo-server) - MCP server for MongoDB operations and queries.
- [Redis MCP](https://github.com/modelcontextprotocol/servers) - MCP server for Redis key-value operations.
- [Supabase MCP](https://github.com/supabase-community/supabase-mcp) - MCP server for Supabase — database, auth, storage, and edge functions.
- [Neon MCP](https://github.com/neondatabase/mcp-server-neon) - MCP server for Neon serverless Postgres — branches, queries, and management.
- [ClickHouse MCP](https://github.com/ClickHouse/mcp-clickhouse) - MCP server for ClickHouse analytical queries.
- [DuckDB MCP](https://github.com/motherduckdb/mcp-server-motherduck) - MCP server for DuckDB and MotherDuck queries.

## Cloud & Infrastructure

- [AWS MCP](https://github.com/aws/aws-mcp) - Official AWS MCP servers for interacting with AWS services.
- [Kubernetes MCP](https://github.com/strowk/mcp-k8s-go) - MCP server for Kubernetes cluster management and operations.
- [Docker MCP](https://github.com/ckreiling/mcp-server-docker) - MCP server for Docker container management.
- [Terraform MCP](https://github.com/hashicorp/terraform-mcp-server) - MCP server for Terraform infrastructure management.
- [Cloudflare MCP](https://github.com/cloudflare/mcp-server-cloudflare) - MCP server for Cloudflare Workers, KV, R2, and D1.
- [Vercel MCP](https://github.com/vercel/mcp-adapter-vercel) - MCP adapter for deploying MCP servers to Vercel.
- [Azure MCP](https://github.com/Azure/azure-mcp) - MCP server for Azure cloud services.
- [DigitalOcean MCP](https://github.com/digitalocean/mcp-server) - MCP server for DigitalOcean infrastructure management.

## Developer Tools

- [GitHub MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - Official MCP server for GitHub — repos, issues, PRs, and code search.
- [GitLab MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) - Official MCP server for GitLab operations.
- [Git MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - Official MCP server for Git repository operations.
- [Filesystem MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) - Official MCP server for local filesystem operations.
- [Linear MCP](https://github.com/jerhadf/linear-mcp-server) - MCP server for Linear issue tracking and project management.
- [Sentry MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) - Official MCP server for Sentry error tracking.
- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - Microsoft's MCP server for browser automation with Playwright.
- [Puppeteer MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) - Official MCP server for browser automation with Puppeteer.
- [Postman MCP](https://github.com/postmanlabs/postman-mcp-server) - MCP server for Postman API testing and collections.

## Communication

- [Slack MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) - Official MCP server for Slack workspace interactions.
- [Discord MCP](https://github.com/v-3/discordmcp) - MCP server for Discord bot operations and messaging.
- [Email MCP](https://github.com/hannesrudolph/mcp-server-email) - MCP server for sending and reading emails.
- [Twilio MCP](https://github.com/twilio-labs/mcp-server-twilio) - MCP server for Twilio SMS and communication APIs.
- [Microsoft Teams MCP](https://github.com/modelcontextprotocol/servers) - MCP server for Microsoft Teams integration.

## Search & Web

- [Brave Search MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) - Official MCP server for Brave Search API.
- [Exa MCP](https://github.com/exa-labs/exa-mcp-server) - MCP server for Exa neural search — semantic web search for AI.
- [Fetch MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) - Official MCP server for fetching and parsing web content.
- [Tavily MCP](https://github.com/tavily-ai/tavily-mcp) - MCP server for Tavily AI-optimized search.
- [Firecrawl MCP](https://github.com/mendableai/firecrawl-mcp-server) - MCP server for Firecrawl web scraping and crawling.
- [Browserbase MCP](https://github.com/browserbase/mcp-server-browserbase) - MCP server for cloud browser sessions and web automation.
- [Perplexity MCP](https://github.com/ppl-ai/modelcontextprotocol) - MCP server for Perplexity AI search.
- [Serper MCP](https://github.com/nicholaskajoh/mcp-server-serper) - MCP server for Google SERP results via Serper API.

## AI & LLM

- [OpenAI MCP](https://github.com/openai/openai-mcp) - MCP server for OpenAI API interactions.
- [HuggingFace MCP](https://github.com/huggingface/mcp-course) - HuggingFace's MCP course and server implementations.
- [LangChain MCP](https://github.com/langchain-ai/langchain-mcp-adapters) - Adapters for using MCP tools with LangChain agents.
- [Qdrant MCP](https://github.com/qdrant/mcp-server-qdrant) - MCP server for Qdrant vector database operations.
- [Chroma MCP](https://github.com/chroma-core/chroma-mcp) - MCP server for Chroma vector database.
- [Pinecone MCP](https://github.com/pinecone-io/pinecone-mcp) - MCP server for Pinecone vector search.
- [Weaviate MCP](https://github.com/weaviate/mcp-server-weaviate) - MCP server for Weaviate vector search engine.

## Data & Analytics

- [BigQuery MCP](https://github.com/LucasHild/mcp-server-bigquery) - MCP server for Google BigQuery queries and dataset management.
- [Snowflake MCP](https://github.com/datawiz168/mcp-snowflake-service) - MCP server for Snowflake data warehouse operations.
- [Pandas MCP](https://github.com/dillondesilva/pandas-mcp) - MCP server for data analysis with pandas DataFrames.
- [Grafana MCP](https://github.com/grafana/mcp-grafana) - MCP server for Grafana dashboards and data exploration.
- [Jupyter MCP](https://github.com/datalayer/jupyter-mcp-server) - MCP server for Jupyter notebook execution.
- [Databricks MCP](https://github.com/databricks/databricks-mcp) - MCP server for Databricks workspace operations.

## Productivity

- [Google Drive MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) - Official MCP server for Google Drive file operations.
- [Notion MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/notion) - MCP server for Notion workspace interactions.
- [Obsidian MCP](https://github.com/smithery-ai/mcp-obsidian) - MCP server for searching and reading Obsidian vault content.
- [Todoist MCP](https://github.com/abhiz123/todoist-mcp-server) - MCP server for Todoist task management.
- [Google Calendar MCP](https://github.com/nspady/google-calendar-mcp) - MCP server for Google Calendar events and scheduling.
- [Apple Notes MCP](https://github.com/sirmews/apple-notes-mcp) - MCP server for reading and searching Apple Notes.
- [Raycast MCP](https://github.com/raycast/mcp-server-raycast) - MCP server for Raycast productivity launcher.

## Media & Files

- [S3 MCP](https://github.com/aws/aws-mcp) - MCP server for Amazon S3 file operations.
- [Cloudinary MCP](https://github.com/cloudinary/cloudinary-mcp-server) - MCP server for Cloudinary image and video management.
- [FFmpeg MCP](https://github.com/mojowebs/mcp-server-ffmpeg) - MCP server for video/audio processing with FFmpeg.
- [Sharp Image MCP](https://github.com/nicholaskajoh/mcp-server-sharp) - MCP server for image processing with Sharp.
- [PDF MCP](https://github.com/reyoung/pdf-mcp-server) - MCP server for reading and extracting content from PDFs.

## Finance & Payments

- [Stripe MCP](https://github.com/stripe/agent-toolkit) - Stripe's AI agent toolkit with MCP server for payments.
- [Plaid MCP](https://github.com/plaid/mcp-server-plaid) - MCP server for Plaid financial data connections.
- [Coinbase MCP](https://github.com/coinbase/agentkit) - Coinbase AgentKit with MCP server for crypto operations.
- [Yahoo Finance MCP](https://github.com/calvernaz/alphavantage-mcp) - MCP server for stock market data and financial analysis.

## Monitoring & Observability

- [Sentry MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) - Official MCP server for error tracking with Sentry.
- [Datadog MCP](https://github.com/DataDog/datadog-mcp-server) - MCP server for Datadog metrics, logs, and APM.
- [Grafana MCP](https://github.com/grafana/mcp-grafana) - MCP server for Grafana monitoring and visualization.
- [PagerDuty MCP](https://github.com/PagerDuty/mcp-server-pagerduty) - MCP server for PagerDuty incident management.

## Clients & Hosts

- [Claude Desktop](https://claude.ai/download) - Anthropic's desktop app with native MCP client support.
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - Anthropic's CLI tool for coding with built-in MCP support.
- [Cursor](https://www.cursor.com/) - AI code editor with MCP client integration.
- [Windsurf (Codeium)](https://codeium.com/windsurf) - AI IDE with MCP support for enhanced coding.
- [Continue.dev](https://continue.dev/) - Open-source AI code assistant with MCP support for VS Code and JetBrains.
- [Zed](https://zed.dev/) - High-performance code editor with MCP integration.
- [Cline](https://github.com/cline/cline) - Autonomous coding agent for VS Code with MCP support.
- [Sourcegraph Cody](https://sourcegraph.com/cody) - AI coding assistant with MCP support for code understanding.
- [Amazon Q Developer](https://aws.amazon.com/q/developer/) - AWS AI assistant with MCP client capabilities.
- [Genkit (Google)](https://github.com/firebase/genkit) - Google's AI framework with MCP plugin support.

## Testing & Debugging

- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) - Official visual debugging tool for MCP servers.
- [mcp-cli](https://github.com/wong2/mcp-cli) - CLI tool for testing and interacting with MCP servers.
- [mcpx](https://github.com/punkpeye/mcp-proxy) - MCP proxy for debugging and logging server communications.
- [Supergateway](https://github.com/nicholaskajoh/supergateway) - Proxy for running stdio MCP servers over SSE transport.

## Tutorials & Guides

- [MCP Quickstart Guide](https://modelcontextprotocol.io/quickstart) - Official getting started tutorial for building your first MCP server.
- [Building MCP with Python](https://modelcontextprotocol.io/quickstart/server) - Step-by-step guide to building MCP servers in Python.
- [Building MCP with TypeScript](https://modelcontextprotocol.io/quickstart/server) - TypeScript MCP server tutorial.
- [HuggingFace MCP Course](https://github.com/huggingface/mcp-course) - Free course on building and using MCP servers.
- [Anthropic MCP Docs](https://docs.anthropic.com/en/docs/agents-and-tools/mcp) - Official Anthropic documentation on MCP integration.
- [Awesome MCP Servers (punkpeye)](https://github.com/punkpeye/awesome-mcp-servers) - Another comprehensive collection of MCP servers.
- [MCP.so](https://mcp.so/) - Directory and registry for discovering MCP servers.
- [Glama MCP Directory](https://glama.ai/mcp/servers) - Curated directory of MCP servers with categories.
- [Smithery](https://smithery.ai/) - Registry for discovering and installing MCP servers.

## Community

- [MCP GitHub Discussions](https://github.com/orgs/modelcontextprotocol/discussions) - Official discussion forum for MCP development.
- [MCP Discord](https://discord.gg/anthropic) - Anthropic's Discord with MCP-focused channels.
- [r/ClaudeAI](https://www.reddit.com/r/ClaudeAI/) - Reddit community with active MCP discussions.
- [MCP Servers GitHub Topic](https://github.com/topics/mcp-server) - Discover MCP servers on GitHub by topic.
- [MCP Tools GitHub Topic](https://github.com/topics/mcp) - Broader MCP ecosystem on GitHub.

---

## Support

If you find this list useful, consider supporting its maintenance:

[![Patreon](https://img.shields.io/badge/Patreon-Support%20this%20list-F96854?logo=patreon&logoColor=white)](https://patreon.com/Rohianon)

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
