<h2 align="center">Hi, I'm Katya <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28"></h2>
<p align="center">
  <b>AI Engineer · ML Engineer</b>
</p>

## 🔬 About Me

- I build LLM applications with RAG and tool-calling agents, and choose between designs by measuring them on test sets, not on a few demo questions.
- Conducting applied research at the **Czech University of Life Sciences Prague (ČZU)** focusing on machine learning methods, fuzzy mathematical modeling, and decision-support algorithms.
- Building production-grade ML/AI systems using **Python, PyTorch, PySpark, Azure, Docker & FastAPI**.
- I plan and design systems end to end: requirements, UML models, data model, API contract and release flow.

---

## 🏆 Featured Project

### [BeCoMe](https://github.com/caitlon/BeCoMe)
> Award winner, Best Publication and Applied Project competition, Agrarian Perspectives conference.  
> Live web app: [becomify.app](https://www.becomify.app) · Documentation: [docs.becomify.app](https://docs.becomify.app)

<p align="left">
  <img src="https://img.shields.io/badge/python-3.13+-3776AB?logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/fastapi-0.141+-009688?logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/react-19+-61DAFB?logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/typescript-6.0+-3178C6?logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/postgresql-16+-4169E1?logo=postgresql&logoColor=white" alt="PostgreSQL" />
</p>

Software that helps expert panels turn disagreement into a defensible decision under fuzzy uncertainty.
- An LLM assistant answers questions about the method and explains each project's result, seeing only what the user can see.
- RAG over the docs and the method papers: `bge-m3` embeddings in pgvector plus BM25, merged by reciprocal rank fusion. LLM-written chunk captions raised hit@5 on the development set from 73% to 87%.
- A tool-calling LangChain agent delivered about a quarter of the facts that a fixed retrieve-then-answer pipeline did on a sealed set of 80 questions, so production runs the pipeline.
- Evaluated on held-out and sealed question sets in English and Czech, with blinded LLM judges grading the answers.
- Models run in the EU on OVHcloud, and the server flags answers that cite a missing passage or give a number it cannot find in the sources.
- Implements the Best Compromise Mean method on triangular fuzzy numbers, with mean and median consensus and outlier-resistant disagreement metrics.
- Full-stack product with real-world case studies (flood prevention policy, COVID-19 budget allocation, cross-border mobility).

---

## 🛠️ Tech Stack

### GenAI & MLOps
<p align="left">
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangSmith" />
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow" />
</p>

### ML & AI Engineering
<p align="left">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,scikitlearn,opencv" alt="ML & AI Engineering" />
</p>

### Languages & Frameworks
<p align="left">
  <img src="https://skillicons.dev/icons?i=python" width="48" alt="Python" title="Python" />
  &nbsp;<img src="images/fastmcp.svg" width="48" alt="FastMCP" title="FastMCP" />
  &nbsp;<img src="https://skillicons.dev/icons?i=fastapi" width="48" alt="FastAPI" title="FastAPI" />
  &nbsp;<img src="https://skillicons.dev/icons?i=postgres" width="48" alt="PostgreSQL" title="PostgreSQL" />
  &nbsp;<img src="https://skillicons.dev/icons?i=bash" width="48" alt="Bash" title="Bash" />
</p>

### Cloud & Infrastructure
<p align="left">
  <img src="https://skillicons.dev/icons?i=azure,docker,githubactions,git" alt="Cloud & Infrastructure" />
</p>

---

## 📊 GitHub Stats & Activity

<div align="center">
  <!-- Streak Stats -->
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=caitlon&locale=en&mode=daily&theme=dracula&hide_border=false&border_radius=5" />
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=caitlon&locale=en&mode=daily&theme=default&hide_border=false&border_radius=5" />
    <img src="https://streak-stats.demolab.com?user=caitlon&locale=en&mode=daily&theme=default&hide_border=false&border_radius=5" height="150" alt="streak graph" />
  </picture>

  <!-- Top Languages -->
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/caitlon/caitlon/output/metrics/languages-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/caitlon/caitlon/output/metrics/languages-light.svg" />
    <img src="https://raw.githubusercontent.com/caitlon/caitlon/output/metrics/languages-light.svg" alt="languages graph" />
  </picture>

  <!-- Spotify Now Playing -->
  <p><i>helping me to survive</i></p>
  <a href="https://spotify-github-profile.kittinanx.com/api/view?uid=31axkco5wyfah2tdwrc4jlrxx6pi&redirect=true">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://spotify-github-profile.kittinanx.com/api/view?uid=31axkco5wyfah2tdwrc4jlrxx6pi&cover_image=true&theme=spotify-embed&show_offline=false&interchange=false&profanity=false&hide_remaster=true&bar_color=53b14f&bar_color_cover=false&mode=dark&background_color=121212" />
      <source media="(prefers-color-scheme: light)" srcset="https://spotify-github-profile.kittinanx.com/api/view?uid=31axkco5wyfah2tdwrc4jlrxx6pi&cover_image=true&theme=spotify-embed&show_offline=false&interchange=false&profanity=false&hide_remaster=true&bar_color=53b14f&bar_color_cover=false&mode=light&background_color=ffffff" />
      <img src="https://spotify-github-profile.kittinanx.com/api/view?uid=31axkco5wyfah2tdwrc4jlrxx6pi&cover_image=true&theme=spotify-embed&show_offline=false&interchange=false&profanity=false&hide_remaster=true&bar_color=53b14f&bar_color_cover=false&mode=light&background_color=ffffff" alt="Now playing on Spotify" />
    </picture>
  </a>
</div>

<!-- Snake Animation -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/caitlon/caitlon/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/caitlon/caitlon/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/caitlon/caitlon/output/github-snake.svg" />
</picture>
