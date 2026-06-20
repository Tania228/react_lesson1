# React ДЗ: Компоненты магазина

Репозиторий содержит два проекта: функциональный и классовый компоненты карточки товара.

---

## 🚀 Запуск

```bash
# Перейти в папку с заданием
cd task1-functional-store   # или task2-class-store

# Установка зависимостей
yarn install

# Запуск
yarn dev
```

---

## 📝 Кратко о заданиях

**Задание 1. `ShopItemFunc`** — функциональный компонент  
Файл: `src/components/ShopItemFunc.jsx`  
Принимает `item` через пропсы, возвращает карточку товара.

**Задание 2. `ShopItemClass`** — классовый компонент  
Файл: `src/components/ShopItemClass.jsx`  
Наследуется от `React.Component`, использует `this.props` и `render()`.

---

## 📦 Данные (пример)

```javascript
const item = {
  brand: 'Tiger of Sweden',
  title: 'Leonard coat',
  description: 'Minimalistic coat in cotton-blend',
  descriptionFull: "Men's minimalistic overcoat...",
  price: 399,
  currency: '£'
};
```

---

## 🎯 Критерии выполнения

- [ ] Проект на Vite
- [ ] Компонент в `src/components/`
- [ ] Использованы правильные классы (`main-content`, `description`, `price`, `purchase-info`, `divider`, `highlight-window`)
- [ ] Цена в формате `{currency}{price.toFixed(2)}`
- [ ] Есть кнопка "Добавить в корзину"
- [ ] Стили из `App.css`
- [ ] Проект запускается без ошибок

---

## 🤔 Разница подходов

| Функциональный | Классовый |
|----------------|-----------|
| `function` | `class extends Component` |
| `props` в аргументах | `this.props` |
| Нет `render()` | Есть `render()` |

---
