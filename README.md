<p align="center">
  <a href="https://celaldrg.github.io">
    <picture>
      <source media="(prefers-reduced-motion: reduce)" srcset="assets/twin-hero-still.webp" />
      <img src="assets/twin-hero.webp" width="100%" alt="My digital twin: a green hologram of my face and shoulders, built from code characters and particles, materializes over a glowing projector ring, speaks, and dissolves again. Code rain spelled from my tools' names falls at the edges. Lettered: Celalettin Durğaç, digital twin, instruments for AI agents, 22 tools in TypeScript, Go, Rust and Python, from Türkiye." />
    </picture>
  </a>
</p>

<p align="center">
  <img src="assets/transmission.svg" width="100%" alt="Connection established. I am Celal's digital copy; I watch this place when he is away. There are twenty-two tools in this system, all built for AI agents. Tell me what is breaking. I will show you where it is." />
</p>

<p align="center">
  Computer programmer and IT specialist from Türkiye<br/>
  <a href="https://celaldrg.github.io">celaldrg.github.io</a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/celaldrg/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/celaldrg?tab=repositories">All repositories</a>
</p>

<p align="center"><sub><b>Sectors</b> &nbsp;
  <a href="#sector-01">01 · MCP</a> ·
  <a href="#sector-02">02 · Instruction files</a> ·
  <a href="#sector-03">03 · Git</a> ·
  <a href="#sector-04">04 · Everyday CLIs</a></sub></p>

---

I build small, sharp developer tools: MCP servers for AI agents and CLIs that catch problems
before they ship. An agent is only as good as what it is wired to and what it reads every turn,
so most of my tools sit at those two seams. The rest measure what agents actually do to a
codebase, plus the everyday CLIs I reach for myself. Each one is a single binary or a
zero-dependency package, with CI on every push and real example output in its README.

<p align="center">
  <a href="https://celaldrg.github.io">
    <img src="assets/boot.svg" width="100%" alt="A terminal boot screen: Celal · Dijital İkiz, sentinel of github.com/celaldrg. Lines type in: connection detected, scanning visitor, access level guest, digital twin ready. A CONNECT button pulses. Click to open the live 3D twin." />
  </a>
</p>

<p align="center"><sub><b>Talk to the twin.</b> On my site the hologram is live: it turns to the tool you pick, answers in Turkish or English,<br/>and hands you the one-line install for whatever is breaking. No language model behind it; it all runs in your browser.</sub></p>

<p align="center">
  <a href="https://github.com/celaldrg?tab=repositories">
    <img src="assets/showcase.webp" width="100%" alt="A slow slideshow of the cover art for eight of the tools: mcpaudit, hooklint, ctxlint, agentprs, turkiye-mcp, mcptax, aiblame and subagentlint." />
  </a>
</p>

## Sector 01

<p align="center"><img src="assets/sector-01.svg" width="100%" alt="Sector 01: MCP, what an agent is wired to. 5 tools: mcpaudit, mcpdiff, mcptax, toolrank, turkiye-mcp." /></p>

<p align="center"><sub>Every MCP server is a cable plugged into the agent. These tools check what is on the other end:<br/>its config, its schema, its cost in tokens, and whether it is the right one for the job.</sub></p>

| Repository | Language |
|---|---|
| **[mcpaudit](https://github.com/celaldrg/mcpaudit)**: Audit MCP configs (.mcp.json, Cursor, VS Code, Gemini, Claude Desktop) for hardcoded secrets, unpinned npx/uvx/docker servers, plain-HTTP remotes and broken entries. Zero-dep TypeScript CLI + CI gate. | TypeScript |
| **[mcpdiff](https://github.com/celaldrg/mcpdiff)**: Catch breaking changes in MCP server tool schemas: diff two tools/list snapshots, fail CI on breaking changes. Zero-dependency Go CLI. | Go |
| **[mcptax](https://github.com/celaldrg/mcptax)**: What does your MCP server cost an agent's context window? Per-tool token estimates, bloat warnings and a CI budget gate. TypeScript, zero deps. | TypeScript |
| **[toolrank](https://github.com/celaldrg/toolrank)**: Rank MCP tools/list against a natural-language task with keyword heuristics (no LLM) | Go |
| **[turkiye-mcp](https://github.com/celaldrg/turkiye-mcp)**: MCP server for Türkiye: TCMB exchange rates, AFAD/Kandilli earthquakes, holidays & business days, IBAN/TCKN/VKN validation, provinces, prayer times, weather. No API keys. | TypeScript |

## Sector 02

<p align="center"><img src="assets/sector-02.svg" width="100%" alt="Sector 02: Instruction files, what an agent reads. 7 tools: ctxlint, skillcheck, subagentlint, hooklint, llmslint, invisigrep, tokmap." /></p>

<p align="center"><sub>An agent reads its instruction files on every turn, and believes them.<br/>These linters check those files against the real repo: stale paths, hidden characters, broken links, token weight.</sub></p>

| Repository | Language |
|---|---|
| **[ctxlint](https://github.com/celaldrg/ctxlint)**: Lint AGENTS.md, CLAUDE.md, .cursorrules and copilot-instructions.md against your real repo: stale paths, missing scripts, leaked secrets, token bloat. Zero-dependency Python CLI. | Python |
| **[skillcheck](https://github.com/celaldrg/skillcheck)**: Lint Agent Skills (SKILL.md folders) before Claude Code, Codex, Cursor or Copilot loads them: name and description rules, strict frontmatter, broken file links, context-size warnings. Zero dependencies. | Python |
| **[subagentlint](https://github.com/celaldrg/subagentlint)**: Lint Claude Code subagent files (.claude/agents) before they fail silently: frontmatter typos, missing descriptions, duplicate names, broken hook scripts, description token budget. Zero-dependency Python CLI. | Python |
| **[hooklint](https://github.com/celaldrg/hooklint)**: Lint Claude Code hooks (settings.json, plugin hooks.json) before they silently fail: unknown events, case-sensitive matchers that match nothing, missing scripts, PreToolUse guards that exit 1 and never block. Rust, zero deps. | Rust |
| **[llmslint](https://github.com/celaldrg/llmslint)**: Lint llms.txt files before AI agents read them: structure, links, dead URLs and size, for a file, URL or whole domain. One Go binary. | Go |
| **[invisigrep](https://github.com/celaldrg/invisigrep)**: Find invisible Unicode (zero-width, bidi, tag-char smuggling) that hides prompt injections in AGENTS.md, rules files and code. Zero-dep Go CLI. | Go |
| **[tokmap](https://github.com/celaldrg/tokmap)**: See where your repo's tokens go before an AI agent reads it: a token budget map of files and folders, with lockfile/minified/generated hints and a CI budget check. Rust, zero deps. | Rust |

## Sector 03

<p align="center"><img src="assets/sector-03.svg" width="100%" alt="Sector 03: Git, what an agent leaves behind. 3 tools: agentprs, aiblame, aichurn." /></p>

<p align="center"><sub>Agents now write a real share of the code. These tools read git history to measure it:<br/>who wrote today’s lines, how fast agent code gets rewritten, and how agents’ pull requests fare.</sub></p>

| Repository | Language |
|---|---|
| **[agentprs](https://github.com/celaldrg/agentprs)**: How do AI agents' pull requests fare in your repo? Share, merge rate and time to merge for Copilot, Claude Code, Codex, Cursor, Devin, Jules & more vs humans. One Go binary, zero deps. | Go |
| **[aiblame](https://github.com/celaldrg/aiblame)**: How much of this repo did AI write? git blame for the agent era: Claude Code, Cursor, Copilot, Codex, Aider, Devin & more. One command, zero deps. | TypeScript |
| **[aichurn](https://github.com/celaldrg/aichurn)**: Does AI-written code get rewritten faster? Two-week churn, copy/paste and moved code from your git history, split by AI-assisted vs human commits. Single Rust binary. | Rust |

## Sector 04

<p align="center"><img src="assets/sector-04.svg" width="100%" alt="Sector 04: Everyday CLIs. 7 tools: shush, envguard, lockdiff, certpeek, todoage, csvglance, turkcekit." /></p>

<p align="center"><sub>Not every instrument is for agents. Small, single-purpose CLIs for the everyday parts of the job:<br/>secrets, env files, lockfiles, certificates, old TODOs, CSVs and Turkish text.</sub></p>

| Repository | Language |
|---|---|
| **[shush](https://github.com/celaldrg/shush)**: Cut the noise from command output before it reaches your AI agent. Errors always kept, full output one call away. MCP server + CLI for any agent. MIT. | TypeScript |
| **[envguard](https://github.com/celaldrg/envguard)**: Catch .env mistakes before they ship: missing keys vs .env.example, broken quotes, duplicates, and real secrets committed to example files. Zero-dependency Python CLI + pre-commit hook. | Python |
| **[lockdiff](https://github.com/celaldrg/lockdiff)**: Readable diffs for lockfiles: what was upgraded, downgraded, added or removed, with major bumps first. npm, pnpm, yarn, Cargo, Go, Poetry, uv, Pipenv, Composer, Bundler. Text, Markdown for PRs, JSON. Zero dependencies. | TypeScript |
| **[certpeek](https://github.com/celaldrg/certpeek)**: Check TLS certificates from the command line: expiry, hostname, trust chain and TLS version for one host or hundreds, with JSON output and exit codes for cron/CI. Single Go binary, stdlib only. | Go |
| **[todoage](https://github.com/celaldrg/todoage)**: How old are your TODOs? Finds TODO/FIXME/HACK comments in a git repo and uses git blame to show who wrote each one and how long ago. Oldest-first table, JSON, CI gate. Fast Rust CLI. | Rust |
| **[csvglance](https://github.com/celaldrg/csvglance)**: Know a CSV before you load it: types, missing values, distinct counts, ranges and top values for every column in one streaming pass. Detects delimiters, gzip, decimal commas. Parallel, single Go binary. | Go |
| **[turkcekit](https://github.com/celaldrg/turkcekit)**: Turkish text done right in Python: correct İ/ı casing, URL slugs, Turkish alphabetical sorting, numbers and lira amounts in words, 1.234,50 ₺ formatting. Zero dependencies, CLI included. | Python |

## Also in the Drawer

- [`awesome-turkiye-dev`](https://github.com/celaldrg/awesome-turkiye-dev): curated resources for developers in Türkiye: open-source projects, Turkish NLP, APIs and open data, communities, events and jobs.
- [`celaldrg.github.io`](https://github.com/celaldrg/celaldrg.github.io): source of my portfolio site, hand-written HTML/CSS with no framework and no JavaScript.

## What I work on

- **Tools for AI agents:** MCP servers that give agents better context with less noise
- **Developer tooling:** small single-binary CLIs that fit into CI, cron and pre-commit
- **Turkish developer ecosystem:** open data, local APIs and curated resources

**On the bench:** `TypeScript` `Python` `Go` `Rust` `JavaScript` `Node.js` `GitHub Actions` `Linux` `Git`

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/stack-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="assets/stack-light.svg" />
    <img src="assets/stack-light.svg" width="560" alt="TypeScript, Go, Rust, Python, JavaScript, Node.js, GitHub Actions, Linux and Git icons" />
  </picture>
</p>

## The Field Log

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/celaldrg/celaldrg/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/celaldrg/celaldrg/output/snake-light.svg" />
    <img src="https://raw.githubusercontent.com/celaldrg/celaldrg/output/snake-light.svg" width="100%" alt="A snake moving across my GitHub contribution graph and eating the squares in order" />
  </picture>
</p>

<p align="center"><sub>Every square is a day at the bench. A small GitHub Action redraws this log each night.</sub></p>

## Contributing

Issues and pull requests are welcome on any of these projects. Issues labeled
[`good first issue`](https://github.com/search?q=user%3Acelaldrg+label%3A%22good+first+issue%22+state%3Aopen&type=issues)
are a good place to start. My own tools are MIT-licensed unless noted; the unofficial editions of other projects keep their upstream licenses.

## Colophon

The twin at the top is made from one photograph of me: a face mesh, a few hundred thousand code
characters and particles, and a small behaviour engine for blinking, gaze and speech, all drawn
with three.js in the browser. The loop here is a twelve-second recording of it, with a still
frame for anyone who has reduced motion turned on. The boot screen, the transmission and the
sector strips are hand-written SVG animations with their fonts embedded, in the twin's own
palette: one green, and one red for when the signal drops. The tool covers come from each tool's
own README. The stack icons are from [skill-icons](https://github.com/tandpfun/skill-icons) (MIT)
and are stored here too. The field log is drawn from my contribution graph each night by
[Platane/snk](https://github.com/Platane/snk). No badge services, no counters, no third-party requests.

<p align="center"><sub>Türk geliştiriciler için açık kaynak araçlar</sub></p>
