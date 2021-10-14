# Инструкция по работе с git и GitHub

## Что такое система контроля версий?

## Что такое git?

Git - это одна из реализаций распределенных систем контроля версий. Git позволяет управлять нашими изменениями, создавать фиксации, ветки, а также сливать их. 

## Подготовка репозитория

Репозиторий - это хранилище файлов, поддерживающее версионность. 
Создать репозиторий можно с помощью применения в папке команды *git init*.

## Создание сохранений

Мы можем создавать "сохранения" наших версий в файлах, такие "сохранения" называются фиксациями или коммитами. 
Используем команды *git commit* и **ОБЯЗАТЕЛЬНО** использовать флаг "-m", после чего в кавычках написать сообщение.   

## Журнал изменений

## Перемещение между сохранениями

Перемещаться между нашими сохранениями можно с помощью команды *git checkout*. Для этого достаточно применить коанду *git checkout <номер коммита>*. 
Можно отменить изменения с помощью команд *git revert* и *git reset*.
*git revert <номер коммита>* отменит изменения до указанной версии и создаст новый коммит.
*git reset --hard <номер коммита>* отменит изменения до указанного коммита и сотрет всю историю изнений после этого коммита.

## Ветки в git

Новая ветка создается с помощью команды *git branch <название ветки>*.

## Слияние веток и решение конфликтов

## Удаление веток

## Скачивание удаленного репозитория



