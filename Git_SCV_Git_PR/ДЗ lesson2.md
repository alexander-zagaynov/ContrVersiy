# Репозиторий для **pull request**


## Создал свой аккаунт на сайте, 
## сделал свой репозиторий.
## Добавил файлы
## Привязал свой компьютер c VSCode к аккаунту на GIT HUB
## Ниже пример
2023-05-02 17:25:59.998 [info] Уровень ведения журнала: Info
2023-05-02 17:26:00.847 [info] Проверка найденного Git в: "/usr/bin/git"
2023-05-02 17:26:02.332 [info] Используется Git "2.24.3 (Apple Git-128)" из "/usr/bin/git"
2023-05-02 17:26:02.361 [info] GitProtocolHandler.handleUri(vscode://vscode.git/clone?url%3Dhttps%3A%2F%2Fgithub.com%2Falexander-zagaynov%2FSCV_Git_PR%26ref%3Dcf3e2af)
2023-05-02 17:26:02.375 [info] Executing git.clone for https://github.com/alexander-zagaynov/SCV_Git_PR
2023-05-02 17:29:02.579 [info] > git clone https://github.com/alexander-zagaynov/SCV_Git_PR /Users/alexanderzagaynov/Documents/GitHub/My_repository/ ДЗ_ final_Alexander Zagaynov/SCV_Git_PR --progress --branch cf3e2af [2193ms]
2023-05-02 17:29:02.594 [info] Cloning into '/Users/alexanderzagaynov/Documents/GitHub/My_repository/ ДЗ_ final_Alexander Zagaynov/SCV_Git_PR'...
fatal: Remote branch cf3e2af not found in upstream origin

#  Инструкция по работе и обучение по 3-му семинару
____

1. * В своём аккаунте на GitHub создать копию репозитория **"AndreyBulgakov19/SCV_Git_PR"** с помощью кнопки **"Fork"**.
Создал копию репозитория путем, путем скачивания файла в свой репозитория нажатием на символ FORK.
Далее, копируем данные, нажимаем на CREATE FORK

---
2. * Клонировать копию репозитория на локальный компьютер.
Переходим в VSCode, запускаем ТЕРМИНАЛ, вводим команду *git clone <ССЫЛКА С GIT HUB>
далее скачивается файл на наш компьютер.

---
3. * Создать новую ветку.
Создал новую ветку SEMINAR 2, куда разместил Домашнее задание по 2 семинару

---
4. * Добавить файл с инструкцией в новую ветку.
Добавил инструкцию в ветку MAIN по 3 семинару

---
5. * Дополнить инструкцию разделами по работе с удалёнными репозиториями, pull request.
   Cоздание удаленного репозитория
   1. В Правом верхнем углу находим <+> нажимаем, и находим <NEW REPOSOTORY> нажимаем
   2. Создаем название репозитрия <REPOSITORY NOME> (Описание к нему по желанию)
   3. Далее, <CREATE REPOSITORY>
Таким алгоритмом действий, мы создали новый REPOSITORY

____

 ## Дополнитено хотелось бы добавить, как работать с чужими репозиториями

   1. В правом верхнем углу, находим кнопку <FORK>
   2. Нам появиться кнопка <CREATE FORK>, нашимаем, создаем копирование.
   3. Появиться кнопка <>CODE , копируем ссылку.
   4. После того как данные скопировали, переходим на наш ПК, заходим в VSCode, и запускаем TERMINAL
   5. Вводим команду * git clone <ССЫЛКА> прикрепляем ссылку.
  Начнется установка удаленного репозитория на наш компьютер.

---
6. * Зафиксировать изменения (коммиты).
  Фиксация изменений/создание коммитов
## MacBook-Pro-Alexander:Git instructional  alexanderzagaynov$ git reflog
bc21b1d (HEAD -> main) HEAD@{0}: commit: Добавил изменения в 6 пункт
eb577d7 HEAD@{1}: commit: Добавили инструкцию в 5 пункт
b6ad2b3 HEAD@{2}: checkout: moving from seminar2 to main
11f5bfe (seminar2) HEAD@{3}: commit: Дополнение 7,8,9,10,11 пункт


---
7. * Отправить изменения на GitHub.
  ОТПРАВИЛ

---
8. * На сайте GitHub выполнить **Pull request**.
   Сделал

______

 ## Домашнее задание *Контроль версий* 

1. Инициализация репозитория

Создаюм файл в репозитории.
Запускаем командой *git init*
чтобы файл начал отслеживаться в индексе, активируем командой *git add.*
(после этого файл добавлен в индекс и будет отслеживаться)

___

2. Запись изменений в репозиторий

Все изменения фиксируем командом *git commit -m "комментарий"*
Создаем первый коммит (родитель) в нашей основной ветки Master или Main для GitHub

_____

3. Проверяем всегда командой
 *git status*

Которая показывает информацию о текущем состоянии нашего файла.

____

4. Просмотр истории коммитов

Просмотр всех совершенных действий командами
*git log* - список всех наших commit которые были сделаны
*git log --graph* - отображение всех веток и commit которые были сделаны
*git reflog* - список всех коммитов, в столбик
## MacBook-Pro-Alexander:Git instructional  alexanderzagaynov$ git reflog
61cc41c (HEAD -> seminar2) HEAD@{0}: commit: добавил 5 и 6 пункт инструкций
b6ad2b3 (main) HEAD@{1}: checkout: moving from main to seminar2
b6ad2b3 (main) HEAD@{2}: Branch: renamed refs/heads/master to refs/heads/main
b6ad2b3 (main) HEAD@{4}: commit: Делаю коммит скачиного файла для фиксации
01c7990 HEAD@{5}: commit (initial): Домашнее задание 2 семинара

_______

5. Перемещение между сохранениями
Чтобы перейти в другой commit - нужно ввести команду
*git checkout < НОМЕР COMMIT> - хеш, достаточно первые 4-5 цифр
Пример перехода:
##
Создал задания по 2семинару
MacBook-Pro-Alexander:git_ДЗ_Alexander Zagaynov alexanderzagaynov$ git checkout 8b5b7c3
**Note: switching to '8b5b7c3'**.

_____

6. Игнорирование файлов
создаем файл *.gitignore*
Добавляем название фото <Capri.png>
Также можно игнорировать группу файлов  <*.png>
## MacBook-Pro-Alexander:Git instructional  alexanderzagaynov$ git status
On branch seminar2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .DS_Store
        SCV_Git_PR/.gitignore
        SCV_Git_PR/Capri.png


______

7. Создание веток в Git
Создаем ветки командой *git branch <ИМЯ ВЕТКИ>*
## MacBook-Pro-Alexander:Git instructional  alexanderzagaynov$ git branch third
MacBook-Pro-Alexander:Git instructional  alexanderzagaynov$ git branch
  main
* seminar2
  third

_____

8. Удаление ветки
Прежде чем удалить, ветку нужно обязательно слить в основную ветку <MASTER> 
Выйти из этой ветки которую хотим удалить. Только после этого можно сделать чистое удаление.
*git branch -d <ИМЯ ВЕТКИ>* - 
*git branch -D <ИМЯ ВЕТКИ>* - принудительное удаление.
## MacBook-Pro-Alexander:Git instructional  alexanderzagaynov$ git branch -d third
Deleted branch third (was 61cc41c).

______

9. Переход между ветками

*git checkout <ИМЯ ВЕТКИ>*
## * commit 61cc41c0efa234fbcddac5096af7c0aead95e0b6 (HEAD -> seminar2)
| Author: Alexander Zagaynov <alexander.zagaynov@gmail.com>
| Date:   Mon May 1 17:39:20 2023 +0300

______

10. Добавление фото/картинок в репозиторий
Фотографии разместил в своем репозитории на GIT HUB 
Вставил ссылки фотографий.
![Дубай,сказочный город](https://github.com/alexander-zagaynov/Imagine/commit/2f9571a7d7300fd47f76d1eeeb30f6f9cdb68949#commitcomment-111251087)

![Москва,столица России](https://github.com/alexander-zagaynov/Imagine/commit/2f9571a7d7300fd47f76d1eeeb30f6f9cdb68949#commitcomment-111314482)

_________

11. Слияние веток
Прежде чем делать слияние, нужно перейти из данной ветки в Master / Main
после этого можно делать слияние командой
 *git merge <ИМЯ ВЕТКИ>*

 _________

## Завершение домашнего задания по второму семинару



