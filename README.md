# Учебный проект №1
## Автор: Соловьева Ольга, студент Яндекс Практикума


Это одностроничный сайт, который был сделан в рамках обучения по професии "Веб разработчик" в [Яндекс Практикуме](https://practicum.yandex.ru/).  Проект направлен на отработку навыков работы с HTML и CSS.

**_Сайт сверстан по методологии БЭМ._**

### В проекте используется:
* флексбокс-верстка
* позиционирование элементов
* элемент iframe (2 видео с YouTube)
* трансформации
* анимации (пример ниже)

Пример анимации:
```css
@keyframes rotation {
  from {
      transform: rotate(0deg);
  }
  to {
      transform: rotate(360deg);
  }
}

.rotation {
  animation-name: rotation;
  animation-duration: 20s;
  animation-timing-function: linear;
  animation-iteration-count: infinite;
}
```
