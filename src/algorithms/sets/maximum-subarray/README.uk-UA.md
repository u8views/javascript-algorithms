# Задача пошуку максимального підмасиву

_Прочитайте це іншими мовами:_
[_English_](README.md).

Задача пошуку максимального підмасиву полягає у знаходженні найбільшого за 
сумою підрядного підмасиву одномірного масиву a[1...n] чисел, де

![Максимальний підмасив](https://wikimedia.org/api/rest_v1/media/math/render/svg/e8960f093107b71b21827e726e2bad8b023779b2)

![Максимальний підмасив](https://www.geeksforgeeks.org/wp-content/uploads/kadane-Algorithm.png)

## Приклад

Зазвичай список містить як позитивні, так і негативні числа, а також 0. 
Для прикладу даний масив з елементами `[−2, 1, −3, 4, −1, 2, 1, −5, 4]`, 
суміжний підмасив з найбільшою сумою буде `[4, −1, 2, 1]`, і дорівнює `6`.

## Рішення

- Прямий перебір `O(n^2)`: [bfMaximumSubarray.js](./bfMaximumSubarray.js)
- Розділити та панувати `O(n^2)`: [dcMaximumSubarraySum.js](./dcMaximumSubarraySum.js)
- Розв'язок за допомогою динамічного програмування `O(n)`: [dpMaximumSubarray.js](./dpMaximumSubarray.js)

## Посилання

- [Wikipedia](https://en.wikipedia.org/wiki/Maximum_subarray_problem)
- [YouTube](https://www.youtube.com/watch?v=ohHWQf1HDfU&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)
- [GeeksForGeeks](https://www.geeksforgeeks.org/largest-sum-contiguous-subarray/)
- [LeetCode](https://leetcode.com/explore/interview/card/top-interview-questions-easy/97/dynamic-programming/566/discuss/1595195/C++Python-7-Simple-Solutions-w-Explanation-or-Brute-Force-+-DP-+-Kadane-+-Divide-and-Conquer)
