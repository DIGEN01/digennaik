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
- On desktop, Skills and Projects are one continuous pinned GSAP scene with pin spacing enabled. The main particle sphere divides into four complete skill cards, with every skill visible at the same time.
- The four skill cards converge directly into one shared credit-card object while the Skills heading fades into Projects. Never introduce a second credit-card element or an empty transition screen.
- For Credit Card Fraud Detection, the shared card enlarges behind centered project details at low opacity. It then comes forward, rotates, and morphs into the shopping cart; the cart moves behind the centered Brazilian E-Commerce details at low opacity.
- Experience, Education, and Contact begin only after the unified scene releases its pin, so later sections never overlap the animation.
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
- Contains the persistent particle-core Hero/About transition, four visible skill cards, one shared Skills-to-Projects morph object, centered project-detail scenes, root-level resume link, theme toggle, and responsive fallbacks.
