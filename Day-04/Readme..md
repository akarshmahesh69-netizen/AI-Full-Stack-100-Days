# Day 4 — Vibe Coding Principles

## Topics Covered

* Vibe Coding Principles
* AI-assisted development
* Scoped AI instructions
* Inspecting AI-generated changes
* Testing and verification
* Preserving existing functionality

## Key Learning

### Vibe Coding

Vibe Coding means using AI as a development partner while the developer remains responsible for understanding, inspecting, testing, debugging, modifying, and explaining the code.

Core workflow:

**Prompt → Understand → Inspect → Run → Test → Debug → Modify → Explain**

### Scoped Changes

AI should be given clear instructions about:

* What to change
* What must remain unchanged
* The expected result

This helps prevent unnecessary modifications to working parts of the application.

### Important Principle

**Small problem → Small instruction → Small change → Test**

AI-generated code is not automatically correct. The developer must verify the result.

## Practical Learning

### Website Modification

The existing hero heading was:

`Akarsh Business`

The required change was:

`SCNC — Premium Formal Wear`

Instruction given to AI:

> Change only the main heading from `Akarsh Business` to `SCNC — Premium Formal Wear`. Do not modify any other content, styling, buttons, sections, or layout.

### Testing

After AI made the change, I:

* Inspected the modification
* Opened the webpage in the browser
* Verified the hero heading changed
* Checked that the product section was unchanged
* Checked that buttons, layout, and styling were unchanged

### Result

The requested change worked correctly without unintended changes.

## Evidence

* Created a precise AI modification instruction
* Applied a controlled website change
* Inspected AI-generated output
* Tested the webpage in the browser
* Verified existing functionality remained unchanged
* Created a Git checkpoint for the Day 4 work

## Git / GitHub

Day 4 work was committed and pushed to GitHub.

Commit message:

`Practice Day 4 vibe coding`

## Skills Demonstrated

* **AI-Assisted Development:** Applied
* **Vibe Coding:** Applied
* **Requirement Control:** Applied
* **Testing:** Practiced
* **Debugging Mindset:** Introduced / Practiced

## Key Takeaways

* AI is a development assistant, not the final authority.
* Give precise and scoped instructions.
* Protect existing working functionality.
* Inspect and test AI-generated changes.
* Fix unintended changes instead of rebuilding unnecessarily.

## Status

**Day 4 — Complete**
