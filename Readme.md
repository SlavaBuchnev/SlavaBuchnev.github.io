
# Локальный запуск сайта

Для локальной разработки необходимо выполнить следующие команды:

## 1. Установка зависимостей

```bash
sudo gem install bundler
bundle config set --local path '~/.gem'
bundle install
```

## 2. Локальный запуск

```bash
bundle exec jekyll serve
```
После запуска сайт будет доступен по адресу [http://localhost:4000](http://localhost:4000).  
Чтобы остановить сервер, нажмите `Ctrl+C` в терминале.
