<img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=muhammadhardwinv.muhammadhardwinv" />

<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Hi+There!+👋;+I'm+Hardwin+Variansyah!;" />
</h1>

<h3 align="center">Empowering Digital Transformation through Computer Science and IT Development</h3>

<br/>

<div align="center">
 
 🔭 I’m currently working on **Binus University**
 
 🌱 I’m currently work as **Programmer Laboratory Assistant**

💬 Discuss with me about **Python, Javascript, PHP, ... or anything [here](https://github.com/muhammadhardwinv/muhammadhardwinv/issues)**

 </div>
 
<div align="center"> 
  <a href="mailto:mhardwin@outlook.com">
    <img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red" />
  </a>
  <a href="https://www.linkedin.com/in/muhammadhardwinv/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
  </a>
  <a href="https://github.com/muhammadhardwinv" target="_blank">
     <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white" target="https://github.com/muhammadhardwinv" /> <!-- sqlite, safari, google-chrome are other good icon options -->
  </a>
</div>

 <hr/>
 
<h2 align="center">⚒️ Languages-Frameworks-Tools ⚒️</h2>
<br/>
<div align="center">
    <img src="https://skillicons.dev/icons?i=react,bootstrap,html,css,vscode,github,figma,tailwind,git,r" />
    <img src="https://skillicons.dev/icons?i=nodejs,python,javascript,firebase,c,java,mysql" /><br>
</div>
<br/>
<hr/>

<div align="center">
  <h2>🐍 Most Used Language Lately 🐍</h2>
  <br>
   <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=muhammadhardwinv"/>
    <br/>
  <br/><br/><br/>
</div>
<div>
   name: generate animation

on:
  # run automatically every 24 hours
  schedule:
    - cron: "0 */24 * * *" 
  
  # allows to manually run the job at any time
  workflow_dispatch:
  
  # run on every push on the master branch
  push:
    branches:
    - master
    
  

jobs:
  generate:
    permissions: 
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5
    
    steps:
      # generates a snake game from a github user (<github_user_name>) contributions graph, output a svg animation at <svg_out_path>
      - name: generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
          
          
      # push the content of <build_dir> to a branch
      # the content will be available at https://raw.githubusercontent.com/<github_user>/<repository>/<target_branch>/<file> , or as github page
      - name: push github-contribution-grid-snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
</div>

<hr/>

<h2 align="center">⚡ Stats ⚡</h2>
<a href="https://git.io/streak-stats"><img src="https://streak-stats.demolab.com?user=muhammadhardwinv&theme=radical&card_width=1000" alt="GitHub Streak" /></a>
<br>
<div align=center>
  
</div>

<br/><br/>

<hr/>

<br/>
</div>
<br/>

