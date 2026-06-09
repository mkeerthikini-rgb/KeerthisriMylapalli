<div align="center">  <picture>  
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KeerthisriMylapalli/KeerthisriMylapalli/output/github-contribution-grid-snake-dark.svg" />  
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/KeerthisriMylapalli/KeerthisriMylapalli/output/github-contribution-grid-snake.svg" />  
  <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/KeerthisriMylapalli/KeerthisriMylapalli/output/github-contribution-grid-snake.svg" />  
</picture>  </div>  <details>  
<summary>⚙️ How to enable the snake animation</summary>  Create .github/workflows/snake.yml in your profile repo:

name: Generate Snake  
on:  
  schedule:  
    - cron: "0 0 * * *"  
  workflow_dispatch:  
jobs:  
  generate:  
    runs-on: ubuntu-latest  
    steps:  
      - uses: Platane/snk@v3  
        with:  
          github_user_name: mkeerthikini-rgb  
          outputs: |  
            dist/github-contribution-grid-snake.svg  
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark  
      - uses: crazy-max/ghaction-github-pages@v3  
        with:  
          target_branch: output  
          build_dir: dist  
        env:  
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

</details>  
---

🤝 Let's Connect

<div align="center">  




</div>  
---

<div align="center">  "Intelligence is the ability to adapt to change." — Stephen Hawking

If you find my work interesting, drop a ⭐ or reach out — I'm always open to collaborating on meaningful projects.
