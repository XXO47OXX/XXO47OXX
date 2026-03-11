## Hi, I'm XXO47OXX

Building tools at the intersection of **AI** and **web infrastructure**.

---

### Featured Project

<table>
<tr>
<td width="600">

**[spa-reader-mcp](https://github.com/XXO47OXX/spa-reader-mcp)** — MCP server that renders JavaScript SPAs and extracts LLM-ready Markdown

[![npm version](https://img.shields.io/npm/v/spa-reader-mcp.svg)](https://www.npmjs.com/package/spa-reader-mcp)
[![npm downloads](https://img.shields.io/npm/dm/spa-reader-mcp.svg)](https://www.npmjs.com/package/spa-reader-mcp)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Traditional web scrapers fail on SPAs because content is rendered by JavaScript after page load. **spa-reader-mcp** launches headless Chromium via Playwright, waits for full render, then extracts clean Markdown using Mozilla Readability + Turndown.

**Highlights:**
- Singleton browser with per-request isolation
- SSRF protection & selector injection prevention
- 100 KB output cap with line-boundary truncation
- [Model Context Protocol](https://modelcontextprotocol.io) compatible

```bash
npx spa-reader-mcp          # zero-install, just works
```

</td>
</tr>
</table>

---

### Tech Stack

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

---

<sub>Published 2026-03-11</sub>
