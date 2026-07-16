<div align="center">

<img src="https://raw.githubusercontent.com/USERNAME/USERNAME/main/assets/banner.png" width="100%" alt="banner" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=5EEAD4&background=050B1300&center=true&vCenter=true&width=600&lines=Building+real+AI+products%2C+not+just+demos;RAG+pipelines+%C2%B7+computer+vision+%C2%B7+NLP;Grinding+DSA%2C+one+commit+at+a+time" alt="Typing SVG" />

</div>

<img src="https://raw.githubusercontent.com/USERNAME/USERNAME/main/assets/terminal-divider.svg" width="100%" alt="divider"/>

## `> whoami`

I'm **Supreet Mohapatra**, a CSE undergrad from India building at the intersection of **applied AI** and **full-stack development**.

I build things that actually work — RAG pipelines, computer vision systems, NLP tools, and AI-integrated web apps. Currently deepening my DSA & system design skills while shipping real projects.

## `> currently_running.sh`

- 🧠 Building **DocMind-AI** — AI-powered PDF platform with semantic search & vector retrieval
- 📈 Grinding DSA daily on LeetCode (Java) · tracking progress in `DSA-series`
- 🏗️ Learning system design fundamentals
- ✍️ Writing about what I build on Medium & DEV.to
- 🤝 Open to collaborating on AI-integrated apps and open source

📫 **supreetmohapatra06@gmail.com**

<img src="https://raw.githubusercontent.com/USERNAME/USERNAME/main/assets/terminal-divider.svg" width="100%" alt="divider"/>

## `> ./debug_mode.sh`

> Every bug fixed here is a real lesson from shipping AI products. Click through, make a choice, see where it leads.

<details>
<summary><b>▶ START: docmind-ai just crashed in production. What do you check first?</b></summary>
<br>

<details>
<summary>🔍 A. Check if the vector DB retrieval is even returning relevant chunks</summary>
<br>

Good instinct — most "AI is dumb" bugs are actually **retrieval bugs**, not model bugs. The chunks were splitting mid-sentence, scattering related content across vectors.

**Fix:** overlap-aware chunking + re-embed.

➡️ *Lesson: garbage retrieval in = garbage generation out. The model was never the problem.*

**[Continue to Stage 2 ▼](#stage-2)**

</details>

<details>
<summary>🤖 B. Assume the LLM is hallucinating and tweak the prompt</summary>
<br>

Two hours rewriting the prompt. Output barely changes — the issue was upstream, in the data, not the wording.

➡️ *Lesson: this is exactly why I built `hallucination-detector` — most "hallucinations" are downstream of a data problem, not a model problem.*

**[Continue to Stage 2 ▼](#stage-2)**

</details>

<details>
<summary>😅 C. Panic-restart the server and hope it fixes itself</summary>
<br>

It does not fix itself. But it teaches you to add proper logging *before* the next crash.

➡️ *Lesson: real projects teach you things tutorials never do.*

**[Continue to Stage 2 ▼](#stage-2)**

</details>

</details>

<details>
<summary><a name="stage-2"></a><b>▶ STAGE 2: The fix works locally. Do you ship it straight to main?</b></summary>
<br>

<details>
<summary>🚀 A. Yes — it works on my machine, ship it</summary>
<br>

Classic. It breaks for a user with a slightly larger PDF than your test file.

➡️ *Lesson: "works on my machine" isn't a fix, it's a hypothesis.*

**[Continue to final stage ▼](#stage-3)**

</details>

<details>
<summary>🧪 B. Write one edge-case test first (empty file, huge file, weird encoding)</summary>
<br>

Smart. You catch a crash on empty PDFs before a real user does.

➡️ *Lesson: this is the DSA-brain kicking in — think about the edge case before it thinks about you.*

**[Continue to final stage ▼](#stage-3)**

</details>

</details>

<details>
<summary><a name="stage-3"></a><b>▶ FINAL: You win. What's the actual takeaway?</b></summary>
<br>

🏆 **You've completed debug_mode.sh**

There's no "correct" path above — every branch reflects something true about building real AI products: retrieval usually matters more than prompt cleverness, most hallucinations are data problems in disguise, and edge cases don't announce themselves — you have to go looking.

That's the whole philosophy behind this README: **build things that actually work**, not things that just demo well.

</details>

<img src="https://raw.githubusercontent.com/USERNAME/USERNAME/main/assets/terminal-divider.svg" width="100%" alt="divider"/>

## `> stack --list`

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,cpp,js,ts&theme=dark" /><br>
  <img src="https://skillicons.dev/icons?i=react,vite,tailwind,html,css&theme=dark" /><br>
  <img src="https://skillicons.dev/icons?i=fastapi,nodejs,flask&theme=dark" /><br>
  <img src="https://skillicons.dev/icons?i=mongodb,postgres,redis&theme=dark" /><br>
  <img src="https://skillicons.dev/icons?i=docker,aws,vercel,git,github&theme=dark" /><br>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv&theme=dark" />
</p>

## `> ls ./projects`

### 🧠 AI & ML

| Project | What it does | Stack |
|---|---|---|
| [hallucination-detector](https://github.com/) | Chrome extension + FastAPI backend that detects AI hallucinations using NLI models | Python · FastAPI · NLP · Chrome Extension · Gemini |
| [baby-cry-analyzer](https://github.com/) | Classifies infant cries (hunger, pain, tiredness) from audio using ML | Python · TypeScript · ML · Deep Learning |
| [Smart-attendance-system](https://github.com/) | Face recognition + voice verification + GPS-based attendance automation | Python · OpenCV · Pillow · Voice Recognition |
| [Friday-ai](https://github.com/) | Voice-enabled AI desktop assistant with a web interface, inspired by Iron Man's FRIDAY | Python · JS · TTS · HTML/CSS |

### 🌐 Full Stack & Frontend

| Project | What it does | Stack |
|---|---|---|
| [CodeBridge](https://github.com/) | Learning & internship platform with student/admin flows, cart, events | React · Vite · Tailwind · Axios |
| [EcoHub](https://github.com/) | Carbon footprint & sustainability tracking platform | React · JavaScript · Vite |

### 📚 Learning in Public

| Project | What it does |
|---|---|
| [DSA-series](https://github.com/) | My daily DSA grind — LeetCode problems, patterns, notes in Java |

<img src="https://raw.githubusercontent.com/USERNAME/USERNAME/main/assets/terminal-divider.svg" width="100%" alt="divider"/>

## `> contact --all`

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Portfolio-050B13?style=for-the-badge&logo=vercel&logoColor=5EEAD4" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Medium-050B13?style=for-the-badge&logo=medium&logoColor=5EEAD4" /></a>
  <a href="#"><img src="https://img.shields.io/badge/DEV.to-050B13?style=for-the-badge&logo=devdotto&logoColor=5EEAD4" /></a>
  <a href="mailto:supreetmohapatra06@gmail.com"><img src="https://img.shields.io/badge/Email-050B13?style=for-the-badge&logo=gmail&logoColor=5EEAD4" /></a>
  <a href="#"><img src="https://img.shields.io/badge/LinkedIn-050B13?style=for-the-badge&logo=linkedin&logoColor=5EEAD4" /></a>
</p>

## `> git log --stat`

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=USERNAME&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165"/>
</p>

<img src="https://raw.githubusercontent.com/USERNAME/USERNAME/main/assets/terminal-divider.svg" width="100%" alt="divider"/>
