# Руководство пользователя Git
## Локальный репозиторий
* git init - инициализирует локальный репозиторий
* git config --global user.name "Nmae" - указать имя, которым будут подписаны коммиты
* git config --global user.email Email - указать электропочту, которая будет в описании комминтариях.
* git add ./manual.md - добавить файл в локакальный репозиторий
* git commit -m "комемнтарий (описание изменений)"
* git commit -am / git commit -a -m "добавление изменения и комментария (описание изменений)"
* git log - список комментариев (изменений)
* git checkout b9344 - переключиться на выбранный комментрий (просмотреть,сравнить изменения)
* git checkout master  переключиться на коммит, на который указывает master, рабочую директорию вернуть к состоянию на момент этого коммита
* git diff - сравнить рабочую директорию и индекс