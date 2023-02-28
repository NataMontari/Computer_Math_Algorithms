# Лабораторна робота №1

**Мета:** дослідити запропоновані алгоритми, реалізувати їх та навчитись використовувати дерева у реальному світі.

**Критерії порівняння:** змінюючи кількість вершин та заповненість графу знати мінімальний час виконання.

**Процес дослідження:** спочатку було необхідно навчитись виконувати алгоритм на папері. Згодом реалізувати його у програму, яка працювала б швидко та правильно. Останнім етапом було порівняти алгоритми. Для цього я використовувала функцію генерації графа та обчислення часу з прикріпленого файлу.

### Перше завдання
У цьому задванні потрібно було реалізувати два підпункти. Перше дослідження стосувалось алгоритмів Прима та Краскала. Результи є такмми:

- Прима краще працює з графами, де параметр заповненості графу більший, а Краскала, коли менший.
- Прим може включити у каркас різні ребра, якщо вони однакової ваги. Це не вплине на загальну сумарну вагу графу, але використані ребра будуть відрізнятись. Крускал ж завжди має єдиний розвʼязок.

У другому підпункті потібно було реалізувати один з двох алгоритмів, у нашому випадку Флойда-Воршалла. Результати: середній час роботи нашого алгоритма приблизно однаковий з середнім часом роботи вбудованого, але трошки швидший з більшою кількість вершин. Причиною цієї похибки може бути те, що наш алгоритм реалізовує лише пошук найкоротших відстаней між парами вершин, тим часом як вбудований алгоритм надає доступ до інформацію про попередню вершину, яку треба пройти або відстань до між заданими парами вершин була найкоротшою, що дозволяє користувачеві прослідкувати шлях, який треба пройти для отримання найкоротшої відстані.

### Друге завдання 

У цьому завдання потрібно було реалізувати дерево рішень. Наше дерево ми тестували на двох датасетах: iris, breast cancer. На обох з них точність передбачення була доволі висока.

## Висновок

Ми краще навчились працювати у команді та реащовувати алгоритми необхідні у майбутньому.
