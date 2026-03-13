# FomoDéjàVu — Historical Investment Calculator (GitHub Pages)

> **Live site:** [fomodejavu.github.io/historical-investment-scenarios](https://fomodejavu.github.io/historical-investment-scenarios/)  
> **Full calculator:** [fomodejavu.com](https://fomodejavu.com/)

---

This repository hosts the GitHub Pages static site for the [historical-investment-scenarios](https://github.com/fomodejavu/historical-investment-scenarios) open dataset.

## What this is

A free, fully static **"What If I Had Invested?"** calculator featuring:

- 24 historical investment scenarios (stocks, ETFs, crypto, dividends, DCA, inflation)
- All scenarios with split-adjusted returns, DRIP data, and educational context
- Embeddable widget — copy the HTML and drop it anywhere
- No server, no API calls, no sign-up required
- 100% open source, MIT licensed

## Repo structure

```
fomodejavu-github-pages/
├── index.html       ← Main calculator & scenario browser
├── 404.html         ← Custom 404 with redirect
├── _config.yml      ← Jekyll/GitHub Pages config
├── robots.txt
└── sitemap.xml
```

## Deployment

This site is deployed automatically via **GitHub Pages** from the `main` branch.

To deploy your own copy:
1. Fork this repo
2. Go to Settings → Pages → Source: Deploy from branch → `main` / `/ (root)`
3. Your site will be live at `https://{username}.github.io/{repo-name}/`

## Data source

All scenario data comes from the [historical-investment-scenarios](https://github.com/fomodejavu/historical-investment-scenarios) open dataset.

Full methodology, data sources, and assumptions: [fomodejavu.com/methodology](https://fomodejavu.com/methodology/)

## License

MIT. Free to use, modify, and deploy. Attribution appreciated.

---

*Built by [FomoDéjàVu](https://fomodejavu.com/) — educational tools for understanding historical investment returns.*
