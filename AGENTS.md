# Portfolio project memory

## Repository

- Owner: `DIGEN01`
- Repository: `DIGEN01/digennaik`
- Site entry point: `index.html`
- Architecture: one self-contained HTML file with inline CSS and JavaScript; no build step.

## Approved visual direction

- Dark navy analytics interface with cyan, violet, and teal accents.
- Preserve the custom cursor and trailing cursor ring.
- Hero shows “Digen Naik.” on the left and a detailed live particle data core on the right.
- The core is rendered in canvas from 3D particles, network edges, globe grid lines, orbit rings, glows, and small dashboard accents.
- The page sequence is Hero → About → Skills → Projects → Experience → Education → Contact.
- About contains one heading and a concise professional narrative; do not add a separate profile or process panel.
- The particle core remains fixed on the right while the Hero copy scrolls into About.
- On desktop, the Skills stage pins itself with pin spacing enabled. The core becomes four circular skill nodes in one row, four rectangular detail panels appear below, the circles disappear, and the four panels converge into one rectangle before reshaping into the credit card.
- The Projects heading remains visible while a pinned GSAP story pans horizontally from Credit Card Fraud Detection to Brazilian E-Commerce BI Analysis. The background credit card rotates and crossfades into a shopping cart between projects.
- Skills and Projects must pin their own stage elements inside auto-height parent sections so later sections are pushed down and never overlap a pinned scene.
- On mobile and with reduced motion, Skills and Projects use a readable vertical layout without pinning.
- Resume button always targets `resume.pdf` in the repository root. The PDF may be added later.

## Skill taxonomy

1. BA & Process Tools
   - Requirements gathering, stakeholder communication, process improvement, root-cause analysis, documentation, Microsoft 365, SharePoint.
2. Data & Analytics
   - Analysis and querying: SQL, MySQL, MS SQL Server, Excel, data cleaning, data validation, exploratory analysis, statistical analysis.
   - Programming and data science: Python, Pandas, NumPy, scikit-learn, XGBoost, TensorFlow, classification, predictive modelling.
   - BI and visualization: Power BI, Tableau, Excel dashboards, KPI reporting, data storytelling.
3. Methods & Frameworks
   - Agile methodology, Waterfall methodology.
4. Cloud & Dev Tools
   - Azure, Git, VS Code, Jupyter Notebook, Windows environments.

## Change boundaries

- Experience, Education, and Contact remain unchanged unless explicitly requested.
- Maintain keyboard accessibility and `prefers-reduced-motion` support.
- Test at 375px mobile and 1280px desktop before publishing visual changes.

## Current branch

- `agent/hero-particle-core`
- Contains the persistent particle-core Hero/About transition, four-circle/four-rectangle skill transformation, corrected self-pinning scroll stages, horizontal two-project story, root-level resume link, theme toggle, and responsive fallbacks.
