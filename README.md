# SmartChef frontend (pages 6–7)

Frontend prototype built with React, JavaScript, Vite, and regular CSS.

## Run locally on macOS
1. Install Node.js LTS if it isn't installed.
2. Open this folder in VS Code.
3. Open Terminal in VS Code (`Terminal → New Terminal`).
4. Run:
   ```bash
   npm install
   npm run dev
   ```
5. Open the localhost URL printed by Vite.

## Prototype notes
- Navigation only activates Recipes and My Fridge; other menu items are placeholders.
- Recipe selector is a temporary stand-in for the recipe selected on the previous page.
- Fridge inventory is saved in localStorage.
- Recipe timers are per-step and independent.
- Nutrition values are demo approximations; connect real recipe calculations before presenting as accurate.
