<p align="center">
  <img src="https://img.shields.io/badge/Built%20for-Lenny's%20Data%20Community-6c5ce7?style=for-the-badge&logoColor=white" alt="Built for Lenny's Data Community">
  <img src="https://img.shields.io/badge/Powered%20by-Claude-f97316?style=for-the-badge&logoColor=white" alt="Powered by Claude">
  <img src="https://img.shields.io/badge/100%25-Client--Side-00cec9?style=for-the-badge" alt="100% Client-Side">
</p>

<h1 align="center">Product Wisdom Explorer</h1>

<p align="center">
  <strong>Interactive tools that turn podcast and newsletter wisdom from Lenny Rachitsky into explorable, visual experiences.</strong>
</p>

<p align="center">
  Two standalone web apps — no servers, no APIs, no build steps. Just open and explore.
</p>

---

## The Apps

### 1. Product Wisdom Graph

> An interactive knowledge graph that maps the frameworks, mental models, and connections between 50+ podcast guests.

Explore how ideas connect across episodes. See which guests share frameworks, what topics cluster together, and discover unexpected links between product management concepts. Click any node to dive into quotes, context, and related ideas.

**Features:**
- Force-directed graph with real-time physics simulation
- Filter by topic, guest, framework, or tactical insight
- Search across all nodes and connections
- Detail panel with original quotes and sources
- Responsive dark theme

<p align="center">
  <em>[ Screenshot: wisdom-graph/screenshot.png ]</em>
</p>

---

### 2. PM Career Advisor

> An interactive career advisor that surfaces real, specific advice from podcast guests — matched to your situation.

Ask about career transitions, managing up, landing a PM role, navigating ambiguity, or any product management challenge. Get back curated wisdom from people who've been there — with full attribution and episode links.

**Features:**
- Conversational interface with topic-based exploration
- Real quotes from real guests (not AI-generated advice)
- Career stage and topic filtering
- Source attribution for every piece of advice

<p align="center">
  <em>[ Screenshot: career-advisor/screenshot.png ]</em>
</p>

---

## Try It

No install. No dependencies. No build step.

```
git clone https://github.com/quest-commits/lennys-data-explorer.git
cd lennys-data-explorer
```

Then open any of these in your browser:

| App | File |
|-----|------|
| Hub page | `index.html` |
| Wisdom Graph | `wisdom-graph/index.html` |
| PM Career Advisor | `career-advisor/index.html` |

Or just visit the **[GitHub Pages site](https://quest-commits.github.io/lennys-data-explorer/)** (once deployed).

---

## How It Was Built

These apps were built in a single session using **[Claude](https://claude.ai)** and the **[Lenny's Data starter pack](https://www.lennysdata.com)** — a public dataset of podcast transcripts and newsletter posts from [Lenny Rachitsky](https://www.lennyspodcast.com).

The process:
1. Loaded podcast transcripts and newsletter posts from the starter pack
2. Used Claude to extract frameworks, mental models, quotes, and guest relationships
3. Built self-contained HTML/CSS/JS apps with no external dependencies
4. Everything runs client-side — the data is embedded directly in the HTML

**Tech stack:** Vanilla HTML, CSS, JavaScript, Canvas API. Zero dependencies.

---

## Credits

- **[Lenny Rachitsky](https://www.lennysnewsletter.com)** — for building an incredible body of product management knowledge through his podcast and newsletter
- **[lennysdata.com](https://www.lennysdata.com)** — for making the data open and accessible to builders
- **[Claude by Anthropic](https://claude.ai)** — AI assistant used to analyze transcripts and build the apps
- All podcast guests whose wisdom powers these tools

---

<p align="center">
  <br>
  <img src="https://img.shields.io/badge/Built%20for%20the-Lenny's%20Data%20Community-6c5ce7?style=flat-square&labelColor=1a1a2e" alt="Lenny's Data Community">
  <br><br>
  <em>Part of the ecosystem of projects built on <a href="https://www.lennysdata.com">lennysdata.com</a></em>
  <br>
  <em>Want the full dataset? <a href="https://www.lennysdata.com">Get access here.</a></em>
</p>
