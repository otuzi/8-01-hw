# Домашнее задание к занятию 8.01. Git - Качан Олег
---
## Задание 1.

Что нужно сделать:

1. Зарегистрируйте аккаунт на GitHub.
2. Создайте публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».
3. Склонируйте репозиторий, используя https протокол git clone ....
4. Перейдите в каталог с клоном репозитория.
5. Произведите первоначальную настройку Git, указав своё настоящее имя и email: `git config --     global user.name` и `git config --global user.email johndoe@example.com`.
6. Выполните команду `git status` и запомните результат.
7. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
8. Ещё раз выполните `git status` и продолжайте проверять вывод этой команды после каждого         следующего шага.
9. Посмотрите изменения в файле README.md, выполнив команды `git diff` и `git diff --staged`.
10. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой `git       add README.md`.
11. Ещё раз выполните команды `git diff` и `git diff --staged`.
12. Теперь можно сделать коммит `git commit -m 'First commit'`.
13. Сделайте `git push origin master`.
В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

>Мой репозиторий:
<https://github.com/otuzi/8-01-hw/blob/main/README.md> 

<img width="760" alt="Screenshot 2023-06-18 at 15 09 21" src="https://github.com/otuzi/8-01-hw/assets/61628386/aea0b051-5ad4-4a98-b417-c253fd63c9ad">

---
## Задание 2.

### Что нужно сделать:

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
2. Добавьте файл .gitignore в следующий коммит `git add....`
Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.
Сделайте коммит и пуш.
В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.


<img width="826" alt="Screenshot 2023-06-18 at 15 13 27" src="https://github.com/otuzi/8-01-hw/assets/61628386/e3266627-4e25-4401-99e1-a6ac4e93e618">


---
## Задание 3.

### Что нужно сделать:

1. Создайте новую ветку dev и переключитесь на неё.
2. Создайте файл test.sh с произвольным содержимым.
3. Сделайте несколько коммитов и пушей, имитируя активную работу над этим файлом.
4. Сделайте мердж этой ветки в основную. Сначала нужно переключиться на неё, а потом вызывать git merge.
5. Сделайте коммит и пуш.
6. 
В качестве ответа прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.
