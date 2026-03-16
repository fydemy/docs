## Fydemy Docs

This repository contains the public documentation and learning paths for **Fydemy**, built with **[Mintlify](https://mintlify.com/)**.

The site is deployed as a static documentation site and is meant to be the single source of truth for:

- **Learning paths** (for example, the Certified Web Dev path)
- **Community onboarding** and role descriptions
- **Open‑source project documentation**

The Mintlify configuration lives in `docs.json`, and the main landing page content is defined in `index.mdx`.

---

## Getting Started

**Prerequisite:** You only need to use **Mintlify** to work with this project.

1. **Clone this Github**

   ```bash
   git clone https://github.com/fydemy/docs fdocs
   cd fdocs
   ```

2. **Install Mintlify CLI**  
   Follow the official Mintlify instructions to install the CLI globally:

   ```bash
   npm i -g mint
   ```

3. **Run the local docs server**  
   From the repository root:

   ```bash
   mint dev
   ```

   This will start a local development server so you can preview the docs.

---

## Repository Structure

- **`docs.json`**: Mintlify configuration (theme, navigation, branding, links).
- **`index.mdx`**: Landing page for the documentation site.
- **`web/`**: MDX content for the Certified Web Dev learning path and related sections.
- **`assets/`**: Logos, favicons, and illustrative assets used throughout the docs.

---

## Contributing

We welcome contributions from **students**, **mentors**, **contributors**, and **speakers**.

- **Students / Others**:
  - Use the learning paths and weekly sessions to grow your skills.
  - Open issues if you find mistakes, unclear explanations, or have ideas for new content.

- **Mentors**:
  - Help improve explanations, examples, and structure.
  - Review pull requests from learners.

- **Contributors**:
  - Tackle open issues, improve wording, fix typos, update assets, or add new sections.
  - See `CONTRIBUTING.md` for detailed guidelines.

- **Speakers**:
  - Propose new content based on talks or workshops.
  - Coordinate with the community via Discord before making large structural changes.

Before opening a pull request, please read `CONTRIBUTING.md`.

---

## Community

To join the community and get involved:

1. Join our Discord: `https://discord.gg/7FBpTEXqVj`
2. Choose a role: `student`, `mentor`, `contributor`, or `speaker`.
3. Introduce yourself in the **#welcome** channel.

Useful links:

- **Discord**: `https://discord.gg/7FBpTEXqVj`
- **Website**: `https://fydemy.com`
- **GitHub org**: `https://github.com/fydemy`
- **Events**: `https://luma.com/fydemy`

---

## License

This project is licensed under the **MIT License**. See `LICENSE` for details.
