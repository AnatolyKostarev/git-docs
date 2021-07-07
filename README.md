#git-docs
1. git init — инициализирует git репозиторий в папке
2. git add — добавляет файл, делает его доступным для комита
3. git commit — комитит изменения, вместе с сообщением
4. git push — заливает на сервер
5. git pull — забирает изменения
6. git remote add origin ... — указать путь к удаленному репозиторию
7. git remote set-url origin ... — изменяет путь удаленного репозитория
8. git status — проверка текущего статуса
9. git log или git log --pretty=oneline — история коммитов (отредактировано)

1. git clone — клонирует репозиторий с гитхаба
2. ls -a — показывает все файлы и папки включая скрытые
3. git branch — показывал все ветки
4. git branch <название_ветки> — создает новую ветку <название_ветки>
5. git branch -d <название_ветки> — удаляет ветку <название_ветки>
6. git switch <название_ветки> — переключается между ветками
7. git checkout <хэш_коммита> <имя_файла> — изменяет текущий файл меняя его до состояния этого файла в коммите с хэшем <хэш_коммита>
8. git merge <имя_ветки> — сливает ветки, в текущую вливается <имя_ветки>
9. git reset <хэш_коммита> — удаляет все коммиты которые были после <хэш_коммита>, но сохраняет изменения в файлах (их можно будет закомитеть)
10. git reset --hard <хэш_коммита> — удаляет все коммиты которые были после <хэш_коммита> и НЕ сохраняет изменения в файлах
12. git restore --staged <имя_файла> — выводит файл <имя_файла> из staged (обратное действие для команды git add)
11. git restore <имя_файла> — отменяет последние незакомиченные действия над файлом <имя_файла> (отредактировано) 
