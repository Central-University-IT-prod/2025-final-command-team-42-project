# Front-end

## Запуск

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Нужно создать `.env` в папке frontend с таким содержимым:
```
SERVER_URL="http://127.0.0.1/api"
```
## Заметки

### Роутинг

- **Home Page** - Главная страница. Если пользователь не вошёл - будет лендинг с ссылкой на логин, если вошёл - вишлист с напоминанием о непросмотренных фильмах и горячий топ недели (по оценкам пользователей);
- **Films Page** - Список всех фильмов + фильтры и поисковик;
- **Recommendations Page** - Страница рекомендаций в стиле Тиндера;
- **Bookmarks Page** - Закладки (посмотренные, можно пересмотреть, буду смотреть);
- **User Page** - Максимально простая страница пользователя (выйти из аккаунта, удалить аккаунт, сбросить рекомендации);
- **Login Page** - Регистрация и авторизация.
