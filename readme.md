## Итструкция по GIT

## Подготовка репозитория
Для создания репозитория используется комманада *git init*. Чтобы создать репозторий напишите в терминале с открытой папкой для репозитория *git init*

## Добавление файлов в репозиторий
Чтобы добавить файлы к коммиту испоьзуется фоманда *git add*
для этого в папке с репозиторием необходимо написать *git add /название файла/* 
Чтобы добавить все файлы #git add ./#
 

## Создание commit
Для создания коммита используется комманада git commit. Чтобы создать новый коммит в терминале с открытой папкой репозитория пишем комманду *git commit -m <сообщение к коммиту>* Сообения к коммитам писать обязательно.  Фактически комманда *git commit* моздает новую версию файла. Чтобы добавить и сохранить файл, пользуемся 
*git commi -am*


## Просмотр изменения данных. 
Чтобы посмотреть все изменения, существует комманда *git log* и ее более короткая версия *git log --oneline* Для просмотра несохраненных изменений, пользуемся *git diff*
Для отката файла к более старой версии пишем *git chtckout <указание номера необходимого коммита>*

## Отдельные ветки
Существует возможность создавать ответвления от основной ветки. Чтобы определить, в какой ветке находишься, пиши *git branch* Для создания новой ветки необходимо ввести *git branch <название ветки>*. Для удаления ветки - *git branch -d <название ветки>*. Чтобы графиически вывести на экран ветвление версий файла, существует комманда 
*git log --graph*. Работа в отдельной ветке ведется для того, чтобы тестировать внесенные изменения. Если все изменения в дополнительной ветке устраивают, ветки можно слить коммандой #git merge# При их слиянии возможны возникновения конфликтов, которые решаются в ручном режиме, с выбором вариантов слияния. #git merge aborte# -отменить слияние веток. 
. *git reflog* - показывает все перемещения между ветками
. *git checkout -b <имя ветки> * - комманда создания и перемещения в новую ветку   
 
