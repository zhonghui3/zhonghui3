<div align="center">
  
<!-- 动态波浪头部 -->
![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Hi%2C%20I'm%20Zhonghui%20%F0%9F%91%8B&fontSize=35&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Embedded%20AI%20Engineer%20%7C%20%E5%B5%8C%E5%85%A5%E5%BC%8FAI%E5%B7%A5%E7%A8%8B%E5%B8%88&descSize=18&descAlignY=55)

</div>

<!-- 个人介绍打字效果 -->
<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=1000&color=2196F3&center=true&vCenter=true&random=false&width=435&lines=Welcome+to+my+GitHub+Profile!;Focusing+on+embedded+systems+%26+AI;Always+learning+new+things" alt="Typing SVG" />
  </a>
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=zhonghui3&label=Profile%20views&color=2196F3&style=for-the-badge" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/zhonghui3?style=for-the-badge&color=2196F3" alt="Followers" />
  <img src="https://img.shields.io/github/stars/zhonghui3?style=for-the-badge&color=2196F3" alt="Stars" />
</div>

<br>

---

### 🚀 About Me

<div align="left">
  <img align="right" height="160" src="https://github-readme-stats.vercel.app/api/wakatime?username=zhonghui3&theme=dark&bg_color=0d1117&hide_border=true&layout=compact&custom_title=My%20Week&v=2" alt="Wakatime stats" />
  
  👨‍💻 I'm an Embedded AI Engineer passionate about building intelligent edge devices.
  
  🎯 Currently focusing on:
  - Embedded systems development (C/C++, Linux, RTOS)
  - UI development with Qt and LVGL
  - AI model deployment on edge devices
  - Low-power IoT system design

  📚 Always learning and exploring new technologies in the embedded AI field.
</div>

<br clear="right">

---

### 🛠️ Tech Stack

<div align="center">

**Languages**  
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Frameworks & Tools**  
![Qt](https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![LVGL](https://img.shields.io/badge/LVGL-29B6F6?style=for-the-badge&logo=lvgl&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-00ADD8?style=for-the-badge&logo=freebsd&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Hardware Platforms**  
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberry-pi&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Kendryte K230](https://img.shields.io/badge/K230-6D4C41?style=for-the-badge&logo=microchip&logoColor=white)
![Rockchip](https://img.shields.io/badge/Rockchip-FF6C37?style=for-the-badge&logo=rockchip&logoColor=white)

</div>

---

### 📊 GitHub Analytics

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=zhonghui3&show_icons=true&theme=algolia&bg_color=0d1117&hide_border=true&rank_icon=github&include_all_commits=true" alt="GitHub stats" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zhonghui3&layout=compact&theme=algolia&bg_color=0d1117&hide_border=true&hide=html,css,javascript" alt="Top languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=zhonghui3&theme=algolia&background=0d1117&hide_border=true" alt="GitHub Streak" />
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=zhonghui3&theme=algolia&bg_color=0d1117&hide_border=true" alt="Profile Details" />
</div>

---

### 🐍 Contribution Snake

<div align="center">
  <img alt="snake eating my contributions" src="https://raw.githubusercontent.com/zhonghui3/zhonghui3/output/github-contribution-grid-snake-dark.svg" />
</div>

<details>
<summary>📝 How to enable the snake animation?</summary>
<br>

The snake animation runs via GitHub Actions and updates daily. To set it up:
1. Create a new branch named `output` in this repository
2. Add this workflow to `.github/workflows/snake.yml`:
```yaml
name: Generate Snake Animation
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
          github_user_name: zhonghui3
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
3. Run the workflow manually once to generate the first snake animation
</details>

---

### 📊 3D Contribution Wall

<div align="center">
  <img src="https://github-contributor-stats.vercel.app/api?username=zhonghui3&limit=5&theme=algolia&combine_all_yearly_contributions=true&hide_border=true" alt="3D Contribution Wall" />
</div>

---

### 📂 Featured Projects

<div align="center">
  <p>🌟 My open source projects are coming soon... 🌟</p>
  
  <!--
  <a href="https://github.com/zhonghui3/your-project">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=zhonghui3&repo=your-project&theme=algolia&bg_color=0d1117&hide_border=true" />
  </a>
  <a href="https://github.com/zhonghui3/your-project2">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=zhonghui3&repo=your-project2&theme=algolia&bg_color=0d1117&hide_border=true" />
  </a>
  -->
</div>

---

### 🤝 Connect With Me

<div align="center">
  <a href="mailto:kevinzz251216@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <!-- Add more social links here when you have them
  <a href="https://linkedin.com/in/yourusername">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://your-blog.com">
    <img src="https://img.shields.io/badge/Blog-FF7139?style=for-the-badge&logo=firefox-browser&logoColor=white" alt="Blog" />
  </a>
  -->
</div>

---

### 👋 Thanks for Visiting!

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer&text=End%20of%20Profile&fontSize=20&fontColor=ffffff&fontAlignY=65" />
</div>

<!-- 分隔线，明确标识自定义内容结束 -->
<div align="center">
  <sub>✨ Custom profile content ends here • Below are GitHub default sections ✨</sub>
  <br><br><br>
</div>

<!-- 随机开发笑话
![Jokes Card](https://readme-jokes.vercel.app/api?theme=algolia)
-->
