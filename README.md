# Сайт разработчика Hangman 2.0

Адрес сайта: https://trinarr.github.io/

Файл авторизованных продавцов рекламы: https://trinarr.github.io/app-ads.txt

## Публикация

В настройках репозитория GitHub откройте **Settings → Pages → Build and deployment** и выберите **Source: GitHub Actions**.
После отправки коммита в ветку `main` workflow `.github/workflows/pages.yml` публикует `index.html` и `app-ads.txt`. Его также можно запустить вручную: **Actions → Publish GitHub Pages → Run workflow**.

После успешной публикации проверьте, что `/app-ads.txt` открывается без авторизации и показывает текст файла. Укажите `https://trinarr.github.io/` как сайт разработчика в RuStore.

## Обновление app-ads.txt

Заменяйте корневой файл актуальной версией из рекламного кабинета. Не меняйте идентификаторы вручную. Если используете несколько рекламных сетей, объединяйте их актуальные строки в одном файле.

Политики игры продолжают публиковаться отдельно: https://trinarr.github.io/hangman20_godot/