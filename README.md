# Туториал по работе с Git

## Начало работы

Для начала работы, необходимо инициализировать сам Git

Для его инициализации введите команду 

```
  git init
```

## Добавление файла

Для добавления файла в Git необходимо воспользоваться командой 

```
git add название файла
```

## Получение информации от Git о его текущем состоянии

```
git status 
```
## Создание коммита 
```
git commit -m "message"
```
## Вывод нв экрвн истории коммитов 

```
git log
```
## Клонирование репозитория на ПК
```
git clon <url - адрес репозитория>
```
## Получение изменений и слияние с локальной версией
```
git pull
```
## Отправляет локальную версию на внешний 
```
git push
```
## Сбрасывает линк с предыдущего репозитория 
```
git remout set-url origin <url - адрес репозитория>
```