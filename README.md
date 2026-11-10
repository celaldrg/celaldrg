<h1 align="center">Celalettin Durğaç</h1>

<p align="center">
  Computer programmer and IT specialist from Türkiye. I build small, sharp developer tools:<br/>
  MCP servers for AI agents and CLIs that catch problems before they ship.
</p>

<p align="center">
  <a href="https://celaldrg.github.io"><img src="https://img.shields.io/badge/portfolio-celaldrg.github.io-111?style=flat-square" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/celaldrg/"><img src="https://img.shields.io/badge/LinkedIn-celaldrg-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/celaldrg?tab=repositories"><img src="https://img.shields.io/badge/open%20source-MIT-111?style=flat-square" alt="Open source, MIT"/></a>
</p>

---

### Featured projects

| Project | Language | What it does |
| --- | --- | --- |
| [**aichurn**](https://github.com/celaldrg/aichurn) | ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white) | Does AI-written code get rewritten faster? Replays git history line by line: two-week churn, copy/paste and moved code, split by AI-assisted vs human commits. Ran on 13 popular repos. Single binary. |
| [**agentprs**](https://github.com/celaldrg/agentprs) | ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white) | How do AI agents' pull requests fare in your repo? Share, merge rate and time to merge for Copilot, Claude Code, Codex, Cursor, Devin, Jules and 8 more, next to human PRs. GitHub Action, SVG card + badge. |
| [**aiblame**](https://github.com/celaldrg/aiblame) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | How much of this repo did AI write? `git blame` for the agent era: the share of today's code written with Claude Code, Cursor, Copilot, Codex, Aider, Devin and 9 more. Works on any GitHub repo, SVG card + badge, CI gate. Zero dependencies. |
| [**shush**](https://github.com/celaldrg/shush) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | Compresses noisy command output (test runs, installs, builds) before it reaches an AI agent. Errors are always kept. ~69% fewer tokens on a real benchmark. MCP server + CLI. |
| [**turkiye-mcp**](https://github.com/celaldrg/turkiye-mcp) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | MCP server with 17 Türkiye-specific tools: TCMB exchange rates, earthquakes, holidays and business days, IBAN/TCKN/VKN validation, provinces, prayer times, weather. No API keys. |
| [**lockdiff**](https://github.com/celaldrg/lockdiff) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | Readable diffs for lockfiles: upgraded, downgraded, added and removed packages with major bumps first. 10 formats (npm, pnpm, yarn, Cargo, Go, Poetry, uv, ...), Markdown for PR comments. |
| [**csvglance**](https://github.com/celaldrg/csvglance) | ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white) | Profiles a CSV in one streaming pass: types, missing values, distinct counts (HyperLogLog), ranges and top values per column. Detects delimiters, gzip, decimal commas. ~1 s per million rows. |
| [**todoage**](https://github.com/celaldrg/todoage) | ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white) | How old are your TODOs? Uses `git blame` to show who wrote each TODO/FIXME and when, oldest first, with a CI gate for stale ones. |
| [**certpeek**](https://github.com/celaldrg/certpeek) | ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white) | Checks TLS certificates for one host or hundreds: expiry, hostname, trust chain, TLS version. JSON output and exit codes for cron/CI. |
| [**envguard**](https://github.com/celaldrg/envguard) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | Linter for `.env` files: syntax errors, duplicates, keys missing from `.env.example`, and real secrets committed by mistake. pre-commit hook included. |
| [**turkcekit**](https://github.com/celaldrg/turkcekit) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | Turkish text done right in Python: correct `İ/ı` casing, URL slugs, Turkish alphabetical sorting, numbers and lira amounts in words, `1.234,50 ₺` formatting. Zero dependencies, CLI included. |
| [**llmslint**](https://github.com/celaldrg/llmslint) | ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white) | Linter for `llms.txt`, the file that points AI agents at your docs: structure, link format, relative and dead URLs, size of the `Optional` section. Works on a file, URL or whole domain; JSON and CI modes. |
| [**skillcheck**](https://github.com/celaldrg/skillcheck) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | Linter for Agent Skills, the `SKILL.md` folders that Claude Code, Codex, Cursor and Copilot load on demand: name and description rules, strict frontmatter with line numbers, broken file links, context-size warnings. Zero dependencies; JSON and GitHub annotation output. |
| [**tokmap**](https://github.com/celaldrg/tokmap) | ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white) | See where your repo's tokens go before an AI agent reads it: a token budget map of files and folders, flags lockfiles, minified bundles, generated code and snapshots, and a `--budget` CI check. Single binary, zero dependencies. |
| [**invisigrep**](https://github.com/celaldrg/invisigrep) | ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white) | Find invisible Unicode (zero-width, bidi overrides, tag-character ASCII smuggling) that hides prompt injections in `AGENTS.md`, rules files and code, and decode the hidden text. Zero-dependency CLI with CI exit codes. |
| [**mcpdiff**](https://github.com/celaldrg/mcpdiff) | ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white) | Catch breaking changes in MCP server tool schemas: diff two `tools/list` snapshots (removed tools, new required params, type and enum changes) and fail CI. Zero-dependency CLI. |
| [**mcptax**](https://github.com/celaldrg/mcptax) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | What your MCP server costs an agent's context window: per-tool token estimates from `tools/list` (saved or live stdio), warnings for missing, duplicate or bloated descriptions, deep schemas and huge enums, and a `--budget` CI gate. Zero dependencies. |
| [**toolrank**](https://github.com/celaldrg/toolrank) | ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white) | Rank MCP `tools/list` tools for a natural-language task with name/description/schema heuristics (no LLM): top-N scores, token estimates, and a `-budget` mode to keep only what fits. Zero-dependency Go CLI. |
| [**ctxlint**](https://github.com/celaldrg/ctxlint) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | Lint the files your coding agents read every turn (`AGENTS.md`, `CLAUDE.md`, `.cursorrules`, `copilot-instructions.md`) against the real repo: stale paths and links, missing npm/make scripts, leaked secrets, home-dir paths, token bloat, copy-pasted drift. Zero dependencies. |
| [**awesome-turkiye-dev**](https://github.com/celaldrg/awesome-turkiye-dev) | ![Markdown](https://img.shields.io/badge/-Curated%20list-555?style=flat-square&logo=markdown&logoColor=white) | Curated resources for developers in Türkiye: open-source projects, Turkish NLP, APIs and open data, communities, events and jobs. |

Every project is MIT-licensed, has CI on every push, and ships with real example output in its README.

### What I work on

- **Tools for AI agents:** MCP servers that give agents better context with less noise
- **Developer tooling:** small single-binary CLIs that fit into CI, cron and pre-commit
- **Turkish developer ecosystem:** open data, local APIs and curated resources

### Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### Activity

<p>
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=celaldrg&show_icons=true&hide_border=true&hide_rank=true&count_private=false" alt="GitHub stats" />
  <img height="150" src="https://streak-stats.demolab.com/?user=celaldrg&hide_border=true" alt="GitHub streak" />
</p>

### Contributing

Issues and pull requests are welcome on any of these projects. Issues labeled
[`good first issue`](https://github.com/search?q=user%3Acelaldrg+label%3A%22good+first+issue%22+state%3Aopen&type=issues)
are a good place to start.

<p align="center"><sub>Türk geliştiriciler için açık kaynak araçlar</sub></p>

