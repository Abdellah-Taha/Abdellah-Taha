<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:2C5364,100:00C9A7&height=200&section=header&text=Abdellah-Taha%20Zirari&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20%26%20DevOps%20%7C%20Systems%20%26%20Algorithms&descAlignY=55&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2500&pause=800&color=00C9A7&center=true&vCenter=true&multiline=true&repeat=true&width=650&height=60&lines=Valar;42+Student+%40+1337+Rabat+(UM6P);Exploring+AI+%2F+ML+Systems;Learning+DevOps+%26+Cloud+Infra;Building+%40+Algorithms+%26+Systems" alt="Typing SVG" />
</a>

<img src="https://komarev.com/ghpvc/?username=Abdellah-Taha&label=Profile%20Views&color=00C9A7&style=flat" alt="profile views"/>

</div>

<br/>

## 👨‍💻 About Me

```yaml
🎓 Education: Bachelor's in Computer Science (SMI, Faculté des Sciences Rabat)
📚 Currently: 42 curriculum at 1337, UM6P Rabat
🤖 Focus: AI/ML systems, small-model inference, constrained decoding
⚙️ DevOps: Learning containerization, CI/CD pipelines, Linux infrastructure
💻 Low-Level: Memory management and concurrency in C
🐍 Python: Graph algorithms, real-time visualization, typed pipelines
🧪 Standards: Strict mypy, flake8-clean code, readable READMEs
🐧 Environment: Linux / WSL
```

<br/>

## 🚀 Featured Projects

<details>
  <summary><b>🛩️ Fly-in — Drone Fleet Routing Simulator</b> (Click to expand)</summary>
  <br/>
  Multi-drone routing over a weighted graph of hubs (normal / restricted / priority / blocked zones), minimizing total turns to destination.
  <ul>
    <li>Two-phase offline scheduling: <b>penalized repeated Dijkstra</b> for path planning, <b>weighted round-robin</b> for drone assignment</li>
    <li>Staggered departures + live Dijkstra fallback on unexpected blocks</li>
    <li>Real-time <b>Arcade</b> renderer with coordinate normalization and frame-interpolated movement</li>
    <li>mypy strict + flake8-clean across 4 modules</li>
  </ul>
  <a href="https://github.com/Abdellah-Taha/Fly-in">🔗 View Repository</a>
</details>

<details>
  <summary><b>🧠 call_me_maybe — Function Calling with Small LLMs</b> (Click to expand)</summary>
  <br/>
  Translates natural-language prompts into schema-compliant JSON function calls using <b>Qwen3-0.6B</b>.
  <ul>
    <li>Constrained decoding via prefix-tree function-name selection</li>
    <li>Type-constrained parameter generation + JSON repair logic</li>
    <li>Pydantic-validated output schemas</li>
  </ul>
  <a href="https://github.com/Abdellah-Taha/call_me_maybe">🔗 View Repository</a>
</details>

<details>
  <summary><b>🧵 Codexion — Multi-threaded C Simulation</b> (Click to expand)</summary>
  <br/>
  Concurrency-focused simulation in C, handling synchronization and logging across multiple threads.
  <ul>
    <li>Mutexes and condition variables for thread coordination</li>
    <li>Race-free logging pipeline</li>
  </ul>
  <a href="https://github.com/Abdellah-Taha/codexion">🔗 View Repository</a>
</details>

<details>
  <summary><b>🌱 What's Next?</b> (Click to expand)</summary>
  <br/>
  Currently pointed toward AI infrastructure and DevOps — containerizing projects, wiring up CI/CD, and exploring ML deployment pipelines.
</details>

<br/>

## 🛠️ Languages & Tools

<div align="center">

<img src="https://skillicons.dev/icons?i=c,python,docker,linux,git,github,bash,vscode&theme=dark" />

<br/><br/>

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

<br/>

## 📊 GitHub Stats & Trophies

<div align="center">

<img height="160" src="https://github-profile-trophy.vercel.app/?username=Abdellah-Taha&theme=dracula&column=4&margin-w=15&margin-h=15&no-bg=true" alt="trophies" />

<br/><br/>

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Abdellah-Taha&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abdellah-Taha&layout=compact&theme=tokyonight&hide_border=true" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Abdellah-Taha&theme=tokyonight&hide_border=true" />

</div>

<br/>

## 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/Abdellah-Taha/Abdellah-Taha/output/github-contribution-grid-snake.svg" alt="snake animation" />

</div>

<details>
  <summary><b>ℹ️ How to setup the contribution snake</b> (Click to expand)</summary>
  <br/>
  The snake animates your real contribution graph and needs a one-time GitHub Action setup. 
  Create a file named <code>snake.yml</code> in <code>.github/workflows/</code> of your profile repo, then it auto-updates daily.
  
  ```yaml
  name: Generate Snake
  on:
    schedule:
      - cron: "0 0 * * *" # Runs daily
    workflow_dispatch:
  jobs:
    build:
      runs-on: ubuntu-latest
      steps:
        - uses: Platane/snk@master
          with:
            github_user_name: Abdellah-Taha
            outputs: |
              dist/github-contribution-grid-snake.svg
              dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        - uses: crazy-max/ghaction-github-pages@v3.1.0
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  ```
</details>

<br/>

## 📫 Get in Touch

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/taha-zirari-2a8178238/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdellahzirari2005@gmail.com)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9A7,100:0F2027&height=100&section=footer" width="100%"/>

<div align="center">⭐️ From <a href="https://github.com/Abdellah-Taha">Abdellah-Taha</a></div>
````
