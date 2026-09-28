# ⚡ Gabriel Willian — Personal Portfolio & Resume

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Portfólio moderno, minimalista e de alta performance inspirado no design editorial suíço.**  
Projetado para apresentar cases de software corporativo, hiperautomação de processos (RPA), aplicações web sob medida e inteligência artificial aplicada.

[Ver Demonstração Online ↗](#-publicação-e-deploy) · [Reportar Bug](https://github.com/gabrielwillianfb/portfolio/issues) · [Solicitar Orçamento](https://wa.me/5547991485201)

</div>

---

## 📌 Visão Geral

Este projeto é uma réplica refinada do modelo de portfólio pessoal **Clean Personal Resume** ([Figma Reference](https://public-buzz-pure.figma.site/)), construído exclusivamente com tecnologias web nativas (**HTML5 Semântico e CSS Moderno Puro**). 

O foco é eliminar bibliotecas desnecessárias para atingir **pontuação máxima no Google PageSpeed (100/100)**, tempo de carregamento inferior a meio segundo e uma experiência de leitura limpa tanto no desktop quanto no mobile.

```
┌──────────────────────────────────────┬───────────────────────────────────────────────────────┐
│ GABRIEL WILLIAN,                     │ CASES & PROJETOS DE DESTAQUE                          │
│ Desenvolvedor de Software Fullstack  │ ───────────────────────────────────────────────────── │
│                                      │ 1. Plataforma de Hiperautomação (RPA Empresarial)     │
│ ┌──────────────────────────────────┐ │ 2. ConfixBuild — Landing Page Comercial (GSAP / React)│
│ │ Bio: Sistemas de Informação      │ │ 3. NutriPersona AI — Plataforma Nutricional (Angular & Nest) │
│ │ (UNIASSELVI) + IA Generativa     │ │ 4. Deep Learning Captcha OCR (PyTorch CRNN / 15ms)    │
│ └──────────────────────────────────┘ │ 5. Trading AI Platform (FastAPI / XGBoost / Docker)   │
│                                      │                                                       │
│ • gabriel.beck03@gmail.com ↗         │ SERVIÇOS & OFERTAS                                    │
│ • WhatsApp (Conversar) ↗             │ • Automação Empresarial & RPA                         │
│ • LinkedIn ↗                         │ • Sistemas Web Sob Medida & Dashboards                │
│ • GitHub ↗                           │ • Landing Pages Comerciais                            │
│                                      │ • APIs, Integrações & Inteligência Artificial         │
└──────────────────────────────────────┴───────────────────────────────────────────────────────┘
```

---

## 📂 Estrutura de Arquivos

```text
portfolio/
├── index.html        # Página inicial com os 5 cases, serviços, skills e links de contato
├── about.html        # Página "Sobre Mim" com trajetória, valores e metodologia de atendimento
├── styles.css        # Design System completo (Dark Mode puro, tipografia Google Fonts, responsividade)
└── README.md         # Documentação completa do projeto
```

---

## 🎨 Design System & Estética

- **Tema:** Dark Mode editorial puro (`#000000`).
- **Separadores:** Linhas sutis com borda de `0.5px` a `1px` em tom grafite neutro (`#383838`).
- **Tipografia:**
  - *Títulos e Destaques:* **Schibsted Grotesk** (Google Fonts) — proporções equilibradas e alta legibilidade.
  - *Corpo e Textos de Apoio:* **Geist** (Google Fonts) — moderna, geométrica e limpa.
- **Layout Responsivo:**
  - *Desktop (≥ 1024px):* Duas colunas com barra lateral esquerda **sticky** (perfil e contatos visíveis durante toda a rolagem da página).
  - *Mobile (< 1024px):* Coluna única fluida com empilhamento vertical suave e áreas de clique confortáveis para touch.

---

## 💼 Projetos em Destaque no Portfólio

1. **Plataforma Corporativa de Hiperautomação (RPA):**
   - Orquestração de mensageria assíncrona distribuída com RabbitMQ e parque de workers/VMs.
   - Gestão segura de credenciais integrando cluster HashiCorp Vault com controle de acesso estrito (RBAC).
   - Dashboard executivo em tempo real com cálculo de ROI e economia de mais de 70% do tempo manual.
2. **ConfixBuild — Landing Page Comercial ([Demo Online ↗](https://confixbuild.vercel.app/)):**
   - Interface comercial de alta conversão para o segmento de construção e reformas.
   - Animações fluidas com a biblioteca GSAP, alternância de tema Dark/Light e metodologia BEM CSS.
3. **NutriPersona AI — Plataforma de Inteligência Nutricional:**
   - Web App interativo em Angular 20 (Signals e Standalone) com backend modular em NestJS 11.
   - Algoritmos clínicos (Mifflin-St Jeor), curadoria inteligente por IA, lista de compras e PDFs vetoriais com jsPDF.
4. **Deep Learning Captcha OCR Engine:**
   - Modelo de Visão Computacional em PyTorch (CRNN: CNN + BiLSTM + CTC Loss).
   - Inferência de 15ms sem dependência de APIs externas pagas e gerador sintético de 100k imagens.
5. **Trading AI & Quant Analytics Platform:**
   - Backend assíncrono em Python 3.12 com FastAPI, SQLAlchemy 2.0 Async e PostgreSQL 16.
   - Feature engineering financeiro, modelos XGBoost e travas de segurança com Kill Switch.

---

## 🚀 Como Executar Localmente

Como o projeto é construído em HTML5 e CSS nativos, **não há necessidade de instalar dependências nem rodar comandos de build (`npm install` ou `npm run build`)**.

### Opção 1: Abrir diretamente no navegador
Dê um duplo clique no arquivo `index.html`.

### Opção 2: Servidor local com Python
No terminal, dentro da pasta `portfolio`:
```bash
python -m http.server 8080
```
Acesse em seu navegador: `http://localhost:8080`

### Opção 3: Extensão Live Server (VS Code / Antigravity)
Clique com o botão direito em `index.html` e selecione **Open with Live Server**.

---

## 🌐 Publicação e Deploy Gratuito

### 🟢 Deploy na Vercel (Recomendado — Menos de 1 minuto)

1. Crie um repositório no seu GitHub chamado `portfolio` e envie os arquivos desta pasta:
   ```bash
   git init
   git add .
   git commit -m "feat: portfolio minimalista inicial"
   git branch -M main
   git remote add origin https://github.com/gabrielwillianfb/portfolio.git
   git push -u origin main
   ```
2. Acesse [vercel.com](https://vercel.com/) e faça login com seu GitHub.
3. Clique em **Add New Project**, selecione o repositório `portfolio`.
4. Deixe as opções padrão e clique em **Deploy**.
5. Seu portfólio estará online com certificado HTTPS automático (ex: `gabrielwillian.vercel.app`).

### 🐙 Deploy no GitHub Pages

1. No repositório no GitHub, vá em **Settings** > **Pages**.
2. Em **Build and deployment > Source**, selecione **Deploy from a branch**.
3. Em **Branch**, selecione `main` e a pasta `/(root)`.
4. Clique em **Save**. O site será publicado em `https://gabrielwillianfb.github.io/portfolio`.

---

## 👨‍💻 Autor

**Gabriel Willian Fernandes Beck**  
Desenvolvedor de Software Fullstack & Especialista em Automação  
*Graduando em Sistemas de Informação (UNIASSELVI) & Estudioso de Inteligência Artificial Generativa*

- 💬 WhatsApp: [(47) 99148-5201](https://wa.me/5547991485201)
- 💼 LinkedIn: [linkedin.com/in/gabrielwillianfb](https://www.linkedin.com/in/gabrielwillianfb/)
- 🐙 GitHub: [github.com/gabrielwillianfb](https://github.com/gabrielwillianfb)
- ✉️ Email: [gabriel.beck03@gmail.com](mailto:gabriel.beck03@gmail.com)

---

## 📄 Licença

Este projeto está sob a licença [MIT](https://opensource.org/licenses/MIT). Sinta-se livre para utilizar como referência ou base para o seu próprio portfólio!
