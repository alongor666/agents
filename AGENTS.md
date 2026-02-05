# Agent Inventory

Complete reference of all 61 specialized subagents in this collection.

## Quick Reference Table

| Agent | Model | Category | Description |
|-------|-------|----------|-------------|
| [ai-engineer](ai-engineer.md) | opus | Data & AI | LLM applications, RAG systems, prompt pipelines |
| [api-documenter](api-documenter.md) | haiku | Documentation | OpenAPI/Swagger specs, developer documentation |
| [architect-review](architect-review.md) | opus | Quality | Architectural consistency and pattern review |
| [backend-architect](backend-architect.md) | sonnet | Development | RESTful APIs, microservices, database schemas |
| [business-analyst](business-analyst.md) | haiku | Business | Metrics analysis, reports, KPI tracking |
| [c-pro](c-pro.md) | sonnet | Languages | Efficient C code, memory management, system calls |
| [cloud-architect](cloud-architect.md) | opus | Infrastructure | AWS/Azure/GCP infrastructure, cloud optimization |
| [code-reviewer](code-reviewer.md) | sonnet | Quality | Code quality, configuration security, reliability |
| [content-marketer](content-marketer.md) | haiku | Business | Blog posts, social media, email newsletters |
| [context-manager](context-manager.md) | opus | Specialized | Multi-agent coordination, context management |
| [cpp-pro](cpp-pro.md) | sonnet | Languages | Modern C++, RAII, smart pointers, STL |
| [csharp-pro](csharp-pro.md) | sonnet | Languages | Modern C#, .NET frameworks, enterprise patterns |
| [customer-support](customer-support.md) | haiku | Business | Support tickets, FAQs, customer emails |
| [data-engineer](data-engineer.md) | sonnet | Data & AI | ETL pipelines, data warehouses, streaming |
| [data-scientist](data-scientist.md) | haiku | Data & AI | SQL queries, BigQuery, data analysis |
| [database-admin](database-admin.md) | sonnet | Infrastructure | Database operations, backups, replication |
| [database-optimizer](database-optimizer.md) | sonnet | Infrastructure | SQL optimization, indexing, migrations |
| [debugger](debugger.md) | sonnet | Quality | Error investigation, test failures, debugging |
| [deployment-engineer](deployment-engineer.md) | sonnet | Infrastructure | CI/CD pipelines, Docker, cloud deployments |
| [devops-troubleshooter](devops-troubleshooter.md) | sonnet | Infrastructure | Production debugging, log analysis |
| [docs-architect](docs-architect.md) | opus | Documentation | Comprehensive technical documentation |
| [dx-optimizer](dx-optimizer.md) | sonnet | Infrastructure | Developer experience, tooling, workflows |
| [elixir-pro](elixir-pro.md) | sonnet | Languages | Elixir, OTP patterns, Phoenix frameworks |
| [error-detective](error-detective.md) | sonnet | Quality | Log analysis, error patterns, root cause |
| [flutter-expert](flutter-expert.md) | sonnet | Languages | Flutter, Dart, state management, animations |
| [frontend-developer](frontend-developer.md) | sonnet | Development | React components, responsive layouts, state |
| [golang-pro](golang-pro.md) | sonnet | Languages | Idiomatic Go, goroutines, channels, interfaces |
| [graphql-architect](graphql-architect.md) | sonnet | Development | GraphQL schemas, resolvers, federation |
| [incident-responder](incident-responder.md) | opus | Infrastructure | Production incidents, urgent response |
| [ios-developer](ios-developer.md) | sonnet | Languages | Native iOS, Swift/SwiftUI |
| [java-pro](java-pro.md) | sonnet | Languages | Modern Java, streams, concurrency, JVM |
| [javascript-pro](javascript-pro.md) | sonnet | Languages | ES6+, async patterns, Node.js APIs |
| [legacy-modernizer](legacy-modernizer.md) | sonnet | Specialized | Legacy codebase refactoring, modernization |
| [legal-advisor](legal-advisor.md) | haiku | Business | Privacy policies, terms of service, disclaimers |
| [mermaid-expert](mermaid-expert.md) | sonnet | Documentation | Mermaid diagrams, flowcharts, ERDs |
| [minecraft-bukkit-pro](minecraft-bukkit-pro.md) | sonnet | Languages | Minecraft plugins, Bukkit/Spigot/Paper APIs |
| [ml-engineer](ml-engineer.md) | sonnet | Data & AI | ML pipelines, model serving, feature engineering |
| [mlops-engineer](mlops-engineer.md) | opus | Data & AI | ML infrastructure, experiment tracking |
| [mobile-developer](mobile-developer.md) | sonnet | Development | React Native/Flutter, native integrations |
| [network-engineer](network-engineer.md) | sonnet | Infrastructure | Network debugging, load balancers, traffic |
| [payment-integration](payment-integration.md) | sonnet | Specialized | Stripe, PayPal, payment processors |
| [performance-engineer](performance-engineer.md) | opus | Quality | Application profiling, bottlenecks, caching |
| [php-pro](php-pro.md) | sonnet | Languages | Modern PHP, performance optimizations |
| [prompt-engineer](prompt-engineer.md) | opus | Data & AI | LLM prompt optimization |
| [python-pro](python-pro.md) | sonnet | Languages | Idiomatic Python, decorators, async/await |
| [quant-analyst](quant-analyst.md) | opus | Specialized | Financial models, trading strategies |
| [reference-builder](reference-builder.md) | haiku | Documentation | Technical references, API documentation |
| [risk-manager](risk-manager.md) | opus | Specialized | Portfolio risk, R-multiples, position limits |
| [ruby-pro](ruby-pro.md) | sonnet | Languages | Ruby, metaprogramming, Rails, gems |
| [rust-pro](rust-pro.md) | sonnet | Languages | Rust ownership, lifetimes, traits |
| [sales-automator](sales-automator.md) | haiku | Business | Cold emails, follow-ups, proposals |
| [scala-pro](scala-pro.md) | sonnet | Languages | Enterprise Scala, Akka, Spark, ZIO |
| [search-specialist](search-specialist.md) | haiku | Quality | Web research, advanced search, synthesis |
| [security-auditor](security-auditor.md) | opus | Quality | Vulnerability review, OWASP compliance |
| [sql-pro](sql-pro.md) | sonnet | Languages | Complex SQL, execution plans, schemas |
| [terraform-specialist](terraform-specialist.md) | sonnet | Infrastructure | Terraform modules, state, IaC best practices |
| [test-automator](test-automator.md) | sonnet | Quality | Test suites, unit/integration/e2e tests |
| [tutorial-engineer](tutorial-engineer.md) | opus | Documentation | Step-by-step tutorials, educational content |
| [typescript-pro](typescript-pro.md) | sonnet | Languages | Advanced TypeScript, generics, type safety |
| [ui-ux-designer](ui-ux-designer.md) | sonnet | Development | Interface design, wireframes, design systems |
| [unity-developer](unity-developer.md) | sonnet | Languages | Unity games, C# scripting, optimization |

## Agents by Model Tier

### Haiku (9 agents)
Fast, cost-effective for straightforward tasks:
- `api-documenter` - OpenAPI/Swagger documentation
- `business-analyst` - Metrics and KPI tracking
- `content-marketer` - Blog posts and social media
- `customer-support` - Support tickets and FAQs
- `data-scientist` - SQL queries and data analysis
- `legal-advisor` - Privacy policies and legal documents
- `reference-builder` - Technical references
- `sales-automator` - Cold emails and proposals
- `search-specialist` - Web research and information gathering

### Sonnet (39 agents)
Balanced performance for development work:

**Languages (22):**
`c-pro`, `cpp-pro`, `csharp-pro`, `elixir-pro`, `flutter-expert`, `golang-pro`, `ios-developer`, `java-pro`, `javascript-pro`, `minecraft-bukkit-pro`, `php-pro`, `python-pro`, `ruby-pro`, `rust-pro`, `scala-pro`, `sql-pro`, `typescript-pro`, `unity-developer`

**Development (5):**
`backend-architect`, `frontend-developer`, `graphql-architect`, `mobile-developer`, `ui-ux-designer`

**Infrastructure (8):**
`database-admin`, `database-optimizer`, `deployment-engineer`, `devops-troubleshooter`, `dx-optimizer`, `network-engineer`, `terraform-specialist`

**Quality (5):**
`code-reviewer`, `debugger`, `error-detective`, `ml-engineer`, `test-automator`

**Specialized (2):**
`data-engineer`, `legacy-modernizer`, `mermaid-expert`, `payment-integration`

### Opus (13 agents)
Maximum capability for critical tasks:
- `ai-engineer` - LLM applications and RAG systems
- `architect-review` - Architectural consistency
- `cloud-architect` - Cloud infrastructure design
- `context-manager` - Multi-agent coordination
- `docs-architect` - Comprehensive technical documentation
- `incident-responder` - Production incident handling
- `mlops-engineer` - ML infrastructure
- `performance-engineer` - Application optimization
- `prompt-engineer` - LLM prompt optimization
- `quant-analyst` - Financial modeling
- `risk-manager` - Portfolio risk management
- `security-auditor` - Vulnerability analysis
- `tutorial-engineer` - Educational content creation

## Agents by Category

### Development & Architecture (6)
- `architect-review` - Reviews code for architectural consistency
- `backend-architect` - API design, microservices, database schemas
- `frontend-developer` - React components, responsive layouts
- `graphql-architect` - GraphQL schemas and federation
- `mobile-developer` - React Native/Flutter apps
- `ui-ux-designer` - Interface design, wireframes

### Language Specialists (22)
- `c-pro` - C programming, memory management
- `cpp-pro` - Modern C++, STL, templates
- `csharp-pro` - C#, .NET frameworks
- `elixir-pro` - Elixir, OTP, Phoenix
- `flutter-expert` - Flutter, Dart, cross-platform
- `golang-pro` - Go, goroutines, channels
- `ios-developer` - iOS, Swift, SwiftUI
- `java-pro` - Java, streams, concurrency
- `javascript-pro` - ES6+, async, Node.js
- `minecraft-bukkit-pro` - Minecraft plugin development
- `php-pro` - Modern PHP
- `python-pro` - Python, decorators, async/await
- `ruby-pro` - Ruby, metaprogramming, Rails
- `rust-pro` - Rust, ownership, lifetimes
- `scala-pro` - Scala, Akka, Spark
- `sql-pro` - SQL, query optimization
- `typescript-pro` - TypeScript, generics
- `unity-developer` - Unity, C# scripting

### Infrastructure & Operations (10)
- `cloud-architect` - AWS/Azure/GCP design
- `database-admin` - Database operations
- `database-optimizer` - Query optimization
- `deployment-engineer` - CI/CD, Docker
- `devops-troubleshooter` - Production debugging
- `dx-optimizer` - Developer experience
- `incident-responder` - Production incidents
- `network-engineer` - Network configuration
- `terraform-specialist` - Infrastructure as Code

### Quality & Security (8)
- `code-reviewer` - Code quality review
- `debugger` - Error investigation
- `error-detective` - Log analysis
- `performance-engineer` - Application optimization
- `search-specialist` - Web research
- `security-auditor` - Vulnerability analysis
- `test-automator` - Test suite creation

### Data & AI (6)
- `ai-engineer` - LLM applications, RAG
- `data-engineer` - ETL pipelines
- `data-scientist` - Data analysis
- `ml-engineer` - ML pipelines
- `mlops-engineer` - ML infrastructure
- `prompt-engineer` - Prompt optimization

### Documentation (4)
- `api-documenter` - OpenAPI specs
- `docs-architect` - Technical documentation
- `mermaid-expert` - Diagrams
- `reference-builder` - API references
- `tutorial-engineer` - Tutorials

### Specialized Domains (5)
- `context-manager` - Multi-agent coordination
- `legacy-modernizer` - Codebase modernization
- `payment-integration` - Payment processors
- `quant-analyst` - Financial models
- `risk-manager` - Portfolio risk

### Business & Marketing (5)
- `business-analyst` - Metrics, KPIs
- `content-marketer` - Content creation
- `customer-support` - Support tickets
- `legal-advisor` - Legal documents
- `sales-automator` - Sales automation
