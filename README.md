# LR6
Лабораторная работа №6

Создав аккаунт на сайте GitHub и сделав копию, и установив git. Создаем папоку на рабочем столе или в другом удобном месте. В локальном репозитории мы клонируем то что с сайта вволя команду : 
**git clone https://github.com/Kurtyanik/LR6/**
После того как все скопируется вводим команду чтобы войти и начать работать: **sd LR6**
После того как вошли мы вводим имя пользователя, группу и  ФИО и емаил (рис(1)). Там и команды для этого. 
Комадой **git log** мы узнаем историю ветки в которой мы находимся для того чтобы поменять ветку вводим **git branch branch1** так мы переходим на другую ветку и там тоже проверяем историю последних изменений (рисунок 2 и 3).
___
По заданию мы делаем слияние в ветку master командой **git merge branch1** и видим что у нас конфликт(рис 4)
___
Пишем **git status** чтобы узнать где конфликт, в этом файле который показывается мы должны сделать изменения которые нас устраивают сохранить и сделать коммит, для изменения файла пишем **nano (тут название файла)** там изменяем на то что нас устраивает, сохраняем пишем коммит и сохраняем и конфликт решен.(рисунок 5 и 6)
___
После этого надо удалить ветку branch1 делаем это командой **git branch -d branch1** и видим что у нас она удалилась(рисунок 7)
____
После этого делаем изменения в файлах на выбор и после этого добовляем их и пишим к ним коммиты для это после изменения пишем **git add (название файла) и после него git commit и собственно пишем коммит**(рисунок 9 и 10) потом нам надо откатить коммит а это собственно (рисунок 11) пишем **git revert HEAD --no-edit** 
___
Создаем ветку для отчета **git branch otchet** перейти на другую ветку надо **git checkout otchet** рисунок(8)
___
История операций (рисунок 12) 
![ccc](1.png)
