# Перестановка

_Прочитайте це іншими мовами:_
[_English_](README.md).

Коли порядок не має значення, це є **Комбінацією**.

Коли порядок **має** значення, це є **Перестановка**.

**Комбінація для сейфу - 472**. Нам дійсно важливий порядок. `724` не працюватиме, так само як 
і `247`. Це має бути точно `4-7-2`.

## Перестановка без повторень

Перестановка, також називається "зміною порядку", є перестановкою елементів у 
впорядкованому списку `S` в однозначну відповідність з самим `S`.

Нижче наведено перестановки рядка `ABC`.

`ABC ACB BAC BCA CBA CAB`

Наприклад, перші три людини на бігових змаганнях: ви не можете бути першим і другим.

**Кількість комбінацій**

```
n * (n-1) * (n -2) * ... * 1 = n!
```

## Перестановки з повторенням

Коли дозволяється повторення, ми маємо перестановки з повторенням. 
Наприклад, блокування нижче: це може бути 333.

![Блокування перестановки](https://www.mathsisfun.com/combinatorics/images/combination-lock.jpg)

**Кількість комбінацій**

```
n * n * n ... (r times) = n^r
```

## Шпаргалка

![Огляд перестановок і комбінацій](./images/overview.png)

![Огляд перестановок](./images/permutations-overview.jpeg)

| | |
| --- | --- |
|![Перестановки з повторенням](./images/permutations-with-repetitions.jpg) | ![Перестановки без повторення](./images/permutations-without-repetitions.jpg) |

*Зроблено за допомогою [okso.app](https://okso.app)*

## Посилання

- [Wikipedia](https://uk.wikipedia.org/wiki/%D0%9F%D0%B5%D1%80%D0%B5%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0)
- [Math Is Fun](https://www.mathsisfun.com/combinatorics/combinations-permutations.html)
- [Permutations/combinations cheat sheets](https://medium.com/@trekhleb/permutations-combinations-algorithms-cheat-sheet-68c14879aba5)
