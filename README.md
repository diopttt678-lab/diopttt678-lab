# Hi, I'm Talla Diop (MLIA) 👋

High-school student (1ère S2, LYNAQE Kaffrine 🇸🇳) building AI and computer vision projects in Python.

🎯 **Goal: IOAI 2027, Singapore.** I competed in 2026 in Astana with Team Senegal (no podium), so Singapore is about finishing what I started.

---

## 🔭 Projects

### 🎮 [chifoumi-arbitre](https://github.com/diopttt678-lab/chifoumi-arbitre)
Rock-paper-scissors you play with your hand through the webcam: MediaPipe Hands → gesture classification → a computer opponent that cheats.

**The bug I'm proudest of fixing:** `cv2.waitKey()` blocks. I was calling `waitKey(1800)` for the cheat popup, which froze the whole game loop for 1.8 seconds. Now the popup is drawn over a fixed number of frames instead, so the loop never blocks.

✅ 5 tests cover the rules and gesture logic, no webcam needed:
- `test_neuf_affrontements`: all nine matchups resolve correctly
- `test_triche_totale_fait_toujours_gagner_lordi`: the cheat logic
- `test_sans_triche_jamais_signalee`: no false positives
- `test_taux_de_victoire_a_30_pourcent`: win-rate tuning
- `test_gestures`: gesture classification

### 🖥️ MLIA Academic OS
<!-- Add the repo link here once it's published -->
My personal academic operating system, built on [Hermes Agent](https://github.com/NousResearch/hermes-agent):
- A **Telegram coach bot**
- **6 specialist agents**: planning, per-subject study, gap detection, curriculum tracking, administration, accountability
- Runs on `gemini-3.1-flash-lite`. I stay on free models by design.
- Separate profiles for focused work: `chef-pack`, `hackathonsia`, `idea-receive`, `ai-veil`, `s2links`, plus `Repair_man` for maintenance

---

## 🛠️ Tools & Languages
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/-MediaPipe-0097A7?style=flat&logo=google&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/-pandas-150458?style=flat&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![Telegram](https://img.shields.io/badge/-Telegram-26A5E4?style=flat&logo=telegram&logoColor=white)
![Obsidian](https://img.shields.io/badge/-Obsidian-7C3AED?style=flat&logo=obsidian&logoColor=white)

## 🌱 Currently learning
- ML, NLP and computer vision for IOAI 2027
- AI ethics: understanding it, not memorising it
- Writing the test *before* the code

## 🧠 How I work
I learn in small concrete steps (visual, flashcards, exercises) and keep tasks short and actionable. Outside code, I'm aiming to be strong in every subject of the S2 track, from maths and physics to languages.

---

📫 [LinkedIn](https://www.linkedin.com/in/talla-diop-7098bb291/) · diopt3878@gmail.com · I write in French and English (French and Wolof at home).
