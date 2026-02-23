# Olá, eu sou Felipe Cagnin! 👋

### Desenvolvedor Full Stack | Graduando em Ciência da Computação (UNIP)

Unindo a precisão da formação técnica pelo **SENAI** com o aprofundamento acadêmico em **Ciência da Computação pela UNIP (Jundiaí)**. Minha atuação é focada no ecossistema **Laravel & Vue.js**, com forte interesse em arquitetura de sistemas, escalabilidade e a interação profunda entre software e hardware.

---

### 🚀 Especialidades & Foco Técnico

- **Backend & APIs:** Desenvolvimento de soluções robustas com **PHP (Laravel)** e **Node.js**, aplicando padrões de projeto e foco em segurança.
- **Frontend Moderno:** Interfaces reativas e performáticas com **Vue.js**, **React** e ecossistema mobile com **React Native**.
- **Data & Performance:** Estudo constante sobre otimização de bancos de dados relacionais e eficiência de algoritmos.
- **Infraestrutura:** Entendimento de redes, servidores e como o código impacta o ambiente físico de processamento.

---

### 🛠 Stack Tecnológica

#### Languages & Frameworks
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

#### Base & Web Essentials
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)

---

### 📈 Estatísticas de Desenvolvedor

name: Update README cards

on:
  schedule:
    - cron: "0 3 * * *" # Roda diariamente às 3 da manhã
  workflow_dispatch: # Permite rodar manualmente no botão "Run workflow"

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4

      - name: Generate stats card
        uses: readme-tools/github-readme-stats-action@v1
        with:
          card: stats
          # Aqui você coloca as opções que queríamos, como o tema e ícones
          options: username=${{ github.repository_owner }}&show_icons=true&theme=tokyonight&include_all_commits=true
          path: profile/stats.svg
          token: ${{ secrets.GITHUB_TOKEN }}

      - name: Generate languages card
        uses: readme-tools/github-readme-stats-action@v1
        with:
          card: languages
          options: username=${{ github.repository_owner }}&layout=compact&theme=tokyonight
          path: profile/langs.svg
          token: ${{ secrets.GITHUB_TOKEN }}

      - name: Commit cards
        run: |
          git config user.name "github-actions"
          git config user.email "github-actions@users.noreply.github.com"
          git add profile/*.svg
          git commit -m "Update README cards" || exit 0
          git push
---

### 🤝 Conecte-se Comigo
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://https://www.linkedin.com/in/felipe-cagnin)
[![E-mail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cagnin.lima.2007@gmail.com)

*"A verdadeira maestria no software vem de entender a abstração sem nunca esquecer a fundação física que a sustenta."*
