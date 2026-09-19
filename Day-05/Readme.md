# Day 5 — AI Code Editors & AI-Assisted Development

## Topics Covered

* AI Code Editors
* Cursor
* AI-assisted development
* Project inspection
* AI-generated code modification
* Scoped changes
* Testing and verification
* Developer responsibility when using AI

## Roadmap

**ROADMAP:** The curriculum includes AI-assisted Development and AI Code Editors as part of the AI Full-Stack Developer learning path.

**Day 5 focus:** Practical use of Cursor as an AI coding editor and application of AI-assisted development principles.

---

## Key Learning

### AI Code Editors

An AI code editor combines a normal development environment with integrated AI assistance.

Cursor was used to work directly with the existing project instead of creating a separate practice project.

The important skill is not simply using an AI editor. The goal is to understand how to use AI while keeping control over the project and code.

---

## AI-Assisted Development Workflow

The workflow practiced today was:

**Understand the Project → Inspect Current State → Make the Necessary Change → Test the Result**

The developer remains responsible for verifying the AI-generated changes.

AI can assist with:

* Understanding existing code
* Identifying relevant files and structures
* Making requested modifications
* Explaining changes

The developer decides:

* What should be changed
* What should remain unchanged
* Whether the change is correct
* Whether the result passes testing

---

## Practical Learning

### Step 1 — Open Existing Project

Opened the existing:

`AI-Full-Stack-100-Days`

project in Cursor.

The project contained the previous daily records and website files.

---

### Step 2 — Inspect Before Editing

Cursor was instructed:

> Inspect the existing product section in `Day-01/index.html`. Do not modify any files yet. Identify where the product information is defined and briefly explain the structure you found.

Cursor identified that:

* Product information was stored directly in HTML.
* The product section was inside the `Trending Products` section.
* Products were represented using `<li>` elements.
* Existing products were T-Shirt, Jeans, and Hoodie.
* The product information included price, sizes, and availability.
* The section had an existing HTML structure that needed to be understood before modification.

Cursor also identified other existing issues, but those were **not changed** because they were outside the requested task.

---

### Step 3 — Define a Controlled Change

The requested modification was to add one new product:

**Formal Pants — ₹1,799 — Sizes: M, L, XL — Available**

The instruction required:

* Preserve the existing product structure.
* Preserve the existing layout and styling.
* Keep all existing products.
* Do not modify unrelated sections.

---

### Step 4 — AI Makes the Change

Cursor added one additional product item:

`Formal Pants — ₹1,799 — Sizes: M, L, XL — Available`

The existing:

* T-Shirt
* Jeans
* Hoodie

were preserved.

Cursor also reported that the header, About section, footer, button, and CSS were left untouched.

---

### Step 5 — Inspect the Result

The generated HTML was inspected to verify that the requested product was added without unnecessary modifications.

This reinforced the principle:

**AI output must be inspected before it is considered correct.**

---

### Step 6 — Test the Actual Website

Cursor's browser tool could not load the local `file://` page.

Instead, the HTML file was opened directly in the browser.

The rendered webpage was checked.

### Test Result

* Formal Pants appeared ✅
* Existing products remained ✅
* Product structure was preserved ✅
* Layout was preserved ✅
* Styling was preserved ✅
* Other page sections remained unchanged ✅

The actual browser verification confirmed that the requested change worked.

---

## Important Learning

### AI Can Discover Problems Without Being Told to Fix Them

During inspection, Cursor identified other issues in the existing project.

However, those issues were not automatically fixed.

This reinforced an important developer principle:

> **AI can identify problems; the developer decides which problems should be changed.**

Avoid expanding the scope of a task unnecessarily.

---

## Cursor vs VS Code

Also learned that the same development work can be performed in VS Code.

VS Code is a general-purpose code editor, while Cursor provides a development environment with integrated AI assistance.

The goal is not to replace understanding with AI.

The goal is to use AI to make development more efficient while maintaining developer control.

---

## Skills Demonstrated

### AI-Assisted Development

**Level: Applied**

Used Cursor to inspect an existing project, make a controlled change, and verify the result.

### Project Inspection

**Level: Applied**

Used AI to understand the existing product section before making modifications.

### Scoped Modification

**Level: Applied**

Added only the requested product while preserving existing content and structure.

### Testing

**Level: Applied**

Opened the actual HTML page in a browser and verified the rendered result.

### Developer Judgment

**Level: Applied**

Distinguished between issues discovered by AI and changes that were actually required for the current task.

---

## Evidence

* Opened the existing project in Cursor.
* Inspected the existing product section before editing.
* Added one new product using a controlled instruction.
* Preserved the existing products and page structure.
* Tested the actual webpage in a browser.
* Verified that the requested change worked.
* Verified that unrelated parts of the page were not changed.

---

## Key Takeaways

1. AI should understand the project before making changes.
2. Inspect the current state before editing.
3. Give AI a clearly scoped task.
4. Do not allow unrelated changes.
5. Inspect AI-generated modifications.
6. Test the actual application.
7. The developer makes the final decision about whether the result is correct.

### Core Principle

**Understand → Inspect → Change → Test → Verify**

---

## Status

**Day 5 — Complete**
