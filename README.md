<div align="center">

<a href="https://usethrone.dev">
  <img src="https://usethrone.dev/assets/og-image.png" alt="Throne: paste an MCP server, get the verdict" width="760"/>
</a>

<p>
  <a href="https://usethrone.dev"><img src="https://img.shields.io/badge/Building-Throne-1F9D55?style=flat-square&logo=icloud&logoColor=white"/></a>
  &nbsp;
  <a href="https://github.com/marketplace/actions/throne-mcp-gate"><img src="https://img.shields.io/badge/Marketplace-Throne%20MCP%20Gate-0E0E10?style=flat-square&logo=github&logoColor=white"/></a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=TaimoorKhan10&style=flat-square&color=1F9D55&label=Profile+Views" />
</p>

</div>

---

## Hi, I'm Taimoor

I'm building **[Throne](https://usethrone.dev)**, the release gate for MCP servers.

Every MCP directory today lists self-reported entries. Nobody runs the servers. Throne does: it executes each server in a disposable microVM, tests it against real client behaviour (Claude Code and Cursor), scans the source for security issues, and publishes the evidence. It is the first MCP registry where every verdict is backed by a real execution.

### What I'm building

- 🏰 **[usethrone.dev](https://usethrone.dev)** is the MCP registry of record. Every scanned server gets a public evidence page with its verdict, the full protocol run, and the security review.
- ⚙️ **[usethrone/throne-ci](https://github.com/usethrone/throne-ci)** is a GitHub Action that runs the full scan on every pull request and blocks merges that would break real clients.
- 🛡️ Two independent verdicts per server: client compatibility and a static security review. They are never mixed into one number.

### How it is built

Python, FastAPI, Firecracker microVMs on Fly Machines, and Postgres, with a client engine calibrated from recorded Claude Code and Cursor traffic. One disposable VM per scan, destroyed after it. Nothing outlives a run.

### Reach me

<p>
  <a href="https://usethrone.dev"><img src="https://img.shields.io/badge/usethrone.dev-1F9D55?style=for-the-badge&logo=icloud&logoColor=white"/></a>
  &nbsp;
  <a href="mailto:hello@usethrone.dev"><img src="https://img.shields.io/badge/hello@usethrone.dev-0E0E10?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  &nbsp;
  <a href="https://linkedin.com/in/taimoor-khan-87501226a"><img src="https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

<sub>Previously: machine learning and LLM systems engineering. Now all in on Throne.</sub>
