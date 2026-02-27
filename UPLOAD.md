# How to upload this repo to GitHub (Web UI) / Как залить в GitHub (через сайт)

## 🇷🇺
> Важно: GitHub **не распаковывает** zip автоматически. Нужно распаковать архив на компьютере и загрузить файлы/папки.

1. Создайте пустой репозиторий на GitHub (Public).
2. Скачайте архив и распакуйте его в папку `qa-portfolio`.
3. Откройте репозиторий → **Add file → Upload files**.
4. Откройте распакованную папку, нажмите **Ctrl+A** (выделить всё) и перетащите **все файлы и папки** в область загрузки GitHub.
   - Лучше делать в Chrome/Edge: структура папок сохранится.
5. Нажмите **Commit changes**.

Если в репозитории появилась лишняя вложенность (например `qa-portfolio/qa-portfolio/...`), значит вы перетащили не содержимое, а родительскую папку. Нужно заливать так, чтобы в корне репозитория были `README.md` и `PROJECTS.md`.

## 🇬🇧
GitHub web UI does **not** unzip archives automatically. Unzip locally and upload the folder contents.

1. Create an empty GitHub repository.
2. Unzip this archive to a local folder.
3. Repo → **Add file → Upload files**.
4. Select **all files and folders** from the extracted folder (Ctrl+A) and drag & drop into GitHub uploader (Chrome/Edge recommended).
5. Commit changes.

Make sure `README.md` and `PROJECTS.md` are in the repository root.
