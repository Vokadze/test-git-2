1. git status

2. git add [files] подготавливает файлы для записи в специальную область - stage (команда все файлы (.))

3. git commit -m  "comment" (git commit -m "init project")

4. git log (подробная информация)
   commit 45109c3821beef244f5920df41940beba4f65489 (HEAD -> master)
   Author: Сергей Ездаков <esdakov@mail.ru>
   Date:   Sat Nov 12 23:21:08 2022 +0300
   init project (нашей информации еще нет на GitHub)

5. git log --oneline (краткая информация)
   45109c3 (HEAD -> master) init project

6. git push [rep_link] [branch_name]
   git remote -v - [rep_link] - ссылка не репозиторий
   [branch_name] - ветка
   
7. git push origin master
8. git reset --hard - удаляет все сделанные изменения ОСТОРОЖНО!!!

ВЕТКИ

master
develop
feature/main-page
feature/about-company

9. git branch develop - создание ветки

10. Pull requests на GitHub - объединение веток на GitHub.

11. git pull origin master - перемещаем все изменения на Github в master на master в vscode то есть в рабочий код master