# 🪞 Interview Mirror

**Interview Mirror** is an asynchronous behavioral self-coaching application built for the Interhuman May Build Challenge. It bridges the gap between what candidates *intend* to say and what their physical delivery actually *signals* under pressure.

Instead of analyzing text keywords or scripts, this tool leverages behavioral AI to interpret non-verbal communication layers—helping job seekers refine their presence before stepping into a real interview.

---

## ✨ Features

- **Role-Specific Frameworks:** Choose between 4 distinct job profiles (**Sales, Customer Success, Leadership, or Communications**). 
- **Dynamic Question Banks:** Features 6 highly realistic, role-specific prompts per profile with a live shuffle mechanism so you never run out of practice topics.
- **Competency-Weighted Analytics:** Automatically filters and maps Interhuman's 12 core social signals to the specific competencies required for the job
- **Constructive Self-Coaching Outputs:** Instantly translates raw API rationales into tactical, empowering self-coaching feedback instead of punitive HR marks.

---

## 🛠️ Tech Stack & Architecture

- **Frontend:** Pure HTML5, CSS3, and modern vanilla JavaScript.
- **Media Capture:** Native WebRTC and `MediaRecorder` APIs to handle browser webcam and microphone recording safely on the client side.
- **AI Engine:** Integrated directly with the **Interhuman Upload & Analyze API** to generate multi-modal event timelines, signal probabilities, and behavioral rationales.
- **Privacy & Ethics By Design:** Reframed from an invasive HR gatekeeping tool into a private, candidate-side psychological mirror—sidestepping the ethical and regulatory complications of automated hiring pipelines.

---

## 🚀 Local Development

While this application is hosted publicly via GitHub Pages, you can run it locally to bypass certain browser media restrictions:

1. Clone or download this repository.
2. Open your terminal/PowerShell in the folder containing `index.html`.
3. Start a local server:
```bash
   python -m http.server 8080
```
4. Navigate to http://localhost:8080 in Google Chrome.
5. Paste your Interhuman API key and start practicing!

## 💡 Behavioral Science Context
Human communication is plagued by self-reporting gaps. In high-stakes environments like interviews, candidates routinely struggle to objectively evaluate their own delivery. By structuring Interhuman's raw behavioral timestamps into constructive coaching frameworks, Interview Mirror makes the invisible visible, empowering individuals to close the gap between their intended message and actual non-verbal delivery.
