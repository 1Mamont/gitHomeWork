# Инструкция Git
(для выделения большими буквами перед текстом ставим # )
## Что такое git ?
(для выделение меньшим размером ставим две ## )



Git - консольная утилита для отслеживания истории изменений файлов. Используется для кода и других файлов, например, картинок. Позволяет откатывать версии, сравнивать и сливать изменения в репозиторий. Репозиторий - хранилище кода и его изменений. Git работает локально, хранит репозитории в папках на диске.


## *Основные Команды*

* ###  git init

 Создать репозиторий Инициализирует пустой репозиторий.

* ### git add

Команда git add сохраняет и добавляет содержимое рабочей директории в индекс (staging area) для последующего коммита. По умолчанию git commit использует лишь этот индекс, так что вы можете использовать git add для сборки слепка вашего следующего коммита.
* ### git status
Команда git status показывает состояния файлов в рабочей директории и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе. Вдобавок к этому выводятся подсказки о том, как изменить состояние файлов.
* ### git diff
Команда git diff используется для вычисления разницы между любыми двумя Git деревьями. Это может быть разница между вашей рабочей директорией и индексом (собственно git diff), разница между индексом и последним коммитом (git diff --staged), или между любыми двумя коммитами (git diff master branchB).
* ### git commit
Команда git commit берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок.
* ### git branch
Команда git branch — это своего рода “менеджер веток”. Она умеет перечислять ваши ветки, создавать новые, удалять и переименовывать их.
* ### git checkout
Команда git checkout используется для переключения веток и выгрузки их содержимого в рабочую директорию.
* ### git log
Команда git log используется для просмотра истории коммитов, начиная с самого свежего и уходя к истокам проекта. По умолчанию, она показывает лишь историю текущей ветки, но может быть настроена на вывод истории других, даже нескольких сразу, веток. Также её можно использовать для просмотра различий между ветками на уровне коммитов.
* ### Картинка

    Чтобы вставить изображение в текст нужно написать: 
    ![текст если картинка не закрузилась](hj.jpg)  имя файла из которого достать
    ![This](12.png)

    * ## Ссылки 

    Ссылки вставлять так [Gb](https://gb.ru)

     * Использовать:  [] - в них [__название ссылки__] 
    
        и () - в них (*адрес ссылки*)


* ## git clone 

Данная команда клонирует полностью проект.

* ## git push 
git push origin master - отправить в удалённый репозиторий (с сокр. именем origin) данные своей ветки master

* ## Конфликт 

![Есть три варианта решения=) ](Конфликт.png)