<!-- Commit header.svg to this repo, then the image below will render -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 200" width="100%">
  <defs>
    <style>
      .hand {
        animation: wave 2.8s ease-in-out infinite;
        transform-box: fill-box;
        transform-origin: bottom center;
        display: inline-block;
      }
      @keyframes wave {
        0%, 45%, 100% { transform: rotate(0deg); }
        10%  { transform: rotate(16deg); }
        20%  { transform: rotate(-8deg); }
        30%  { transform: rotate(16deg); }
        38%  { transform: rotate(-4deg); }
      }
      .name {
        animation: fadeUp 0.9s cubic-bezier(0.16,1,0.3,1) 0.1s both;
      }
      .role {
        animation: fadeUp 0.9s cubic-bezier(0.16,1,0.3,1) 0.4s both;
      }
      .bar {
        animation: expand 0.9s cubic-bezier(0.16,1,0.3,1) 0.3s both;
        transform-origin: 120px center;
        transform: scaleX(0);
      }
      .dot1 { animation: pulse 3s ease-in-out 0s infinite; }
      .dot2 { animation: pulse 3s ease-in-out 0.6s infinite; }
      .dot3 { animation: pulse 3s ease-in-out 1.2s infinite; }
      .dot4 { animation: pulse 3s ease-in-out 1.8s infinite; }
      .dot5 { animation: pulse 3s ease-in-out 2.4s infinite; }
      @keyframes fadeUp {
        from { opacity: 0; transform: translateY(12px); }
        to   { opacity: 1; transform: translateY(0); }
      }
      @keyframes expand {
        from { transform: scaleX(0); }
        to   { transform: scaleX(1); }
      }
      @keyframes pulse {
        0%, 100% { opacity: 0.07; }
        50%       { opacity: 0.18; }
      }
    </style>
  </defs>

  <!-- Background -->
  <rect width="900" height="200" fill="#0d1117"/>

  <!-- Subtle grid dots (decorative) -->
  <circle cx="800" cy="40"  r="2" fill="#58a6ff" class="dot1"/>
  <circle cx="840" cy="80"  r="2" fill="#58a6ff" class="dot2"/>
  <circle cx="820" cy="130" r="2" fill="#58a6ff" class="dot3"/>
  <circle cx="860" cy="50"  r="1.5" fill="#58a6ff" class="dot4"/>
  <circle cx="780" cy="100" r="1.5" fill="#58a6ff" class="dot5"/>
  <circle cx="870" cy="160" r="1.5" fill="#58a6ff" class="dot1"/>
  <circle cx="750" cy="60"  r="1" fill="#58a6ff" class="dot2"/>
  <circle cx="760" cy="150" r="1" fill="#58a6ff" class="dot3"/>

  <!-- Waving hand emoji -->
  <text x="80" y="118"
        font-size="54"
        text-anchor="middle"
        class="hand">👋</text>

  <!-- Name -->
  <text x="120" y="102"
        font-family="'SF Pro Display','Helvetica Neue',Arial,sans-serif"
        font-size="42"
        font-weight="700"
        letter-spacing="-0.5"
        fill="#ffffff"
        class="name">Moses Wanjema</text>

  <!-- Blue underline that slides in -->
  <rect x="120" y="111" width="292" height="2.5" rx="1.25" fill="#1f6feb" class="bar"/>

  <!-- Role line -->
  <text x="120" y="145"
        font-family="'SF Pro Display','Helvetica Neue',Arial,sans-serif"
        font-size="15"
        font-weight="400"
        letter-spacing="0.3"
        fill="#8b949e"
        class="role">ML Engineer  ·  Data Engineer  ·  AI Builder</text>

  <!-- Bottom border line -->
  <rect x="0" y="196" width="900" height="1" fill="#21262d"/>
</svg>

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=Sellesta&color=1f6feb&style=flat-square&label=)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/moses-wanjema-a43253133/)
[![Hugging Face](https://img.shields.io/badge/HuggingFace-fcc72b?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/sellestas)
[![Portfolio](https://img.shields.io/badge/Portfolio-22c55e?style=flat-square&logo=notion&logoColor=white)](https://datascienceportfol.io/brilliantpenman)
[![Devpost](https://img.shields.io/badge/Devpost-003e54?style=flat-square&logo=devpost&logoColor=white)](https://devpost.com/Sellesta)

</div>

<br/>

I build at the intersection of data, ML, and clean software — from ETL pipelines and LLM fine-tuning to production APIs. Currently experimenting with Rust microservices and working with [@macroai](https://github.com/macroai). Open to remote opportunities.

**🏆 Hackathon winner** — Vet2TechChatbox · AI Chatbot Hackathon

<br/>

---

### Stack

[![Python](https://skillicons.dev/icons?i=py,ts,rust,go,nextjs,nestjs,tailwind,graphql,aws,postgres,docker&theme=dark)](https://skillicons.dev)

<br/>

---

### Projects

| | Project | Stack |
|---|---|---|
| 🏆 | **[Vet2TechChatbox](https://github.com/Sellesta/Vet2TechChatbox-)** — Hackathon-winning AI chatbot bridging veterans into tech | Python · GPT · FastAPI |
| 🤖 | **[AI Resume Ranker](https://github.com/Sellesta/Resume-Ranker)** — NLP screener that scores resumes with Transformers | Python · Hugging Face · Streamlit |
| 🔄 | **[Reddit Data Pipeline](https://github.com/Sellesta/Reddit-Data-Pipeline-with-Airflow-Celery-PostgreSQL-S3-AWS-Glue-Athena-and-Redshift)** — ETL from Reddit → Redshift via Airflow + AWS | Python · Airflow · S3 · Redshift |
| 🌍 | **[Language Tutor Bot](https://devpost.com/Sellesta)** — African language learning chatbot *(hackathon finalist)* | GPT-Neo · Twilio · FastAPI |
| 📊 | **[Canada Crime Dashboard](https://github.com/Sellesta/Visualizing-Canada-s-Crime-Stats-in-PowerBI)** — National crime data in PowerBI | Python · Jupyter · PowerBI |
| 🔌 | **[Softheon Integration](https://github.com/Sellesta/Softheon-Integration-Sandbox)** — Python + SQL pipeline → Softheon API | Python · SQL |

<br/>

---

### Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Sellesta&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&icon_color=1f6feb&title_color=58a6ff&hide_rank=true" height="140"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sellesta&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff" height="140"/>

<img src="https://streak-stats.demolab.com?user=Sellesta&theme=github-dark-blue&hide_border=true&background=0d1117&ring=1f6feb&fire=388bfd&currStreakLabel=58a6ff" width="48%"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Sellesta&theme=github-compact&bg_color=0d1117&color=58a6ff&line=1f6feb&point=388bfd&hide_border=true&area=true" width="100%"/>

</div>

<br/>

---

### Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sellesta/Sellesta/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Sellesta/Sellesta/output/github-contribution-grid-snake.svg"/>
    <img alt="Snake" src="https://raw.githubusercontent.com/Sellesta/Sellesta/output/github-contribution-grid-snake.svg"/>
  </picture>
</div>

<details>
<summary>Snake setup (one-time GitHub Action)</summary>

Create `.github/workflows/snake.yml`:

```yaml
name: Snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: Sellesta
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

<br/>

---

<div align="center">
  <sub>Building something ambitious? <a href="https://www.linkedin.com/in/moses-wanjema-a43253133/">Let's talk.</a></sub>
</div>
