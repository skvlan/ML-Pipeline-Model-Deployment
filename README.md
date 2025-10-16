   # Projekt UMwC 48789
   To jest mój pierwszy projekt na GitHub. 🚀


## 🧩 Continuous Integration – GitHub Actions

Ten projekt zawiera workflow **CI-ML**, który:
- uruchamia się automatycznie na push, PR lub manualnie,
- instaluje zależności z plików `requirements*.txt`,
- wykonuje lint (flake8) i format check (black),
- uruchamia testy pytest,
- trenuje model ML (Logistic Regression),
- publikuje model jako artefakt z nazwą środowiska (`model-dev`, `model-prod`),
- wykorzystuje repozytoryjne Variables i Secrets.
