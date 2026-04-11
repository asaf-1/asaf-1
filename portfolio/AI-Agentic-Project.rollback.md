# AI-Agentic-Project Portfolio Rollback

This file documents how to revert the `AI-Agentic-Project` card that was added to `portfolio/asaf-nuri-portfolio.html` and the later reordering of the side-project cards.

## Change Summary

- Added one new side-project card under the `GitHub Side Projects` section
- Reordered the side-project cards so stronger QA and infrastructure repos appear earlier
- Renamed `Mini-Projects-` to `side-projects` in the portfolio display only

## Files Affected

- `portfolio/asaf-nuri-portfolio.html`

## Rollback Options

### Option 1: Remove only the added card and restore the old order

Delete the `AI-Agentic-Project` block from the `GitHub Side Projects` section and restore the previous numbering and ordering for the remaining cards.

### Option 2: Restore from Git

If the change has already been committed, revert the commit that introduced the `AI-Agentic-Project` card.

If the change is still local, restore the previous file version with Git for:

- `portfolio/asaf-nuri-portfolio.html`

## Current Intended Order

- `Repo 01` `QA-Lead-Enterprise-Project`
- `Repo 02` `AI-Agentic-Project`
- `Repo 03` `jenkins-pipelines`
- `Repo 04` `GO-ParaBank`
- `Repo 05` `CrawlitChromeExtension`
- `Repo 06` `side-projects`
- `Repo 07` `Israelite-News-Hub`
- `Repo 08` `Ness-Project`
- `Repo 09` `Amiio-RealEstate-Project`

## Added HTML Block

```html
<div class="repo-card">
  <div class="repo-top">
    <div>
      <div class="repo-num">Repo 09</div>
      <div class="repo-name">AI-Agentic-Project</div>
    </div>
    <a href="https://github.com/asaf-1/AI-Agentic-Project" target="_blank" rel="noreferrer" class="repo-link">Open Repo</a>
  </div>
  <div class="repo-desc">Local-first agentic infrastructure demo showing how Playwright, Obsidian workflow, Docker, Jenkins, and public-safe repo rules can work together in one reusable QA portfolio project.</div>
  <div class="repo-tags">
    <span class="tech-tag">Node.js</span>
    <span class="tech-tag">Playwright</span>
    <span class="tech-tag">Docker</span>
    <span class="tech-tag">Jenkins</span>
    <span class="tech-tag">Obsidian</span>
  </div>
</div>
```
