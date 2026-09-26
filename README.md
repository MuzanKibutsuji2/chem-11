# CHEM11

A modern, interactive CBSE Class 11 Chemistry learning lab. Built with React + Vite.

## Included now

- Responsive dashboard with five chapter curriculum and progress indicators
- Dark mode, global search entry point, mobile navigation
- Mole calculator with molar masses, moles, and particle reasoning
- Molecule/VSEPR explorer for H2O, CO2, NH3, CH4, BF3, PCl5, SF6 and XeF4
- Atomic calculator for protons, neutrons and electrons
- Interactive periodic table with element detail panel
- Practice arena with feedback and local progress persistence
- Chapter-organised formula sheet

## Run locally

```bash
npm install
npm run dev
```

## Publish on GitHub Pages

1. Push this repository to GitHub (the workflow is already included).
2. In **Settings → Pages**, set **Source** to **GitHub Actions**.
3. Push to `main` or run **Deploy to GitHub Pages** from the Actions tab.

The Vite base path is configured for the repository name `chem-11`. If the repository is renamed, update `base` in `vite.config.js`.

## Scope notes

This first product build prioritizes reliable, teachable interactions over pretending to solve arbitrary chemistry. The calculator and supported molecule set intentionally show their working and provide useful error states. Advanced question banks, equation balancing and larger element datasets are natural next expansion areas.
