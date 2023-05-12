# Практическая работа 09

## Перебазирование
____
### Задание 0

Склонировать репозиторий
```
$git clone https://github.com/userzamt/megasupersite.git
```
____
### Задание 1

Добавить блок с описанием пиццы и кнопкой "Заказать". Сделать коммит.

```
$git checkout -b dev
...
$ git commit -a -m 'Add Neapolitan pizza'
```

____
### Задание 2

Добавить блок с описанием пиццы без кнопки. Сделать коммит.

```
$ git commit -a -m 'Add pizza al Padellino'
```

____
### Задание 3

```
$git switch master
```
Добавить кнопку "Заказать" для второго блока. Сделать коммит

```
$ git commit -a -m 'Add order button for the second block about another type of pizza'
```

____
### Задание 4
```
$git checkout -b hotfix
```
<Здесь должны были быть много букв, но они ушли>
```
Тут могла быть ваша реклама
```

```
$ git commit -a -m 'Change names in navigation panel'
...
$ git switch -
Switched to branch 'master'

$ git merge hotfix
Updating 0c83d4b..406d4c2
Fast-forward
...
```

----
### Задание 5

```
$ git checkout dev
Switched to branch 'dev'
```
Изменить название в панели навигации и ~~расскомментировать~~ добавить логотип фирмы.

```
$ git commit -a -m 'Change the title, uncomment line of code for adding a logo'
```

----
### Задание 6

Произведите перебазирование ветки *dev* **относительно *master***

```
$ git rebase master
```

----
### Задание 7

<неразборчиво>

```
https://github.com/GnuriaN/format-README
```

----
### Задание 8

Создать репозиторий на любой из хостинг платформ для размещения проектов.

```
https://github.com
```
Залить сайт на удалённый репозиторий.
