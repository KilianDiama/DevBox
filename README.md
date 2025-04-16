# 🧰 DevBox

**DevBox** est une boîte à outils pour développeurs : un assistant intelligent et polyvalent qui centralise des utilitaires pour t’aider à coder plus vite, mieux, et avec style.

---

## 🧠 À propos

Conçu pour être un compagnon de bureau numérique, **DevBox** te permet :

- De générer du code automatiquement avec l’IA
- De formater ou corriger du code existant
- D’expliquer des snippets complexes
- De gérer des mini-projets ou tâches récurrentes en dev

Un assistant personnel 100% Python, 100% productivité.

---

## ✨ Fonctionnalités

- 💬 Génération de code avec GPT (ex: "génère une fonction Flask")
- 🧠 Résumés ou explications de code
- 🛠️ Outils de formatage, nettoyage, renommer des variables, etc.
- 🖥️ Interface simple via Tkinter
- 📁 Système modulaire pour ajouter tes propres plugins

---

## 🛠️ Tech Stack

- Python
- OpenAI API
- Tkinter
- Ast / re / os / shutil (outils internes pour manipuler le code)
- Optionnel : Black, Flake8 (formatting & linting)

---

## ⚙️ Installation

```bash
git clone https://github.com/KilianDiama/DevBox.git
cd DevBox
pip install -r requirements.txt
🔐 Configure ta clé OpenAI dans un fichier .env ou directement dans le script.

▶️ Utilisation
bash
Copier
Modifier
python devbox.py
Lance la GUI et commence à générer, corriger ou manipuler du code avec des prompts simples.

📸 Aperçu
Ajoute une capture d’écran de l’interface ou un exemple de génération de code.

🔮 Roadmap
📦 Marketplace de plugins DevBox (formateurs, snippets, AI assistants)

🌐 Version web en Streamlit ou Next.js

🧠 Ajout de mémoire contextuelle pour suivre un projet dans le temps

⌨️ Intégration VSCode / Sublime (en extension)

📜 Licence


✍️ Par Diamajax
“DevBox, c’est pas un IDE. C’est ton copilote.” — Diamajax
