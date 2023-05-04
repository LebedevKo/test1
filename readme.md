# команды для git

**git init** - инициализируем наш репозиторий

**git  add 'namefile'** либо **git  add .** - добавить файлу версионность (во втором случае всем файлам в этой папке).

**git status** - общий статус гита

**git commit -m 'message'** - фиксирование изменений с комментарием

**git commit -am 'messege'** - добавление и фиксация изменений с коментарием (без команды add)

**git log** - посмотреть журнал изменений

**git log --graph** показывает журнал изменений в виде древа

**git checkout ...** - перейти в то изменение, которое нужно было (на тот коммит, который нужен). вместо ... пишем первые символы (или название актуальной ветки (main or master) и видем, что было на том этапе)

**git chechout -b name_branch** - создает и сразу переходит на новую ветку

 **git diff** - показывает разницу между сохраненным и актуальным текстом.

 **git branch** показывает на какой ветке мы находимся. 
 **git branch 'name'** создает новую ветку

 **git branch -d 'name'** удаляет ненужную ветку

 **git merge** слияние веток

 если возникает конфликт, то над кофликтом будут варианты решения этого конфликта: оставить текущую (в той, куда перелил из другой вариант), оставить новую (ту, что влили), оставить оба варианта и сравнить.

 для игнорирования файлов создается файл ".gitignore" в папке. в этом файле gitignor пишем тот файл, который будем игнорировать. далее добавляем его в отслеживаемые (add), сохраняем (commitим его)

**git rebase name_branch** слияние веток таким образом, что с этой ветки (где мы сейчас) на *namebranch* все коммиты будут последовательны

добавили строку, чтоб проверить как работет гитхаб

