# Руководство по использованию Git 20.01.2023

## Команды Git

git version - Проверка версии git

Для начала работы - git config --global user.name "..." / git config --global user.email "..."

Сделать папку репозиторием - git init 

Добавить файл к отслеживанию - git add

Создать коментарий к сохранению - git commit -m "..."

Журнал сохранений - git log

Выход из журнала сохранений - Q

Hазницу между текущим состоянием файла и тем, что уже сохранено - git diff

Перемещение по журналу сохранений - git ceckout + первые символы commit

Проверка статуса - git status

Возвращение в актуальное состояние - git ceckout master

## Язык разметки Marckdoun

Выделение курсивом - *Курсив*

Выделение полужирным - **Полужирный**

## Списки

1.
2.
3.

*
*
*
***

В Markdown поддерживает два стиля оформления ссылок:

*Гиперссылка, с немедленным указанием адреса (внутритекстовая)

*Гиперссылка, подобная сноске


[название ссылки](https://gist.github.com/Jekins/2bf2d0638163f1294637#-горизонтальные-линии-разделители/ "Необязательная подсказка")

или

[название ссылки] :https://gist.github.com/Jekins/2bf2d0638163f1294637#-горизонтальные-линии-разделители



## Горизонтальные линии (разделители)
***
Первая часть текста
***
Вторая часть текста

---
Третья часть  текста

## Работа с изображением

![joker](joker.jpeg)   

## Второй способ вставить изображение

[img1]: joker.jpeg 

![Djoker][img1]

# Работа с удалёнными рапозитоииями
------------------------------------------------

 Просмотр списка настроенных удалённых репозиториев - git remote

 Скопировать удалённый репозиторий себе на компьютер - git clone + ссылка на удалённый репозиторий. Пример:
git clone https://github.com/schacon/ticgit

Выкачивание данных из удалённого репозитория - git pull + URL

Загрузка данных в удалённый репозиторий - git push