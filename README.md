<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A192F,100:112240&height=200&section=header&text=LAKSHMIDEVI%20GUVVA&fontSize=35&fontColor=ffffff&animation=fadeIn" />
</p>

<h3 align="center">
  Java Full Stack Developer
</h3>

<p align="center">
  Passionate about building clean, responsive, and scalable web applications.
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=guvvalakshmidevi&label=Profile%20Views&color=0A66C2&style=for-the-badge" alt="profile views" />
</p>

---

### About Me
- Java Full Stack Developer.
- Interested in frontend, backend, and database development.
- Currently building practical projects and improving problem-solving skills.
- Focused on creating user-friendly applications with modern technologies.

### Tech Stack
<p align="center">
  <img src="https://img.shields.io/badge/Java-0A192F?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-112240?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-0A192F?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-112240?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-0A192F?style=for-the-badge&logo=javascript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-112240?style=for-the-badge&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-0A192F?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-112240?style=for-the-badge&logo=git&logoColor=white" />
</p>

### Projects
- **Project 1:** Add your best project with GitHub link.
- **Project 2:** Add your second project.
- **Project 3:** Add your final strong project.

### GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=guvvalakshmidevi&show_icons=true&theme=tokyonight&hide_border=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=guvvalakshmidevi&layout=compact&theme=tokyonight&hide_border=true" height="160" />
</p>

### Contact
<p align="center">
  <a href="https://www.linkedin.com/in/lakshmi-devi-guvva-476288342?utm_source=share_via&utm_content=profile&utm_medium=member_android">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:guvvalakshmidevi988@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/guvvalakshmidevi">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/guvvalakshmidevi/guvvalakshmidevi/output/github-contribution-grid-snake.svg" alt="snake animation" />
</p>
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4

      - name: Generate snake
        uses: Platane/snk@v3
        id: snake-gif
        with:
          github_user_name: guvvalakshmidevi
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
            dist/github-contribution-grid-snake.gif

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          <picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/guvvalakshmidevi/guvvalakshmidevi/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/guvvalakshmidevi/guvvalakshmidevi/output/github-contribution-grid-snake.svg">
  <img alt="github contribution snake" src="https://raw.githubusercontent.com/guvvalakshmidevi/guvvalakshmidevi/output/github-contribution-grid-snake.svg">
</picture>
