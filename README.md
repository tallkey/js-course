# JavaScript Course

JavaScript course

# 14.02 lesson 1 Введение

Самое важное: Выражения, функции, объекты.

Практически люб. сущность - объект

Массив - объект, функция - объект, число и строка - объект → (только ведут как объект, primitive)

console.log() - console → Object.

Log → Method (функция объекта)

Точечная запись - доступ к св-вам объект. Здесь - доступ к методу объекта.

() - Вызов функции ( метод console) внутри метода - аргумент.

Любая функция - возвращает значение

Выражение - возвращает значение

/

# 15.02 lesson 2 Переменные

Выражение с побочными действиями - side effects (возвращает значение и выполняет действие)

Переменные - дают повторный доступ к значениям

PascalCase - типы и классы

DB_PASSWORD - значения известны до запуска и не меняются

camelCase - все остальные переменные

//Объявление переменных

let - change variable

const - konstanta

var - global

let a - объявление

let a = 2 - присваивание

let b - undefined (нет значения)

const a = 20 (присваивание и объявление должно быть сразу)

# 21.02 lesson 3 Типы переменных

const a = 22 - number
const b = '22' - string

переменная -> имеет значение -> тип

## Примитивные типы

boolean
number string null undefined symbol

null - присваевается вручную (только)

undefined - достаточно объявить как (let a)

## Ссылочный тип - Object

Ссылка на переменную в другом месте. Переменная не хранит объект, а только ссылку на него.

arr = [1,2,3] - Переменная содержит только ссылку на область в памяти где находится массив (Массив - объект)

let a = {
a: 10,
b: '2'
}

## Динамическая типизация

### Cтатическая и динамическая типизация

String a = 'abc'

int b = 20 //Not js language

b = 'xyz' -> Error

Динамическая: a = 20 // number

a = '20' -> Ok // string

// Объявлять переменные до их использования. Использовать по возможности const

# 23.02 lesson 4 Объекты

Добавление св-тв к объекту -> obj.popular = true (Dot notation)

Меняем только объект! Переменная объекта так и содержит ссылку на объект. (Мутация)

const cpn = 'country'

obj[cpn] = 22 - bracket notation. Можно добавлять переменную в объект с указанием ее значения.

delete obj.country - удаление св-ва объекта
delete obj[cpn]

## Сокращенный формат записи

const name = 'alex'
const age = 22

const obj = {

name,

age

}

# Глобальные объекты lesson 4 25.05
