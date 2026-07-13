# Personal Site Placeholder Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Create a single `index.html` placeholder page that shows DANIELDAVEY.CO.UK in bold caps at the top of an otherwise blank white page.

**Architecture:** One self-contained HTML5 file at the repo root. All styles live in a `<style>` block in `<head>`. No external dependencies, no JavaScript, no build step.

**Tech Stack:** HTML5, CSS (inline in `<style>` block)

---

### Task 1: Create index.html

**Files:**
- Create: `index.html`

- [ ] **Step 1: Create the file**

Create `index.html` at the repo root with this exact content:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Daniel Davey</title>
  <style>
    *, *::before, *::after {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background: #fff;
      font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
      padding: 40px 48px;
    }

    .name {
      display: inline-block;
      font-size: 12px;
      font-weight: 700;
      letter-spacing: 5px;
      color: #111;
      text-transform: uppercase;
      border-bottom: 1px solid #111;
      padding-bottom: 12px;
    }
  </style>
</head>
<body>
  <span class="name">danieldavey.co.uk</span>
</body>
</html>
```

- [ ] **Step 2: Verify in browser**

Open `index.html` directly in a browser (double-click the file). Confirm:
- White background, no margin/padding on the edges
- `DANIELDAVEY.CO.UK` appears top-left in small bold caps with wide letter-spacing
- A thin black rule runs under the text
- Nothing else on the page

- [ ] **Step 3: Commit and push**

```bash
git add index.html
git commit -m "Add placeholder index.html"
git push origin master
```
