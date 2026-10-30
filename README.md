# EV Market Analysis Website

A responsive, static website created from the supplied **EV-Market-Analysis project PDF**.

## Run the website
1. Extract `EV_Market_Analysis_Website.zip`.
2. Open the extracted folder.
3. Double-click `index.html` to open it in Chrome, Edge, or another browser.
4. Internet is only needed for the optional Google Fonts. The charts and website work without a chart library.

## Publish with GitHub Pages
1. Sign in to GitHub and create a new **Public** repository.
2. Extract this ZIP on your laptop.
3. Upload `index.html`, `styles.css`, `script.js`, and the `assets` folder (you may also upload this README and the reference PDF).
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select **main** and **/(root)**, then click **Save**.
7. Wait for GitHub Pages to publish. Your website link will appear in the Pages section.

## About the data
The website follows the project PDF's dashboard and visualisations:
- KPI cards: total annual sales units and average customer rating.
- Sales by category, sales trend, battery type distribution, regional distribution and manufacturer comparison.
- Dataset fields: battery, vehicle, charging, efficiency and CO₂ indicators.

**Data note:** The original PDF contains screenshots rather than the full underlying CSV. Values visible in the charts are transcribed where legible. The manufacturer bars and year-by-year trend points are approximate readings from the screenshot and are labelled accordingly. For exact interactive analysis, replace these illustrative values with the original `ev_market_train.csv` data.

## Files
- `index.html` — page structure and content
- `styles.css` — responsive styling
- `script.js` — charts and interactions
- `EV-Market-Analysis project pdf.pdf` — supplied project reference
