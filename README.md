<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d9488,100:ea580c&height=200&section=header&text=Wasiq%20Shairzad&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=CS%20%26%20Math%20Student%20%7C%20AI%2FML&descAlignY=60&descSize=20" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=0d9488&center=true&vCenter=true&width=700&lines=Reading+papers+and+building+things;Transformers%2C+diffusion%2C+and+whatever+breaks+next;Paris-based%2C+self-directed%2C+going+deep)](https://git.io/typing-svg)

</div>

---

## About Me

I'm a **CS & Math student in Paris** on a self-directed path into AI/ML — reading papers, running experiments, and building real things along the way.

- 🔬 Currently exploring: **attention mechanisms, transformer internals, and diffusion models**
- 🛠️ Building: **projects that go from paper to code to something that actually runs**
- 📺 Documenting the journey on **[YouTube @WasiqShairzad](https://youtube.com/@WasiqShairzad)**
- 🧠 Learning philosophy: understand it deeply, then build it from scratch

---

## Featured Research

### 🧬 Differential Neural Attention (DNA)

> *Combining Nonlinear Attention Scoring with Noise Cancellation for Enhanced Transformer Performance*

A novel attention mechanism that unifies two complementary advances:

| Property | Standard | Diff-Attn | Neural-Attn | **DNA (Ours)** |
|:---------|:--------:|:---------:|:-----------:|:--------------:|
| Scoring Function | Bilinear | Bilinear (diff) | Nonlinear (FFN) | **Nonlinear (diff FFN)** |
| Noise Cancellation | — | ✓ | — | **✓** |
| Cross-dim Interaction | — | — | ✓ | **✓** |
| Attention Sparsity | Low | Medium | Low | **High** |

**Key result**: DNA achieves near-zero attention variance and the lowest effective rank across all baselines — the most focused, sparse attention patterns.

```python
from src.attention import DifferentialNeuralAttention

attn = DifferentialNeuralAttention(d_model=512, n_heads=8, layer_idx=0)
output = attn(x)  # drop-in replacement for standard attention
```

→ **[View Project](https://github.com/AhmadWasiq/differential-neural-attention)**

---

## Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-0d9488?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-ea580c?style=for-the-badge&logo=pytorch&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-0d9488?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-ea580c?style=for-the-badge&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-0d9488?style=for-the-badge&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-ea580c?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-0d9488?style=for-the-badge&logo=supabase&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-ea580c?style=for-the-badge&logo=openai&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-0d9488?style=for-the-badge&logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-ea580c?style=for-the-badge&logo=node.js&logoColor=white)

</div>

---

## Projects

### AI & Machine Learning

| Project | Description | Stack |
|---------|-------------|-------|
| [**Differential Neural Attention**](https://github.com/AhmadWasiq/differential-neural-attention) | Novel attention mechanism combining nonlinear FFN scoring with differential noise cancellation — formal expressiveness proofs + experiments on WikiText-2 and CIFAR-10 | PyTorch, Python |
| [**AI Experiments**](https://github.com/AhmadWasiq/ai-experiments) | RAG systems, legal document analysis, healthcare pre-consultation pipelines | Python, FastAPI, OpenAI, ChromaDB |
| [**YOLO PPE Detector**](https://github.com/AhmadWasiq/yolo-ppe-detector) | Real-time safety equipment detection with GUI — webcam, video, and image input | Python, YOLOv8, OpenCV, PyQt5 |
| [**LM Learner**](https://github.com/AhmadWasiq/lm-learner) | Interactive ML learning app — write and run Python in-browser with live visualizations | React, TypeScript, Pyodide, Plotly.js |
| [**Novus**](https://github.com/AhmadWasiq/novus) | AI innovation engine that generates and refines project ideas | FastAPI, Next.js, OpenRouter |

### Healthcare & Medical AI

| Project | Description | Stack |
|---------|-------------|-------|
| [**Vita**](https://github.com/AhmadWasiq/vita) | Full-stack AI healthcare platform — symptom assessment, appointment scheduling, real-time patient-doctor communication | Next.js, React Native, Supabase, AI SDK |
| [**Vita MVP**](https://github.com/AhmadWasiq/vita-mvp) | Healthcare MVP with AI chat, multi-platform apps, and appointment management | FastAPI, React Native, SQLite |
| [**DOCM**](https://github.com/AhmadWasiq/docm) | Practice management for hair transplant surgeons — AI consultations, voice transcription, Gmail/Calendar integration | React, TypeScript, Supabase, OpenAI |
| [**VitaScript**](https://github.com/AhmadWasiq/vitascript) | AI-powered electronic prescription generation | Next.js, OpenAI |
| [**Palmyra Med Chat**](https://github.com/AhmadWasiq/palmyra-med-chat) | Chat interface for NVIDIA's Palmyra Med 70B medical AI model | Vanilla JS, NVIDIA API |
| [**Clinic MVP**](https://github.com/AhmadWasiq/clinic-mvp) | Clinic intranet with patient management and WhatsApp integration | Next.js, FastAPI |

### Commerce & Consumer AI

| Project | Description | Stack |
|---------|-------------|-------|
| [**Buy AI**](https://github.com/AhmadWasiq/buy-ai) | Chat-first consumer agent — shop, book rides, pay bills through natural language | React, TypeScript, Tailwind |
| [**BuyFaster**](https://github.com/AhmadWasiq/buyfaster) | Voice-powered AI shopping app with product search and Stripe payments | React, Vite, Convex, Stripe |
| [**Gold American**](https://github.com/AhmadWasiq/gold-american) | E-commerce AI shopping assistant for a jewelry store | Node.js, WooCommerce, OpenAI |

### Robotics

| Project | Description | Stack |
|---------|-------------|-------|
| [**NAO ChatGPT**](https://github.com/AhmadWasiq/nao-chatgpt) | ChatGPT integration for the Softbank NAO humanoid robot — natural voice conversations with configurable personas | Python, OpenAI, NAOqi SDK |

### Games & Creative

| Project | Description | Stack |
|---------|-------------|-------|
| [**Tap & Dodge**](https://github.com/AhmadWasiq/tap-and-dodge) | Mobile arcade game with physics, power-ups, and haptic feedback | React Native, Expo, Matter.js |
| [**Sky Runner**](https://github.com/AhmadWasiq/sky-runner) | Endless runner built with Phaser 3 | TypeScript, Phaser 3 |
| [**Image to Poem**](https://github.com/AhmadWasiq/image-to-poem) | Upload an image, get an AI-generated poem using GPT-4o vision | HTML, Vanilla JS, OpenAI |
| [**Hair Transplant 3D**](https://github.com/AhmadWasiq/hair-transplant-3d) | Interactive 3D hair transplant simulator | Three.js |

### Community & Tools

| Project | Description | Stack |
|---------|-------------|-------|
| [**Simurg Donation Ledger**](https://github.com/AhmadWasiq/simurg-donation-ledger) | Donation tracking and management for nonprofits | React, TypeScript, Supabase |
| [**Global Nonprofits Guide**](https://github.com/AhmadWasiq/global-nonprofits-guide) | Directory and AI-powered guide for global nonprofit organizations | Next.js, Supabase, Perplexity |
| [**Portfolio**](https://github.com/AhmadWasiq/portfolio) | Personal portfolio with project showcase and voice agent | React, TypeScript, Tailwind |

---

## GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=AhmadWasiq&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&title_color=0d9488&icon_color=ea580c" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AhmadWasiq&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&title_color=0d9488" />

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ea580c,100:0d9488&height=100&section=footer" width="100%"/>

*Building in public. Learning out loud.*

</div>
