# Emeritus LMS Specialist — Technical Assessment

[![Candidate: Rohit Srivastava](https://img.shields.io/badge/Candidate-Rohit%20Srivastava-00875a?style=for-the-badge)](https://github.com/rohit2215)
[![Role: LMS Specialist](https://img.shields.io/badge/Role-LMS%20Specialist-111827?style=for-the-badge)](https://emeritus.org)
[![W3C Valid & Accessible](https://img.shields.io/badge/Accessibility-WCAG%202.1%20AA%20Compliant-00875a?style=for-the-badge)]()

---

## 📌 Overview

This repository contains the complete submission for the **Emeritus LMS Specialist Technical Assessment**. All tasks across all three sections have been authored with semantic, accessible HTML5, responsive CSS3, and strict adherence to the Emeritus design language and brand guidelines.

- **Candidate Name:** Rohit Srivastava
- **Role:** LMS Specialist
- **Repository:** [rohit2215/LMS-Assignment](https://github.com/rohit2215/LMS-Assignment)
- **Target Organization:** [Emeritus](https://emeritus.org)

---

## 📂 Repository Structure

```plaintext
LMS-Assignment/
├── section-1/                          # Section I: Basic HTML & CSS Coding (70 Points)
│   ├── images/
│   │   └── apple.png                   # Custom image asset for Q9
│   ├── q1_welcome_edutech.html         # Q1: Accessible Edutech Welcome Webpage (10 pts)
│   ├── q2_link_tooltip.html            # Q2: OpenAI Link with Hover Tooltip in New Tab (5 pts)
│   ├── q3_faculty_table.html           # Q3: Accessible Faculty Details Table (5 pts)
│   ├── q4_accordion.html               # Q4: Accessible 3-Section CSS Accordion (10 pts)
│   ├── q5_tabs.html                    # Q5: Accessible 3-Tab Interface (10 pts)
│   ├── q6_debug_spacing.html           # Q6: Debug Spacing in Nested Lists (5 pts)
│   ├── q7_nested_list.html             # Q7: Multi-Level Nested List Hierarchy (5 pts)
│   ├── q8_code_formatting.html         # Q8: Monospace Preformatted Text Block (5 pts)
│   ├── q9_apple_layout.html            # Q9: Tableless Media Object Layout (5 pts)
│   └── q10_shadow_box.html             # Q10: Tableless CSS Drop-Shadow Container (10 pts)
│
├── section-2/                          # Section II: Multiple Choice Questions (10 Points)
│   ├── answers.md                      # Detailed MCQ solutions with rationale
│   └── mcqs.html                       # Interactive MCQ assessment portal
│
├── section-3/                          # Section III: Free Form Coding (20 Points)
│   ├── q1_features_page.html           # Q1: Full-page website with lists & header separation
│   └── q2_ten_html_tags.html           # Q2: 16+ semantic HTML tags with "How & Where" guides
│
├── Rohit_Srivastava_Emeritus_LMS_Specialist_Test.html  # Single Consolidated Submission Document
└── README.md                           # Documentation & testing walkthrough
```

---

## 📑 Detailed Section Breakdown

### Section I: Basic HTML & CSS Coding (70 Points)

| # | Question & Objective | Points | Source File | Key Technical Implementations |
| :-: | :--- | :-: | :--- | :--- |
| **Q1** | **Accessible Edutech Welcome Page** | 10 | [`section-1/q1_welcome_edutech.html`](section-1/q1_welcome_edutech.html) | `<h1>Welcome to edutech</h1>`, edutech explanation lead paragraph, responsive 6-card benefits grid, Emeritus color palette (`#00875a`), WCAG accessibility landmarks. |
| **Q2** | **OpenAI Link with Tooltip** | 5 | [`section-1/q2_link_tooltip.html`](section-1/q2_link_tooltip.html) | `target="_blank"` with `rel="noopener noreferrer"`, dual native `title="Visit OpenAI website"` and interactive CSS hover/focus tooltip bubble. |
| **Q3** | **Accessible Faculty Table** | 5 | [`section-1/q3_faculty_table.html`](section-1/q3_faculty_table.html) | Semantic `<table>` with `<caption>Faculty details</caption>`, 4 column headers (`<th scope="col">`), and 4 populated rows of academic profiles with avatar photos. |
| **Q4** | **3-Section CSS Accordion** | 10 | [`section-1/q4_accordion.html`](section-1/q4_accordion.html) | Built using native grouped `<details name="curriculum-accordion">` and `<summary>`. Clicking any section expands it and collapses the others; clicking again collapses it. 100% accessible. |
| **Q5** | **3-Tab Interface** | 10 | [`section-1/q5_tabs.html`](section-1/q5_tabs.html) | Program Overview, Comprehensive Syllabus, and Faculty tabs. Pure CSS visibility toggling (`:checked ~ .tab-panels .tab-panel { display: block; }`) with ARIA roles. |
| **Q6** | **Debug Nested List Spacing** | 5 | [`section-1/q6_debug_spacing.html`](section-1/q6_debug_spacing.html) | Eliminated default browser margins (`1em`) on `<p>` and `<ul>` by applying `style="margin: 0px;"`, removing the unwanted vertical gaps. Includes live side-by-side comparison. |
| **Q7** | **Multi-Level Nested List** | 5 | [`section-1/q7_nested_list.html`](section-1/q7_nested_list.html) | Level 1 in red with disc bullets, Level 2 in black with circle bullets (`list-style-type: circle`), and Level 3 in black with square bullets (`list-style-type: square`). |
| **Q8** | **Preformatted Monospace Block** | 5 | [`section-1/q8_code_formatting.html`](section-1/q8_code_formatting.html) | Replicated light-grey rounded box (`#f1f3f5`) with monospace preserved multi-line formatting using semantic `<pre><code>`. |
| **Q9** | **Tableless Media Layout** | 5 | [`section-1/q9_apple_layout.html`](section-1/q9_apple_layout.html) | Modern CSS Flexbox media object layout placing the custom apple photo on the left and description text on the right without HTML tables. |
| **Q10** | **Tableless Shadow Structure** | 10 | [`section-1/q10_shadow_box.html`](section-1/q10_shadow_box.html) | Modern CSS drop-shadow container (`box-shadow: 0 10px 25px -3px rgba(0,0,0,0.15)`) with rounded corners (`border-radius: 12px;`) containing spaced text lines without tables. |

---

### Section II: Multiple Choice Questions (10 Points)

Complete solutions with technical rationale are documented in [`section-2/answers.md`](section-2/answers.md) and interactively in [`section-2/mcqs.html`](section-2/mcqs.html):

1. **Hyperlink tag:** **`b. <a>`** — Anchor tag with `href` creates hyperlinks.
2. **Tag to render an image:** **`a. img`** — Standard HTML element for image rendering; `src` is an attribute.
3. **Root element of HTML document:** **`a. <html>`** — Represents the root element enclosing all other tags.
4. **Empty tag in HTML:** **`b. An empty tag does not require a closing tag`** — Void elements (`<img>`, `<br>`, `<hr>`) have no closing tag.
5. **Correct about HTML:** **`b. HTML uses tags defined within the language.`** — Predefined by W3C/WHATWG specs.
6. **Survey has one/more correct answer:** **`a. True`** — LMS surveys support single-select and multi-select responses.
7. **“`<h1>`” tag used for smallest heading style:** **`b. False`** — `<h1>` is the largest heading style; `<h6>` is the smallest.
8. **“`<caption>`” tag is used for:** **`c. defines a table caption`** — Reserved specifically for accessible `<table>` titles.
9. **True about HTML tags:** **`b. Are not case sensitive`** — HTML parser is case-insensitive, though lowercase is recommended.
10. **Property used to change font of text:** **`a. font-family`** — Sets the prioritized font family list in CSS.

---

### Section III: Free Form Coding (20 Points)

| # | Question & Objective | Points | Source File | Key Technical Implementations |
| :-: | :--- | :-: | :--- | :--- |
| **Q1** | **Features Webpage** | 10 | [`section-3/q1_features_page.html`](section-3/q1_features_page.html) | Full-page layout with custom background (`#f4fbf7`), `<h1>Welcome to My Website</h1>` with distinct green header separation, `<h2>Explore the Features</h2>`, 3-item unordered list, 3-item ordered list, and a paragraph with nested bullet points. |
| **Q2** | **Demonstration of HTML Tags** | 10 | [`section-3/q2_ten_html_tags.html`](section-3/q2_ten_html_tags.html) | Live demonstration of 16+ semantic HTML tags (`<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<h1>`-`<h3>`, `<mark>`, `<strong>`, `<em>`, `<blockquote>`, `<cite>`, `<ul>`, `<ol>`, `<li>`, `<table>`, `<caption>`, `<th>`, `<td>`, `<form>`, `<input>`, `<button>`, `<time>`, `<footer>`). Includes in-depth **How it is used** and **Where it is used in LMS** guides for each tag. |

---

## ♿ Accessibility Standards (WCAG 2.1 AA)

All implementations adhere strictly to the assignment's **"Accessible / Barrier-Free"** requirement:
- **Semantic HTML5:** Native landmark elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **Keyboard Usability:** Full keyboard tab-stop navigation with prominent `:focus-visible` outlines.
- **Screen Reader Compatibility:** Proper ARIA roles (`role="tablist"`, `role="tab"`, `role="tabpanel"`, `role="region"`), explicit table `<caption>`, and descriptive `alt` attributes.
- **Color Contrast:** High text-to-background contrast ratios exceeding the WCAG 2.1 AA minimum of 4.5:1.

---

## 🚀 How to Run & Preview Locally

Clone the repository and open any file in your default browser:

```bash
# Clone the repository
git clone https://github.com/rohit2215/LMS-Assignment.git
cd LMS-Assignment

# Open individual questions (macOS)
open section-1/q1_welcome_edutech.html
open section-1/q4_accordion.html
open section-2/mcqs.html
open section-3/q1_features_page.html

# Open the unified single submission document
open Rohit_Srivastava_Emeritus_LMS_Specialist_Test.html

# Or start a local lightweight web server
python3 -m http.server 8000
# Visit http://localhost:8000 in your browser
```

---

## 👤 Author Information

- **Candidate:** Rohit Srivastava
- **Role:** LMS Specialist
- **Email:** rohitsrivastava@arre.co.in
- **GitHub:** [@rohit2215](https://github.com/rohit2215)
- **Submission Date:** November 14, 2026
