# Cloud Security Office Hours — Python Study Group

*Weekly, hands-on Sprints to learn Python for cloud security — short, project-driven, and community-led.*
Adapted from the Study Guide. 

---

## 🎯 Purpose

Run short, fixed-length **Sprints** where participants learn Python by building small, cloud-security-relevant projects (culminating in a CloudTrail analysis capstone). After a Sprint completes, the group decides the next Sprint — and we repeat as long as the community finds value in meeting.

---

## 🗓 Sprint 1 — cadence & important dates

* **Regular meeting:** Saturdays, **10:00 AM – 11:30 AM EST** (weekly).
* **Sprint 1 duration:** **November 1, 2025 – January 17, 2026** (holiday breaks included). 
* **Where we meet:** CSOH Zoom (link announced in Discord).
* **Chat & coordination:** CSOH Discord — *Learning* channel.
* **Shared drive:** CSOHP Open Share (treat as public by link — be careful with sensitive material). 

---

## 🧭 How a Sprint works

* **Structure:** Weekly sessions mix quick check-ins, open Q&A, and a short demo or mini-presentation by a participant.
* **Learning by doing:** Each week has a focused objective and a small project or exercise.
* **Recordings:** Presentation segments *may* be recorded; open Q&A is ideally unrecorded to keep the space comfortable. 
* **After the Sprint:** The group reconvenes to pick the next Sprint’s theme and schedule. If the group wants to continue, we run another Sprint.

---

## 🗂 Sprint 1 — weekly topics (summary)

Each week includes objectives and a short hands-on project so you learn by doing. Dates below reflect the Sprint 1 cadence. 

1. **Week 0 — Orientation**
   Kickoff, logistics, Zoom/Discord setup, shared drive guidelines. 

2. **Week 1 — Python basics (Nov 1, 2025)**
   Run scripts, variables, input/output. *Mini-project:* interactive prompt script. 

3. **Week 2 — Reading & filtering logs (Nov 8, 2025)**
   File I/O, filtering lines. *Mini-project:* fake firewall log filter. 

4. **Week 3 — Lists, dicts & loops (Nov 15, 2025)**
   Aggregation and counting. *Mini-project:* event counting threat-hunt. 

5. **Week 4 — Flask basics (Nov 22, 2025)**
   Simple web server and routes. *Mini-project:* Hello World with multiple routes. 

6. **Week 5 — Forms & user input (Flask) (Dec 6, 2025)**
   GET/POST and local persistence. *Mini-project:* small To-Do app. 

7. **Week 6 — JSON crash course (Dec 13, 2025)**
   Parse JSON, handle CloudTrail-style events. *Mini-project:* extract `eventName`, `userIdentity.userName`, `sourceIPAddress`. 

8. **Week 7 — Analyzing local logs (Dec 20, 2025)**
   Top eventNames, failed `ConsoleLogin` detections, optional CSV export. 

9. **Week 8 — Intro to Boto3 & S3 (Jan 3, 2026)**
   Set up credentials, list/download objects (local practice possible). 

10. **Week 9 — CloudTrail + Boto3 (Part 1) (Jan 10, 2026)**
    Download and parse gzipped CloudTrail logs; begin analysis. 

11. **Week 10 — CloudTrail + Boto3 (Capstone) (Jan 17, 2026)**
    Build a CloudTrail analyzer: top users/events/IPs, detect IAM changes, export CSV. 

---

## ✅ Getting started (participants)

* **Prereqs:** Computer with modern browser; Python 3.10+ installed *or* use GitHub Codespaces (see below). Optional: an AWS free tier account for hands-on S3/CloudTrail practice.
* **Before week 0:** Join CSOH Discord and confirm Zoom access. Verify `python --version` locally or that Codespaces loads in your browser. 
* **Safety:** Do **not** share AWS credentials, PII, or sensitive logs in public chat or the shared drive. The shared drive is accessible by anyone with the link — treat it like public storage. 

---

## 💻 GitHub Codespaces — short explainer (user-focused)

To reduce setup friction, we will provide a **Codespace** tuned for Python dev. This is a browser-hosted VS Code environment preconfigured for the Sprint exercises.

**What to expect**

* Ready-to-use VS Code in your browser with Python available.
* Preinstalled common Python tooling (linters, test runner, virtualenv support).
* Integrated Git, port forwarding for local web servers (Flask demos), and persistent settings.

**How to use it (overview)**

1. From the study-group repo on GitHub: **Code → Codespaces → Create codespace** (or pick an existing one).
2. Wait for initialization; the browser VS Code will open.
3. Use the integrated terminal to run exercises or start local servers.
4. Use the Git UI in Codespaces to create branches, commit, and open PRs.
5. Optionally connect the Codespace to your desktop VS Code.

**Best practices**

* Treat Codespaces as a disposable dev environment — commits go to Git as usual.
* Don’t store secrets in the Codespace; use environment variables or GitHub Secrets for CI.
* Codespaces reduces local setup friction — but using your local Python install is perfectly fine.

*(No Codespaces config or code is included here — this is an explainer for users only.)*

---

## 📚 Resources (starter list)

* Python docs: [https://docs.python.org/3/tutorial/](https://docs.python.org/3/tutorial/)
* Flask quickstart: [https://flask.palletsprojects.com/](https://flask.palletsprojects.com/)
* Boto3 & AWS SDK: [https://boto3.amazonaws.com/](https://boto3.amazonaws.com/)
* JSON, gzip, csv module docs (Python stdlib)
  Full bibliography and handouts are kept in the shared drive. 

---

## 🤝 Contributing & facilitation

* Lead a mini-topic (10–15 min)? Volunteer in Discord.
* Facilitation and moderation rotate by volunteer. Organizers coordinate in Discord.
* Use **Conventional Commits** for commit messages to keep history clear.
* Open issues for bugs, resources, or topic requests. PRs welcome.

---

## 🛡 Code of Conduct

* Respectful behavior required — assume positive intent.
* No marketing or sales pitches.
* Do not post credentials, PII, or sensitive logs in public channels. Violations may result in removal from the group.

---

## 📬 Contact & links

* Study Guide & Sprint materials: see the attached Study Guide. 
* CSOH Zoom & Discord: posted in Study Group announcements.
* Want additional repo docs (CONTRIBUTING.md, facilitator checklist, issue templates)? Ask and we’ll draft them.
