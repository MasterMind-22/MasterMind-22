<p>
name: user-statistician

on:
  schedule:
    - cron: '0 3 * * *'
  workflow_dispatch:

jobs:
  stats:
    runs-on: ubuntu-latest
      
    steps:
    - uses: actions/checkout@v2

    - name: Generate the user stats image
      uses: cicirello/user-statistician@v1
      with:
        colors: dark-dimmed
        custom-title: My GitHub Statistics
        hide-keys: joined, mostStarred, mostForked, followers, following, private
        max-languages: 100
        animated-language-chart: true
      env:
        GITHUB_TOKEN: ${{secrets.GITHUB_TOKEN}}
</p>
<p align="center">
  <img src="https://badge.mediaplus.ma/levi/yonadry" alt="yonadry's 42 stats" /></a>
</p>

<br><br>
# 💻 Languages and Tools:
<p align="left"> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> </p>

  <br><br>
# 📊 GitHub Stats:
[![Yonadry's GitHub stats](https://github-readme-stats.vercel.app/api?username=MasterMind-22)](https://github.com/MasterMind-22/github-readme-stats)
![](https://github-readme-streak-stats.herokuapp.com/?user=MasterMind-22&theme=tokyonight&hide_border=false)<br/>


<br><br><br>
<img align="center" src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" />
