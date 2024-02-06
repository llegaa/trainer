# Учебный файл README.md

## Инициализация репозитория
1. Создайте новую папку для проекта.
2. Откройте терминал в этой папке и выполните команду:
   ```
   git init
   ```

## Добавление файлов в репозиторий
1. Добавьте файлы в индекс для коммита:
   ```
   git add .
   ```
2. Зафиксируйте изменения в репозитории с комментарием:
   ```
   git commit -m "Описание коммита"
   ```

## Создание коммита

- См. шаги в разделе "Добавление файлов в репозиторий".

## Просмотр истории коммитов
- Просмотреть историю коммитов можно с помощью команды:
  ```
  git log
  ```
## Хеш коммита
- После создания коммита вы получите хеш коммита. Этот хеш - уникальный идентификатор коммита в репозитории.

## Знакомство с GitHub
- Для знакомства с GitHub: [Официальный сайт GitHub](https://github.com/)

## Регистрация на GitHub
1. Перейдите на [сайт GitHub](https://github.com).
2. Нажмите на "Sign up" и заполните регистрационную форму.

## Создание удаленного репозитория
1. Зайдите на GitHub и нажмите "New repository".
2. Укажите имя репозитория, добавьте описание и создайте.

## Генерация SSH ключа
1. Генерируйте SSH ключ командой:
   ```
   ssh-keygen -t rsa -b 4096 -C "ваш_email@example.com"
   ```

## Привязка SSH ключа к GitHub
1. Скопируйте содержимое публичного ключа:
   ```
   cat ~/.ssh/id_rsa.pub
   ```
2. Добавьте ключ на GitHub в настройках аккаунта.

## Связка локального и удаленного репозиториев
1. Добавьте удаленный репозиторий к local репозиторию:
   ```
   git remote add origin git@github.com:yourusername/yourrepository.git
   ```

## Синхронизация локального и удаленного репозитория
- Для отправки изменений на удаленный репозиторий:
  ```
  git push origin main
  ```

## Файл README
Этот файл README.md - ваш главный и информативный файл, где вы описываете свой проект и как с ним работать.
