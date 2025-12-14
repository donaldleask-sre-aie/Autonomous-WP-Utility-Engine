# 🤖 Autonomous-WP-Utility-Engine
**Author:** Donald Leask (donaldleask-sre-aie)

A powerful, natural-language-driven agent utilizing the **Gemini API** to manage and automate core WordPress system utilities. Designed for high-velocity site reliability and administrative toil reduction.

## ⚡ Core Capabilities
This agent consolidates multiple single-purpose plugins into one autonomous engine:

* **Autonomic Content Hygiene:** * **Auto-Tagging:** Automatically reads draft content and generates relevant taxonomy tags (`generate_draft_tags`).
    * **Excerpt Generation:** Auto-generates excerpts for all drafts (`add_draft_excerpts`).
* **Natural Language "God Mode":** * Trigger a terminal overlay (**Ctrl + K**) to issue complex SRE commands in plain English.
* **System Consolidation:** * **Native SMTP Courier:** Replaces "WP Mail SMTP" by routing emails natively through your configured host.
    * **Subscriber System:** Built-in newsletter and subscriber management table.
* **Database SRE:** Executes root-level cleanup (revisions, transients, spam) via simple prompts.

---

## 🚨 CRITICAL LEGAL & USAGE WARNINGS 🚨

### 1. License and Warranty (Read Carefully)
This software is released under the **GNU General Public License, Version 3 (GPLv3)**.

* **NO WARRANTY:** The code is provided "AS IS" without warranty of any kind, express or implied. YOU ASSUME ALL RISK regarding the quality and performance of the program.
* **LIABILITY:** The author is not liable for any damages—incidental, consequential, or otherwise—that result from the use or inability to use this software.
* **CORE FUNCTION:** This agent executes root-level commands (database modification, code injection) directly on your WordPress installation. Use is solely at your own risk.

### 2. Billing Disclaimer
**Note on Billing:** Use of this agent requires a valid Google Gemini API Key. **API usage is subject to Google's current pricing and will be billed directly to your personal Google Cloud account.** This project is not responsible for any incurred API costs.

### 3. Required Expertise (If You Have to Ask, Do Not Use)
This is a developer utility engine, **NOT** a plug-and-play solution. Successful and safe operation requires:

* Advanced understanding of WordPress Database and File Structure.
* Proficiency in obtaining and managing Google Gemini API keys.
* Familiarity with standard Site Reliability Engineering (SRE) principles.

**If you are unsure how to install this or provision the required API keys, you should not be using this tool.**

---

## 🛑 Support and Communication

* **ZERO SUPPORT PROVIDED:** The author provides **no personal support, troubleshooting, or installation assistance** via email, social media, or any other private channel.
* **COMMUNICATION:** All bug reports, security disclosures, and contributions must be submitted solely through the **GitHub Issues** tab for this repository.
* **CONTRIBUTIONS:** Pull requests are welcome from experienced developers who wish to enhance functionality, improve security, or submit clean code.

---

## Installation & Setup

1.  **Clone** this repository to your local machine.
2.  **Install** as a standard WordPress plugin by placing the directory in `wp-content/plugins/`.
3.  **Activate** the plugin via the WordPress Admin Dashboard.
4.  **Configure** your Gemini API Key in the plugin's settings panel (**Settings > Autonomous Utility**).
5.  **Launch** the terminal by pressing **`Ctrl + K`** anywhere in the Admin dashboard.
