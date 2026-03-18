# GitHub-Homework

Ez a repository egy DevOps CI/CD házi feladat megoldását tartalmazza.

## Cél

A projekt célja egy egyedi Nginx alapú Docker image létrehozása, majd annak automatikus buildelése és feltöltése Docker Hub-ra GitHub Actions segítségével.

## Tartalom

- `Dockerfile`  
  Egy egyedi Nginx Docker image-et épít.

- `index.html`  
  Az Nginx által megjelenített kezdőoldal.

- `.github/workflows/docker-image.yml`  
  GitHub Actions workflow, amely buildeli és feltölti az image-et Docker Hub-ra.

## Eredmény

A konténer elindítása után az Nginx automatikusan elindul, és a következő szöveget jeleníti meg:

`DevOps homework by: Békefi Bendegúz`