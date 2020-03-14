# Домашнее задание ШРИ по теме "Асинхронность"

## Задания

Нужно написать функцию, которая реализует задание вашего варианта. Массивами, математическими операциями и операциями сравнения пользоваться нельзя. Код нужно разместить на отдельной страничке и выложить её на GitHub Pages.

### Вариант 4

- [html страница] (https://dmahno.github.io/shri-async-second-task/)

Посчитать площадь треугольника.

```ts
function(x1: Number, y1: Number, x2: Number, y2: Number, x3: Number, y3: Number,
    cb: (result: Number) => void) {

}
```

## Бонусное задание

Реализовать в отдельном файле собственную версию методов:

- [Promise.any](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Promise/any)
- [Promise.allSettled](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Promise/allSettled)
- [Promise.prototype.finally](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Promise/finally)

```js
Promise._any = // реализация
Promise._allSettled = // реализация
Promise.prototype._finally = // реализация
```
