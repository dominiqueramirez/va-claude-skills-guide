# Claude Skills Training Module

## What This Is
A single-page VA-branded training guide covering how to create and use custom Claude skills (SKILL.md files) with GitHub Copilot in VS Code.

## How to View
Open `index.html` directly in a browser — no build step or server required. It's a self-contained HTML file with all styling inline.

## How to Edit
Edit `index.html` directly. Each section is a `<div class="section-card">` block. Replace the placeholder banners with your actual training content.

### Section structure
Each section follows this pattern:
```html
<div class="section-card" id="section-id">
  <div class="section-card-header">
    <span class="step-num">Section N</span>
    <h2>Section Title</h2>
  </div>
  <div class="section-card-body">
    <!-- Your content here -->
  </div>
</div>
```

## Styling
Uses the same VA Brand style (navy/blue/gold palette, Source Sans Pro font, section cards) as the `github-copilot` training module. All CSS is embedded in the `<style>` tag — no external dependencies.

## Current Sections (all placeholder)
1. What Are Skills?
2. Skill File Structure
3. Creating Your First Skill
4. Triggers & Invocation
5. Example Skills
6. Best Practices
7. Troubleshooting
