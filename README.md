<!--
  Setup:
  The contribution snake needs the Platane/snk GitHub Action (.github/workflows/snake.yml) in this repo.
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0F19,50:15213B,100:22D3EE&height=210&section=header&text=OMOR%20FARUCK%20ULLAS&fontSize=44&fontColor=F5F5F7&animation=fadeIn&fontAlignY=38&desc=Low-Resource%20NLP%20%C2%B7%20Applied%20AI%20%C2%B7%20Embedded%20Systems&descSize=16&descAlignY=58&descColor=22D3EE" width="100%" alt="Header" />

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&pause=1200&color=22D3EE&center=true&vCenter=true&width=700&lines=%24+python+train.py+--lang+bn+--task+propaganda;%24+flash+esp32+--project+HelioSense;%24+git+commit+-m+%22turn+messy+data+into+systems%22;%24+status+%3D%3D+building" alt="Typing SVG" />

</div>

<br/>

```python
# about.py

class Omor:
    university  = "United International University (UIU), Dhaka"
    degree      = "B.Sc. in CSE  |  graduating 2027"

    research    = ["Low-resource Bangla NLP", "Propaganda detection", "Dataset construction"]
    engineering = ["Full-stack web", "IoT / ESP32", "DevOps", "Football analytics"]

    principle   = "Messy real-world data -> systems that actually work"

    def open_to(self):
        return ["research collaboration", "NLP / AI projects", "embedded + IoT builds"]
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:22D3EE,50:A78BFA,100:F5A623&height=3" width="100%" alt="divider" />
</div>

## 🧬 Research: Propaganda Detection in Bangla

Bangla has hundreds of millions of speakers but very few resources for studying coordinated manipulation online. I am working with a team to ask a simple question: **can coordinated propaganda be detected in a low-resource language?**

```mermaid
flowchart LR
    A[Online media<br/>collection] --> B[Cleaning &<br/>normalization]
    B --> C[Annotation<br/>scheme]
    C --> D[Bangla propaganda<br/>dataset]
    D --> E[Baselines &<br/>models]
    E --> F[Evaluation &<br/>error analysis]
    style D fill:#15213B,stroke:#22D3EE,color:#F5F5F7
```

**Current stage:** literature mapping. Existing datasets, preprocessing methods, and evaluation protocols are being reviewed before the research direction is locked.

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:22D3EE,50:A78BFA,100:F5A623&height=3" width="100%" alt="divider" />
</div>

## ⚙️ Systems I Build

| | Project | What it does | Stack | State |
|:-:|---|---|---|:-:|
| ☀️ | **HelioSense** | Real-time smart solar panel monitoring | ESP32 · C++ · Sensors | 🟠 building |
| 🌊 | **Local Flood Management System** | Environmental monitoring + early flood-warning prototype | ESP32 · C++ · Sensors | 🟢 done |
| 🛍️ | **KaajerBazar** | Micro-project marketplace for Bangladeshi students, with AI-assisted bid matching | Next.js · Tailwind · Claude API · Supabase | 🟢 done |
| 🩺 | **MediSheba BD** | Healthcare platform with live queue tracking for patients and doctors | React · TypeScript · Node.js · MySQL | 🟢 done |
| 📄 | **JavaFX Resume Generator** | Desktop resume builder built around OOP design principles | Java · JavaFX | 🟢 done |
| 🔎 | **Bangla Propaganda Detection** | Research on coordinated propaganda in low-resource Bangla | NLP · Dataset construction | 🟠 research |

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:22D3EE,50:A78BFA,100:F5A623&height=3" width="100%" alt="divider" />
</div>

## 🏗️ How My Stack Fits Together

```mermaid
flowchart TB
    subgraph Edge["Edge / IoT"]
        S[Sensors] --> M[ESP32 · C++]
    end
    subgraph Backend["Backend"]
        API[FastAPI · Node.js]
        DB[(PostgreSQL · MySQL · Supabase)]
    end
    subgraph ML["AI / ML"]
        P[PyTorch · TensorFlow]
        H[Hugging Face]
    end
    subgraph Web["Web"]
        UI[React · Next.js · TypeScript · Tailwind]
    end
    M --> API
    API <--> DB
    API <--> P
    P --- H
    API --> UI
```

<details>
<summary><b>🔧 Full toolbox (click to expand)</b></summary>

<br/>

**Languages**
<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**AI / ML**
<br/>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Web & Backend**
<br/>
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Data**
<br/>
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

**Embedded & Tools**
<br/>
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

</details>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:22D3EE,50:A78BFA,100:F5A623&height=3" width="100%" alt="divider" />
</div>

## 📡 Live Status

```yaml
now:
  researching: Bangla propaganda datasets & detection methods
  building:    HelioSense (ESP32 solar monitoring)
  learning:    advanced NLP, low-resource language processing, DevOps
next:
  goal:        publish research on low-resource Bangla NLP
  open_to:     collaboration on AI/ML, NLP, embedded systems
```

## 📊 Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=omorfarukullas&theme=react-dark&bg_color=0B0F19&color=22D3EE&line=22D3EE&point=F5A623&area=true&hide_border=true" width="100%" alt="GitHub activity graph" />

<br/><br/>

<img src="https://raw.githubusercontent.com/omorfarukullas/omorfarukullas/output/github-contribution-grid-snake-dark.svg" width="100%" alt="Contribution snake" />

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:22D3EE,50:A78BFA,100:F5A623&height=3" width="100%" alt="divider" />
</div>

## 🔌 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/omorfarukullas)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/omorullas/)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/berlinsergio34)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:omor.farukh16@gmail.com)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/omorfaruk16)
[![Portfolio](https://img.shields.io/badge/Portfolio-22D3EE?style=for-the-badge&logoColor=white)](https://omorfarukullas.vercel.app/)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=omorfarukullas&color=22D3EE&style=flat-square&label=Profile+Views)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22D3EE,50:15213B,100:0B0F19&height=140&section=footer&animation=fadeIn&text=connection_status%3A%20open&fontSize=20&fontColor=F5F5F7&fontAlignY=80" width="100%" alt="Footer" />

</div>
