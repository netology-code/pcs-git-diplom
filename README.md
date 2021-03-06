# Курсовая работа по итогам модуля «GIT - система контроля версий»

Курсовая работа необходима для проверки практических навыков, полученных в ходе прохождения курса
по GIT.

Мы создадим репозиторий с вашим резюме (выдуманным или реальным). Позже вы сможете дополнять этот
репозиторий ссылками на свои работы и новыми навыками.

## Задание

1. Создайте локальный репозиторий на компьютере (название может быть любым).
1. Создайте в локальном репозитории файл `README.md`.
1. В файле должны быть:
    - заголовок с вашим именем;
    - абзац текста о вас;
    - список навыков (нумерованный или маркированный список).
1. В папке с локальным репозиторием создайте подпапку `img/`. 
1. В подпапку `img/` положите фотографию (можно вашу, можно любую другую из интернета).
1. В файле `README.md` разместите картинку из подпапки `img/`.
1. Создайте в локальном репозитории файл `.gitignore` и добавьте в него правила для игнорирования системных файлов, чтобы они не
   попали в удалённый репозиторий в проект.
1. Создайте удалённый репозиторий на GitHub.
1. Свяжите локальный репозиторий с удалённым.
1. Закоммитьте изменения, отправьте коммит в удалённый репозиторий.
1. Убедитесь, что в удалённом репозитории отображаются все нужные файлы.
1. Создайте в удалённом репозитории два ишью (issue) с задачами на улучшение вашего резюме. Например, «добавить
   ссылки на проекты» или «добавить список волонтёрских активностей».

На проверку пришлите ссылку на удалённый репозиторий.

## Итог

Итогом курсовой работы должна быть ссылка на репозиторий на сайте GitHub. В репозитории должны
быть файлы:

- `README.md`;
- `.gitignore`;
- подпапка `img/` с одной картинкой.

Также в репозитории должно быть два ишью с любым текстом.

---

## Что будет считаться ошибкой:

1. Любая ссылка, отличающаяся от прямой ссылки на репозиторий на сайте GitHub.
1. В репозитории нет файла `README.md`.
1. Файл `README.md` пустой или не содержит нужных элементов: заголовка, текста, списка, картинки.
1. В репозитории нет подпапки `img/` или в этой подпапке нет файла с картинкой.
1. В репозитории нет файла `.gitignore`, он неверно назван или пустой.
1. В репозитории нет двух ишью. 

---

## Подсказки

Ниже размещены подсказки. Советуем обращаться к ним только в случае возникновения трудностей.

<details>
  <summary>Подсказки</summary>
  
  1. Для размещения картинки в `README.md` используйте конструкцию `![Название картинки](img/имя-картинки)`.
  1. Системными считаются файлы `.DS_Store`, `Thumbs.db`, папка `.idea`.
  1. Для связывания локального и удалённого репозиториев используйте команду `git remote add origin ссылка-на-удалённый-репозиторий`.
  1. Обязательно проверьте, что файлы отображаются правильно в удалённом репозитории, в них видно всё содержимое.
  1. Коммитов может быть больше, если вам потребовалось вносить изменения. Это не будет считаться ошибкой.
</details>
