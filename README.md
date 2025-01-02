![](https://iwb.jp/wp-content/uploads/2024/09/javascript-new-date-add-utc-gmt-9-hours.jpg)

Слайд 1: Тема презентации
Заголовок: JavaScript: new Date, new Set, new Map

Введение в объекты Date, Set и Map
Применение и синтаксис
Слайд 2: new Date — Работа с датами и временем
Описание:
new Date() — это встроенный объект для работы с датами и временем в JavaScript. Он позволяет легко получать текущее время, а также выполнять манипуляции с датами.

Основные методы:

new Date() — создаёт объект с текущей датой и временем.
new Date(milliseconds) — создаёт объект с датой, которая указана в миллисекундах от 1 января 1970 года (UNIX-эпоха).
new Date(dateString) — создаёт объект на основе строки, представляющей дату.
new Date(year, month, day, hours, minutes, seconds, milliseconds) — задаёт конкретную дату и время.

let currentDate = new Date();  // Текущее время
let specificDate = new Date(2025, 0, 2); // 2 января 2025 года

Методы объекта Date:

Get methods:

let date = new Date(2005, 9, 20, 12, 12, 12, 1222);
console.log(date.getFullYear());
console.log(date.getMonth());
console.log(date.getDate());
console.log(date.getDay());
console.log(date.getHours());
console.log(date.getMinutes());
console.log(date.getSeconds());
console.log(date.getMilliseconds());
console.log(date.getTime());

Set methods:

let setdate = new Date();
setdate.setFullYear(2005);
setdate.setMonth(9);
setdate.setDate(20);
setdate.setHours(10);
setdate.setMinutes(30);
setdate.setSeconds(25);
setdate.setMilliseconds(2211);
console.log(setdate);

Преимущества Set:

Позволяет хранить только уникальные значения.
Эффективен для поиска и удаления элементов.


Конечно, вот идея для презентации на тему JavaScript: new Date, new Set, и new Map. Я разделю это на три части, чтобы каждая тема была представлена отдельно, а также предложу краткие пункты для слайдов.

Слайд 1: Тема презентации
Заголовок: JavaScript: new Date, new Set, new Map

Введение в объекты Date, Set и Map
Применение и синтаксис
Слайд 2: new Date — Работа с датами и временем
Описание:
new Date() — это встроенный объект для работы с датами и временем в JavaScript. Он позволяет легко получать текущее время, а также выполнять манипуляции с датами.

Основные методы:

new Date() — создаёт объект с текущей датой и временем.
new Date(milliseconds) — создаёт объект с датой, которая указана в миллисекундах от 1 января 1970 года (UNIX-эпоха).
new Date(dateString) — создаёт объект на основе строки, представляющей дату.
new Date(year, month, day, hours, minutes, seconds, milliseconds) — задаёт конкретную дату и время.
Пример:

let currentDate = new Date();  // Текущее время
let specificDate = new Date(2025, 0, 2); // 2 января 2025 года
Методы объекта Date:

.getFullYear() — возвращает полный год.
.getMonth() — возвращает месяц (0-11).
.getDate() — возвращает день месяца.
.getHours(), .getMinutes(), .getSeconds() — время.
Слайд 3: new Set — Множества
Описание:
Set — это коллекция уникальных значений. Она позволяет хранить только уникальные элементы, исключая дубли.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSfkD_v5NvONUPbEcZSCeZfrtIASJZMs9OZA&s)

Основные методы:

new Set() — создаёт новый объект Set.
.add(value) — добавляет значение в множество (если оно ещё не существует).
.has(value) — проверяет, существует ли элемент в множестве.
.delete(value) — удаляет элемент из множества.
.clear() — удаляет все элементы из множества.
Пример:

javascript
Копировать код
let set = new Set();
set.add(1);
set.add(2);
set.add(1);  // Повторяющееся значение не будет добавлено
console.log(set);  // Set { 1, 2 }
Преимущества Set:

Позволяет хранить только уникальные значения.
Эффективен для поиска и удаления элементов.

Слайд 4: new Map — Карты (ассоциативные массивы)
Описание:
Map — это коллекция пар "ключ-значение", где ключи могут быть любого типа (не только строки).

Основные методы:

new Map() — создаёт новый объект Map.
.set(key, value) — добавляет пару ключ-значение в Map.
.get(key) — получает значение по ключу.
.has(key) — проверяет, существует ли ключ в Map.
.delete(key) — удаляет пару ключ-значение.
.clear() — удаляет все элементы.

let map = new Map();
map.set('name', 'John');
map.set(1, 'one');
console.log(map.get('name'));  // John
console.log(map.get(1));       // one


Преимущества Map:

Ключи могут быть любых типов (строки, числа, объекты).
Порядок элементов сохраняется.


Слайд 6: Применение
Когда использовать Date:

Работать с датами и временем (например, отображение текущего времени или планирование событий).
Когда использовать Set:

Хранить уникальные значения (например, коллекция уникальных пользователей или объектов).
Когда использовать Map:

Ассоциировать ключи с конкретными значениями (например, хранение пользовательских данных по уникальным идентификаторам).

Слайд 7: Заключение

new Date() позволяет работать с датами и временем.
new Set() — это структура данных для хранения уникальных значений.
new Map() предоставляет структуру для работы с ассоциативными массивами, где ключи могут быть любыми типами данных.


