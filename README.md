Из ES6 поюзал promises, arrow func, set , spread operators.

http://adventofcode.com/day/6 - создал сетку, применил к ней изменения, посчитал лампочки после изменений.
http://adventofcode.com/day/9 - решил 2 способами: 

1 часть - используя "The nearest neighbour (NN) algorithm". https://en.wikipedia.org/wiki/Travelling_salesman_problem - тут можно почитать подробнее. Вкратце: можно не перебирать 40320(8!) уникальных комбинаций. Вместо этого берут, по очереди, каждую из точек, и ищут кратчайший путь к следующей точке(с помощью рекурсии). И так выстраивается 8 маршрутов и они сравниваются.

2 часть - используя перебор по всем возможным комбинациям.

