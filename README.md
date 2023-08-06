### 6 семестр

#### Курсовая работа по предмету ***"Численные методы решения задач математической физики"***

---

**Тема:** Расчет собственных значений стационарных состояний уравнения Шредингера

**Описание:** В данной курсовой работе представлен алгоритм для решения одномерного стационарного
уравнения Шредингера с произвольным потенциалом. Алгоритм основан на методе
Нумерова. Реализация представлена на языке С++.

Метод Нумерова
— численный метод решения обыкновенных дифференциальных уравнений второго
порядка, в которых не фигурирует член первого порядка. Метод является многошаговым
и обладает вторым порядком точности. Локальная погрешность метода имеет
четвертый порядок

Метод является явным, что делает его алгоритмически простым для реализации.
Также, он обладает вторым порядком аппроксимации.
В отличии от методов Рунге—Кутты, вычислять дополнительные значения функции
в промежуточных точках не требуется.

Также в алгоритм был внедрен метод пристрелки, который дает возможность проинтегрировать именно нужное нам уравнение (изначальная функция неизвестна).

В качестве тестовых примеров рассматривались задачи с тривиальным, симметрическим и асимметрическим потенциалами.
