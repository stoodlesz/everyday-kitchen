# The Everyday Kitchen

A mobile-friendly, single-page recipe book prepared for GitHub Pages.

## Included
- Search by recipe name, category or ingredient
- Category filters
- Recipe detail pages with ingredient checkboxes and method
- Portion scaling controls
- Personal notes saved in the browser (localStorage)
- Seed recipes: Ninja pasta ham & broccoli gratin, carrot cake baked oats, protein carrot cake baked oats, gluten-free chicken & mushroom pasta bake, broccoli onion & cheese cornbread

## Publish with GitHub Pages
1. Create a new public repository on GitHub, e.g. `everyday-kitchen`.
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. After GitHub Pages publishes, the site URL will appear on the Pages settings screen.

No build step or dependencies are required.

## Updating recipes
Edit the `recipes` array in `index.html`. Each recipe contains `name`, `category`, `art`, `time`, `serves`, `desc`, `ingredients`, `steps`, `nutrition` and `notes`.
