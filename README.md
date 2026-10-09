<div align="center">

# Math Solved

**A free, fully working online calculator — instant answers, no paywall, no sign-up**

Built with plain HTML, CSS, and vanilla JavaScript. Runs entirely in your browser — no backend, no tracking, no account.

<br />

<a href="https://hajir.is-a.dev/calc">
  <img src="https://img.shields.io/badge/Live_Demo-hajir.is--a.dev%2Fcalc-8B5CF6?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Live Demo" />
</a>
<a href="https://buymeacoffee.com/hajirstudio">
  <img src="https://img.shields.io/badge/Support_the_Project-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Buy Me a Coffee" />
</a>

<br />

<img src="https://img.shields.io/badge/Version-v0.1.1-blue?style=flat-square" alt="Version v0.1.1" />
<img src="https://img.shields.io/badge/License-CC0_1.0-lightgrey?style=flat-square" alt="CC0 1.0 Universal" />
<img src="https://img.shields.io/badge/Status-Active-success?style=flat-square" alt="Status active" />

<br />

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
<img src="https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="Vanilla JavaScript" />
<img src="https://img.shields.io/badge/No_Build_Step-4B0082?style=flat-square" alt="No build step" />
<img src="https://img.shields.io/badge/No_Tracking-success?style=flat-square" alt="No tracking" />

<br />

<img src="https://i.postimg.cc/GmWt2wch/H-blue.webp" alt="Math Solved calculator" width="120" />

</div>

---

<div align="center">

### Table of Contents

<table>
<tr>
<td valign="top" width="33%">

**Getting Started**

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Usage](#usage)

</td>
<td valign="top" width="33%">

**Reference**

- [Keyboard Shortcuts](#keyboard-shortcuts)
- [How It Works](#how-it-works)
- [Project Structure](#project-structure)
- [Privacy](#privacy)
- [Troubleshooting](#troubleshooting)

</td>
<td valign="top" width="33%">

**Community**

- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Development Setup](#development-setup)
- [License](#license)
- [Author & Support](#author--support)

</td>
</tr>
</table>

</div>

---

## Overview

> **Math Solved** is a real, fully working calculator that runs entirely in your browser — every answer appears the instant you press equals. No unlock fee, no account, no usage limit.

<table>
<tr>
<td width="50%" valign="top">

### What it does

- Adds, subtracts, multiplies, divides
- Handles decimals, percentages, and negative numbers
- Shows a live preview before you press equals
- Copies any answer to your clipboard in one click
- Full keyboard and touch support
- Works on desktop, tablet, and mobile

</td>
<td width="50%" valign="top">

### What it doesn't need

- No framework
- No build step
- No npm dependencies
- No backend server
- No account or login
- No tracking scripts
- No cookie banners
- No paywall of any kind

</td>
</tr>
</table>

> [!NOTE]
> Optional donations via Buy Me a Coffee keep the project alive — they never unlock, gate, or hide any result. Every answer appears on screen whether you donate or not.

---

## Features

<table>
<tr>
<td width="50%" valign="top">

### Arithmetic

- Addition, subtraction, multiplication, division
- Percentage (`%`) button — converts the current number
- Parentheses support via keyboard `(`, `)`
- Negative numbers — including starting with `-`
- Decimal point with single-dot validation
- Operator swapping — press `+` after `-` and it replaces
- Live preview — the result updates as you type

### Display & feedback

- Expression line — shows what you typed, formatted as `×` and `÷`
- Result line — plain preview while typing, glowing accent when final
- Error states — clear messages for `Division by zero` and `Invalid expression`
- Pop animation on every final answer
- Long expressions auto-scroll horizontally

</td>
<td width="50%" valign="top">

### Input

- On-screen keypad with large touch targets
- Full keyboard support — numbers, operators, `Enter`, `Backspace`, `Esc`
- Copy answer to clipboard — button or `Ctrl / ⌘ + C`
- Toast notification on successful copy
- One-time donation reminder — appears at most 3 times per session, never blocks the answer
- `localStorage` flag stops reminders permanently after any donation link is clicked

### Interface

- Dark glassmorphic design with a purple accent
- Animated grid background and floating gradient orbs
- Responsive layout — mobile-first, two-column on desktop
- Reduced-motion support — respects `prefers-reduced-motion`
- Safe-area friendly padding
- Skip-free semantic HTML with ARIA labels
- `<noscript>` fallback for JavaScript-disabled browsers

</td>
</tr>
</table>

---

## Requirements

> Math Solved runs entirely in a browser.

| Requirement | Details |
|---|---|
| **Browser** | Any modern browser — Chrome, Firefox, Edge, Safari |
| **JavaScript** | Must be enabled |
| **Connection** | Not required after first load — works offline |
| **Storage** | Optional — `localStorage` used only for the donation-reminder flag |
| **Installation** | None — open the file and use it |

---

## Installation

> No build step. No package manager. Just open the file.

### Option A — Use the hosted version

<div align="center">

**[hajir.is-a.dev/calc](https://hajir.is-a.dev/calc)**

</div>

### Option B — Clone and open locally

```bash
git clone https://github.com/haiere/calc.git
cd calc
```

Then open index.html in your browser — double-click it, or right-click and choose Open with your preferred browser.

Option C — Serve through a local static server

<table>
<tr>
<td width="50%" valign="top">

Python

```bash
python -m http.server 8000
```

</td>
<td width="50%" valign="top">

Node.js

```bash
npx serve .
```

</td>
</tr>
</table>

Then open:

```text
http://localhost:8000
```

---

Quick Start

1. Open Math Solved in your browser
2. Enter numbers using the on-screen keypad — or type directly on your keyboard
3. Choose an operator: +, −, ×, or ÷
4. Enter the second number
5. Press = or Enter to see the result
6. Press AC or Esc to clear and start a new calculation

[!TIP]
The keyboard is usually faster than tapping — especially for longer calculations. Enter evaluates, Backspace deletes one character, Esc clears everything.

---

Usage

Buttons

Button Action
0–9 Enter digits
. Add a decimal point
+ − × ÷ Select an arithmetic operator
% Convert the current number to a percentage (÷ 100)
AC Clear all input and reset the calculator
⌫ Delete the last character
= Evaluate the current expression
Copy answer Copy the last result to your clipboard
Buy a coffee Optional — opens Buy Me a Coffee in a new tab

Understanding the display

<table>
<tr>
<td width="50%" valign="top">

Two lines

· Top line — the expression you have typed (shown as × and ÷)
· Bottom line — the result

Three states

· Placeholder (0) — nothing typed yet
· Preview — the live result while typing
· Final — the confirmed answer after pressing equals

</td>
<td width="50%" valign="top">

Edge cases

· Division by zero — clear error message, expression preserved
· Invalid expression — mismatched parentheses or bad input
· Very large or very small numbers — shown in scientific notation
· Trailing decimals — single dot enforced per number
· Repeated operators — last one wins

</td>
</tr>
</table>

---

Keyboard Shortcuts

Math Solved listens for keyboard input so you can work without touching the mouse.

Key Action
0–9 Enter digits
. Decimal point
+ Addition
- Subtraction
* Multiplication
/ Division
( ) Parentheses
% Percentage
Enter or = Evaluate
Backspace Delete last character
Delete or Esc Clear everything
Ctrl / ⌘ + C Copy the last answer

[!NOTE]
Shortcuts are ignored while the donation modal is open — except Esc (to close it) and Tab (to cycle focus inside the dialog).

---

How It Works

Math Solved does not use eval() or Function(). Instead, it evaluates expressions through a small, self-contained math engine.

<table>
<tr>
<td width="33%" valign="top">

1. Tokenizer

Scans the expression character by character and produces a list of tokens — numbers, operators, and parentheses.

</td>
<td width="33%" valign="top">

2. Shunting-yard

Converts the infix token stream into Reverse Polish Notation (RPN), respecting operator precedence and unary minus.

</td>
<td width="33%" valign="top">

3. RPN evaluation

Evaluates the RPN stack. Division by zero and malformed input throw clear, catchable errors.

</td>
</tr>
</table>

Why this matters:

· No eval() — safe against code injection through the display
· Deterministic — the same expression always yields the same result
· Predictable — no browser-specific parsing quirks
· Extensible — new operators and functions can be added to the tokenizer and precedence table

---

Project Structure

Math Solved is a single self-contained HTML file — everything lives in index.html.

```text
calc/
├── index.html      # Markup, inline CSS, inline JavaScript
├── LICENSE         # CC0 1.0 Universal
└── README.md       # Project documentation
```

Inside index.html

Section Contents
<head> SEO meta tags, Open Graph, Twitter Card, JSON-LD structured data (SoftwareApplication, FAQPage), inline <style>
Body → Layout Decorative grid + orbs, calculator card, info panel, floating donation button, modal, toast
Inline <script> Safe math engine (tokenizer → RPN → eval), keypad handlers, keyboard handlers, copy, modal, toast, boot

[!NOTE]
The single-file architecture keeps deployment trivial — copy index.html anywhere and it works. There is no build step, no asset pipeline, and no dependency to install.

---

Privacy

Math Solved does not collect anything. Everything runs locally in your browser.

<table>
<tr>
<td width="50%" valign="top">

What stays on your device

· All arithmetic — tokenizing, evaluation, formatting
· Clipboard operations — via the browser's Clipboard API
· The donation-reminder flag — stored in localStorage under the key mathsolved.v011.donated

</td>
<td width="50%" valign="top">

What never happens

· No analytics, tracking pixels, or telemetry
· No cookies set by the application
· No account, login, or personal data collection
· No server round-trips during calculation
· No data sent to any backend operated by the project

</td>
</tr>
</table>

External resources

The page loads no external resources except:

· Buy Me a Coffee — opened in a new tab only when you click a donation link
· Structured data images — referenced in <meta> tags for social previews, not fetched by the page

[!NOTE]
localStorage is used only to remember that a user has donated, so the optional reminder does not appear again. Clearing site data resets this flag.

---

Troubleshooting

<details>
<summary><b>Buttons do not respond</b></summary>

<br />

· Confirm that JavaScript is enabled in your browser
· Refresh the page
· Check the browser console for errors — open Developer Tools with F12
· Make sure you are opening index.html directly, not through a build tool

</details>

<details>
<summary><b>Keyboard input does not work</b></summary>

<br />

· Click once on the calculator area to give the page focus
· Make sure no other input field on the page has focus
· Check that your browser has not intercepted the key — some browser extensions override shortcuts
· Shortcuts are ignored while the donation modal is open — press Esc first

</details>

<details>
<summary><b>Result looks wrong</b></summary>

<br />

· Check the order of operations — Math Solved respects standard precedence, unlike a basic pocket calculator
· Use parentheses (, ) to group expressions if needed
· Confirm that you have entered the decimal point correctly
· Press AC or Esc to clear and start again
· Very large or very small numbers may be displayed in scientific notation

</details>

<details>
<summary><b>Copy answer does not work</b></summary>

<br />

· The button is disabled until you have a final answer — press = first
· Your browser may block clipboard access on non-HTTPS pages — the hosted version uses HTTPS
· A fallback copy method is used if the Clipboard API is unavailable
· Some browsers require a user gesture — clicking the button provides one

</details>

<details>
<summary><b>The donation reminder feels intrusive</b></summary>

<br />

· The reminder appears at most 3 times per session
· It never appears within 3 minutes of a previous one
· It never blocks, hides, or defers an answer — the result is on screen before the dialog opens
· Clicking any donation link (even without donating) permanently stops reminders on that browser
· The flag is stored in localStorage under mathsolved.v011.donated — you can clear it manually if needed

</details>

<details>
<summary><b>Layout looks broken on mobile</b></summary>

<br />

· Refresh the page
· Check the browser zoom level — pinch to reset
· Try rotating the device to landscape
· Test in a different browser to rule out a rendering issue
· The layout adapts at 1000px (desktop) and 400px (small phones) breakpoints

</details>

<details>
<summary><b>Page does not load</b></summary>

<br />

· If opening locally, confirm that index.html exists and is readable
· If using a local server, check that the server is running on the correct port
· If using the hosted version, check your internet connection
· If JavaScript is disabled, the <noscript> fallback will explain what to do

</details>

---

Roadmap

Possible future additions — not guaranteed, but on the list.

<table>
<tr>
<td width="50%" valign="top">

Calculator

· Scientific mode — sin, cos, tan, log, √
· Memory buttons — M+, M−, MR, MC
· Calculation history panel
· Copy expression as well as result

</td>
<td width="50%" valign="top">

Interface

· Light theme toggle
· Sound feedback on button press
· PWA support — installable, offline-first
· Additional locales for decimal separators and grouping

</td>
</tr>
</table>

---

Contributing

Contributions, bug reports, and suggestions are welcome.

How to contribute

1. Fork the repository
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes
4. Test in at least two browsers — for example Chrome and Firefox
5. Test on both desktop and mobile screen sizes
6. Commit your changes:
   ```bash
   git commit -m "Add: short description of your change"
   ```
7. Push the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
8. Open a pull request with a clear description

Guidelines

· Keep the project dependency-free
· Do not introduce a build step
· Preserve keyboard support for all new buttons
· Keep the math engine free of eval() and Function()
· Test both mouse and keyboard input
· Keep the layout responsive across mobile and desktop
· Preserve the "no paywall" principle — nothing in the calculator may be gated behind a donation
· Update this README when adding major features

---

Development Setup

No tools required beyond a browser and a text editor.

Local development

1. Clone the repository
2. Open the project folder in your editor
3. Edit index.html — CSS and JavaScript are inline
4. Refresh the browser to see your changes

Optional local server:

```bash
python -m http.server 8000
```

Or:

```bash
npx serve .
```

Then open http://localhost:8000.

Testing checklist

<table>
<tr>
<td width="50%" valign="top">

☐ Addition works correctly
☐ Subtraction works correctly
☐ Multiplication works correctly
☐ Division works correctly
☐ Division by zero shows a clear error
☐ Percentage button works
☐ Decimal point works
☐ Single dot enforced per number
☐ Operator swap works — e.g. + then −
☐ Negative numbers work — including starting with -
☐ Parentheses work via keyboard

</td>
<td width="50%" valign="top">

☐ AC resets everything
☐ Backspace deletes one character
☐ Esc clears everything
☐ Enter evaluates
☐ Ctrl / ⌘ + C copies the answer
☐ Live preview updates while typing
☐ Long expressions scroll horizontally
☐ Keyboard input works for all keys
☐ Layout is usable on mobile
☐ No console errors
☐ Works offline after first load

</td>
</tr>
</table>

---

License

This project is released under CC0 1.0 Universal — a public domain dedication.

You are free to copy, modify, distribute, and use the work for any purpose, including commercial purposes, without asking permission.

See the LICENSE file for the full text.

---

Author & Support

<div align="center">

Developed by Hajir Studio

<br />

Channel Purpose
Website hajir.is-a.dev
GitHub github.com/haiere
Support the project Buy me a coffee

<br />

<a href="https://buymeacoffee.com/hajirstudio">
  <img src="https://img.shields.io/badge/Buy_Me_a_Coffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Buy Me a Coffee" />
</a>

<br />
<br />

<sub>
Donations are 100% optional — the calculator stays free whether you donate or not.<br />
Your support helps maintain this and other open projects. Thank you.
</sub>

</div>

---

<div align="center">

Free. Fast. No paywall.

<br />

<a href="https://hajir.is-a.dev/calc">
  <img src="https://img.shields.io/badge/Open_Calculator-8B5CF6?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Open Calculator" />
</a>
<a href="https://buymeacoffee.com/hajirstudio">
  <img src="https://img.shields.io/badge/Support_the_Project-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Support the Project" />
</a>

<br />
<br />

<sub>
Math Solved v0.1.1 · Made with simplicity in mind.
</sub>

</div> 
