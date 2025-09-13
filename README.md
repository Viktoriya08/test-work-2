

# Тестовое задание Гнездилова Виктория

**Верстка** - [https://viktoriya08.github.io/test-work-2/](https://viktoriya08.github.io/test-work-2/)

**Макет** - [https://www.figma.com/design/HvkvEax2RvGdx71a2RS2nz/%D1%82%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D1%8B%D0%B9-%D0%BC%D0%B0%D0%BA%D0%B5%D1%82?node-id=7-509&t=KixeOP7bS4t0iZau-0](https://www.figma.com/design/HvkvEax2RvGdx71a2RS2nz/%D1%82%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D1%8B%D0%B9-%D0%BC%D0%B0%D0%BA%D0%B5%D1%82?node-id=7-509&t=KixeOP7bS4t0iZau-0)

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
