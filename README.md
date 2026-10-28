<h1 align="center">Celalettin Durğaç</h1>

<p align="center">
  Computer engineer in Ankara, Türkiye. I build small, sharp developer tools:<br/>
  MCP servers for AI agents and CLIs that catch problems before they ship.
</p>

<p align="center">
  <a href="https://celaldrg.github.io"><img src="https://img.shields.io/badge/portfolio-celaldrg.github.io-111?style=flat-square" alt="Portfolio"/></a>
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
| [**awesome-turkiye-dev**](https://github.com/celaldrg/awesome-turkiye-dev) | ![Markdown](https://img.shields.io/badge/-Curated%20list-555?style=flat-square&logo=markdown&logoColor=white) | Curated resources for developers in Türkiye: open-source projects, Turkish NLP, APIs and open data, communities, events and jobs. |

Every project is MIT-licensed, has CI on every push, and ships with real example output in its README.

### Browser games

Small games that run in any browser, phone included. Vanilla JavaScript, no build step, game logic covered by `node --test` unit tests.

| Game | Live | What it is |
| --- | --- | --- |
| [**Chess**](https://github.com/celaldrg/chess-web) | [▶ play](https://celaldrg.github.io/chess-web/) | Full rules (castling, en passant, promotion, threefold, fifty-move) and an alpha-beta engine with 3 levels. PGN export. |
| [**Sapan**](https://github.com/celaldrg/sapan) | [▶ play](https://celaldrg.github.io/sapan/) | Physics slingshot game on Matter.js: 5 levels of crumbling castles, stars and level select. |
| [**Sudoku**](https://github.com/celaldrg/sudoku) | [▶ play](https://celaldrg.github.io/sudoku/) | Generator that guarantees a unique solution, solver, notes, hints and 3 difficulties. |
| [**2048**](https://github.com/celaldrg/2048) | [▶ play](https://celaldrg.github.io/2048/) | Sliding-tile puzzle with animations, multi-step undo and saved games. |
| [**Scientific Calculator**](https://github.com/celaldrg/calculator) | [▶ play](https://celaldrg.github.io/calculator/) | Own expression parser (no eval): functions, DEG/RAD, factorial, implicit multiplication, history. |
| [**Minesweeper**](https://github.com/celaldrg/minesweeper) | [▶ play](https://celaldrg.github.io/minesweeper/) | Three difficulties, safe first click, flags, chording and long-press on mobile. |
| [**Kanat**](https://github.com/celaldrg/kanat) | [▶ play](https://celaldrg.github.io/kanat/) | One-tap flying game with original art, rising difficulty and saved high score. |
| [**Breakout**](https://github.com/celaldrg/breakout) | [▶ play](https://celaldrg.github.io/breakout/) | Brick breaker with 3 levels, multi-ball and other power-ups, tunnel-free collisions. |
| [**Snake**](https://github.com/celaldrg/snake) | [▶ play](https://celaldrg.github.io/snake/) | Four speed levels, walls or wrap mode, swipe controls and an on-screen D-pad. |
| [**Tic-Tac-Toe**](https://github.com/celaldrg/tic-tac-toe) | [▶ play](https://celaldrg.github.io/tic-tac-toe/) | Unbeatable minimax AI, proven by an exhaustive test over every possible game. |
| [**Reversi**](https://github.com/celaldrg/reversi) | [▶ play](https://celaldrg.github.io/reversi/) | Rules checked against perft counts, a 3-level engine in a Web Worker with a perfect endgame solve, 3D disc flips. |
| [**Mangala**](https://github.com/celaldrg/mangala) | [▶ play](https://celaldrg.github.io/mangala/) | The traditional Turkish mancala game with its real capture rules and a 3-level alpha-beta opponent. |
| [**Four in a Row**](https://github.com/celaldrg/four-in-a-row) | [▶ play](https://celaldrg.github.io/four-in-a-row/) | Negamax with alpha-beta, a transposition table and iterative deepening, running in a Web Worker. |
| [**Memory**](https://github.com/celaldrg/memory) | [▶ play](https://celaldrg.github.io/memory/) | Card-matching game: three board sizes, solo or two players on one device, 18 original SVG symbols and 3D flips. |
| [**Maze**](https://github.com/celaldrg/maze) | [▶ play](https://celaldrg.github.io/maze/) | Perfect mazes from three generators (backtracker, Prim, Kruskal with union-find), five levels and a BFS solution path. |
| [**15 Puzzle**](https://github.com/celaldrg/15-puzzle) | [▶ play](https://celaldrg.github.io/15-puzzle/) | Sliding puzzle from 3×3 to 5×5: every shuffle is solvable, IDA* hints on 3×3 and a picture mode. |
| [**Tavla**](https://github.com/celaldrg/tavla) | [▶ play](https://celaldrg.github.io/tavla/) | Turkish backgammon against the computer (two levels) or a friend: bar entry, hitting, doubles, bearing off and mars. |
| [**Dama**](https://github.com/celaldrg/dama) | [▶ play](https://celaldrg.github.io/dama/) | Turkish draughts with flying kings and forced maximum captures, and an alpha-beta opponent in a Web Worker. |
| [**Adam Asmaca**](https://github.com/celaldrg/adam-asmaca) | [▶ play](https://celaldrg.github.io/adam-asmaca/) | Hangman with English and Turkish word lists that knows ı from i, an animated SVG drawing, hints and streaks. |
| [**Dokuz Taş**](https://github.com/celaldrg/dokuz-tas) | [▶ play](https://celaldrg.github.io/dokuz-tas/) | Nine men's morris with placing, moving and flying phases, a three-level computer opponent and drag, tap or keys. |
| [**Gomoku**](https://github.com/celaldrg/gomoku) | [▶ play](https://celaldrg.github.io/gomoku/) | Five in a row on a wooden 15×15 board: freestyle or exactly-five rule, alpha-beta AI with three levels in a Web Worker. |
| [**Pişti**](https://github.com/celaldrg/pisti) | [▶ play](https://celaldrg.github.io/pisti/) | The classic Turkish card game against the computer: piştis, full scoring with a round summary, matches to 51, 101 or 151. |
| [**Space Shooter**](https://github.com/celaldrg/space-shooter) | [▶ play](https://celaldrg.github.io/space-shooter/) | Vertical arcade shooter: ten scripted waves, a three-phase boss, a blaster plus three weapons that level up. |
| [**Word Search**](https://github.com/celaldrg/word-search) | [▶ play](https://celaldrg.github.io/word-search/) | 20 categories in English and Turkish, three sizes up to 15×15 in all 8 directions, every word hidden exactly once; drag, tap or keys. |
| [**Nonogram**](https://github.com/celaldrg/nonogram) | [▶ play](https://celaldrg.github.io/nonogram/) | Paint-by-numbers logic puzzles: 20 hand-made pictures up to 15×15 and endless random ones, each with exactly one solution and no guessing. |
| [**Bulls and Cows**](https://github.com/celaldrg/bulls-and-cows) | [▶ play](https://celaldrg.github.io/bulls-and-cows/) | Crack the secret number, or let a minimax solver crack yours (any 4-digit one in at most 7 guesses); 3 to 5 digits, notes and answer checking. |
| [**Amiral Battı**](https://github.com/celaldrg/amiral-batti) | [▶ play](https://celaldrg.github.io/amiral-batti/) | Sea battle against the computer: drag five ships onto your sea, three AI levels, optional salvo and touching-ship rules, saved battles. |
| [**Solitaire**](https://github.com/celaldrg/solitaire) | [▶ play](https://celaldrg.github.io/solitaire/) | Klondike with Draw 1 or 3, numbered deals, a solver that can deal only winnable games, unlimited undo, hints and auto-complete. |
| [**Dots and Boxes**](https://github.com/celaldrg/dots-and-boxes) | [▶ play](https://celaldrg.github.io/dots-and-boxes/) | 3×3 to 7×7 boards against a friend or a computer whose Hard level counts chains, plays the long-chain rule and double-deals. |
| [**Batak**](https://github.com/celaldrg/batak) | [▶ play](https://celaldrg.github.io/batak/) | The Turkish trick-taking game with bidding, against three computer players that bid, pick trumps and remember the cards played. |
| [**Okey**](https://github.com/celaldrg/okey) | [▶ play](https://celaldrg.github.io/okey/) | The Turkish tile game against three computer players that read the discards, with a draggable two-row rack, seven pairs and false jokers. |
| [**Air Hockey**](https://github.com/celaldrg/air-hockey) | [▶ play](https://celaldrg.github.io/air-hockey/) | Neon air hockey with swept collisions, a computer opponent on three levels that predicts wall bounces, and two players on one screen. |
| [**Go**](https://github.com/celaldrg/go-game) | [▶ play](https://celaldrg.github.io/go-game/) | Go on 9x9, 13x13 and 19x19 with superko, handicap, area scoring and a Monte Carlo tree search computer player in a Web Worker. |

### Visualizers, simulations and tools

Built the same way: vanilla JavaScript, no build step, logic covered by `node --test` unit tests.

| Tool | Live | What it is |
| --- | --- | --- |
| [**Sorting Visualizer**](https://github.com/celaldrg/sorting-visualizer) | [▶ open](https://celaldrg.github.io/sorting-visualizer/) | Ten sorting algorithms step by step, with live counters, narration and complexity notes. |
| [**Pathfinding Visualizer**](https://github.com/celaldrg/pathfinding-visualizer) | [▶ open](https://celaldrg.github.io/pathfinding-visualizer/) | A*, Dijkstra, BFS, greedy search and DFS on a grid you draw, plus two maze generators. |
| [**Game of Life**](https://github.com/celaldrg/game-of-life) | [▶ open](https://celaldrg.github.io/game-of-life/) | Conway's Life on a canvas you draw on: zoom and pan, B/S rule presets such as HighLife and Day & Night, eight classic patterns. |
| [**Typing Test**](https://github.com/celaldrg/typing-test) | [▶ open](https://celaldrg.github.io/typing-test/) | Typing speed test with English and Turkish word lists: WPM, accuracy, consistency and a per-second chart. |
| [**Pixel Art Editor**](https://github.com/celaldrg/pixel-art) | [▶ open](https://celaldrg.github.io/pixel-art/) | Pixel sprites with mouse, pen or touch: fill, line, rectangle, mirror drawing, undo and PNG export up to 16×. |
| [**Focus Timer**](https://github.com/celaldrg/focus-timer) | [▶ open](https://celaldrg.github.io/focus-timer/) | Focus sessions with short and long breaks, drift-free timing, a task list with estimates and a 7-day chart. |
| [**Drum Machine**](https://github.com/celaldrg/drum-machine) | [▶ open](https://celaldrg.github.io/drum-machine/) | An 8-track, 16-step drum machine with synthesized drums, swing, patterns A–D, a song chain and share links. |
| [**Web Piano**](https://github.com/celaldrg/piano) | [▶ open](https://celaldrg.github.io/piano/) | A piano for touch and keyboard: four synth sounds, sustain, a recorder that keeps 8 takes and a Learn mode. |
| [**Kanban Board**](https://github.com/celaldrg/kanban) | [▶ open](https://celaldrg.github.io/kanban/) | A private Kanban board: drag and drop for mouse, touch and keyboard, WIP limits, filters and undo/redo. |
| [**Color Palette Generator**](https://github.com/celaldrg/color-palette) | [▶ open](https://celaldrg.github.io/color-palette/) | Harmonious palettes in OKLCH with locks, WCAG contrast checks, 50–950 shade scales and CSS, JSON or Tailwind export. |
| [**Markdown Editor**](https://github.com/celaldrg/markdown-editor) | [▶ open](https://celaldrg.github.io/markdown-editor/) | Live-preview Markdown with its own parser: synced scrolling, code highlighting, a table of contents and .md/.html export. |
| [**QR Code Generator**](https://github.com/celaldrg/qr-generator) | [▶ open](https://celaldrg.github.io/qr-generator/) | QR codes encoded from scratch with Reed–Solomon error correction: links, Wi-Fi, e-mail, SMS and vCards, PNG or SVG. |
| [**Unit Converter**](https://github.com/celaldrg/unit-converter) | [▶ open](https://celaldrg.github.io/unit-converter/) | 136 units in 14 categories with exact definitions; type “5 ft 3 in to cm”, see every unit at once, keep favorites. |
| [**Password Generator**](https://github.com/celaldrg/password-generator) | [▶ open](https://celaldrg.github.io/password-generator/) | Unbiased passwords and English or Turkish passphrases, an honest strength meter with crack times, and a checker for your own password. |
| [**JSON Formatter**](https://github.com/celaldrg/json-formatter) | [▶ open](https://celaldrg.github.io/json-formatter/) | Exact line and column errors, 20-digit numbers kept as written, a relaxed mode that repairs, a fast tree with JSONPath queries, and a diff. |
| [**Loan Calculator**](https://github.com/celaldrg/loan-calculator) | [▶ open](https://celaldrg.github.io/loan-calculator/) | Equal installments or equal principal with tax, fees, grace months and extra payments; schedule, chart, two offers and an affordability solver. |
| [**Regex Tester**](https://github.com/celaldrg/regex-tester) | [▶ open](https://celaldrg.github.io/regex-tester/) | Live highlighting with colored named groups, a plain-language explanation of every token, replace and split previews, shareable links. |
| [**Function Plotter**](https://github.com/celaldrg/function-plotter) | [▶ open](https://celaldrg.github.io/function-plotter/) | Its own parser, up to six functions with sliders, symbolic derivatives, roots, extrema, intersections and shaded integrals. |
| [**Fractal Explorer**](https://github.com/celaldrg/fractal-explorer) | [▶ open](https://celaldrg.github.io/fractal-explorer/) | Mandelbrot, Julia, Burning Ship, Tricorn and Multibrot, rendered progressively on Web Workers, with a live Julia picker. |
| [**Text Diff**](https://github.com/celaldrg/text-diff) | [▶ open](https://celaldrg.github.io/text-diff/) | Line, word and character diffs with a linear-space Myers algorithm, a side-by-side view, unified patches and a patch applier. |
| [**Mini Sheet**](https://github.com/celaldrg/mini-sheet) | [▶ open](https://celaldrg.github.io/mini-sheet/) | A small spreadsheet with its own formula parser (no eval), 25 functions, a dependency graph, undo/redo and CSV import and export. |
| [**Fourier Drawing**](https://github.com/celaldrg/fourier-drawing) | [▶ open](https://celaldrg.github.io/fourier-drawing/) | Draw any closed shape and watch a chain of rotating circles trace it, computed with an FFT; choose the number of terms and export SVG. |

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

<p align="center"><sub>Türk geliştiriciler için açık kaynak araçlar · Ankara</sub></p>
