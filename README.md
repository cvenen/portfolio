# Carly Venenciano — Data & Analytics Portfolio

Data analyst with a B.A. in Mathematics (Occidental College) and experience cleaning and validating large multi-file datasets, building end-to-end data infrastructure, and presenting findings to non-technical audiences.

📄 [Resume](./resume/Carly%20Venenciano_Resume.pdf) · ✉️ carlyvenenciano@gmail.com · 🔗 [LinkedIn](https://linkedin.com/in/carlyvenenciano)

---

## Projects

### ⚾ Success-at-One-Pitch: MLB Batting & Pitching Prediction Models
**Women in Sports Data Hackathon 2024** | Team Stat Sistahs

Defined a custom "success-at-one-pitch" metric and built 8 multilinear regression models to predict batter and pitcher outcomes on a single pitch, using MLB minor league pitch- and bat-tracking data.

- Collected, cleaned, and standardized 1,200+ JSONL files using Pandas and NumPy
- Used backward selection with VIF and _p_-value diagnostics to test for multicollinearity and validate feature selection
- Found launch-angle sweet spot percentage to be the strongest batting predictor, with swing length and exit velocity also retained (adj. R² = 0.42, n = 31 batters)
- Documented model limitations (small per-pitch-type samples, no at-bat-level data) and recommended next steps

📄 [Final paper](./wisd-hackathon/WISD-2024.pdf)

---

### 🧪 WebAssembly Engine Benchmarking
**Software Engineer Research Intern, Carnegie Mellon University REUSE**

Built a full data pipeline and self-serve exploration tool for a WebAssembly benchmarking study, from raw benchmark data to an interactive public-facing dashboard.

- Designed a PostgreSQL database integrating 2,000+ rows across 18 metrics from multiple WebAssembly engine benchmarks
- Built automated pipelines in Python and shell scripting to load and structure benchmark data
- Developed a Flask API and website with interactive Vega-Lite dashboards that explain the study, define key terms, and present results, so non-technical audiences can explore findings without running code
- Continued the research independently after the internship, running WebAssembly benchmarking experiments on AWS EC2
- Presented findings in a poster session and written report

📄 [Final paper](./cmu-reuse/Wasm%20Paper.pdf) · 🖼️ [Poster](./cmu-reuse/Wasm%20Poster.png) · 📊 [Slide deck](./cmu-reuse/Wasm%20Presentation.pdf) · 💻 [Project repo](https://github.com/composablesys/wish-you-were-fast)

---

### ⚽ Soccer Analytics & Fan Engagement Website
**UX/Analytics Project, Human-Computer Interaction Course**

- Created a Matplotlib 3D data visualization comparing goals, minutes played, and touches on the ball for the top 8 Champions League scorers; results showed no clear relationship between touches on the ball and goals scored
- Prototyped a responsive website in Figma to improve fan engagement and accessibility in soccer analytics

---

## Skills

**Languages & Data:** SQL (PostgreSQL), Python (Pandas, NumPy)

**Data Engineering:** ETL pipelines, Flask (REST APIs), API design and web development (HTML/CSS, JavaScript), shell scripting, Linux, AWS (EC2), Git/GitHub

**Analysis & Visualization:** Regression/statistical modeling, data cleaning and validation, Vega-Lite, Plotly, Matplotlib, Jupyter

---

## Repo structure

```
├── README.md
├── resume/
│   └── Carly Venenciano_Resume.pdf
├── hackathon/
│   └── WISD-2024.pdf
└── cmu-reuse/
    ├── Wasm Paper.pdf
    ├── Wasm Poster.png
    └── Wasm Presentation.pdf
```
