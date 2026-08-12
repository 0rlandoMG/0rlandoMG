<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:0F766E,100:2563EB&height=210&section=header&text=Orlando%20Marrero%20Gonz%C3%A1lez&fontSize=40&fontColor=ffffff&fontAlignY=33&desc=AI%20Engineer%20%C2%B7%20Software%20Engineer&descAlignY=54&descSize=17&animation=fadeIn" width="100%" alt="Orlando Marrero González — AI Engineer & Software Engineer" />

<a href="https://orlandomarrero-dev.vercel.app/">
  <img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=2DD4BF&center=true&vCenter=true&width=700&lines=I+bring+LLMs+on-device%2C+no+cloud+required;Post-ASR+correction+%26+summarization+with+SLMs;Validated+with+stats%2C+not+vibes+(Wilcoxon%2C+BERTScore);Python+%7C+Java+%7C+PyTorch+%7C+Learning+LangGraph" alt="I bring LLMs on-device, no cloud required — post-ASR correction and summarization with SLMs — validated with stats, not vibes — Python, Java, PyTorch, learning LangGraph" />
</a>

<p>
  <img src="https://img.shields.io/badge/La_Habana,_Cuba-open_to_remote-0F766E?style=for-the-badge&logo=googlemaps&logoColor=white" alt="La Habana, Cuba — open to remote work" />
  <img src="https://img.shields.io/badge/Open_to-AI_/_Software_Engineer_roles-2563EB?style=for-the-badge&logo=handshake&logoColor=white" alt="Open to AI and Software Engineer roles" />
</p>

<p>
  <a href="https://orlandomarrero-dev.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=firefoxbrowser&logoColor=2DD4BF" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/orlando-marrero-g/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:0rlandomarrerog@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://wa.me/5356078084"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
</p>

</div>

---

## 👨‍💻 About me

I'm a **Software Engineer** with 2 years of experience shipping desktop and web applications, with hands-on work getting **small language models running fully on-device** — no cloud calls — inside a production speech-transcription product.

- 🎙️ **Junior Software Engineer @ Ingenius** — built the UI and internationalization for **Notus**, a Whisper/WhisperX-based transcription desktop app.
- 🧠 My undergraduate thesis integrated **Phi-4-mini** (quantized, GGUF, via `llama.cpp`) into Notus for **post-ASR correction** and **multi-style summarization**, running locally on ~3GB VRAM.
- 📐 I like knowing *why* something works: both modules were validated with **Wilcoxon signed-rank, Kruskal-Wallis, Mann-Whitney U, and BERTScore**, not eyeballed.
- 🎓 **B.Sc. Software Engineering @ CUJAE** (Havana), **Feb 2023 – Jun 2026**.
- 🏢 Also shipped a **Java/Spring Boot** backend and **Vue.js** frontend for a digital-transformation platform at **ETECSA**.
- 📚 Currently deepening **agentic AI** skills — **LangGraph** and multi-agent orchestration — to grow further into AI engineering.
- 🌍 Based in **Havana, Cuba**, open to **remote** roles.

---

## 📈 Results from my thesis work

Numbers from the on-device NLP modules I built for Notus, validated against a custom 10-audio Spanish corpus (~2.5h, human-verified transcripts).

| Result | What it means |
|:--|:--|
| **ΔF1p +0.0120, p = 0.0039** (Wilcoxon signed-rank) | Post-ASR correction module significantly restored punctuation vs. raw Whisper output, with only a small, controlled effect on transcription accuracy |
| **BERTScore F1 0.869** (95% CI 0.842–0.901) | Summaries stayed closely faithful to source content — near a much larger reference LLM — across all 3 styles × 3 lengths tested |
| **1 SLM, 2 tasks, 0 cloud calls** | Correction + summarization both run locally with Phi-4-mini (Q4_K_M, GGUF), ~3GB VRAM footprint |
| **3 languages** (ES / EN / FR) | i18n support I implemented for the Notus production interface |

---

## 🛠️ Tech stack

**AI / NLP & on-device inference**

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/llama.cpp-000000?style=flat-square" alt="llama.cpp" />
  <img src="https://img.shields.io/badge/Phi--4--mini-6E56CF?style=flat-square" alt="Phi-4-mini" />
  <img src="https://img.shields.io/badge/GGUF_/_Quantization-6E56CF?style=flat-square" alt="GGUF and quantization" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/Whisper_/_WhisperX-black?style=flat-square" alt="Whisper and WhisperX" />
  <img src="https://img.shields.io/badge/Prompt_Engineering-0F766E?style=flat-square" alt="Prompt Engineering" />
  <img src="https://img.shields.io/badge/Map--Reduce_Pipelines-0F766E?style=flat-square" alt="Map-Reduce pipelines" />
  <img src="https://img.shields.io/badge/Statistical_Validation-2563EB?style=flat-square" alt="Statistical validation" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-learning-1C3C3C?style=flat-square&logo=langgraph&logoColor=white" alt="LangGraph — learning" />
</p>

**Languages, frameworks & backend**

<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,java,c,cpp,js&theme=dark" alt="Python, Java, C, C++, JavaScript" />
  </a>
</p>
<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=spring,fastapi,nestjs,vue,postgres,sqlite&theme=dark" alt="Spring Boot, FastAPI, Nest.js, Vue.js, PostgreSQL, SQLite" />
  </a>
</p>

**Tools & infra**

<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,github,docker,linux&theme=dark" alt="Git, GitHub, Docker, Linux" />
  </a>
</p>

---

## 🔭 Featured work

<table>
<tr>
<td width="50%" valign="top">

### 🎙️ Notus — On-Device NLP Modules

![Thesis](https://img.shields.io/badge/Undergraduate_thesis-0D1117?style=for-the-badge&logo=googlescholar&logoColor=2DD4BF)

Post-ASR correction and multi-style summarization for a production speech-transcription app, running **fully on-device** with **Phi-4-mini**. Correction uses a chunk-level validation pipeline to control hallucination risk; summarization covers 3 styles × 3 lengths via Map-Reduce to work around the model's context window.

Validated with **Wilcoxon**, **Kruskal-Wallis**, **Mann-Whitney U** and **BERTScore** on a self-built Spanish audio corpus.

`Python` · `PyTorch` · `Flet` · `Phi-4-mini` · `llama.cpp` · `WhisperX`

</td>
<td width="50%" valign="top">

### 🏢 Tetradig — Digital Transformation Assessment

[![Repo](https://img.shields.io/badge/View_repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/0rlandoMG/Tetr4dig-digital-transformation-assessment)

Desktop platform for **ETECSA** (Cuba's national telecom) that scores companies' digital-transformation maturity across dimensions, perspectives, and areas — replacing a manual, spreadsheet-based process. Delivered with a 3-person team over nine months.

Modeled the shared PostgreSQL schema, built backend logic, and implemented the Java Swing interface, plus parts of the companion web frontend.

`Java 22` · `Java Swing` · `PostgreSQL` · `Vue.js`

</td>
</tr>
</table>

<details>
<summary><b>🚧 In progress</b></summary>

<br />

**LangGraph Agent** *(coming soon)* — an agentic project focused on multi-agent orchestration and tool use, part of my move into agentic AI. Repository link will be added once it ships.

`LangGraph` · `AI Agents` · `Prompt Engineering`

</details>

---

## 💼 Experience

<details open>
<summary><b>Timeline</b></summary>

<br />

**🎙️ Junior Software Engineer — Ingenius** · *2024 – 2026 · ~2 years · Full-time*
> Built and maintained the UI for **Notus**, a Whisper/WhisperX-based transcription desktop app (Flet), and shipped **i18n support in Spanish, English, and French**. For my undergraduate thesis, designed and integrated two on-device NLP modules powered by **Phi-4-mini** running locally via `llama.cpp` — a post-ASR correction pipeline and a Map-Reduce summarizer — both validated with non-parametric statistical tests.
> `Python` `PyTorch` `Flet` `Phi-4-mini` `llama.cpp` `WhisperX` `i18n`

**🏢 Full-Stack Developer — ETECSA** · *Aug 2024 – Nov 2024 · Contract*
> Collaborated on the database design and backend for a digital-transformation assessment platform, as part of a 3-developer team. Built the desktop UI in Java Swing and the web-facing UI in Vue.js.
> `Java` `Java Swing` `Spring Boot` `PostgreSQL` `SQLite` `Vue.js`

</details>

---

## 📊 GitHub stats

<div align="center">

<img width="49%" src="https://github-readme-stats-sigma-five.vercel.app/api?username=0rlandoMG&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&show_icons=true&bg_color=0D1117&title_color=2DD4BF&icon_color=2563EB" alt="Orlando's GitHub stats" />
<img width="49%" src="https://streak-stats.demolab.com/?user=0rlandoMG&theme=tokyonight&hide_border=true&background=0D1117&stroke=2DD4BF&ring=2563EB&fire=F0883E&currStreakLabel=2DD4BF" alt="Orlando's contribution streak" />

<img width="42%" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=0rlandoMG&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&layout=compact&bg_color=0D1117&title_color=2DD4BF&langs_count=10" alt="Most used languages" />

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=0rlandoMG&bg_color=0D1117&color=2DD4BF&line=2563EB&point=FFFFFF&area=true&hide_border=true&custom_title=Contribution%20activity" alt="Contribution activity graph" />

</div>

---

## 🎓 Education & languages

**B.Sc. Software Engineering** — Ciudad Universitaria José Antonio Echeverría (**CUJAE**) · *Feb 2023 – Jun 2026*
Undergraduate thesis: *On-Device NLP Modules for Notus — Post-ASR Correction & Summarization with Phi-4-mini*

**Languages** — Spanish (native) · English (A2, certified by CUJAE)

---

<div align="center">

### 💬 Let's build something

Based in **Havana, Cuba**, open to **remote AI Engineer / Software Engineer** roles.

<a href="mailto:0rlandomarrerog@gmail.com"><img src="https://img.shields.io/badge/0rlandomarrerog@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email 0rlandomarrerog@gmail.com" /></a>
<a href="https://www.linkedin.com/in/orlando-marrero-g/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
<a href="https://orlandomarrero-dev.vercel.app/"><img src="https://img.shields.io/badge/See_the_portfolio-0D1117?style=for-the-badge&logo=firefoxbrowser&logoColor=2DD4BF" alt="See the portfolio" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,50:0F766E,100:0D1117&height=120&section=footer&text=Building%20smart%20systems%2C%20on-device%20and%20on%20purpose&fontSize=16&fontColor=ffffff&fontAlignY=72" width="100%" alt="Building smart systems, on-device and on purpose" />

</div>
