

# Тестовое задание Гнездилова Виктория

**Верстка** - [https://viktoriya08.github.io/test-work-2/](https://viktoriya08.github.io/test-work-2/)

**Макет** - [https://www.figma.com/design/o0mJkLUbaM0pdeMQIZ3gdj/Test-Task---Solar?node-id=0-1&p=f&t=bj4vW703AczRmjm0-0](https://www.figma.com/design/o0mJkLUbaM0pdeMQIZ3gdj/Test-Task---Solar?node-id=0-1&p=f&t=bj4vW703AczRmjm0-0)

## Начало работы

Установка npm зависимостей

### Требования
- `node-version: 18.x`
- `yarn` – используем как основной пакетный менеджер

### Установка
- `yarn` – установка всех проектных зависимостей
- `yarn start` – запуск локального сервера в `dev-моде`
- `yarn run build` или `yarn build` – компиляция миницированных файлов, без запуска сервера.

### Скрипты
- `yarn run lint:scss` – линтинг SCSS
- `yarn run lint:ts` – линтинг JS
- `yarn run lint:pug` – линтинг PUG
- `yarn run test` – проверить всё
- `yarn run vite` – старт дев-сервера, но без дополнительного отслеживания изменений в картинках и иконках
- `yarn run vite:build` – полная сборка, подготовка `production-версии` проекта
- `yarn run vite:preview`: – превью `production-версии` проекта (рекомендуется запускать после выполнения команды `yarn run vite:preview`)
