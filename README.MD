# Hi, I'm Luis Gonzalez <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Hi.gif" width="29px">
# My activity on Github
![GitHub Activity Graph](https://activity-graph.herokuapp.com/graph?username=luisdgd07&theme=dracula&hide_border=true)

# My statistics
## Stats📈
<p align="center">
<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs?username=luisdgd07&show_icons=true&theme=dracula&title_color=ff8000&text_color=ffffff&bg_color=6a6a6a&locale=en&layout=compact&hide_border=true" alt="#luisdgd07" /> 
<img width="48%" src="https://github-readme-stats.vercel.app/api?username=luisdgd07&show_icons=true&theme=dracula&title_color=ff8000&text_color=ffffff&bg_color=6a6a6a&locale=en&hide_border=true" alt="luisdgd07" />
<img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=luisdgd07&theme=highcontrast&hide_border=true" alt="luisdgd07" />
</p>

name: Update README

on:
  schedule:
    - cron: '*/30 * * * *'
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: Update this repo's README with recent activity

    steps:
      - uses: actions/checkout@v2
      - uses: jamesgeorge007/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
<!--START_SECTION:activity-->
<!--END_SECTION:activity-->
Donate to me 💰
https://bit.ly/3B3svnr
