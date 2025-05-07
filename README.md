<div align="center">
  
  <!-- Animated Header -->
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=7A3FF7&background=45FF8E00&center=true&vCenter=true&width=435&lines=Hi+👋,+I'm+irawanap;Full+Stack+Developer;Open+Source+Contributor" alt="Typing Animation" />

  <!-- Snake Game -->
  ![Snake Game](https://github.com/irawanap/irawanap/blob/output/github-contribution-grid-snake.svg)

  <!-- Animated Stats -->
  <div align="center">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=irawanap&show_icons=true&theme=radical&count_private=true&hide_border=true&animated=true" />
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=irawanap&layout=compact&theme=radical&hide_border=true&animated=true" />
  </div>

  <!-- Animated Skills -->
  <h3>🛠 Tech Stack</h3>
  <div>
    <img src="https://skillicons.dev/icons?i=js,react,nodejs,py,go,mysql,mongodb,firebase&theme=dark&animate=true" />
    <br/>
    <img src="https://skillicons.dev/icons?i=git,github,vscode,figma,gcp,docker&theme=dark&animate=true" />
  </div>

  <!-- Contact -->
  <h3>📫 Connect</h3>
  <p>
    <a href="https://linkedin.com/in/irawanajipangestu">
      <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-irawanaajipangestu-blue?style=for-the-badge&logo=linkedin&logoColor=white" />
    </a>
    <a href="mailto:irawanajhi22@gmail.com">
      <img alt="Email" src="https://img.shields.io/badge/Email-Contact%20Me-red?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
  </p>

  <!-- Visitor Counter -->
  <p align="center"> 
    <img src="https://profile-counter.glitch.me/irawanap/count.svg" alt="Visitor Counter" /> 
  </p>

</div>


name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *"
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: Platane/snk@master
        with:
          github_user_name: irawanap
          svg_out_path: ./output/github-contribution-grid-snake.svg
      - uses: EndBug/add-and-commit@v9
        with:
          message: "Update snake"
