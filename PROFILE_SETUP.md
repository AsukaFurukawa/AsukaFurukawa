### Publish your Pokémon‑style GitHub profile

Follow these steps to make this README your GitHub front page.

1) Create a repo named exactly your GitHub username. For you it looks like `AsukaFurukawa`.

2) Initialize and push from this folder:

```bash
cd /Users/prachi.sinha1/Desktop/Prachi_GitFrontPage
git init
git branch -M main
git add .
git commit -m "feat(profile): Pokémon-style profile front page"
git remote add origin https://github.com/AsukaFurukawa/AsukaFurukawa.git
git push -u origin main
```

3) If your username is different, edit the `README.md` links (search for `AsukaFurukawa`) and change the remote URL above.

4) Refresh your GitHub profile page. GitHub automatically uses this repo’s `README.md` as your profile front page.

Optional: customize
- Edit `assets/trainer-card.svg` scores and labels.
- Replace project links under “Pokédex (Projects)”.
- Swap the banner text in `assets/banner.svg`.

Enable extras
- The snake workflow (`.github/workflows/snake.yml`) will create `output` branch SVGs after the first push. If images don’t appear, go to the repo Actions tab and run "generate-snake" once.
- Trophies, activity graph, and stat cards are third‑party readmes that render on the fly; no extra setup needed.


