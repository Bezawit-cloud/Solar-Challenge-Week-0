# Solar Panel Challenge - Week 0

This repository sets up the Solar Panel Challenge Week 0, including project structure, virtual environment, dependencies, and GitHub Actions workflow.

---

## Project Structure
.github/workflows/ci.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
│ ├── init.py
│ ├── notebooks/init.py
│ └── scripts/init.py
├── tests/init.py
## Steps
1. Create GitHub Repository
- Name: `solar-challenge-week0`
- Do **not** add README (we have one locally)

 2. Clone Repository
```bash
git clone https://github.com/YourUsername/solar-challenge-week0.git
cd C:\Users\bezis\Downloads\kifya(1)
 3. Create Virtual Environment
python -m venv myenv
 4. Create .gitignore
myenv/
data/
 5. Create GitHub Actions Workflow
mkdir -p .github/workflows
echo.> .github/workflows/ci.yml

6 Create Branch
git checkout -b setup-task
Add, Commit, Push
git add .
git commit -m "init: setup project structure, .gitignore, workflow, README"
git push origin setup-task
7 Merge to Main
GitHub → Pull Requests → New → Compare setup-task with main → Merge
8 Verify
.github/workflows/ci.yml exists in main




