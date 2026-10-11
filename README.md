<h1 align="center">Haim Galata</h1>
<h3 align="center">Software Engineer · AI, Backend & 3D Computer Vision</h3>

&nbsp;

<p align="center">
  <a href="https://linkedin.com/in/haim-galata-864b5b322/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:haimgalata@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

&nbsp;

Computer Science graduate (B.Sc., Sapir Academic College, 2026, GPA 90.1) who builds backend services and AI systems end to end: from LLM pipelines and computer-vision models to APIs, databases and cloud deployment.

- **Now:** Applied R&D Intern at **CoreWise**, a startup building LiDAR-based 3D scanning for home inspectors  
- **Before:** Research Intern at **CBG Cyber Labs, Ben-Gurion University**, where I owned the LLM layer of a network-intrusion detection pipeline  
- **Looking for:** Software Engineer, Backend, AI or Computer Vision roles in Israel

---

## Current Work: CoreWise (Applied R&D, 3D Computer Vision)

I work with the founder on open technical problems in an iPhone LiDAR scanning product: turning early ideas into experiments, building proofs of concept on real scans, and translating results into product requirements.

- Evaluated multi-scan point cloud registration across ARKit sessions (**ICP, RANSAC, FPFH**). When it proved unreliable, proposed a fixed start point (QR code) that relocalizes every scan into a shared WorldMap, now part of the product  
- Built a video-to-3D proof of concept with **YOLOE** and **SAM 2** that tracks objects such as windows across frames and maps them into the point cloud using ARKit depth and camera poses  
- Field-test the full workflow (iPhone app → cloud → web dashboard) and turn findings into features  
- `Python` `Open3D` `ARKit` `LiDAR` `Point Clouds` `YOLOE` `SAM 2`

*Company code is private; happy to walk through the approach in an interview.*

---

## Featured Projects

### [PrioritAI](https://github.com/haimgalata/Rocket-Damage-Prioritization-System): AI Damage Prioritization System

Decision-support platform that helps local authorities decide which rocket-damaged buildings to repair first, by combining a damage-classification model, GIS analysis and an LLM-generated explanation. Final project, team of 2.

- Trained a **ResNet50** model on 4,675 synthetic images, then fine-tuned it on hand-labeled real photos. Accuracy on held-out real images rose from **24.6% to 76.9%**  
- Built the **FastAPI** backend and deployed the ML service independently on **Google Cloud Run**  
- `Python` `TensorFlow` `FastAPI` `PostgreSQL` `Supabase` `React` `TypeScript` `Docker` `GCP`

### [SpeakTech](https://github.com/haimgalata/hackathon-english-platform): AI English Practice for Tech Professionals

Full-stack platform where developers practice spoken English with an AI tutor that gives structured feedback, plus vocabulary games and a teacher dashboard.

- `Next.js` `TypeScript` `MongoDB` `Groq (Llama 3.3)` `Web Speech API` `Phaser 3` `Tailwind CSS`

### [The Categories Game](https://github.com/haimgalata/the-categories-game): Multiplayer Telegram Bot

Real-time multiplayer game built at a hackathon. Answers are checked by a hybrid engine: fixed rules plus an LLM that returns a fixed-schema JSON response, with fallbacks for invalid output.

- `Python` `MongoDB` `Telegram Bot API` `Groq`

### [Stock Prediction using LDA](https://github.com/haimgalata/Stock-prediction-using-LDA)

Predicts next-day stock movement in 5 classes. The **Linear Discriminant Analysis** model is implemented from scratch in NumPy, without an ML library.

- `Python` `NumPy`

---

## Research Experience: CBG Cyber Labs, BGU

- Designed and built from scratch an LLM pipeline that explains anomalous network traffic and scores how likely it is to be malicious  
- Built three reasoning modes: baseline, CTI-augmented (VirusTotal, AbuseIPDB, IPQualityScore), and **multi-agent consensus**, where two opposing "expert" LLMs argue and a judge model decides  
- Built experiment infrastructure covering 16+ configurations, with config-driven runs, ablation studies, precision-recall evaluation, and checkpoint/resume

---

## Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=py,java,cpp,cs,js,ts" alt="Languages"/><br/>
  <img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,react,nextjs,tailwind" alt="Frameworks"/><br/>
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,supabase,docker,gcp,git,linux" alt="Data and DevOps"/><br/>
  <img src="https://skillicons.dev/icons?i=tensorflow,sklearn" alt="ML"/>
</p>

&nbsp;

**AI:** LLM integration (OpenAI, Gemini, Groq), prompt engineering, multi-agent pipelines, Claude Code, Cursor  
**3D & Vision:** Open3D, ARKit, LiDAR point clouds, ICP / RANSAC / FPFH registration, YOLOE, SAM 2, OpenCV
