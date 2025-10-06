# 3D Print Wizard

A simple browser-based app that lets you **generate and view 3D printable models** directly in your web browser — no server required.

## 🚀 Features
- Generate 3D models using simple text prompts (e.g. `cube 20`, `sphere 10`, `cylinder 8 30`).
- View existing STL, OBJ, or GLTF files in real time.
- Export models to **STL** format for 3D printing.
- Choose between **millimeters** and **inches** before exporting.

## 🧭 How to Host on GitHub Pages
1. Go to [GitHub.com](https://github.com) → Create a new repository (public).
2. Upload `index.html` and this `README.md`.
3. Commit the changes.
4. Go to **Settings → Pages**.
5. Under **Source**, select `main` branch and `/ (root)` folder, then click **Save**.
6. Wait 1–2 minutes. Your site will be live at:

   `https://yourusername.github.io/3d-print-wizard`

## 💡 Example Prompt
```
cube 20
translate 30 0 0
sphere 10
color #ff8844
```