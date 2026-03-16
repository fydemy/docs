## Contributing to Fydemy Docs

Thank you for your interest in contributing to the **Fydemy** documentation and learning paths.

This project uses **Mintlify** for all documentation. The only tool you need to work on the docs is the **Mintlify CLI**.

---

## How to Get Started

1. **Fork and clone the repo**
   ```bash
   git clone https://github.com/<your-username>/docs.git
   cd docs
   ```

2. **Install Mintlify**
   ```bash
   npm install -g mintlify
   ```

3. **Run the docs locally**
   ```bash
   mintlify dev
   ```
   Open the local URL printed in the terminal to preview changes as you edit.

---

## Types of Contributions

- **Content improvements**
  - Fix typos or grammar.
  - Clarify explanations or re‑organize sections.
  - Add examples, diagrams (as assets), or step‑by‑step guides.

- **New content**
  - Add new pages to existing learning paths.
  - Propose new learning paths or sections (please open an issue first for bigger changes).

- **Navigation and structure**
  - Update `docs.json` to reflect new pages or groups.
  - Improve labels, grouping, or ordering where it helps learners.

---

## Working With Mintlify

- **Configuration**:  
  The main Mintlify configuration is in `docs.json`. It defines the theme, navigation, logo, and global links.

- **Content**:  
  Content is written in **MDX** (`.mdx` files), including the main landing page `index.mdx` and the learning path content in the `web/` directory.

- **Assets**:  
  Images and icons live in the `assets/` directory and are referenced from MDX content and `docs.json`.

When editing MDX:

- Keep headings and sections short and scannable.
- Use code blocks, callouts, and lists to make content easy to follow.
- Make sure all internal links are valid and match the navigation.

---

## Branching and Pull Requests

1. **Create a feature branch**
   ```bash
   git checkout -b feat/<short-description>
   ```

2. **Make your changes**
   - Update or add `.mdx` files and, if needed, update `docs.json`.
   - Run `mintlify dev` and review your changes in the browser.

3. **Run basic checks**
   - Ensure the site builds:
     ```bash
     mintlify build
     ```
   - Fix any build errors or broken links.

4. **Open a pull request**
   - Clearly describe what you changed and why.
   - Add screenshots if you changed layout, navigation, or visuals.

---

## Content Guidelines

- **Audience first**:  
  Assume readers are learners at various stages; avoid unnecessary jargon, and explain terms on first use.

- **Consistent tone**:  
  Friendly, supportive, and encouraging. Focus on actionable, step‑by‑step guidance.

- **Inclusive examples**:  
  Use neutral, inclusive examples and language.

- **Accuracy**:  
  Verify commands, code snippets, and external links before submitting.

---

## Community & Support

If you want to coordinate on a contribution, discuss ideas, or ask questions:

- Join the Discord: `https://discord.gg/7FBpTEXqVj`
- Introduce yourself in **#welcome**
- Use the appropriate channels (e.g. topics, grinding hall, or contribution‑focused channels) to discuss doc changes.

We appreciate every contribution—whether it is a small typo fix or a new learning path. 💡

