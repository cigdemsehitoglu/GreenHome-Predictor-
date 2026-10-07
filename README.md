# GreenHome Predictor

**Interactive Regression Modeling of Household Monthly Electricity Consumption**

Created: October 7, 2026

## What it is
A fully self-contained interactive web page that lets users predict monthly electricity consumption of a home using a multiple linear regression model.

### Features
- Interactive sliders & dropdowns (home size, occupants, temperature, insulation, heating type)
- Real-time prediction of kWh / month
- Scatter plot showing the prediction relative to a sample of 180 households
- Pure HTML + Plotly (no server, no R, no Python required)

## How to use / deploy on GitHub Pages
1. Upload `index.html` to a new public GitHub repository
2. Go to **Settings → Pages**
3. Source: Deploy from branch `main` / folder `/ (root)`
4. Save → wait ~1 minute → your live link appears

Open the page in any modern browser to interact with the model.
