<!--
GitHub Profile README
Place this file in the root of a PUBLIC repository named exactly: garapatiruthik
Edit project links, add missing dates, and keep experimental metrics tied to their benchmark configuration.
-->

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,45:312E81,100:4338CA&height=220&section=header&text=RUTHIK%20GARAPATI&fontSize=42&fontColor=F8FAFC&fontAlignY=35&desc=AI%20ENGINEERING%20%E2%80%A2%20MACHINE%20LEARNING%20%E2%80%A2%20RESEARCH&descAlignY=58&descSize=16&animation=fadeIn" alt="Ruthik Garapati — AI Engineering, Machine Learning and Research" />

  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=2800&pause=850&color=8B5CF6&center=true&vCenter=true&width=850&lines=Building+retrieval-grounded+LLM+systems;Exploring+agentic+AI+and+efficient+model+fine-tuning;Researching+foundation+models+for+time-series+forecasting" alt="Building retrieval-grounded LLM systems | Exploring agentic AI and efficient fine-tuning | Researching time-series foundation models" />

  <p>
    <a href="https://www.linkedin.com/in/ruthik-garapati-793047268"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://github.com/garapatiruthik"><img src="https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
    <a href="mailto:garapatiruthik@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
    <img src="https://komarev.com/ghpvc/?username=garapatiruthik&style=for-the-badge&color=6D5AE6&label=PROFILE+VIEWS" alt="Profile views" />
  </p>
</div>

<p align="center">
  <a href="#about">About</a> •
  <a href="#experience">Experience</a> •
  <a href="#research">Research</a> •
  <a href="#featured-projects">Projects</a> •
  <a href="#technical-toolkit">Skills</a> •
  <a href="#recognition">Recognition</a> •
  <a href="#education--certifications">Education</a>
</p>

---

## About

I’m an **AI/ML engineer** interested in building intelligent systems that are not only capable, but also measurable, efficient, and useful in real workflows. My work spans **LLM applications, retrieval-augmented generation (RAG), agentic workflows, model fine-tuning, computer vision, and time-series forecasting**.

I completed a collaborative **3+1 international degree pathway** across Andhra University, India, and Blekinge Institute of Technology (BTH), Sweden. I enjoy moving between hands-on engineering and research: building systems, benchmarking their behaviour, and understanding the trade-offs behind the results.

- **Current focus:** LLM engineering, memory-efficient fine-tuning, RAG, and Model Context Protocol (MCP) integrations.
- **Research:** Comparing Chronos-T5 and Mamba for urban traffic forecasting using the METR-LA dataset.
- **Applied experience:** Built a RAG-based candidate-screening pipeline covering **5,000+ documents**.
- **Beyond code:** Hackathon teamwork, national-level fencing, and creative digital outreach.

> *Build systems that reason, retrieve, and act — then measure what they get right.*

## Experience

| Role | Organization | Period | Selected work |
|---|---|---|---|
| **AI Engineer Intern** | Sails Software Solutions Pvt. Ltd. · India | Jul 2026 – Present | Fine-tuning Llama 3.1 8B Instruct with LoRA and Soup layer streaming; experimenting with double-buffered GPU transfers for memory-efficient supervised fine-tuning; building LangChain, RAG, and MCP workflows. |
| **Machine Learning Intern** | Justera Group AB · Stockholm, Sweden | Oct 2025 – Jun 2026 | Developed a RAG-based resume-screening pipeline for **5,000+ documents**, combining Sentence Transformers, BM25, FAISS, and cross-encoder reranking; used AWS for inference and storage. |
| **Data Analyst Intern** | Balina IT Solutions | Jun 2025 – Aug 2025 | Cleaned and transformed salon-business data and built a Streamlit dashboard for business metrics, customer visit frequency, spending patterns, and repeat-customer analysis. |

<details>
  <summary><strong>Earlier internships, web development & creative contributions</strong></summary>

  ### Web Developer Intern — Sails Software Solutions
  - Contributed to an **eKart proof of concept** using Angular, TypeScript, JavaScript, HTML, and CSS.
  - Worked on product categories, search, product availability, and adding or removing products from the shopping cart.
  - Built experience in component-based UI development, feature logic, and debugging.

  ### Foundational Web Development Internship — Early Undergraduate Experience
  - Learned core website concepts through HTML, CSS, and JavaScript, with introductory exposure to Spring Boot.
  - Practised programming logic, basic data structures and algorithms, UI design, and debugging.
  - Built a personal portfolio website to apply the fundamentals in a working project.

  ### Data Science Intern — Oasis Infobyte
  - Developed foundational experience in data exploration, cleaning, analysis, and visualisation while applying Python-based data workflows to practical exercises.

  ### Machine Learning Intern — Bharat Intern
  - Studied core ML workflows, model-building concepts, and evaluation techniques, with learning exposure to Python-based ML tools and deep-learning frameworks.

  ### Digital Content & Video Editing Volunteer — Edumoo Club, Andhra University
  - Volunteered to support campus digital outreach by editing short videos and creating visual posters in Canva.
  - Wrote and refined promotional content, including with early AI-assisted writing tools; contributed material published through the club’s official LinkedIn and Instagram channels.
  - Recognised for creative contributions and the quality of volunteer work.
</details>

### Selected engineering benchmarks

| Workstream | Observed result | Context |
|---|---:|---|
| RAG resume screening | **5,000+ documents** | Retrieval and matching pipeline developed during the Justera internship. |
| Chronos-T5 vs. Mamba thesis | **~188× inference-speed difference** | Evaluated setup: 7.16 ms for Mamba vs. 1.35 s for Chronos-T5; speed and accuracy trade-offs are described below. |
| Llama fine-tuning experiments | **3.3 GB peak VRAM · 113 tokens/s** | Values from a benchmark run in the current experimental setup; results are configuration-dependent. |

## Research

### [Comparative Analysis of Chronos-T5 Foundation Model and Mamba State Space Architecture for Urban Traffic Forecasting](https://bth.diva-portal.org/smash/record.jsf?pid=diva2:2085482)

**Bachelor’s thesis · Blekinge Institute of Technology · 2026**

Compared zero-shot forecasting with **Chronos-T5** against a **weather-augmented Mamba state-space model** on the METR-LA traffic dataset. The work examines the trade-off between point-forecast accuracy, inference cost, and probabilistic fit rather than treating one model as universally superior.

| Evaluation dimension | Chronos-T5 | Weather-augmented Mamba |
|---|---:|---:|
| Mean Absolute Error (MAE) | **1.58 mph** | 4.57 mph |
| Inference time in the evaluated setup | 1.35 s | **7.16 ms** |
| KL divergence | 16.45 bits | **1.07 bits** |

**Key takeaway:** Chronos-T5 achieved lower MAE in the reported comparison, while Mamba provided much lower inference latency and a lower KL-divergence value. Adding weather covariates reduced Mamba’s forecasting error by **10.57%** in the reported experiment.

[Read the thesis on BTH DiVA](https://bth.diva-portal.org/smash/record.jsf?pid=diva2:2085482) · [Connect on LinkedIn](https://www.linkedin.com/in/ruthik-garapati-793047268)

## Featured Projects

| Project | What it does | Technologies / links |
|---|---|---|
| **[AI Travel Planner](https://github.com/garapatiruthik/Project-Agentic-AI)** | A stateful, multi-agent travel-planning workflow that coordinates transport, accommodation, activities, and itinerary generation. A budget-auditing feedback loop can route the workflow back to revise options when the plan exceeds its budget. | `Python` · `LangGraph` · `MCP` · `LLM APIs` · external travel and mapping services · [Source code](https://github.com/garapatiruthik/Project-Agentic-AI) |
| **[INEB — Facial Intoxication Detection](https://github.com/garapatiruthik/Facial-Intoxication-detection)** | Computer-vision prototype that extracts five facial features with MediaPipe and feeds them into a Random Forest classifier. Includes a Streamlit interface for experimentation. It is a prototype, not a medical or forensic assessment tool. | `Python` · `MediaPipe` · `OpenCV` · `scikit-learn` · `Streamlit` · [Source code](https://github.com/garapatiruthik/Facial-Intoxication-detection) |
| **Salon Business Intelligence Dashboard** | Prepared salon/customer datasets and created visual analytics for business review, including customer frequency, spending, and repeat-customer patterns. | `Python` · `Pandas` · `NumPy` · `Streamlit` |
| **Ticket Pranali — Museum Ticketing Concept** | Smart India Hackathon concept for improving museum visits through chatbot-assisted booking, multilingual support, time-slot management, visitor sequencing, and indoor navigation concepts. | `AI/NLP` · `Python` · `Chatbot workflows` · `Product ideation` · [SIH project context](#recognition) |
| **Scalable Serverless Image Processing** | Built with a teammate as a cloud-computing capstone: S3 object-created events trigger a Python Lambda function to transform images and store outputs. A load test simulated 150 concurrent uploads; CloudWatch was used to inspect execution behaviour and tune resource settings. | `AWS S3` · `AWS Lambda` · `Python` · `Pillow` · `CloudWatch` · [LinkedIn](https://www.linkedin.com/in/ruthik-garapati-793047268) |

<!-- Add Agentic Codebase Analyzer & Test Generator to Featured Projects after its public repository contains the implementation, setup instructions, and a project README. -->

## Technical Toolkit

| Domain | Tools and concepts |
|---|---|
| **Generative AI & LLM Engineering** | LLM applications · RAG · LangChain · LangGraph · MCP · LoRA / parameter-efficient fine-tuning · prompt and tool orchestration |
| **Machine Learning & Computer Vision** | PyTorch · scikit-learn · OpenCV · MediaPipe · Random Forest · model evaluation · feature engineering |
| **Time-Series & Research** | Chronos-T5 · Mamba / state-space models · traffic forecasting · exogenous weather features · MAE · KL divergence · experimental benchmarking |
| **Data & Analytics** | Python · Pandas · NumPy · SQL · data cleaning · exploratory data analysis · Streamlit · Plotly · Power BI / Tableau |
| **Cloud & Backend** | AWS · FastAPI · Docker · Git · REST API integration · inference workflows |
| **Programming & Web Foundations** | Python · Java · C · JavaScript · TypeScript · Angular · React · HTML · CSS · Spring Boot fundamentals |

<div align="center">
  <br />
  <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,opencv,fastapi,aws,docker,git,github,java,c,js,ts,angular,react,html,css&perline=9" alt="Technology icons" />
</div>

## Recognition

| Recognition | Contribution |
|---|---|
| **MLH Codefest · BTH, Sweden** | **Innovation & Creativity Award** for the Facial Intoxication Detection project. |
| **Smart India Hackathon — Internal Round** | **3rd Prize · Team Leader** — Ticket Pranali, a museum ticketing and visitor-experience concept. |
| **HackAP — Robotics Theme** | **2nd Prize** — sports-performance analysis model using computer-vision/MediaPipe workflows. |
| **HackAP — Art & Culture Theme** | **3rd Prize** — Art Square, a cultural-heritage initiative/platform concept connecting people with artists. |
| **BTH Bachelor’s International Merit Scholarship** | Merit-based scholarship for studies in Artificial Intelligence and Machine Learning. |
| **Symposium Presentation** | **3rd Prize** for a presentation on blockchain applications in pharmacy. |
| **Fencing** | Represented Andhra University at Inter-University Fencing Nationals in **2022 and 2024**; also earned state-level medals. |

## Education & Certifications

### Education

- **B.Sc. in Artificial Intelligence & Machine Learning** — Blekinge Institute of Technology (BTH), Sweden · **2025–2026** · **8.72/10**
- **B.Tech. (Honours) in Computer Science & Engineering** — Andhra University College of Engineering, India · **2022–2026**

### Selected certifications

- **Large Language Models** — NPTEL
- **Reinforcement Learning** — NPTEL
- **Software Reliability** — NPTEL
- **High Performance Scientific Computing** — NPTEL
- **Business Ethics** — NPTEL · **Elite + Gold** (top 2%, as reported on the credential)
- **Data Science** — PW (Physics Wallah)

## GitHub Activity

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=garapatiruthik&show_icons=true&hide_border=true&rank_icon=github&theme=tokyonight&include_all_commits=true" alt="GitHub statistics for garapatiruthik" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=garapatiruthik&layout=compact&hide_border=true&langs_count=8&theme=tokyonight" alt="Most used programming languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=garapatiruthik&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />
</div>

## Let’s Connect

I’m interested in **AI engineering, applied machine learning, LLM systems, and research-oriented software development**. I value thoughtful collaboration, reproducible experiments, and engineering decisions supported by evidence.

<p align="center">
  <a href="https://www.linkedin.com/in/ruthik-garapati-793047268"><img src="https://img.shields.io/badge/LinkedIn-Ruthik%20Garapati-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:garapatiruthik@gmail.com"><img src="https://img.shields.io/badge/Email-garapatiruthik%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/garapatiruthik"><img src="https://img.shields.io/badge/GitHub-garapatiruthik-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:4338CA,55:312E81,100:0F172A&height=100&section=footer" alt="Decorative footer" />
</div>
