## Hi there 👋
![Harbertw's GitHub stats](https://github-readme-stats.vercel.app/api?username=Harbertw&theme=dark&show_icons=true)

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

name: Update WakaTime Stats

on:
  schedule:
    - cron: "0 0 * * *" # Ежедневное обновление
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}


<!--
**harbertw/harbertw** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
### 📊 Weekly Development Breakdown

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->


Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
