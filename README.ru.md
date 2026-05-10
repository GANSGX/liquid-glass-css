# Liquid Glass CSS

В этом репозитории есть две версии документации:
- English: `README.md`
- Русская: `README.ru.md`

Минималистичный open-source набор liquid glass стилей на чистом CSS с фокусом на темный фон.
В репозитории только базовые стили, а авторский mock-концепт здесь:
[test-motion-design.vercel.app](https://test-motion-design.vercel.app/).

## Зачем

- Чистый glass-эффект без лишнего визуального шума
- На темной теме эффект выглядит заметно лучше
- Переиспользуемые классы для форм, карточек и навигации

## Что внутри

- Только CSS, без JavaScript
- Размытие, контурный блик и глубина через тени
- Минималистичный темный стиль
- Готовые HTML-примеры

## Установка

### Клонирование

```bash
git clone https://github.com/<your-username>/liquid-glass-css.git
cd liquid-glass-css
```

### Подключение

```html
<link rel="stylesheet" href="./css/liquid-glass.css">
```

## Быстрый старт

```html
<section class="glass-form liquid-glass">
  <h1 class="glass-title">Welcome Back</h1>
  <input class="glass-input" placeholder="Email" />
  <button class="glass-button">Sign In</button>
</section>
```

## Классы

- `.liquid-glass` - базовая стеклянная панель
- `.nav-blob` - усиленный стеклянный блок для навигации/активных состояний
- `.glass-form` - обертка для форм и карточек
- `.glass-input` - поле ввода
- `.glass-textarea` - textarea
- `.glass-button` - основная кнопка
- `.glass-button.secondary` - вторичная кнопка

## Примеры

- [examples/form-login.html](./examples/form-login.html)
- [examples/form-contact.html](./examples/form-contact.html)
- [examples/variants.html](./examples/variants.html)
- Референс mock-сайт: [test-motion-design.vercel.app](https://test-motion-design.vercel.app/)

## Скриншоты

Mock hero (glass nav + CTA):

![Mock Hero](./assets/mock-hero.png)

Mock секция протокола:

![Mock Protocol](./assets/mock-protocol.png)

Mock карточки фич:

![Mock Cards](./assets/mock-cards.png)

## Локальный запуск

Открыть пример напрямую:

```bash
open ./examples/form-login.html
```

Или через локальный сервер:

```bash
npx serve .
```

## Лицензия

MIT
