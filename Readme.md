# Инструкция по работе с Git

## Подготовка репозитория
Для создания репозитория используется команда *git init*. Чтобы созадать репозиторий напишите в терминале с открытой папкой для репозитория *git init*.

## Добавление файлов в репозиторий

Для добавления файла к коммиту используется комманда *git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*.

## Создание коммита

Для создания коммита используется команда *git commit*. Чтобы создать новый коммит в терминале с открытой папкой-репозиторием пишем команду *git commit -m "<сообщение к коммиту>"*. Сообщения к коммитам писать ***ОБЯЗАТЕЛЬНО***.

## Состояние файла

Для того, чтобы посмотреть состояние файлов в рабочем каталоге и индексе (что было изменено, но не добавлено в индекс, какие ожидают коммита), используем команду *git status*. Для этого в терминале вводим *git status*.

## Разница между файлами

Для вычесления разницы между любыми файлами используется команда *git diff*. Для этого в терминале необходимо написать *git diff*.

## Отмена изменений

Для отмены изменений импользуется команда *git reset*. Для этого в терминале необходимо написать *git reset*.  

## Удаление ненужной информации из рабочего каталога

Для удаления ненужной информации используем команду *git clean*. Для этого в терминале необходимо написать *git clean*.

## Ветки

Для просмотра колличества веток, а так же для определения своего нахождения используем команду *git branch*. Для этого в терминале необходимо написать *git branch*.

# создание новой ветки

Для создания новой ветки используем команду *git branch*  и название новой ветки. Для этого в терминале пишем *git branch new_branch_name*.

# переключение с ветки

Для переключения веток и выгрузки их содержимого в рабочий каталог используем команду *git checkout*. Для этого в терминале пишем *git checkout* или *git checkout another_branch*. 

# слияние веток

Для слияния двух веток используем команду *git merge*. Для этого в терминале пишем *git merge branch_to_merge_*. 

## История коммитов

Для того, чтобы посмотреть всю историю коммитов используем команду *git log*. Для этого в терминале пишем *git log* - так мы увидим историю коммитов начиная с самого свежего и уходя к истокам проекта.

## Встроенная документация Git

Для отображения встроенной документации Git о других командах используем команду *git help*. 

## Хранение незафиксированных измненией

Для временного сохранения всех незафиксированных изменений с целью очистки рабочего каталога без необходимости фиксировать незавершенную работу в текущей ветке - используем команду *git stash*.

## Удаленный репозиторий 

Для связи с удаленным репозиторием и взятии из него всех изменений, которых пока нет, а так же для сохранения их локально, используем команду *git fetch*.

# "Cкачивание" информации из удаленного репозитория

Для того, чтобы забрать изменения из указанного удаленного репозитория, а затем слить их с текущей веткой, используем команду *git pull*.

# Передача информации в удаленный репозиторий 

Команда *git push* используется для установления связи с удаленным репозиторием, вычесления локальных изменений отсутствующих в нем, и собственно их передачи в вышеупомянутый репозиторий.

# Управление списком удаленных репозиториев

Команда *git remote* позволяет сохранить длинные URL репозиториев в виде понятных коротких строк.

## Архив коммитов

Для упаковки в архив указанных коммитов или всего репозитория используем команду *git archive*.

## Осмотр и сравнивание 

Команда *git show* используется для просмотра информации о метке или коммите.

Команда *git shortlog* служит для подведения итогов команды *git log*. При этой команде листинг всех коммитов будет сгруппирован по автору.

## Откладка

Для поиска коммита в котором впервые проявился баг или проблема используем команду *git bisect*.

Команда *git blame* выводит перед каждой строчкой файла SHA-1 коммита, последний раз менявшего эту строку и автора этого коммита. 

Команда *git grep* используется для поиска любой строки или регулярного выражения в любом из файлов проекта.


















