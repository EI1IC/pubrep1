# GitCheatSheet
Student assignment to learn git commands

### Задание для студентов

Вам нужно пыполнять задяния и вносить изменения в файл README.md, записывая команду, которую вы выполнили.

**Задание 1**. Виберите (локальную) папку для нового проекта и клонируйте в нее данный репозиторий.
```sh
git записать команду клонирования
$ git clone https://github.com/teacher-fiit/GitCheatSheet.git
Cloning into 'GitCheatSheet'...
remote: Enumerating objects: 13, done.
remote: Counting objects: 100% (13/13), done.
remote: Compressing objects: 100% (12/12), done.
remote: Total 13 (delta 1), reused 6 (delta 0), pack-reused 0
Receiving objects: 100% (13/13), done.
Resolving deltas: 100% (1/1), done.

```
**Задание 2**. Перейдите в созданную (клонированную) папку.

**Задание 3**. Заполните второй столбец таблицы html-файла: после записи каждой ячейки индексируйте измененные файлы и выполняйте коммит.
```sh
git записать команду первого добавления
$ git add .
git записать команду первого коммита
$ git commit -m "Добавили описание к командам в index.html"
[main 4edeb24] Добавили описание к командам в index.html
 1 file changed, 17 insertions(+), 17 deletions(-)

```
**Задание 4**. Дополните файл style.css. Индексируйте измененные файлы и выполните коммит.
```sh
git записать команду добавления
$ git add .
git записать команду коммита
$ git commit -m "Добавил границу таблице в файле style.css"
[main ba08ae7] Добавил границу таблице в файле style.css
 2 files changed, 15 insertions(+), 4 deletions(-)

```
**Задание 5**. Создайте пустой (без файлов) публичный удаленный репозиторий в своем аккаунте на GitHub. 
**Задание 6**. Отправьте изменения на удаленный репозиторий. Если будет необходимость, настройте подключения к удаленному репозиторию.
```sh
git записать команду подключения к удаленному репозиторию, если это было необходимо
$ git remote add pubrep1 https://github.com/EI1IC/pubrep1.git

git записать команду отправки изменений
$ git push pubrep1 main
Enumerating objects: 20, done.
Counting objects: 100% (20/20), done.
Delta compression using up to 4 threads
Compressing objects: 100% (18/18), done.
Writing objects: 100% (20/20), 5.56 KiB | 2.78 MiB/s, done.
Total 20 (delta 4), reused 11 (delta 1), pack-reused 0
remote: Resolving deltas: 100% (4/4), done.
To https://github.com/EI1IC/pubrep1.git
 * [new branch]      main -> main

```
