# Памятка Git = GitHub

## Проверка на .git

`$ ls -la`

## Инициализация git

`$ git init`

## В случае ошибки

`rm -rf .git/`

## Индексация файлов перед коммитом

`$ git add.`

## Сохраняем изменения

`$ git commit -m "Commit description"`

## Посмотреть историю коммитов

`$ git log`

## Проверить чье

`$ git config --list | grep user`

## Проверить наличие удаленного репозитория

`$ git remote show origin`

## Можно удалить

`$ git remote rm origin`

## Добавить удаленный репозиторий

`$ git remote add origin https://github.com/ez2say/position.git`

## Отправляем данные на гитхаб

`$ git push origin main`