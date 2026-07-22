<div align="center">

<!-- CYBERPUNK ANIMATED BANNER -->
<img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=700&size=30&duration=4000&pause=1000&color=00FF66&center=true&vCenter=true&width=600&lines=SYSTEM+INITIALIZED...;GUSTAVO+ROCHA+-+16+Y.O.;BACKEND+DEV+%26+DATA+ANALYST;WAKE+UP,+SAMURAI..." alt="Typing SVG" />

<br/>

<!-- CYBERPUNK THEMATIC GIF -->
<img src="https://i.pinimg.com/originals/a3/e5/22/a3e522ff6b7e0978ebbfbbf102f30b9d.gif" width="100%" style="border: 2px solid #00FF66; border-radius: 5px;" alt="Cyberpunk City GIF">

<br/><br/>

Hey there, I'm Gustavo Rocha 👋
16 y/o developer from Brazil 🇧🇷 | Aspiring Backend Engineer & Data Analyst
Building the foundations today to architect the systems of tomorrow.

<br/>

</div>

## 💡 Interests
I'm really into backend systems and data analysis — APIs, servers, databases, and how everything connects behind the scenes. Linux is basically my home at this point. I also love automating stuff and scripting, making boring tasks just disappear. Oh, and I casually find cybersecurity fascinating — not planning to go into it professionally right now, I just think it's super cool to understand how things can be broken and protected in the digital world.

## 🧑‍💻 About Me
🎓 High school student with a serious passion for technology and the cyberpunk aesthetic.
🔧 Currently diving deep into **C#** and Backend Development.
🐧 Linux enthusiast — the terminal is my comfort zone.
🧠 Solid foundations in logic, HTML, and CSS.
📚 Always learning something new, every single day.
🌎 Based in Brazil | Intermediate English speaker.

## 🛠️ Current Skills

<div align="center">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Logic-00599C?style=for-the-badge&logo=processwire&logoColor=white" />
  <img src="https://img.shields.io/badge/Cyber_Security-000000?style=for-the-badge&logo=kalilinux&logoColor=00FF66" />
</div>

## 🚀 Learning Roadmap
✅ HTML & CSS          — Done
✅ Logic & Algorithms  — Done
✅ Linux basics        — Done
🔄 C#                  — In progress
⏳ REST APIs           — Planned
⏳ Databases (SQL)     — Planned
⏳ Data Analysis tools — Planned

## 🎯 Goals
- [ ] Master C# and create a real-world application
- [ ] Build my first complete backend API from scratch
- [ ] Understand how systems work under the hood (OS, networking, data structures)
- [ ] Contribute to an open source project
- [ ] Land my first developer role or internship

## 📊 Network Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=mochaq1&show_icons=true&theme=matrix&border_color=00ff66&include_all_commits=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mochaq1&layout=compact&theme=matrix&border_color=00ff66&hide=html,css" />
</div>

## 📺 Neural Network Uplink

<div align="center">

| 🎧 **CYBERPUNK SYNTHWAVE UPLINK** |
| :---: |
| [![Cyberpunk Video](https://img.youtube.com/vi/Ucw2qFk2xO0/maxresdefault.jpg)](https://www.youtube.com/watch?v=Ucw2qFk2xO0) |
| <sub>▶️ *Click the image above to access the audio terminal on YouTube*</sub> |

</div>

## 🐍 Contribution Pacman

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mochaq1/mochaq1/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mochaq1/mochaq1/output/github-contribution-grid-snake.svg"/>
  <img alt="pacman eating contributions" src="https://raw.githubusercontent.com/mochaq1/mochaq1/output/github-contribution-grid-snake.svg"/>
</picture>
</div>

<details>
<summary>⚙️ How to activate the Pacman snake</summary>

In your profile repo (`mochaq1/mochaq1`), go to Settings → Actions → General.
Enable "Allow all actions and reusable workflows".
Create `.github/workflows/snake.yml`:
```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
