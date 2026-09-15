# 🤝 Contributing Guidelines

Thank you for your interest in contributing to **Awesome UI/UX & Frontend Resources**! 

This repository exists to curate only the highest quality, most reliable, and genuinely accessible design inspirations, frontend libraries, animation engines, and developer utilities. To maintain this high standard, we review all submissions against our strict **5-Pillar Inclusion Criteria**.

---

## 🏛️ The 5-Pillar Inclusion Criteria

Every resource proposed for addition must strictly satisfy all five pillars:

### 1. 🆓 100% Free or Genuine Permanent Free Tier
- The resource must be either **completely free** (open-source or freely hosted) or provide an **unrestricted, permanent free tier**.
- **Disallowed:** "Free trials" that expire after 7, 14, or 30 days; services requiring a credit card or payment information upfront; "freemium" tools where the free tier is an unusable demo or heavily watermarked.

### 2. 🚫 Zero Affiliate Codes or Monetization Parameters
- Submissions must contain **clean, canonical URLs only**.
- All tracking parameters (`?utm_source=`, `?utm_medium=`, `?ref=`), referral tokens, affiliate tags, and vanity link shorteners (bit.ly, tinyurl) **must be stripped**.
- Commercial sponsorships or promotional placements are strictly forbidden.

### 3. ⚡ Actively Maintained
- Software, libraries, and tools must show active maintenance within the past **1–2 years** (recent commits, release tags, or active package updates).
- Web galleries and design vaults must have functional layouts, responsive styling, and modern browser compatibility (no obsolete plugins or dead SSL certificates).

### 4. 🎓 High Pedagogical & Practical Value
- The resource must offer meaningful utility, exceptional craftsmanship, or significant educational value to frontend developers, creative engineers, or UI/UX designers.
- Avoid generic list spam, personal school projects, or incomplete prototypes.

### 5. 🏷️ Accurate Level Indicator Tags
To help learners and professionals quickly find resources suited to their experience level, every submission must be assigned an appropriate skill level tag:

| Tag | Level | Definition |
| :--- | :--- | :--- |
| **`L1`** | **Beginner / Foundational** | Conceptual guides, basic design principles, accessible galleries, ready-to-use HTML/CSS snippets, and zero-setup tools. |
| **`L2`** | **Intermediate / Practical** | Production-grade React/Next.js/Tailwind components, icon suites, practical state management, and real-world design systems. |
| **`L3`** | **Advanced / Specialized** | Custom WebGL/Three.js shaders, low-level physics engines, complex procedural visuals, and cutting-edge creative dev experiments. |

---

## 📋 Markdown Table Formatting Guidelines

When adding a resource to an existing table, ensure your entry adheres to the following formatting standards:

1. **Alphabetical Ordering:** Place the resource in alphabetical order by name within the corresponding category table.
2. **Schema Uniformity:**
   ```markdown
   | **[Resource Name](https://clean-url.com/)** `L1` | Concise 1-2 sentence description explaining the key capability and value. | `Tag1` `Tag2` `Tag3` | [clean-url.com](https://clean-url.com/) |
   ```
3. **Concise Descriptions:** Descriptions should be objective, professional, and highlight unique features. Avoid marketing fluff or buzzwords like "the absolute best".
4. **Focused Tags:** Include 2–4 relevant tags inside backticks (e.g., `` `React` `Tailwind CSS` `Icons` ``).

---

## 🛠️ Step-by-Step Contribution Workflow

1. **Check Existing Resources:** Search `README.md` to ensure the resource is not already cataloged.
2. **Fork the Repository:** Click the **Fork** button at the top right of this repository.
3. **Clone & Create a Branch:**
   ```bash
   git clone https://github.com/<your-username>/UI-UX-RESOURCES.git
   cd UI-UX-RESOURCES
   git checkout -b add/resource-name
   ```
4. **Make Your Changes:** Edit `README.md` to add the resource according to our formatting rules.
5. **Verify Links:** Check that your added URL responds with HTTP 200 (no 404s, SSL errors, or broken redirects).
6. **Commit using Conventional Commits:**
   ```bash
   git commit -m "feat(resources): add Lucide Icons to developer assets"
   ```
7. **Push to Your Fork:**
   ```bash
   git push origin add/resource-name
   ```
8. **Open a Pull Request:** Submit a PR targeting the `main` branch. Fill out our [PR Checklist](.github/pull_request_template.md) completely.

---

## 🚨 Reporting Dead Links or Issues

Notice a dead link, expired domain, or a tool that moved behind a paywall? Please help us by opening a report using our [Report Broken Link Issue Form](https://github.com/CyberParadox-33/UI-UX-RESOURCES/issues/new?template=report_broken_link.yml).

---

## 📜 Code of Conduct

All contributors and maintainers are expected to uphold a welcoming, respectful, and inclusive environment. Please review our [Code of Conduct](CODE_OF_CONDUCT.md) before participating.
