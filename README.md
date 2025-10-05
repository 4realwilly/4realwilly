<h1 align="center">💠 Hi, I'm <span style="color:#1E90FF;">William Holley</span></h1>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1E90FF,100:00BFFF&height=120&section=header&text=Welcome%20to%20My%20Profile!&fontSize=35&fontColor=FFFFFF&animation=fadeIn" />
</div>

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=4realwilly.4realwilly&left_color=1E90FF&right_color=00BFFF" alt="visitors" />
</div>

---

### 💠 About Me

Hello! I’m **William Holley** from **Geneseo, IL** — a dedicated **self-taught web developer** who loves solving problems and crafting elegant web experiences.

💠 I build with **JavaScript**, **React**, and **Node.js** — always striving to learn new technologies.  
💠 Passionate about **innovation, clean design, and creative development**.  
💠 Driven by curiosity and a love for continuous improvement.

---

### ⚙️ My Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,nodejs,react,vite,vercel,supabase,java,gcp,aws,docker,cloudflare,vscode,github,replit,linkedin,discord,ai" />
</div>

---

### 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=4realwilly&show_icons=true&theme=blueberry&count_private=true&hide_border=false" height="160" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=4realwilly&layout=compact&theme=blueberry&hide_border=false" height="160" alt="Top Languages" />
</div>

---

### 🎧 Now Playing on Spotify

<div align="center">
  <a href="https://open.spotify.com/user/312byzmt3yb4w42d6l6di4vx2de4">
    <img src="https://spotify-recently-played-readme.vercel.app/api?user=312byzmt3yb4w42d6l6di4vx2de4&count=3&background_color=0d1117&border_color=1E90FF" alt="Spotify Recently Played" />
  </a>
</div>

---

### 🌐 Connect With Me

<div align="center">
  <a href="https://www.linkedin.com/in/williamholley" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-1E90FF?style=for-the-badge&logo=linkedin&logoColor=white" height="40" />
  </a>
  <a href="https://www.youtube.com/@4realwilly" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-0078D7?style=for-the-badge&logo=youtube&logoColor=white" height="40" />
  </a>
  <a href="https://www.instagram.com/4realwilly" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-00BFFF?style=for-the-badge&logo=instagram&logoColor=white" height="40" />
  </a>
  <a href="mailto:4realwilly@gmail.com">
    <img src="https://img.shields.io/badge/Email-1E90FF?style=for-the-badge&logo=gmail&logoColor=white" height="40" />
  </a>
  <a href="https://discord.gg/" target="_blank">
    <img src="https://img.shields.io/badge/Discord-4169E1?style=for-the-badge&logo=discord&logoColor=white" height="40" />
  </a>
</div>

---

### 💎 Outside of Coding

💠 Writing about tech and sharing knowledge  
💠 Reading and continuous learning  
💠 Gaming and exploring digital creativity  
💠 Traveling and discovering new cultures  

---

### 🌀 GitHub Contribution Animation

> ⚙️ To enable this feature:
> 1. Go to your GitHub repo **`4realwilly/4realwilly`**
> 2. Create a folder: `.github/workflows/`
> 3. Add a file named `snake.yml` with the following content:

```yaml
name: Generate Snake Animation
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: 4realwilly
          outputs: dist/snake.svg
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
