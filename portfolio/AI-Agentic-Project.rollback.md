# AI-Agentic-Project Portfolio Rollback

This file documents how to revert the `AI-Agentic-Project` card that was added to `portfolio/asaf-nuri-portfolio.html`.

## Change Summary

- Added one new side-project card under the `GitHub Side Projects` section
- Left all existing side-project cards unchanged
- Added the new card as `Repo 09`

## Files Affected

- `portfolio/asaf-nuri-portfolio.html`

## Rollback Options

### Option 1: Remove only the added card

Delete the `Repo 09` block for `AI-Agentic-Project` from the `GitHub Side Projects` section and keep the rest of the file unchanged.

### Option 2: Restore from Git

If the change has already been committed, revert the commit that introduced the `AI-Agentic-Project` card.

If the change is still local, restore the previous file version with Git for:

- `portfolio/asaf-nuri-portfolio.html`

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
