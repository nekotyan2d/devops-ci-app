# devops-ci-app

Учебное Flask-приложение для практической работы № 10.

Pylint → pytest → Docker build → smoke-test → GHCR.

Pull Request выполняет проверки. Публикация запускается при push в main.

- Проверка доступности: `/health`
- Образ: `ghcr.io/nekotyan2d/devops-ci-app`
- Конвейер: `.github/workflows/ci.yml`
