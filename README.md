## Проект был создан с помощью CRA

### Запуск проекта:

- git clone git@github.com:<название репозитория>
- npm install
- npm start

### Сохранение настроек:

- Стоит таймаут на 2 секунды, чтобы проверить блокировку кнопок.
- При первом сохранении всегда появляется ошибка (чтобы протестиовать ее появление). При втором сохранение срабатывает.

### Сброс настроек:

Чтобы вернуться на стартовую страницу, надо сбросить настройки в sessionStorage и обновить страницу.  
Сбросить настройки можно командой `sessionStorage.removeItem('settings')` в консоли.
Также можно просто открыть сайт в режиме инкогнито.
