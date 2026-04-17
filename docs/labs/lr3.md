# Лабораторная работа 3

## Деплой на GitHub Pages с использованием Actions

Платформа SourceCraft  
## 1. Создан репозиторий

Выполнен вход на sourcecraft.dev.

Создана публичная организация.

Создан пустой репозиторий.  

## 2. Создан токен

Создан токен с правами Maintainer.

Токен сохранен для дальнейшего использования в URL.  

## 3. SourceCraft добавлен в remote

В локальном репозитории выполнена команда:

```bash
git remote add sourcecraft https://poq1e:<токен>@git.sourcecraft.dev/poq1e/static-site.git
```
Проверено наличие remote: 
```bash
git remote -v
```

Платформа GitHub
## 1. Написан CI файл

В локальном репозитории создан файл ```.github/workflows/mkdocs.yml```

## 2. Создали Action 

В корне проекта создана директория ```.github/workflows/```

##  3. Внутри создали workflow

Создан файл ```.github/workflows/deploy.yml```

## 4. Указали image

в workflow указан раннер ```runs-on ubutsu-latest```

Результат:
