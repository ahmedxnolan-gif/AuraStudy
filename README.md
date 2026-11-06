🌌 AuraStudy — Ultra Eye-Friendly AI Study Companion

📖 Table of Contents •
🚀 Key Features •
🔑 Getting Gemini API Key •
🎨 Color Palettes •
🌐 Deployment

📖 Table of Contents

✨ About The Project

🚀 Key Features

🔑 How to Get a Free Gemini API Key

🎨 Eye-Friendly Dark Themes

🌐 Deployment on GitHub Pages

🛠️ Tech Stack

✨ About The Project

AuraStudy is not just another basic text summarizer. It is a full-featured, ultra eye-friendly, AI-powered study companion crafted for university and high school students.

Designed as a Single-File Web Application, AuraStudy requires zero backend infrastructure or local dependencies. It prioritizes eye ergonomics for long late-night study sessions and introduces a Multi-Page Navigation Engine to eliminate text truncation when reading lengthy study materials.

┌────────────────────────────────────────────────────────────────────────┐
│                        AURASTUDY ARCHITECTURE                          │
├───────────────────┬──────────────────────────────────┬─────────────────┤
│ 📂 MULTI-FORMAT   │ 🧠 GEMINI 3.8 FLASH ENGINE       │ 📖 MULTI-PAGE   │
│ PDF / DOCX / TXT  │ Full Context + Continuous Logic  │ Step-by-Step UI │
└───────────────────┴──────────────────────────────────┴─────────────────┘


🚀 Key Features

Feature

Description

📄 Multi-Page Navigation

Automatically splits comprehensive study guides into logical sequential pages (Page X of Y) to prevent truncation.

🎨 5 Eye-Friendly Themes

Carefully tuned dark palettes to eliminate severe high-contrast glare and reduce eye fatigue.

📚 Universal Document Reader

Native client-side parsing for PDF, DOCX, and TXT files without external server processing.

🗣️ Tri-Language Support

Explains complex topics in Egyptian Arabic, Simple Modern Standard Arabic, or English.

📐 MathJax & LaTeX Engine

Native rendering for complex mathematical notations, formulas, physics equations, and calculus.

💬 Contextual AI Chat Tutor

Interactive side-by-side tutor assistant calibrated strictly to the currently visible page content.

🧪 Smart Practice Generator

Generates tailored quizzes including Multiple Choice (MCQ), True/False, and Essay questions.

🔑 How to Get a Free Gemini API Key

⚡ The API Key is 100% Free and takes less than 60 seconds to generate!

📍 Step-by-Step Instructions:

Visit Google AI Studio:

👉 Google AI Studio — Get API Key

Sign In:

Log in using any standard Google / Gmail account.

Generate Key:

Click the Create API Key button.

Choose Create API key in new project (or select an existing project).

Copy & Paste:

Copy your generated secret key string (starts with AIzaSy...).

Open AuraStudy in your web browser.

Open the Gemini AI Config collapsible section in the sidebar.

Paste the key into the Gemini API Key field and start learning!

🔒 Privacy First Note:
Your API Key is stored exclusively inside your browser's local storage (LocalStorage). 
It is never transmitted to any third-party server and communicates strictly with Google's official endpoints.


🎨 Eye-Friendly Dark Themes

AuraStudy provides 5 engineered, low-glare themes tailored for long reading sessions:

[ ⬛ Deep Charcoal ]  -->  #121417  | Ultra low-light setup for total darkness
[ 🟦 Muted Navy     ]  -->  #0f141c  | Soft navy tones for developer aesthetics
[ 🩶 Slate Gray     ]  -->  #14171a  | Balanced slate contrast for academic reading
[ 🌙 Subtle Midnight]  -->  #0a0e17  | Deep midnight blue for focus & immersion
[ 🪵 Warm Dark Ash  ]  -->  #181716  | Warm muted tones to prevent dry-eye syndrome


🌐 Deployment on GitHub Pages

Because AuraStudy is designed as a clean single-file app (index.html), deploying it to GitHub Pages takes under 2 minutes:

1️⃣ Push files to GitHub:

git add index.html README.md
git commit -m "feat: Deploy AuraStudy Ultra Eye-Friendly Application"
git push origin main


2️⃣ Enable GitHub Pages:

Go to your repository on GitHub.

Click on Settings ⚙️ and navigate to Pages on the left menu.

Under Build and deployment:

Branch: Select main (or master).

Folder: Select / (root).

Click Save.

🔗 Your live website link will be: https://<your-username>.github.io/<repository-name>/

🛠️ Tech Stack

UI Framework: Vanilla HTML5 & Modern CSS3 (CSS Custom Properties, Flexbox, Grid).

Typography: Plus Jakarta Sans, Space Grotesk, Cairo (via Google Fonts).

AI Model: Google Gemini REST API (gemini-3.8-flash / gemini-3.5-flash-lite).

Document Parsing: PDF.js (PDF extraction) & Mammoth.js (DOCX extraction).

Math Rendering: MathJax v3 for LaTeX equation typesetting.
