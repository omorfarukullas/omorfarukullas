<div align="center">

# Building Systems from Messy Data
### Notes on Low-Resource Bangla NLP and Embedded Intelligence

**Omor Faruck Ullas**¹

<sub>¹ Department of CSE, United International University (UIU), Dhaka, Bangladesh · Expected graduation: 2027</sub>

<sub>`living draft` · continuously revised · [omorfarukullas.vercel.app](https://omorfarukullas.vercel.app/)</sub>

</div>

---

> **Abstract.** I am an undergraduate who works where *messy real-world data* meets *working software*. My main research question is whether coordinated propaganda can be detected in Bangla, a language with hundreds of millions of speakers but few NLP resources. Beside research, I build full-stack web platforms and real-time IoT systems on ESP32. This page is a living summary of that work.

**Keywords:** low-resource NLP · Bangla · propaganda detection · dataset construction · IoT · full-stack engineering

---

## 1. Introduction

Most NLP progress is measured in English. For Bangla, even basic questions are still open: *Where is the data? Who labelled it? Does it reflect real online media?*

My view is simple:

$$\max_{\theta}\ \mathbb{E}_{x \sim \text{messy world}}\big[\ \text{usefulness}(f_\theta(x))\ \big]$$

A model that only works on a clean benchmark is not the goal. A system that works on real, noisy input is the goal.[^1]

[^1]: Same idea for hardware. A sensor that works only on my desk is not a product.

## 2. Methods

| Layer | Tools | Used for |
|:--|:--|:--|
| Research & ML | Python · PyTorch · TensorFlow · Hugging Face | Models, datasets, evaluation |
| Backend | FastAPI · Node.js · PostgreSQL · MySQL · Supabase | APIs and data storage |
| Frontend | React · Next.js · TypeScript · Tailwind CSS | Interfaces |
| Embedded | ESP32 · C/C++ · Raspberry Pi | Sensors and real-time monitoring |
| Core | Java · JavaScript · Git · GitHub | Everything else |

<sub>**Table 1.** Methods used across my work.</sub>

## 3. Experiments

**E1 · Bangla Propaganda Detection** `research · in progress`
Can coordinated propaganda be found in Bangla online media? I am working with a team on building a Bangla propaganda dataset and comparing detection methods. Right now I am reading the literature: existing datasets, preprocessing, and evaluation protocols.

**E2 · HelioSense** `ESP32 · C++ · in progress`
A real-time monitoring system for smart solar panels, built on sensors and an ESP32.

**E3 · Local Flood Management System** `ESP32 · C++ · done`
An environmental monitoring prototype that gives early flood warnings.

**E4 · KaajerBazar** `Next.js · Tailwind · Claude API · Supabase · done`
A micro-project marketplace for Bangladeshi students. AI helps match bids to projects.

**E5 · MediSheba BD** `React · TypeScript · Node.js · MySQL · done`
A healthcare platform with live queue tracking for patients and doctors.

**E6 · JavaFX Resume Generator** `Java · JavaFX · done`
A desktop resume builder made to practise OOP design principles.

<sub>**Table 2.** Six experiments. Two are still running.</sub>

## 4. Results

| Metric | Value |
|:--|:-:|
| Experiments completed | 4 / 6 |
| Languages in daily use | Python, C++, Java, TypeScript |
| Hardware platforms | ESP32, Raspberry Pi |
| Main research language | Bangla |

<sub>**Table 3.** Honest summary. Research results will be added when they exist.</sub>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=omorfarukullas&theme=react-dark&bg_color=0B0F19&color=22D3EE&line=22D3EE&point=F5A623&area=true&hide_border=true" width="92%" alt="Contribution activity" />

<sub>**Figure 1.** Contribution activity over time.</sub>

<img src="https://raw.githubusercontent.com/omorfarukullas/omorfarukullas/output/github-contribution-grid-snake-dark.svg" width="92%" alt="Contribution snake" />

<sub>**Figure 2.** The same data, but a snake eats it.</sub>

</div>

## 5. Future Work

- [ ] Lock the research direction for Bangla propaganda detection
- [ ] Release a Bangla propaganda dataset with a clear annotation guide
- [ ] Finish HelioSense and test it with real solar panel data
- [ ] Go deeper into NLP, low-resource methods, and DevOps
- [ ] Write the research up properly

> **Open to:** research collaboration · AI/ML and NLP projects · embedded and IoT builds

<details>
<summary><b>Appendix A · Full toolbox</b></summary>

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

</details>

## References & Contact

1. **GitHub** · [github.com/omorfarukullas](https://github.com/omorfarukullas)
2. **LinkedIn** · [linkedin.com/in/omorullas](https://www.linkedin.com/in/omorullas/)
3. **X** · [x.com/berlinsergio34](https://x.com/berlinsergio34)
4. **Kaggle** · [kaggle.com/omorfaruk16](https://www.kaggle.com/omorfaruk16)
5. **Portfolio** · [omorfarukullas.vercel.app](https://omorfarukullas.vercel.app/)
6. **Correspondence** · [omor.farukh16@gmail.com](mailto:omor.farukh16@gmail.com)

<div align="center">

<sub>Revision log: v0.x, updated whenever the work changes.</sub>

![Profile Views](https://komarev.com/ghpvc/?username=omorfarukullas&color=22D3EE&style=flat-square&label=Readers)

</div>
