# NutriWeek — Calorie & Nutrition Planner

A lightweight, responsive weekly meal planner built with plain HTML, CSS, and JavaScript. No build tools, npm install, API keys, or backend are required.

## Features
- Seven-day meal plan with four meals per day.
- Alternative food options for every meal; changing a dropdown updates daily and weekly nutrition estimates.
- Daily calorie, protein, carbohydrate, fat, and fibre totals.
- Editable daily targets.
- Weekly nutrition overview.
- Export the plan as JSON and print/save as PDF from the browser.
- Responsive layout for desktop and mobile.

## Run locally
Open `index.html` in a modern browser.

## Publish with GitHub Pages
1. Create a GitHub repository (for example, `nutriweek-planner`).
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site; the URL will appear in the Pages section.

## Customize meals
Edit the `mealTemplates` array in `index.html`. Each meal's `options` array contains `name`, `foods`, `kcal`, `p` (protein grams), `c` (carbohydrate grams), `f` (fat grams), and `fi` (fibre grams). Add, remove, or modify options to fit your recipes and portion sizes.

## Nutrition note
All nutrition values are estimates intended for planning, not medical advice. Actual values vary with brand, recipe, cooking method, and whether weights are raw or cooked. Use package labels and consistent weighing for greater accuracy. The default macro targets are 130 g protein, 150 g carbs, and 40 g fat (approximately 1,480 kcal using 4/4/9 kcal per gram); calories from fibre and rounding can cause totals to differ.
