<div align="center">
  <img src="src/site/img/user/1 Website Resources/nmos.png" alt="NMOS Wordmark and Logo" width="300">
</div>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
  </a>
</p>

# Notes, Media, & Other Stuff

Welcome to my public digital garden. I am an electrical engineering student utilizing this space to document anything that I like on the interwebs. Please feel free to recommend anything!

**Core Architecture**

| Component | Technology |
| :--- | :--- |
| **Framework** | Eleventy (11ty) |
| **Content Management** | Obsidian + Digital Garden Plugin |
| **Hosting & Deployment** | Vercel |
| **Styling** | Custom SCSS & HTML (Neon-on-Dark UI) |
| **Interactivity** | Giscus (GitHub Discussions API) |

**Key Features**

* **Seamless Publishing:** Markdown notes are authored in Obsidian and pushed live to the repository via the Digital Garden plugin's API connection.
* **Custom Formatting:** Utilizes raw HTML overrides for specialized multi-toned headers and specific markdown line-break rendering.
* **Integrated Comments:** Global comment widgets injected via Nunjucks (`comments.njk`), powered by Giscus and linked directly to this repository's Discussions tab.
* **Static Delivery:** Pre-compiled static site routing for maximum speed, security, and zero database overhead.

**Local Development**

1. Clone this repository to your local machine.
2. Run `npm install` to download Eleventy and all required package dependencies.
3. Run `npm run start` to spin up a local development server.
4. Edit the SCSS files or Nunjucks templates in the `src` directory to preview hot-reloaded aesthetic changes before pushing them live.
