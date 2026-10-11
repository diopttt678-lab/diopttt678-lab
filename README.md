
# Hi, I'm MLIA (Talla Diop) 👋

Student in **1ère S2** at **LYNAQE Kaffrine**, a scientific-track boarding school in Senegal 🇸🇳 — aiming to be genuinely strong in *every* subject: maths, physics-chemistry, biology, French, English, Spanish, Arabic, history-geography, EPS, and Civic.

I learn in small concrete steps — progressive, visual, with flashcards and exercises — and I'm honest that long unstructured tasks make me procrastinate, so I keep my work short and actionable.

---

### 🎯 Where I'm headed

- **IOAI 2027 — Singapore.** I already competed in 2026 in Astana with Team Senegal (no podium — so Singapore is about finishing what I started).

---

### 🔭 What I'm building

#### 🖥️ MLIA Academic OS

A personal academic operating system running on [Hermes Agent](https://github.com/NousResearch/hermes-agent) — my whole study life in one place:

- A **Telegram coach bot**
- **6 specialist agents**: planning, per-subject study, gap detection, curriculum tracking, administration, accountability
- Runs on `gemini-3.1-flash-lite` (Google) — I stay on free models by design
- Plus separate Hermes profiles for focused work: `chef-pack`, `hackathonsia`, `idea-receive`, `ai-veil`, `s2links`, and a `Repair_man` maintenance profile

#### 🎮 [chifoumi-arbitre](https://github.com/diopttt678-lab/chifoumi-arbitre)

A rock-paper-scissors referee you play with your hand through the webcam — MediaPipe Hands → gesture classification → a cheating computer opponent.

The detail I'm proudest of: `cv2.waitKey()` **blocks**. I was calling `waitKey(1800)` for the cheat popup, which froze the entire game loop for 1.8 seconds. The popup is now remembered and drawn over a fixed number of frames instead — never blocking. 5 tests cover the rules and the gesture logic without a webcam:

- `test_neuf_affrontements` — all nine matchups resolve correctly
- `test_triche_totale_fait_toujours_gagner_lordi` — the cheat logic
- `test_sans_triche_jamais_signalee` — no false positives
- `test_taux_de_victoire_a_30_pourcent` — the win-rate tuning
- `test_gestures` — gesture classification

---

### 🛠️ Tools & languages

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/-MediaPipe-0097A7?style=flat&logo=google&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/-pandas-150458?style=flat&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![Telegram](https://img.shields.io/badge/-Telegram-26A5E4?style=flat&logo=telegram&logoColor=white)
![Obsidian](https://img.shields.io/badge/-Obsidian-7C3AED?style=flat&logo=obsidian&logoColor=white)

### 🌱 Currently working on

IOAI 2027 prep (machine learning, NLP, computer vision, and taking AI ethics seriously rather than memorising it), and getting better at writing the test *before* the code.

---

### 📫 Reach me

GitHub [@diopttt678-lab](https://github.com/diopttt678-lab) · LYNAQE Kaffrine, Senegal 🇸🇳

<sub>I write in French and English — French and Wolof are home, but IOAI is an English-language goal, so I'm putting in the work.</sub>
```
