# C2.B9.5.1 (Пояснение: решение для задания B4.5.1 согласно формулировке задания)


## Задание

Оригинальная формулировка задания приведена [здесь](./TASK.md).


## Решение

1. Создал репозиторий
1. В репозитории создал js-файл с функциями по работе с массивами
1. Опубликовал пакет в npm.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save c2-b9-5-1
```

## Usage

```js
var inArray = require('c2-b9-5-1');
console.log(inArray(['a', 'b', 'c'], 'a'));
//=> true

console.log(inArray(null, 'a'));
//=> false

console.log(inArray(null));
//=> false


arrayLast(['a', 'b', 'c', 'd', 'e', 'f']);
//=> 'f'

arrayLast(['a', 'b', 'c', 'd', 'e', 'f'], 1);
//=> 'f'

arrayLast(['a', 'b', 'c', 'd', 'e', 'f'], 3);
//=> ['d', 'e', 'f']

```