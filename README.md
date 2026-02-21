# Arena (Pygame) → Web (iPad/Safari) via pygbag

## Run locally (optional)
pip install pygbag
pygbag --build src
python -m http.server -d src/build/web 8000

## GitHub Pages
Because GitHub web uploader blocks hidden folders like `.github`, create the workflow file in GitHub UI:

Add file → Create new file → name: `.github/workflows/deploy.yml` and paste the YAML from `workflow_deploy.yml.txt`.
