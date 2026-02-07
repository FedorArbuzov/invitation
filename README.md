# Приглашение на свидание

Страница-приглашение: картинг «Шикана» на Острове мечты и ресторан с вкусным мясом.

## Как опубликовать на GitHub Pages

1. Создай репозиторий на GitHub (например, `invitation` или `date-invitation`).
2. Залей код в репозиторий:
   ```bash
   git init
   git add .
   git commit -m "Invitation page"
   git branch -M main
   git remote add origin https://github.com/ТВОЙ_ЛОГИН/ИМЯ_РЕПОЗИТОРИЯ.git
   git push -u origin main
   ```
3. В репозитории открой **Settings** → **Pages**.
4. В разделе **Build and deployment** выбери:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (или `master`)
   - **Folder**: `/ (root)`
5. Сохрани. Через 1–2 минуты страница будет доступна по адресу:
   `https://ТВОЙ_ЛОГИН.github.io/ИМЯ_РЕПОЗИТОРИЯ/`

Главная страница сайта — `index.html` в корне.
