# Wallis · Naters — Zermatt · Arolla 2026

Статична сторінка з планом тріпу для групи 3 (GitHub Pages).

## Deploy

1. Публічний репозиторій на GitHub, напр. `schweiz-2026`
2. Push цю папку:

```bash
cd schweiz-2026
git init
git add .
git commit -m "Add Switzerland trip plan for GitHub Pages"
git branch -M main
git remote add origin https://github.com/<username>/schweiz-2026.git
git push -u origin main
```

3. GitHub → **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` · folder: **`/docs`**
   - Save

4. Сайт:

```
https://<username>.github.io/schweiz-2026/
```

## Локальний перегляд

```bash
open docs/index.html
```

## Оновлення

Зміни в `docs/index.html` → commit + push.
