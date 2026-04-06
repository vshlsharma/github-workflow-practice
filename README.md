# 🚀 DevOps GitHub Workflow Project

## 📌 Overview
This project demonstrates a complete GitHub-based DevOps workflow including branching strategy, pull requests, issue tracking, and CI/CD automation using GitHub Actions.

---

## ⚙️ Features

- ✅ GitHub branching strategy (`main` + `feature/*`)
- ✅ Pull Request (PR) workflow
- ✅ Issue tracking and linking
- ✅ CI/CD pipeline using GitHub Actions
- ✅ Automated script execution on push
- ✅ Real-time debugging of pipeline failures

---

## 🛠️ Tech Stack

- Git
- GitHub
- Linux (Bash)
- GitHub Actions (CI/CD)

---

## 📂 Project Structure
├── app.sh
└── .github/
└── workflows/
└── devops.yml


---

## 🚀 CI/CD Pipeline

The pipeline is triggered on:
- Push to `main` branch
- Pull requests

### 🔧 Workflow Steps:
1. Checkout repository code
2. Provide execution permission to script
3. Execute shell script (`app.sh`)

---

## 🧪 Script Example

```bash
#!/bin/bash
echo "Hi DevOps World"

🔥 Key Learnings
Implemented real-world GitHub workflow
Understood PR-based development
Learned issue linking (Fixes #issue-number)
Built CI/CD pipeline from scratch
Debugged real pipeline failures
📈 Future Improvements
Add Docker integration
Deploy application on AWS
Enhance pipeline with testing stage
👨‍💻 Author

Vishal Sharma

LinkedIn: https://www.linkedin.com/in/vishalsharma20540/
GitHub: https://github.com/vshlsharma
⭐ Conclusion

This project reflects a hands-on understanding of DevOps practices using GitHub and CI/CD automation.
