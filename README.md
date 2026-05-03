<!-- Commit header.svg to this repo, then the image below will render -->
<img src="https://raw.githubusercontent.com/Sellesta/Sellesta/main/header.svg" alt="Moses Wanjema — ML Engineer · Data Engineer · AI Builder" width="100%"/>

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
