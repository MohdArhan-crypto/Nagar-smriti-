# Nagar Smriti (नगर स्मृति) 🏛️

**City's Institutional Memory & Underground Infrastructure Reconciler**

Nagar Smriti is a web-based municipal utility engine designed to reconcile fragmented agency records (BWSSB, BESCOM, BBMP) for street corridors and resolve infrastructure conflicts using Gemini AI.

---

## 🚀 Live Demo

Access the live application here:  
👉 **[https://MohdArhan-crypto.github.io/Nagar-smriti-/](https://MohdArhan-crypto.github.io/Nagar-smriti-/)**

---

## ✨ Features

* **Cross-Agency Record Parsing**: Reconciles disparate datasets across water, electricity, and road authorities.
* **AI-Powered Conflict Detection**: Uses Google's `gemini-1.5-flash` model to analyze overlapping permits and utility hazards.
* **Client-Side Security**: API keys are handled strictly via local browser storage (`localStorage`) and never sent to a backend server.

---

## 🛠️ How to Use

1. Open the live demo link.
2. Enter your **Gemini API Key** when prompted (key is saved locally in your browser).
3. Select or enter a target corridor query to generate a reconciled infrastructure report.

---

## 🧰 Tech Stack

* **Frontend**: HTML5, Tailwind CSS, Marked.js
* **AI Integration**: `@google/genai` SDK (`gemini-1.5-flash`)
* **Hosting**: GitHub Pages
