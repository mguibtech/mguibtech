<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=26&pause=1000&color=AD0DD9&center=true&vCenter=true&width=600&lines=Ol%C3%A1%2C+sou+Marcos+Guibson+%F0%9F%91%8B;Full+Stack+Developer;React+Native+%7C+NestJS+%7C+TypeScript;Apaixonado+por+resolver+problemas+reais" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/marcos-guibson-santos-da-silva-0b62321a3/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:mguibtch@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://instagram.com/guib_tech" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
  </a>
  <a href="https://www.twitch.tv/mguib" target="_blank">
    <img src="https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white"/>
  </a>
</p>

---

## 👨‍💻 Sobre mim

Sou desenvolvedor **full stack** do Amazonas, com foco em **React Native**, **NestJS** e **TypeScript**. Construo aplicações que resolvem problemas reais — especialmente no contexto amazônico, onde tecnologia ainda tem muito espaço para transformar a vida das pessoas.

Minha jornada começou em 2017 na **Universidade do Estado do Amazonas**, onde me apaixonei por desenvolvimento de jogos com **Unity 3D** e **Construct**. Logo depois entrei para o **LUDUS Lab** como desenvolvedor mobile, experiência que consolidou meu interesse pelo ecossistema JavaScript/TypeScript e por interfaces que de fato encantam o usuário.

Hoje curso **Engenharia de Software na FUCAPI** — Manaus/AM — e desenvolvo o **NavegaJá**, meu principal projeto: uma plataforma que moderniza o transporte fluvial na Amazônia, servindo passageiros, capitães e remetentes de encomendas.

---

## 🚀 Stack

**Mobile & Frontend**

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

**Backend & Infraestrutura**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00f?style=for-the-badge&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)

**UI & Design**

![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-hotpink?style=for-the-badge&logo=SASS&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

**Qualidade & Ferramentas**

![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-026AA7?style=for-the-badge&logo=Trello&logoColor=white)

---

## 🛥️ Projeto em Destaque — NavegaJá

> **Plataforma marketplace para modernizar o transporte fluvial na Amazônia**

O NavegaJá conecta **passageiros**, **capitães de barco** e **remetentes de encomendas** em uma solução digital construída para a realidade de quem vive na região amazônica — onde o rio é a principal via de transporte. Disponível tanto como **app mobile** quanto como **plataforma web**.

### Arquitetura

```
┌─────────────────┐   ┌─────────────────┐
│  React Native   │   │    React Web    │  ← Mobile (iOS/Android) + Web
└────────┬────────┘   └────────┬────────┘
         └──────────┬──────────┘
                    │ HTTPS / REST
                    ↓
         ┌─────────────────┐
         │   NestJS API    │  ← Backend (TypeORM + PostgreSQL)
         └────────┬────────┘
                  │
             ┌────┴────┐
             ↓         ↓
      ┌──────────┐ ┌──────┐
      │PostgreSQL│ │AWS S3│  ← Persistência + Armazenamento
      └──────────┘ └──────┘
```

### Principais funcionalidades
- 🎫 Reserva de passagens com ticket digital e QR Code
- 📦 Sistema de encomendas com rastreamento em tempo real
- 💳 Pagamentos via PIX e cartão
- 🪙 NavegaCoins — programa de fidelidade nativo
- 🔔 Notificações push via Firebase Cloud Messaging
- 📍 Visualização de rotas com react-native-maps
- 🌐 Plataforma web acessível via browser (React)

### Impacto acadêmico
- 🎓 TCC — Engenharia de Software (FUCAPI)
- 📄 Artigo científico em preparação para conferências (SBSI, IHC, CSBC)
- 🏆 Validado como projeto com potencial de publicação e pós-graduação

---

## 📊 Atividade no GitHub

<div align="center">

[![GitHub followers](https://img.shields.io/github/followers/mguibtech?label=Followers&style=for-the-badge&color=AD0DD9&labelColor=1a1a2e)](https://github.com/mguibtech)
[![GitHub User's stars](https://img.shields.io/github/stars/mguibtech?label=Stars+totais&style=for-the-badge&color=AD0DD9&labelColor=1a1a2e)](https://github.com/mguibtech)

</div>

> 💡 Para ver estatísticas detalhadas, acesse **[github.com/mguibtech](https://github.com/mguibtech)**

---

<p align="center">
  <i>Aberto a novas oportunidades — fique à vontade para me chamar! 🚀</i>
</p>
