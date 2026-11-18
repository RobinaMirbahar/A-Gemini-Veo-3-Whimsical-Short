# 🌸 Sofia's Song: A Whimsical 1-Minute Story Made with Gemini & Veo 3

![Video_AI](https://img.shields.io/badge/Video_AI-Google_Veo_3-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Story_Director](https://img.shields.io/badge/Story_Director-Google_Gemini_API-0F9D58?style=for-the-badge&logo=googlecloud&logoColor=white)
![Format](https://img.shields.io/badge/Format-1_Minute_Animated_Short-7C3AED?style=for-the-badge&logo=youtube&logoColor=white)
![Creator](https://img.shields.io/badge/Creator-Robina_Mirbahar-EA4335?style=for-the-badge&logo=github&logoColor=white)

> **Author & Architect:** [Robina Mirbahar](https://github.com/RobinaMirbahar) (Google Developer Expert in Cloud & AI)  
> **Focus:** AI-Directed Cinematic Storytelling, Multi-Shot Prompt Choreography & Audio-Visual Synchronization with Google Veo 3  
> 🎥 **Watch the Short Film:** [Sofia's Song on YouTube](https://www.youtube.com/watch?v=rS-gXC0XoH0)

---

> *“One brave hum. Two magical friends. A village that listened.”*

**Sofia's Song** is a 1-minute Pixar-style animated short created with **Google Gemini prompt engineering** and **Google Veo 3 cinematic video generation**. Over eight cohesive scenes at a glowing lantern festival, timid protagonist *Sofia* overcomes her fear of judgment and discovers her voice—cheered on by her energetic squirrel sidekick *Squiggle* and gentle floating companion *Bloom*.

---

## 🎯 Engineering Purpose & Production Blueprint

### 1. 🎬 Directing Cohesive Multi-Shot Narratives with Google Veo 3
Generating a single 5-second AI clip is straightforward; directing a cohesive 60-second emotional narrative with consistent lighting, camera movement, and character identity requires structured prompt engineering. *Sofia's Song* documents an end-to-end Veo 3 multi-shot workflow.

### 2. 🎼 Gemini-Driven Storyboarding & Acoustic Choreography
Google Gemini structures shot-by-shot camera lenses, color palettes, character descriptors, and musical pacing cues so every cut feels intentional.

### 3. 📖 Reproducible Scene-by-Scene Prompts
Every scene breakdown, character-locking descriptor, and assembly step is shared in [`prompts/`](prompts/) so creators and educators can build their own animated shorts.

---

## 🏗️ Production Pipeline

```mermaid
flowchart TD
    subgraph Concept ["1. Narrative & Character Locking (Google Gemini)"]
        C_Script["Story Arc & Emotional Beat Sheet"]
        C_Char["Canonical Character & Palette Descriptors"]
    end
    subgraph Veo ["2. Multi-Shot Video Synthesis (Google Veo 3)"]
        V_S1["Scenes 0–2: Establishing World & Lighting"]
        V_S2["Scenes 3–5: Character Performance & Motion"]
        V_S3["Scenes 6–7: Climax & Musical Resolution"]
    end
    subgraph Final ["3. Post-Production & Synchronization"]
        F_Cut["60-Second Master Cut (CapCut)"]
    end
    C_Script --> C_Char --> V_S1 --> V_S2 --> V_S3 --> F_Cut
```

---

## 🌟 Cast & Key Story Elements

| Element | Role & Visual Anchor |
| :--- | :--- |
| **🎤 Sofia** | Expressive protagonist with bright eyes, neatly braided black hair, and an embroidered golden-pink traditional festival outfit—timid at first, full of hidden courage. |
| **🐿️ Squiggle** | Loyal, energetic squirrel sidekick wearing a forest-green jumper and red scarf. |
| **🌸 Bloom** | Gentle floating blossom spirit in soft lavender petals and a daisy crown who brings calm encouragement. |
| **🍌 Pretend Mic & Lanterns** | A playful banana microphone, a gentle music box melody, and glowing paper lanterns that unite the festival crowd. |

---

## 📖 Scene Breakdown (60 Seconds)

| Scene | Prompt File | Title | Time | Narrative Beat |
| :---: | :--- | :--- | :---: | :--- |
| **0** | [`scene-0-intro.md`](prompts/scene-0-intro.md) | *What If They Judge Me?* | `0–8s` | Sofia hides behind a bush at the festival, hesitant to step out. |
| **1** | [`scene-1-distraction.md`](prompts/scene-1-distraction.md) | *They’re All Watching…* | `8–16s` | Squiggle grabs the playful banana mic, making the crowd laugh. |
| **2** | [`scene-2-slip.md`](prompts/scene-2-slip.md) | *Oops!* | `16–24s` | Sofia slips into swirling petals as the mic lands right beside her. |
| **3** | [`scene-3-first-note.md`](prompts/scene-3-first-note.md) | *Just One Word…* | `24–32s` | Bloom encourages honesty and heart over perfection. |
| **4** | [`scene-4-hi.md`](prompts/scene-4-hi.md) | *Hi.* | `32–40s` | Sofia finally speaks her first word into the mic. |
| **5** | [`scene-5-step-light.md`](prompts/scene-5-step-light.md) | *Did They Hear Me?* | `40–48s` | Sofia steps into the warm lantern light as petals swirl around her. |
| **6** | [`scene-6-ripple.md`](prompts/scene-6-ripple.md) | *She Sang.* | `48–56s` | Festival-goers begin to hum back—a ripple of shared music. |
| **7** | [`scene-7-chorus.md`](prompts/scene-7-chorus.md) | *Together Now* | `56–60s` | Everyone joins in for a glowing, harmonious finale. |

---

## 🔧 Tools & Official Resources

| Tool | Purpose |
| :--- | :--- |
| **Google Gemini** | Story arc scripting, character locking & shot prompt generation |
| **Google Veo 3** | Cinematic 3D-style video synthesis via Vertex AI |
| **CapCut** | Final timeline assembly, trims, transitions & audio sync |

* 🔗 [Google Veo by DeepMind](https://deepmind.google/models/veo/?utm_campaign=deveco_gdemembers&utm_source=deveco)
* 🔗 [Veo 3 on Vertex AI Documentation](https://cloud.google.com/vertex-ai/generative-ai/docs/models/veo/3-0-generate-preview?utm_campaign=deveco_gdemembers&utm_source=deveco)

---

## 🎥 How to Reproduce

1. Open each scene prompt in [`prompts/`](prompts/) (`scene-0-intro.md` through `scene-7-chorus.md`).
2. Refine or adapt the visual storytelling cues in **Google Gemini**.
3. Render each 8-second shot using **Google Veo 3** on Vertex AI.
4. Assemble and synchronize the rendered clips in **CapCut** (or your preferred NLE).

---

## 🗂️ Repository Structure

```text
A-Gemini-Veo-3-Whimsical-Short/
├── README.md
├── LICENSE
└── prompts/
    ├── scene-0-intro.md
    ├── scene-1-distraction.md
    ├── scene-2-slip.md
    ├── scene-3-first-note.md
    ├── scene-4-hi.md
    ├── scene-5-step-light.md
    ├── scene-6-ripple.md
    └── scene-7-chorus.md
```

Each `.md` file contains a 3D-animation-ready scene specification with dialogue, camera cues, character-consistency anchors, and emotional tone.

---

## 💡 Inspiration

> *A single hum can start a chorus.*

*Sofia's Song* is a reminder that courage often starts small—and when one voice dares to rise, others follow. Created for whimsical storytelling fans, AI filmmakers, and educators.

**✨ Made with imagination. Powered by Google Gemini + Veo 3. ✨**

---

### 🚀 Featured Google Cloud & Agentic AI Portfolio by Robina Mirbahar

| Repository | Architecture & Focus | Live Status |
| :--- | :--- | :--- |
| **[My-antigravity-research-skills](https://github.com/RobinaMirbahar/My-antigravity-research-skills)** | Official Google Antigravity Research Kit: 8 Scientific Skills, Stdio MCP Server (Wilson CIs, DOI checks), Safety Hooks & 60-FPS Paper Explorer | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/My-antigravity-research-skills?style=flat-square&color=4285F4) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/My-antigravity-research-skills?style=flat-square) |
| **[gemma4-multilora-adk-eval](https://github.com/RobinaMirbahar/gemma4-multilora-adk-eval)** | Dynamic Multi-LoRA Hot-Swapping & CI/CD Agent Evaluation (`adk eval`) on Cloud Run GPUs with Gemma 4 & vLLM | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/gemma4-multilora-adk-eval?style=flat-square&color=4285F4) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/gemma4-multilora-adk-eval?style=flat-square) |
| **[slothsre-napops](https://github.com/RobinaMirbahar/slothsre-napops)** | SlothSRE ("NapOps") — Overnight Gemma 4 & Google ADK Incident Digest Agent with OpenTelemetry & Sentry AI Monitoring | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/slothsre-napops?style=flat-square&color=34A853) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/slothsre-napops?style=flat-square) |
| **[streamforge-event-adk](https://github.com/RobinaMirbahar/streamforge-event-adk)** | Real-Time Event-Driven Multi-Agent Pipelines on Google Cloud with ADK (`ParallelAgent` & `LoopAgent`), Eventarc & Pub/Sub | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/streamforge-event-adk?style=flat-square&color=FBBC04) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/streamforge-event-adk?style=flat-square) |
| **[a2a-mcp-mesh-cloudrun](https://github.com/RobinaMirbahar/a2a-mcp-mesh-cloudrun)** | Agent-to-Agent (A2A) & Multi-MCP Mesh on Cloud Run with Gemma 4, Google ADK, Spanner Graph & AlloyDB | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/a2a-mcp-mesh-cloudrun?style=flat-square&color=EA4335) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/a2a-mcp-mesh-cloudrun?style=flat-square) |
| **[cloudguard-gemma-agent](https://github.com/RobinaMirbahar/cloudguard-gemma-agent)** | 6-Part Production Gemma Enterprise Agent Platform (ADK, Cloud Run L4 GPU, Firestore, Model Armor, Vertex AI QLoRA) | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/cloudguard-gemma-agent?style=flat-square&color=4285F4) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/cloudguard-gemma-agent?style=flat-square) |
| **[Comic-Studio-Ai](https://github.com/RobinaMirbahar/Comic-Studio-Ai)** | Multi-Agent Comic Generator powered by Google Gemini API & FastAPI deployed on Google Cloud Run | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/Comic-Studio-Ai?style=flat-square&color=EA4335) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/Comic-Studio-Ai?style=flat-square) |
| **[vertex-ai-imagen3](https://github.com/RobinaMirbahar/vertex-ai-imagen3)** | Generate AI-powered product & editorial images using Google Vertex AI Imagen 3 in Google Colab | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/vertex-ai-imagen3?style=flat-square&color=34A853) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/vertex-ai-imagen3?style=flat-square) |
| **[cozy-ai-agent-cafe-game](https://github.com/RobinaMirbahar/cozy-ai-agent-cafe-game)** | Prompt Paws: 60 FPS Cozy AI Agent Bakery Simulation Game teaching RAG, Guardrails, Context Caching & Multi-Agent Loops | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/cozy-ai-agent-cafe-game?style=flat-square&color=7928CA) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/cozy-ai-agent-cafe-game?style=flat-square) |

<div align="center">
  <img src="https://raw.githubusercontent.com/RobinaMirbahar/RobinaMirbahar/main/ProfileImages/GithubBanner.svg" alt="Robina Mirbahar Banner" width="100%" />
</div>

<!-- AUTHOR_SIGNATURE_START -->
---

## 👩‍💻 About the Author

**Robina Mirbahar — Google Cloud & AI Architect**  
*Google Developer Expert (GDE) in Cloud & AI • Published Author • Women Techmakers Ambassador*

[![GitHub](https://img.shields.io/badge/GitHub-RobinaMirbahar-181717?style=for-the-badge&logo=github)](https://github.com/RobinaMirbahar)
[![Medium](https://img.shields.io/badge/Medium-@robinamirbahar-000000?style=for-the-badge&logo=medium)](https://medium.com/@robinamirbahar)
[![DEV.to](https://img.shields.io/badge/DEV.to-robinamirbahar-0A0A0A?style=for-the-badge&logo=devdotto)](https://dev.to/robinamirbahar)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Robina_Mirbahar-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/robinamirbahar)
[![GDE Profile](https://img.shields.io/badge/Google_Developer_Expert-Profile-4285F4?style=for-the-badge&logo=google)](https://developers.google.com/profile/u/106918534005910641104?utm_campaign=deveco_gdemembers&utm_source=deveco)
[![YouTube](https://img.shields.io/badge/YouTube-@RobinaCodesAI-FF0000?style=for-the-badge&logo=youtube)](https://www.youtube.com/@RobinaCodesAI)
[![X](https://img.shields.io/badge/X-@RobinaMirbahar-000000?style=for-the-badge&logo=x)](https://x.com/RobinaMirbahar)
[![Amazon Author](https://img.shields.io/badge/Amazon_Book-AI_Engineering_(2026)-FF9900?style=for-the-badge&logo=amazon)](https://amazon.com/dp/B0GWCZWCF4)

<!-- AUTHOR_SIGNATURE_END -->
