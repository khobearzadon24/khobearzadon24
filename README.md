<!-- Header  -->

![Header](./github-header-image.png)

<!-- Coding Skills -->

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)

<!-- Waka Time -->

<!--START_SECTION:waka-->

name: Waka Readme

on:
schedule: # Runs at 12am IST - cron: '30 18 \* \* \*'
workflow_dispatch:
jobs:
update-readme:
name: Update Readme with Metrics
runs-on: ubuntu-latest
steps: - uses: anmol098/waka-readme-stats@master
with:
WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
GH_TOKEN: ${{ secrets.GH_TOKEN }}

- uses: anmol098/waka-readme-stats@master
with:
WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
GH_TOKEN: ${{ secrets.GH_TOKEN }}
SHOW_OS: "False"
SHOW_PROJECTS: "False"
SECTION_NAME: "Progress Tracker"
SHOW_UPDATED_DATE : "True"
SHOW_DAYS_OF_WEEK : "False"
SHOW_PROJECTS : "False"
SHOW_LANGUAGE_PER_REPO: "False"
SHOW_LOC_CHART: "False"
<!--END_SECTION:waka-->
