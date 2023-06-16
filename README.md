Использование NumPy и MatPlotLib
Библиотека NumPy имеет очень быстрые алгоритмы работы с массивами. 
Убедитесь в этом, сравнив время выполнения операции поэлементного перемножения стандартных списков и массивов NumPy (numpy.array). 

Задание

1. Для каждого случая создайте два массива в 1 миллион элементов, заполненных случайными значениями чисел, и перемножьте их (в NumPy для этого служит функция numpy.multiply()). 
Чтобы замерить время выполнения, воспользуйтесь функцией perf_counter из библиотеки time.

2. Подгрузите приложенныq файл data1.csv.Выделите данные из столбцов, указанных в вашем варианте и сгенерируйте из них график. Необходимо вывести два графика, наложенные друг на друга, а также график корреляции. Каждый график должен содержать заголовок и подписи по осям.

3. Постройте трёхмерный график согласно формуле x∈(-п;п); y=x; z=tg(x). Используйте Axes3d. В интервалах потребуется np.linspace().