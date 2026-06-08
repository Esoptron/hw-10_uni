# UI Kit для итогового проекта

Домашнее задание 10 по теме «Семантическая разметка и CSS»: базовая дизайн-система для прототипа программного решения.

## Что реализовано

- адаптивная навигация `Navbar` с десктопным горизонтальным меню и мобильным hamburger-меню;
- кнопки `Button`: primary, secondary, disabled, размеры small / medium / large, состояния hover / active / focus;
- формы: `Input` с иконкой и error-состоянием, `Dropdown`, чекбоксы и радиокнопки;
- карточки `Card`: с изображением, без изображения, размеры small / medium / large;
- layout-утилиты на Flexbox и Grid: `container`, `stack`, `grid--cards`;
- отдельная HTML-страница документации с примерами компонентов.

## Структура проекта

```text
.
├── assets/
│   └── card-gradient.svg
├── css/
│   ├── base/
│   │   ├── normalize.css
│   │   └── reset.css
│   ├── components/
│   │   ├── buttons.css
│   │   ├── cards.css
│   │   ├── forms.css
│   │   └── navbar.css
│   ├── layout/
│   │   └── layout.css
│   ├── main.css
│   └── variables.css
├── docs.html
├── index.html
└── README.md
```

## Как открыть

Откройте `index.html` в браузере или запустите локальный сервер:

```bash
python3 -m http.server 8000
```

После запуска доступны страницы:

- главная: <http://localhost:8000/index.html>
- документация: <http://localhost:8000/docs.html>

## Методология

CSS-классы оформлены по БЭМ: блоки (`button`, `form-field`, `dropdown`, `choice`, `card`, `navbar`), элементы (`card__body`, `navbar__link`) и модификаторы (`button--primary`, `card--without-image`, `form-field--error`).
