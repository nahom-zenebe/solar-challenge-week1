
# Solar Challenge Week 0 - Interim Report  
**GitHub Repo:** [solar-challenge-week1](git clone https://github.com/nahom-zenebe/solar-challenge-week1.git)  

---

 **Task 1: Git & Environment Setup (Completed)**  

1. **Repository Setup**  
   - Created a GitHub repository named `solar-challenge-week1` and cloned it locally.  
   - Initialized the project with `.gitignore` to exclude `data/`, `.csv`, and virtual environment files.  

2. **Python Environment**  
   - Set up a virtual environment using `venv` and activated it.  
   - Installed required packages listed in `requirements.txt`:  
     ```python
     pandas==2.0.0
     numpy==1.24.0
     matplotlib==3.7.0
     ```  

3. **CI/CD Pipeline**  
   - Added a GitHub Actions workflow (`.github/workflows/ci.yml`) to automate dependency installation on push.  
   - Committed changes with clear messages:  
     - `"chore: initialized git repo and venv"`  
     - `"ci: added GitHub Actions workflow"`  

4. **Branching Strategy**  
   - Created a `setup-task` branch, made all changes, and merged it into `main` via a Pull Request.  

---
