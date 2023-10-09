### Hi there 👋
![Header](./github-header-image.png)

# I'm a FullStack Developer

- 🔭 I’m currently working on mxa_frontend & mxa_backend
- 🌱 I’m currently learning TypeScript
- 👯 I’m looking to collaborate on projects
- 📫 How to reach me: estebanc_b@hotmail.com  
- 😄 Pronouns: Tebi
- ⚡ Fun fact: i don't know how many pairs are three boots


<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
<!--END_SECTION:waka-->
