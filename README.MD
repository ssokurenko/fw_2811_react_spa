# Agenda

## Блок 1. Основи React.
### Введення
- Основні проблеми при розробці SPA
- Декларативний опис і його переваги
- Короткий огляд основних SPA фреймворків
- Основні концепції React
- MVVM(MVC) и Flux арихтектури - огляд і порівняння

### Основи React
- Компонентний підхід - наше “все"
- Віртуальний DOM, як головна ідея
- JSX - синтаксис зрозумілий кожному верстальщику
- Побудова простого компоненту
- Вчимось використовувати Props і State

### We need to go deeper
- Життевий цикл React-компонент
- Іноді доступ до DOM все ж потрібен: keys і refs
- ShouldComponentUpdate, змушуємо додаток “літати"
- Радість Immutable-данних

### Починаємо масштабуватись
- Налаштовуємо Webpack і Babel
- Розносимо компоненти по файлам
- Структуруємо код
- PropTypes - Створюємо reusable компоненти

## Блок 2. SPA
### Проектуємо Store
- Які стори нам потрібні? Збереження данних і стану системи
- Визначаємо спільний функціонал, пишемо Абстрактний стор
- Згадуємо ООП, створюємо більш специфічні стори
- Розробляємо абстрактні моделі

### Action-creators
- Пишимо диспетчер, звязуємо всю систему
- Створюємо прості екшини, налаштовуємо потік данних
- Розбираємось з асинхронними екшинами
- Підключаємо коммунікацію з API
- Проектуємо систему кешування

### Налаштовуємо роутинг
- Огляд проблеми і варіантів
- Прикручуємо React-router
- React-router у зв’язці з Flux
- Налаштовуємо аутентифікацію
- Розбір корисних API React-router

### Опціонально
- Огляд аналогів Facebook Flux(Redux, Reflux та інші)
- Проблеми великих SPA: server-rendering, code-spliting, offline-first
- JSON API