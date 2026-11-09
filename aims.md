# Цели проекта linux-backup-site

## 2026-11-09 — Страницы для OAuth-приложения Linux Backup

**Цель** — опубликовать homepage и privacy policy, которые Google Auth Platform требует для перевода личного OAuth-приложения Linux Backup (бэкап Ubuntu в Google Drive через rclone/restic) в режим Production.

**Фичи**
- `index.html` — описание приложения.
- `privacy.html` — политика конфиденциальности (scope `drive.file`, данные не передаются третьим лицам).
- Публикация через GitHub Pages: https://zerofivefiveseven.github.io/linux-backup/

**Требования**
- Статические страницы без внешних скриптов и трекеров.
- Личный email не публикуется; контакт — GitHub Issues репозитория.

**План**
1. Создать страницы и коммит.
2. Создать публичный репозиторий `zerofivefiveseven/linux-backup`, включить Pages из ветки `main`.
3. Проверить, что обе страницы отвечают HTTP 200.

**Критерии готовности**
- Обе ссылки открываются; их можно вставить в Branding.

**Вне рамок**
- Верификация домена и приложения Google.
