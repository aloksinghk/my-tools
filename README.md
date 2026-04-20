🚀 Dynamic Tools Hub

A modern, lightweight landing page to organize and access multiple HTML tools from a single interface.

This project provides a clean UI, search & filter capabilities, and favorite tools support — all running purely on static files (no backend required).

✨ Features
🔍 Live Search — Instantly find tools by name
🏷️ Category Filters — Auto-generated from config
⭐ Favorites System — Save frequently used tools (stored in browser)
🎨 Auto Icons — Icons assigned based on category
⚡ Lightweight & Fast — No frameworks, no dependencies
📁 Static Hosting Ready — Works with GitHub Pages, Netlify, etc.
📁 Project Structure

/project-folder
│── index.html # Main landing page
│── tools.json # Tool configuration (source of truth)
│── html-formatter.html
│── json-validator.html
│── color-converter.html
│── ... other tools

⚙️ How It Works
All tools are defined inside tools.json
index.html dynamically reads this file
UI (cards, filters, icons) is generated automatically
🧩 Configure Your Tools

Edit tools.json:

[
{ "name": "HTML Formatter", "file": "html-formatter.html", "category": "HTML" },
{ "name": "JSON Validator", "file": "json-validator.html", "category": "JSON" }
]

Fields
name → Display name of the tool
file → HTML file name (same folder)
category → Used for filtering + icon mapping
▶️ Run Locally

⚠️ Opening directly will NOT work:

file:///index.html

Because browsers block fetch() for local files.

✅ Use a local server:

Option 1 (Python):
python -m http.server

Option 2 (VS Code):

Install Live Server extension
Right-click index.html → Open with Live Server
🌐 Deploy for Free

You can host this project easily:

GitHub Pages
Netlify
Vercel

No backend needed — it's fully static.

⭐ Favorites Feature
Click ⭐ on any tool to save it
Stored in browser localStorage
Persists across sessions
🎨 Categories & Icons

Icons are automatically mapped:

HTML → 🌐
SEO → 📈
Design → 🎨
JSON → 🧩
Utility → 🛠️
Converter → 🔄

You can customize this inside index.html.

🚀 Future Enhancements
Favorites filter (show only starred tools)
Progressive Web App (install like app)
Smart search suggestions
Tool usage analytics
Dark mode
📜 License

Free to use and modify for personal or commercial projects.

🙌 Contribution

Feel free to improve UI, add features, or expand tools.

💡 Author Note

This project is designed for developers who want a simple, personal tools dashboard without complexity.

Enjoy building your own tool hub! 🚀
