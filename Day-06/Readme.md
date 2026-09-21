# Day 6 — Debugging Mindset

## Topics

* Debugging mindset
* Expected vs Actual behavior
* Finding the source of incorrect content
* Translating business requirements into website content
* Testing changes
* Difference between content bugs and code bugs

## Learning

Today I practiced identifying a problem by comparing the expected result with the actual result.

The Services section contained placeholder content instead of describing the real B2B services offered by the business.

I traced the incorrect content back to the HTML and identified the relevant `<p>` elements.

The business requirement was then translated into three services:

* Custom Material Selection
* Custom Material Ratio
* Fast B2B Delivery

I updated the HTML and tested the website in the browser.

## Debugging Workflow

```text
Expected → Actual → Find Source → Fix → Verify
```

## Practical Work

### Problem

The Services section contained placeholder text such as:

```text
Short description of your first service.
```

### Expected

The section should explain the actual flexible B2B services offered by the business.

### Actual

The section displayed generic placeholder descriptions.

### Fix

Updated the HTML with business-specific services and descriptions.

### Testing

Verified the Services section in the browser.

Result:

* All three services were visible.
* The content was displayed correctly.
* The existing page layout remained intact.

## Important Learning

A bug does not always mean broken code.

Today's issue was a **content bug** rather than a demonstrated code bug.

I also learned that removing some HTML tags does not necessarily create a visible error because browsers can recover from certain invalid or incomplete HTML structures.

## AI-Assisted Development

I did not use AI to blindly fix the problem.

I first:

1. Identified the unexpected result.
2. Found where the content existed in the HTML.
3. Understood the actual business requirement.
4. Made the change.
5. Tested the result.

## Skill State

* Debugging Mindset — **Practiced**
* Requirements Understanding — **Applied**
* HTML Modification — **Applied**
* Testing — **Applied**
* Code Debugging — **Introduced, not demonstrated**

## Evidence

* Found the placeholder content.
* Located its source in the HTML.
* Replaced it with relevant B2B service content.
* Tested the result in the browser.
* Distinguished a content bug from a code bug.

## Status

**Day 6 — Complete**
