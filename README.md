# 100Hires-Growth-Marketing-Task

Note on Structure: The repository is organized according to the specified technical rubric, with strategic deep-dives and synthesis housed in the /research/other/ directory for streamlined navigation.

# Growth Marketing Research Portfolio: 100Hires
This repository contains a curated research portfolio on B2B SaaS growth marketing. My goal for this project was to move beyond generic "best practices" and identify actionable, operator-led playbooks that can scale an AI-native recruiting platform.

### Methodology: Curation Over Volume
I deliberately chose not to rely on broad scraping or generic "Top 10" lists. Instead, I used a **Signal-First Curation** approach:
1. **Operator Credibility:** I only selected experts who currently practice the growth strategies they teach (verified via active LinkedIn/Content presence).
2. **Tactical Specificity:** I prioritized experts who provide repeatable frameworks and data-backed playbooks rather than high-level theory.
3. **Strategic Diversity:** The roster includes experts covering the full growth spectrum: Content Strategy, Performance Marketing, Behavioral Science, and Community-Led Growth.

### High-Signal Expert Roster
* **Karthick Raajha** (Tactical Lead Gen)
* **Daniel Saks** (Executive GTM Strategy)
* **Shaun Weston** (In-house Content Execution)
* **Vlad White** (Global PR & SEO Flywheels)
* **Amir Ali** (AI-Powered Copywriting)
* **George Coudounaris** (Paid Media/Demand Gen Systems)
* **Stijn Hendrikse** (T2D3 Scaling Framework)
* **Yury Larichev** (CLG as a Revenue Engine)
* **Vivek Nair** (Conversion Rate Optimization)
* **Nancy Harhut** (Behavioral Science "X-Factor")

### Repository Navigation
* **`research/sources.md`**: The foundation. A complete list of all 10 experts with my critical notes on their frameworks and credibility.
* **`research/strategic-synthesis.md`**: What I learned. An analysis of the patterns, tensions, and the "gap" in current B2B growth advice.
* **`research/growth-architecture.md`**: How I’d execute. A 3-step growth plan applying this research specifically to 100Hires.
* **`research/research-context.md`**: Supplementary sources (PDFs/Deep-dives) used to pressure-test my assumptions.

### How I Worked
I treated this research as a real growth brief. I started with a hypothesis on "AI-native" recruiting growth, gathered operator-grade signal, synthesized the tensions between organic/paid strategies, and drafted a direct execution plan for 100Hires.

# Project Setup & Technical Log

## What tools I installed:
* Cursor IDE
* Claude Code (Cursor Extension)
* Codex (Cursor Extension)
* Git for Windows (Version Control)
* GitHub (Web Platform)

## What steps I completed:
1. Downloaded and installed the Cursor IDE.
2. Installed and successfully authenticated the Claude Code and Codex extensions via the command palette.
3. Created a public GitHub repository named `100Hires-Growth-Marketing-Task`.
4. Installed Git for Windows to enable local repository cloning.
5. Cloned the public repository into my local Cursor workspace.
6. Documented the tool setup, workflow, and technical hurdles in this README.md file.
7. Committed the final documentation and pushed it back to the remote GitHub repository.

## What issues I ran into and how I solved them:

* **GitHub Username Readability:** My initial username choice contained an unreadable consonant cluster.
  * *Solution:* I changed the username to a cleaner variation to ensure a more professional presentation for the recruiter.
* **Hidden Extensions Sidebar:** Cursor opened directly into the Agent view by default, completely hiding the standard left sidebar navigation and ignoring traditional keyboard shortcuts.
  * *Solution:* I navigated to the "Editor Window" toggle in the top right to escape the Agent screen, returning the software to the traditional editor layout where the extensions panel was accessible.
* **Marketplace vs. Plugins Confusion:** I initially navigated into the custom AI "Plugins" section inside Cursor's internal settings, mistaking it for the general extension marketplace.
  * *Solution:* I exited the internal settings menu and used the master command palette to force-open the correct standard Extensions sidebar.
* **Stuck Extension Installation:** The Codex extension experienced a common marketplace visual glitch where the state hung indefinitely on "Installing..." even after the background download finished.
  * *Solution:* I performed a complete manual restart of the Cursor application to force the system interface to update and finalize the installation prompt.
* **Missing Git Clone Command:** When attempting to pull the repository into Cursor, the `Git: Clone` command was entirely missing from the command palette.
  * *Solution:* I realized my local machine lacked the underlying Git version control software. I navigated to git-scm.com, installed the standard Windows package, and completely restarted Cursor so it could detect the new system path variables and unlock the Git commands.