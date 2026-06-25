<div align="center">

<!-- Typing animation via readme-typing-svg -->
<a href="https://github.com/R1cardoSevero">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=3000&pause=1000&color=A855F7&center=true&vCenter=true&width=600&lines=Oi%2C+eu+sou+Ricardo+Severo+%F0%9F%91%8B;Dev+em+construção+%F0%9F%9A%80;Apaixonado+por+tecnologia+%F0%9F%92%BB;Sempre+aprendendo+algo+novo+%F0%9F%8C%B1" alt="Typing SVG" />
</a>

<br/>

<!-- Snake animation (requer GitHub Actions — instruções ao final) -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/R1cardoSevero/R1cardoSevero/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/R1cardoSevero/R1cardoSevero/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/R1cardoSevero/R1cardoSevero/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

## 🧑‍💻 Sobre mim

```typescript
const Ricardo = {
  nome:       "Ricardo Severo",
  localização: "Brasil 🇧🇷",
  foco:       ["Front-end", "HTML", "CSS","React","JavaScript"],
  hobbies:    ["Games 🎮","Tecnologia 💡"]
};
```

---

## 🚀 Tecnologias & Ferramentas

<div align="center">

### Domínio atual
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-%2361DAFB.svg?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-%23339933.svg?style=for-the-badge&logo=nodedotjs&logoColor=white)

### Ferramentas
![Git](https://img.shields.io/badge/Git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-%23007ACC.svg?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

---

## 📊 Minhas Estatísticas

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=R1cardoSevero&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=R1cardoSevero&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=R1cardoSevero&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub Streak"/>
</div>

---

## 🏆 Troféus

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=R1cardoSevero&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7" alt="Troféus"/>
</div>

---

## 🌐 Onde me encontrar

<div align="center">

[![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:seuemail@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://instagram.com)
[![Steam](https://img.shields.io/badge/Steam-%23000000.svg?style=for-the-badge&logo=steam&logoColor=white)](https://store.steampowered.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)

</div>

---

## 📈 Atividade recente

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=R1cardoSevero&bg_color=0D1117&color=A855F7&line=A855F7&point=FFFFFF&area=true&hide_border=true" alt="Gráfico de atividade"/>
</div>

---

<div align="center">

### 🎯 Uma frase que me define

> *"Todo especialista já foi um iniciante. O que importa é nunca parar de aprender."*

<br/>

<!-- Contador de visitas -->
![Visitas](https://komarev.com/ghpvc/?username=R1cardoSevero&color=a855f7&style=for-the-badge&label=VISITAS+AO+PERFIL)

<!-- Wave footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=A855F7&height=100&section=footer" width="100%"/>

</div>

<!--
═══════════════════════════════════════════════════════
  ⚠️  PARA ATIVAR A ANIMAÇÃO DA COBRA:
═══════════════════════════════════════════════════════
  1. Crie a pasta .github/workflows/ no seu repositório
  2. Dentro dela, crie o arquivo snake.yml com este conteúdo:

  name: Generate Snake Animation
  on:
    schedule:
      - cron: "0 0 * * *"
    workflow_dispatch:
  jobs:
    generate:
      runs-on: ubuntu-latest
      steps:
        - uses: Platane/snk/svg-only@v3
          with:
            github_user_name: ${{ github.repository_owner }}
            outputs: |
              dist/github-contribution-grid-snake.svg
              dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        - name: Push to output branch
          uses: crazy-max/ghaction-github-pages@v3.1.0
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

  3. Após o workflow rodar, as imagens estarão disponíveis!
═══════════════════════════════════════════════════════
-->
