🧭 About Me

👨‍🎓 B.Tech – Computer Science & Engineering, VIT Chennai (2022–2026)

💻 Full‑Stack (MERN) + ML/Deep Learning

☁️ AWS Cloud enthusiast & AWS Cloud Practitioner certified

🧩 I love solving real‑world problems and polishing systems end‑to‑end

🏏 Team player (cricket captain) & event host 🎤

🔭 Featured Projects

Visuals make everything better! Add GIFs/demo screenshots inside each card (drag files into your repo’s /assets folder and update the src).

🛠️ Tech Stack
🧪 What I'm Learning

Advanced ML model stacking and MLOps

AWS serverless architectures & CDK

System design for scalable web apps

🏅 Certifications
📊 GitHub Analytics

Tip: If any image fails on first load, refresh once—these services sometimes cache.

🐍 Contribution Graph Snake (Animated)

Enable this with a small GitHub Action (instructions below). Once set, this image animates your contribution graph.

Create a repo named SafeeqAhamed (exactly your username). This becomes your profile README repo.

Add a folder .github/workflows/ and create snake.yml with the contents below.

Commit and push. The Action will generate the output/github-contribution-grid-snake.svg file.

name: Generate snake
on:
  schedule:
    - cron: "0 0 * * *"   # daily
  workflow_dispatch:


jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: SafeeqAhamed
          outputs: |
            dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
🤝 Connect with Me

💼 LinkedIn: @safeeq-ahamed7

💻 GitHub: @SafeeqAhamed

📧 Email: ssafeeq2004@gmail.com

🧠 LeetCode: @Safeeq_Ahamed
