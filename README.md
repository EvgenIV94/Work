Доброго времени суток :)
Постараюсь объяснить ход моего решения:
Опустим банальности в стиле добавил в файл вводные данные...

В задаче было сказано, что не рекомендуется использовать коллекции. Чтож, обойдемся без них.

1. Чтобы создать новый массив, нам необходимо узнать его будущую длину.
Для этого я создал переменную sum типа int и через цикл for узнал сколько всего элементов длинной менее или равное 3 символам находится в исходном массиве.
Условный оператор if помог в этом.

3. Далее создал новый массив resArr длиной sum с пустыми значениями null и пременную k типа int для счетчика в будущем цикле for.

4. Снова прогнал исходный массив через цикл for с применением того же оператора if, но теперь в случае если длина элемента массива менее или равна 3 символам
   добавляется в новый массив resArr. А для того чтобы у нас не было проблем с счетчиком и была создана переменная k, которая инкрементирует при условии true.

5. Новый массив resArr заполнен, осталось сделать вывод в терминал как показано в примере. Для этого в sout обращаемся к Arrays.toString(resArr).

6. Радуемся решению задачи :)
   



