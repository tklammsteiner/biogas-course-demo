# Valorization of Insect Frass for Biogas Production

### Bioprocessing for agricultural side streams into biofuels

Teaching demonstration materials for a course module on turning insect frass (the excrement, uneaten feed and exuviae left over from insect farming) into biogas through anaerobic digestion. The repository is a [Quarto](https://quarto.org/) website that brings together a short course description, an interactive biogas dashboard and the accompanying slide deck.

🌐 **Live site:** `https://tklammsteiner.github.io/teachingdemonstration/`

---

## Course overview

Insect farming (black soldier fly, mealworm, cricket) is growing fast as a source of protein for feed and food, and it generates large volumes of **frass**. Frass is nutrient-rich and organic, which makes it both a fertilizer candidate and a promising feedstock for **anaerobic digestion (AD)**. This course explores how agricultural side streams like frass can be converted into renewable energy while keeping nutrients in the loop.

### Learning objectives

By the end of the course, students should be able to:

1. Describe the composition and characteristics of insect frass as an AD feedstock (C/N ratio, volatile solids, ammonia content, moisture).
2. Explain the four stages of anaerobic digestion: hydrolysis, acidogenesis, acetogenesis and methanogenesis.
3. Identify key process parameters (temperature, pH, organic loading rate, hydraulic retention time) and their effect on biogas yield.
4. Recognise common challenges, such as ammonia inhibition, and strategies like co-digestion to mitigate them.
5. Interpret biogas production data (cumulative yield, methane content, biochemical methane potential) using an interactive dashboard.
6. Place frass-to-biogas within a circular bioeconomy, including digestate use as a biofertilizer.

### Topics covered

| Module | Topic |
|---|---|
| 1 | Insect farming and the frass side stream |
| 2 | Fundamentals of anaerobic digestion |
| 3 | Feedstock characterization and pretreatment |
| 4 | Process optimization and co-digestion |
| 5 | Biogas yield, upgrading and energy balance |
| 6 | Digestate valorization and sustainability |

> Adjust the modules above to match your actual syllabus.

---

## What's in this repository

| Page | Description | File |
|---|---|---|
| **Home** | Course landing page and overview | `index.qmd` |
| **About** | About the instructor | `about.qmd` |
| **Biogas dashboard** | Interactive demo for exploring biogas production data | `dashboard.qmd` |
| **Slide deck** | Lecture slides for the course | *(add path or link)* |

### Biogas dashboard demo

The dashboard (`dashboard.qmd`) is a hands-on demonstration used during the session. It lets students explore how feedstock and process conditions influence biogas output, for example:

- Cumulative biogas / methane production over time
- Comparison between frass and other substrates or co-digestion mixtures
- Effect of process parameters on yield

> Update this list to reflect what your dashboard actually shows, and note whether the data are measured, literature-based or simulated.

### Slide deck

The slide deck accompanies the lecture and walks through the concepts above. 📑 **[View the slides](#)** *(replace with link)*

---

## Repository structure

```
.
├── _quarto.yml          # Quarto project and website configuration
├── index.qmd            # Home page
├── about.qmd            # About me
├── dashboard.qmd        # Biogas dashboard demo
├── custom.scss          # Theme customisation (Sass)
├── styles.css           # Additional styling
├── _assets/             # Images, data and other static files
├── docs/                # Rendered site output (served by GitHub Pages)
└── teaching-materials.Rproj   # RStudio project file
```

---

## About the instructor

See the [About page](about.qmd) for background, research interests and contact details.

---

## Suggested reading

*(Add your key references here, for example:)*

- Review articles on insect frass composition and valorization
- Anaerobic digestion fundamentals (e.g. Angelidaki et al., BMP protocols)
- Studies on co-digestion and ammonia inhibition

---

## License

CC BY 4.0 for teaching materials and MIT for code.

## Citation and contact

If you use or adapt these materials, please credit the author:

Thomas Klammsteiner, *Valorization of Insect Frass for Biogas Production* (2026). Available at: `https://github.com/tklammsteiner/teachingdemonstration`

📧 klammsteiner@pm.me