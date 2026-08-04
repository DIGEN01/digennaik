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
- About uses a professional three-step value process: frame the question, build trusted evidence, and translate insight into action.
- On desktop, the Skills scene pins while the particle core contracts into four compact circular skill nodes. One skill detail panel is active at a time, then the nodes converge into a credit-card handoff.
- The Projects heading remains visible while a pinned GSAP story pans horizontally from Credit Card Fraud Detection to Brazilian E-Commerce BI Analysis. The background credit card rotates and crossfades into a shopping cart between projects.
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
- Contains the particle-core hero, professional About section, compact scroll-driven skill transformation, horizontal two-project story, root-level resume link, theme toggle, and responsive fallbacks.
