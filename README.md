:raised_hand: Me chamo Marcelo :computer:

:small_blue_diamond:Trabalho na area de TI <br/>
:small_blue_diamond:Sou Tecnico de Suporte em TI<br/>
:small_blue_diamond:Trabalho atualmente no Sabin Medicina Diagnostica na cidade de Uberlândia-MG<br/>
:small_blue_diamond:Estou no penultimo periodo de Sistema de Informação<br/>
:small_blue_diamond:Estou buscando conhecimento em Python<br/>
:small_blue_diamond:Tenho conhecimento na introdução HTML e CSS<br/>
:small_blue_diamond:Futuramente vou estudar JavaScript<br/>
<img src=https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Earth.gif width="30">

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=MarceloMederi&show_icons=true&theme=radical)
![Top Langs](https://github-readme-streak-stats.herokuapp.com/?user=MarceloMederi&show_icons=true&theme=radical)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=MarceloMederi&show_icons=true&theme=radical)](https://github.com/MarceloMederi/github-readme-stats)
![Top Langs](https://github-profile-trophy.vercel.app/?username=MarceloMederi&show_icons=true&theme=radical)

![Top Langs](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2F{MarceloMederi}1212%2Fhit-counter)


![Anurag's GitHub stats](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Anurag's GitHub stats](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Anurag's GitHub stats](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Anurag's GitHub stats](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Anurag's GitHub stats](https://img.shields.io/badge/Scratch-4D97FF?style=for-the-badge&logo=Scratch&logoColor=white)
![Anurag's GitHub stats](https://img.shields.io/badge/Cent%20OS-262577?style=for-the-badge&logo=CentOS&logoColor=white)
![Anurag's GitHub stats](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)




Instagram: marcelomederi11

![snake gif](https://github.com/Formandodev/Formandodev/blob/output/github-contribution-grid-snake.svg)

# Nome da Actions:  
name: Snake Game

# Controlador do tempo que sera feito a atualização dos arquivos.
on:
  schedule:
      # Será atualizado a cada 5 horas.
    - cron: "0 */5 * * *"

# Permite executar na na lista de Actions (utilizado para testes de build).
  workflow_dispatch:

# Regras
jobs:
  build:
    runs-on: ubuntu-latest
    steps:

    # Checks repo under $GITHUB_WORKSHOP, so your job can access it
      - uses: actions/checkout@v2

    # Repositorio que será utilizado para gerar os arquivos.
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: MarceloMederi #Seu usuario
          gif_out_path: dist/github-contribution-grid-snake.gif
          svg_out_path: dist/github-contribution-grid-snake.svg

      - run: git status

      # Para as atualizações.
      - name: Push changes
        uses: ad-m/github-push-action@master
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          branch: master
          force: true

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          # the output branch we mentioned above
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<!---
MarceloMederi/MarceloMederi is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
