<div align="center">

<!-- Animated Header Wave -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Dimas%20Rahmanda%20Alfarizi&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Web%20Developer%20%7C%20Informatics%20Student&descAlignY=55&descSize=18"/>

<!-- Typing Animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D9FF&center=true&vCenter=true&random=false&width=600&lines=Hi+there!+I'm+Dimas+%F0%9F%91%8B;Full-Stack+Web+Developer;Informatics+Student+%40+UPNVJATIM;Always+Learning+New+Things+%F0%9F%9A%80;Building+Impactful+Solutions+%F0%9F%92%A1" alt="Typing SVG" />
</a>

<br/>

<!-- Social Badges -->
<p>
  <a href="https://linkedin.com/in/dimasrahmandaalfarizi">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://www.instagram.com/dmsrah">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>
  <a href="mailto:dimas.alfarizi@email.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://dimasrahmandaalfarizi.github.io/portofolio/">
    <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white" />
  </a>
</p>

<img src="https://komarev.com/ghpvc/?username=dimasrahmandaalfarizi&style=for-the-badge&color=0e75b6" alt="Profile Views" />

</div>

---

<!-- About Me -->
<img align="right" alt="Coding" width="380" src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif"/>

### 👨‍💻 About Me

```yaml
name: Dimas Rahmanda Alfarizi
location: Surabaya, Indonesia 🇮🇩
education: Informatics Engineering @ UPNVJATIM
role: Web Developer & Informatics Student
available_for:
  - Internships
  - Collaborations
  - Open Source Projects

interests:
  - Full-Stack Web Development
  - Mobile App Development
  - Cloud Architecture
  - UI/UX Design

fun_facts:
  - "☕ Coffee-powered developer"
  - "🎮 Strategy games enthusiast"
  - "🎵 Codes to sad music vibes"
  - "🌟 Indonesia tech ecosystem advocate"
```

<br clear="both"/>

---

## 🛠️ Tech Stack & Tools

<div align="center">

### 🌐 Frontend
<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,vue,nextjs,nuxtjs,svelte,tailwind,bootstrap" />
</p>

### ⚙️ Backend
<p>
  <img src="https://skillicons.dev/icons?i=laravel,php,nodejs,express,fastapi,graphql" />
</p>

### 🗄️ Database
<p>
  <img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb" />
</p>

### 📱 Mobile
<p>
  <img src="https://skillicons.dev/icons?i=react,androidstudio" />
  &nbsp;
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" height="48"/>
</p>

### ☁️ DevOps & Cloud
<p>
  <img src="https://skillicons.dev/icons?i=docker,aws,gcp,githubactions,linux" />
</p>

### 🔧 Tools
<p>
  <img src="https://skillicons.dev/icons?i=git,github,figma,postman,vscode,xampp" />
</p>

</div>

---

## 📊 GitHub Statistics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=dimasrahmandaalfarizi&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" height="170"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dimasrahmandaalfarizi&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="170"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=dimasrahmandaalfarizi&theme=tokyonight&hide_border=true" />

</div>

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=dimasrahmandaalfarizi&theme=tokyonight&no-frame=true&no-bg=false&column=7" />
</div>

---

## 📈 Activity Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=dimasrahmandaalfarizi&theme=tokyo-night&hide_border=true&area=true&custom_title=Dimas's%20Contribution%20Graph" />
</div>

---

## 🕹️ Pacman eats my Contributions!

<div align="center">

![pacman contribution graph](https://raw.githubusercontent.com/dimasrahmandaalfarizi/dimasrahmandaalfarizi/output/pacman-contribution-graph.svg)

</div>

---

## 🐍 Snake eating my commits...

<div align="center">

![snake gif](https://raw.githubusercontent.com/dimasrahmandaalfarizi/dimasrahmandaalfarizi/output/github-snake.svg)

</div>

<!--
==========================================================
  SETUP PACMAN & SNAKE ANIMATION (WAJIB DILAKUKAN SEKALI)
==========================================================
Buat file: .github/workflows/pacman.yml
Isi dengan:

name: Generate Pacman & Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10
    steps:
      - name: Generate SVG
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg?palette=github
            dist/pacman-contribution-graph.svg?palette=github&color_snake=orange&color_dots=#1a1b27,#1f4287,#4b91f1,#3c7dd9,#00d9ff

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

Push ke GitHub, tunggu Actions jalan, Pacman & Snake langsung muncul!
==========================================================
-->

---

## 🌱 Currently Learning

<div align="center">

| 🚀 Frontend | ⚙️ Backend | ☁️ Cloud | 📱 Mobile | 🎨 Design |
|:-----------:|:---------:|:--------:|:---------:|:---------:|
| Next.js | FastAPI | AWS | React Native | Figma |
| Svelte | GraphQL | Google Cloud | Expo | Adobe XD |

</div>

---

## 💭 Dev Quote of the Day

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" />
</div>

---

<div align="center">

### 🤝 Let's Connect & Build Something Amazing!

<p>
  <a href="https://linkedin.com/in/dimasrahmandaalfarizi">
    <img src="https://img.shields.io/badge/Let's%20Connect!-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://dimasrahmandaalfarizi.github.io/portofolio/">
    <img src="https://img.shields.io/badge/View%20Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white" />
  </a>
  <a href="mailto:dimas.alfarizi@email.com">
    <img src="https://img.shields.io/badge/Send%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer"/>

</div>
