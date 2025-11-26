# News Sentiment Forecast (FNSPID Analysis)

## Goal
Perform exploratory data analysis (EDA) on news headlines and publication data to extract insights for sentiment-based stock prediction.

---

## Project Structure

.vscode/
    settings.json
.github/
    workflows/
        unittests.yml
.gitignore
requirements.txt
README.md
src/
    __init__.py
notebooks/
    __init__.py
    README.md
tests/
    __init__.py
scripts/
    __init__.py
    README.md
data/           # CSV data files (ignored by Git)

---

## Quickstart

1. Create a virtual environment:

python -m venv .venv

2. Activate the virtual environment:

.venv\Scripts\Activate.ps1

3. Install dependencies:

pip install -r requirements.txt

4. Run tests:

pytest

---

## Branching Convention

- feature/* → New features
- task-1 → Initial exploratory data analysis (EDA) and project setup
- main ← Merge completed tasks via Pull Request (PR)

---

## CI/CD

GitHub Actions automatically runs tests on push or PR to ensure code quality.

---

## Task 1 Deliverables

- GitHub repository with task-1 branch
- Project folder structure in place
- Basic EDA on news data:
  - Descriptive statistics (headline length, publisher counts, publication trends)
  - Text analysis / topic modeling
  - Time series analysis of article publication frequency
  - Publisher analysis
- Committed changes at least three times a day with descriptive messages

---

## Contact

Nebiyat Takele  
Email: nebiyattakele23@gmail.com
