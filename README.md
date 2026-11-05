![Preact Logo](https://st.timeweb.com/cloud-static/apps-logo/preact.svg)

# Preact на Bun

Пример приложения [Preact](https://preactjs.com/) на [Bun](https://bun.sh/), которое можно развернуть в **Timeweb Cloud Apps**.

:tada: [Демо]

:rocket: [Создать свой Apps](https://timeweb.cloud/my/apps/create)

:books: [Документация Timeweb Cloud Apps](https://timeweb.cloud/docs/apps)

## Параметры деплоя

Выберите рантайм **Bun**, фреймворк **Preact** и тип приложения **frontend**. Для frontend будет опубликована статическая сборка.

| Параметр | Значение |
| --- | --- |
| Фреймворк | Preact |
| Версия Bun | 1.2 |
| Тип приложения | `frontend` |
| Команда сборки | `bun run build` |
| Директория сборки | `dist` |

## <a name="dev"></a>Локальный запуск проекта

```bash
# установка зависимостей
bun install

# запуск в режиме разработки
bun run dev

# сборка для продакшн
bun run build
```
