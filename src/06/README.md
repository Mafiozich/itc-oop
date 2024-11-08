# Создание классов, создание объектов

 * Попробуем создать классы Cat и Point2d
 * Добавим им методы с параметрами и возвращаемым результатом

## Синтаксис создания класса
```javascript
class ClassName { // начало объявления класса c именем ClassName
  methodName(a, b) { // Метод methodName с параметрами a и b
    // ...
    return a + b; // Ну например
  }
}
```

## Синтаксис создания объекта из класса

```javascript
const obj = new ClassName(); // Если в конструкторе нет параметров
// Кстати, если параметров нет, то можно и вот так:
const obj = new ClassName;
// Если есть один параметр, передаем его при создании:
const obj = new ClassName("argument");

// Если класс определяет методы, их можно вызывать у объекта
obj.methodName(1, 4);
```