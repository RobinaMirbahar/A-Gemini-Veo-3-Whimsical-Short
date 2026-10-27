# 🌸 sofia‑song: A Veo 3 + Gemini Whimsical Story

![Video_AI](https://img.shields.io/badge/Video_AI-Google_Veo_3-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Story_Director](https://img.shields.io/badge/Story_Director-Google_Gemini_API-0F9D58?style=for-the-badge&logo=googlecloud&logoColor=white)
![Format](https://img.shields.io/badge/Format-1_Minute_Animated_Short-7C3AED?style=for-the-badge&logo=youtube&logoColor=white)
![Creator](https://img.shields.io/badge/Creator-Robina_Mirbahar-EA4335?style=for-the-badge&logo=github&logoColor=white)

> **Author & Architect:** [Robina Mirbahar](https://github.com/RobinaMirbahar) (Google Developer Expert in Cloud & AI)  
> **Focus:** AI-Directed Cinematic Storytelling, Multi-Shot Prompt Choreography & Audio-Visual Synchronization with Google Veo 3

---

## 🎯 Why I Built Sofia's Song — A Whimsical Animated Short with Google Gemini & Veo 3 (Engineering Purpose & Real-World Value)

### 1. 🎬 Directing Cohesive Multi-Shot Narratives with Google Veo 3
Generating a single 5-second AI clip is easy; directing a cohesive 1-minute emotional story with consistent lighting, camera movement, and character identity is an engineering discipline. I created *Sofia's Song* to document my end-to-end Veo 3 production workflow.

### 2. 🎼 Gemini-Driven Storyboard & Acoustic Choreography
I used Google Gemini to structure shot-by-shot camera lenses, color palettes, and musical pacing cues so every transition feels intentional.

### 3. 📖 Reproducible Prompt Engineering Blueprint
This repository shares the exact scene breakdown, character locking prompts, and assembly pipeline so creators can build their own animated shorts.

---

## 🏗️ System Architecture

```mermaid
flowchart TD
    subgraph Concept ["1. Narrative & Character Locking (Google Gemini)"]
        C_Script["Story Arc & Emotional Beat Sheet"]
        C_Char["Canonical Character & Palette Descriptors"]
    end
    subgraph Veo ["2. Multi-Shot Video Synthesis (Google Veo 3)"]
        V_S1["Shot 1-4: Establishing World & Lighting"]
        V_S2["Shot 5-8: Character Performance & Motion"]
        V_S3["Shot 9-12: Climax & Musical Resolution"]
    end
    subgraph Final ["3. Post-Production & Synchronization"]
        F_Cut["60-Second Master Cut (Sofia's Song)"]
    end
    C_Script --> C_Char --> V_S1 --> V_S2 --> V_S3 --> F_Cut
```

---

> “One brave hum. Two magical friends. A village that listened.”

**sofia‑song** is a 1‑minute whimsical Pixar-style short created with **Gemini prompt engineering** and **Veo 3 cinematic generation**. It follows *Sofia*, a 12‑year‑old girl in a flowing pink dress, as she faces the fear of judgment and learns to sing her truth — with help from her fluffy squirrel sidekick *Squiggle* and the gentle floating friend *Bloom*.

---

# 🎬 Project Summary

**sofia‑song** is a story of courage, friendship, and finding your voice. Over seven short scenes, we follow Sofia as she sneaks through a festival, hesitates, hums, and — with a nudge from her whimsical companions — brings an entire village into harmony.

---

### 🌟 Key Ingredients

- 👧 **Sofia** — 12 years old, black braid, pink traditional dress
- 🐿️ **Squiggle**: a hyper, scarf-wearing squirrel-like sidekick
- 🌸 **Bloom**: a floating, glowing creature in a lavender petal dress
- 🎤 A **banana** used as a pretend mic
- 🎶 A gentle **music box** and glowing paper lanterns
- 💫 One moment of courage that echoes into joy

--

## 🔧 Tools Used

| Tool       | Purpose                             |
| ---------- | ----------------------------------- |
| **Gemini** | Prompt scripting & scene writing    |
| **Veo 3**  | Cinematic video generation          |
| **CapCut** | Final edit, trim, transitions       |

🔗 [Veo by DeepMind](https://deepmind.google/models/veo/)  
🔗 [Veo API Docs (Vertex AI)](https://cloud.google.com/vertex-ai/generative-ai/docs/models/veo/3-0-generate-preview)

---

## 📖 Scene Breakdown

| 🌸 Scene | File                          | Title             | Time     | Description                                              |
| ----- | --------------------------------------| ------------------- | -------- | -------------------------------------------------------- |
| 0     | [`scene-0-intro.md`](prompts/scene-0-intro.md)              | What If They Judge Me? | 0–8s     | Sofia hides behind bush, afraid to step out.             |
| 1     | [`scene-1-distraction.md`](prompts/scene-1-distraction.md)  | They’re All Watching…  | 8–16s    | Squiggle steals banana mic, kids laugh.                  |
| 2     | [`scene-2-slip.md`](prompts/scene-2-slip.md)                | Oops!                  | 16–24s   | Sofia slips into petals, mic lands beside her.           |
| 3     | [`scene-3-first-note.md`](prompts/scene-3-first-note.md)    | Just One Word…         | 24–32s   | Bloom encourages truth over perfection.                  |
| 4     | [`scene-4-hi.md`](prompts/scene-4-hi.md)                    | Hi.                    | 32–40s   | Sofia finally speaks into mic.                           |
| 5     | [`scene-5-step-light.md`](prompts/scene-5-step-light.md)    | Did They Hear Me?      | 40–48s   | Sofia steps into light — petals swirl.                   |
| 6     | [`scene-6-ripple.md`](prompts/scene-6-ripple.md)            | She Sang.              | 48–56s   | Others begin to hum back — a ripple of music.            |
| 7     | [`scene-7-chorus.md`](prompts/scene-7-chorus.md)            | Together Now           | 56–60s   | Everyone joins in — a glowing, musical celebration.      |
---

## 🧚 Character Profiles

**👧 Sofia**  
12 years old • Bright eyes • Neatly tied black braid  
Wears a traditional flowing pink Asian dress embroidered with golden threads. Timid but full of hidden fire.

**🐿️ Squiggle**  
A squirrel-like, fluffy creature in a forest-green jumper and red scarf. Energetic, bouncy, loyal.

**🌸 Bloom**  
A gentle, floating flower-petal creature dressed in soft lavender petals, with a daisy crown. Brings calm and cheer.

---

## 🎥 How to Use

1. Open each scene prompt in the `/prompts/` folder.
2. Paste them into Gemini to generate visual storytelling prompts.
3. Render cinematic output using Veo 3 (via Vertex AI).
4. Edit and combine scenes using CapCut or similar.
5. Share your 1‑minute story with the world!

---

## 🚀 Repository Structure
sofia‑song/
├── README.md
└── prompts/


Each `.md` file contains a cinematic, 3D‑animation-ready scene description with dialogue, camera cues, character consistency, and emotional tone for Veo 3 or Gemini generation.

---

## 💡 Inspiration

> A single hum can start a chorus.

**sofia‑song** is a reminder that courage often starts small — and that when one voice dares to rise, others follow. Created for whimsical storytelling lovers, educators, and short-form animation fans.

---

## 👩‍💻 Author

**Robina Mirbahar**  
Google Developer Expert (AI/ML) • Google Cloud Champion Innovator – Modern Architecture  
Technical Writer & Veo & Gemini Storyteller  
🔗 [LinkedIn](https://www.linkedin.com/in/robinamirbahar)  
🔗 [Instagram](https://instagram.com/robinamirbahar)  
🔗 [Medium](https://medium.com/@robinamirbahar)  
🔗 [GitHub](https://github.com/RobinaMirbahar)


**✨ Made with imagination. Powered by Gemini + Veo. ✨**


---

### 🚀 Featured Google Cloud & Agentic AI Portfolio by Robina Mirbahar

| Repository | Architecture & Focus | Live Status |
| :--- | :--- | :--- |
| **[gemma4-multilora-adk-eval](https://github.com/RobinaMirbahar/gemma4-multilora-adk-eval)** | Dynamic Multi-LoRA Hot-Swapping & CI/CD Agent Evaluation (`adk eval`) on Cloud Run GPUs with Gemma 4 & vLLM | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/gemma4-multilora-adk-eval?style=flat-square&color=4285F4) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/gemma4-multilora-adk-eval?style=flat-square) |
| **[slothsre-napops](https://github.com/RobinaMirbahar/slothsre-napops)** | SlothSRE ("NapOps") — Overnight Gemma 4 & Google ADK Incident Digest Agent with OpenTelemetry & Sentry AI Monitoring | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/slothsre-napops?style=flat-square&color=34A853) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/slothsre-napops?style=flat-square) |
| **[streamforge-event-adk](https://github.com/RobinaMirbahar/streamforge-event-adk)** | Real-Time Event-Driven Multi-Agent Pipelines on Google Cloud with ADK (`ParallelAgent` & `LoopAgent`), Eventarc & Pub/Sub | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/streamforge-event-adk?style=flat-square&color=FBBC04) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/streamforge-event-adk?style=flat-square) |
| **[a2a-mcp-mesh-cloudrun](https://github.com/RobinaMirbahar/a2a-mcp-mesh-cloudrun)** | Agent-to-Agent (A2A) & Multi-MCP Mesh on Cloud Run with Gemma 4, Google ADK, Spanner Graph & AlloyDB | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/a2a-mcp-mesh-cloudrun?style=flat-square&color=EA4335) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/a2a-mcp-mesh-cloudrun?style=flat-square) |
| **[cloudguard-gemma-agent](https://github.com/RobinaMirbahar/cloudguard-gemma-agent)** | 6-Part Production Gemma Enterprise Agent Series (ADK, Cloud Run L4 GPU, Firestore, Model Armor, Vertex AI QLoRA) | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/cloudguard-gemma-agent?style=flat-square&color=4285F4) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/cloudguard-gemma-agent?style=flat-square) |
| **[Comic-Studio-Ai](https://github.com/RobinaMirbahar/Comic-Studio-Ai)** | Multi-Agent Comic Generator powered by Google Gemini API & FastAPI deployed on Google Cloud Run | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/Comic-Studio-Ai?style=flat-square&color=EA4335) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/Comic-Studio-Ai?style=flat-square) |
| **[vertex-ai-imagen3](https://github.com/RobinaMirbahar/vertex-ai-imagen3)** | Generate AI-powered product & editorial images using Google Vertex AI Imagen 3 in Google Colab | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/vertex-ai-imagen3?style=flat-square&color=34A853) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/vertex-ai-imagen3?style=flat-square) |
| **[Python-Learning-Assistant](https://github.com/RobinaMirbahar/Python-Learning-Assistant)** | AI-powered Python tutor covering 50+ interactive exercises with real-time feedback built with Streamlit + Gemini API | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/Python-Learning-Assistant?style=flat-square&color=FBBC04) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/Python-Learning-Assistant?style=flat-square) |
| **[cozy-ai-agent-cafe-game](https://github.com/RobinaMirbahar/cozy-ai-agent-cafe-game)** | Prompt Paws: 60 FPS Cozy AI Agent Bakery Simulation Game teaching RAG, Guardrails, Context Caching & Multi-Agent Loops | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/cozy-ai-agent-cafe-game?style=flat-square&color=7928CA) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/cozy-ai-agent-cafe-game?style=flat-square) |

<div align="center">
  <img src="https://raw.githubusercontent.com/RobinaMirbahar/RobinaMirbahar/main/ProfileImages/GithubBanner.svg" alt="Robina Mirbahar Banner" width="100%" />
</div>

<!-- AUTHOR_SIGNATURE_START -->
---

## 👩‍💻 About the Author

**Robina Mirbahar — Google Cloud & AI Architect**  
*Google Developer Expert (GDE) in Cloud & AI • Published Author • Multi-Agent Systems & Serverless GPU Builder*

[![GitHub](https://img.shields.io/badge/GitHub-RobinaMirbahar-181717?style=for-the-badge&logo=github)](https://github.com/RobinaMirbahar)
[![Medium](https://img.shields.io/badge/Medium-@robinamirbahar-000000?style=for-the-badge&logo=medium)](https://medium.com/@robinamirbahar)
[![DEV.to](https://img.shields.io/badge/DEV.to-robinamirbahar-0A0A0A?style=for-the-badge&logo=devdotto)](https://dev.to/robinamirbahar)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Robina_Mirbahar-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/robina-mirbahar)
[![GDE Profile](https://img.shields.io/badge/Google_Developer_Expert-Profile-4285F4?style=for-the-badge&logo=google)](https://g.dev/RobinaMirbahar)
[![YouTube](https://img.shields.io/badge/YouTube-@RobinaMirbahar-FF0000?style=for-the-badge&logo=youtube)](https://www.youtube.com/@RobinaMirbahar)
[![X](https://img.shields.io/badge/X-@RobinaMirbahar-000000?style=for-the-badge&logo=x)](https://x.com/RobinaMirbahar)
[![Amazon Author](https://img.shields.io/badge/Amazon_Book-Cloud_Computing_Voyage-FF9900?style=for-the-badge&logo=amazon)](https://www.amazon.com/dp/B0D146249R)

<!-- AUTHOR_SIGNATURE_END -->
