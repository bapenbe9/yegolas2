# Яе голас — сайт (GitHub Pages)

Главная страница — `index.html`. Все остальные файлы лежат в папках рядом с ней:

| Папка | Что внутри |
|---|---|
| `img/` | баннеры и портреты авторок |
| `sheets/` | рабочие листы (`<ключ>.jpg`) |
| `plans/` | планы-конспекты уроков (`<ключ>.docx`) |
| `audio/` | аудиозаписи (`<ключ>-bio.m4a`, `<ключ>-poem.m4a`) |

## Ключи авторок

| Авторка | Ключ |
|---|---|
| Цётка | tsetka |
| Канстанцыя Буйло | buylo |
| Еўгенія Янішчыц | yanishchyts |
| Ніна Мацяш | matsyash |
| Данута Бічэль | bichel |
| Раіса Баравікова | baravikova |
| Людміла Рублеўская | rubleuskaya |
| Яўгенія Пфляўмбаўм | pflaumbaum |
| Ядвіга Бяганская | byaganskaya |
| Зоська Верас | veras |
| Ніна Тарас | taras |

## Как добавить аудио

1. Запись о жизни авторки (биография) назовите `<ключ>-bio.m4a`, чтение стихотворения — `<ключ>-poem.m4a`. Например: `audio/buylo-bio.m4a`, `audio/buylo-poem.m4a`.
2. Положите файл в папку `audio/` (на GitHub: **Add file → Upload files**, затем **Commit changes**).
3. Больше ничего менять не нужно: плеер сам найдёт файл. Пока файла нет, у плеера показывается «Хутка».
4. Формат — `.m4a` (AAC). Для речи хватает 48 кбит/с, моно.

Готовы сейчас: `tsetka-bio.m4a`, `tsetka-poem.m4a`, `baravikova-poem.m4a`, `baravikova-bio.m4a`, `taras-bio.m4a`, `taras-poem.m4a`.

## Правила имён файлов
Только латиница, строчные буквы, без пробелов. GitHub различает регистр: `Buylo.m4a` и `buylo.m4a` — разные файлы.

## Как выложить на GitHub Pages
1. Создайте репозиторий (Public) на github.com.
2. **Add file → Upload files**: перетащите `index.html`, `.nojekyll` и папки `img`, `sheets`, `plans`, `audio` (сами файлы и папки, не архив).
3. **Commit changes**.
4. **Settings → Pages**: Source — *Deploy from a branch*, ветка `main`, папка `/(root)` → **Save**.
5. Через 1–2 минуты сайт откроется по адресу `https://<логин>.github.io/<имя-репозитория>/`.
