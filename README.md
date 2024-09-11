# Практика по курсу "Введение в компьютерное зрение"

## Требования к структуре директорий

`FamiliaIO`
|
|--- `lab1`
|--- `lab2`
|--- `lab3`

## Практическая работа №1. Обработка изображений с использованием библиотеки OpenCV

Порядок выдачи: после лекции 2.

**Задача.** Разработать библиотеку фильтров с помощью базовых операций
над изображениями (матрицами) в OpenCV:
-	Функция перевода изображения в оттенки серого.
-	Функция изменения разрешения изображения.
-	Функция применения фотоэффекта сепии к изображению.
-	Функция применения фотоэффекта виньетки к изображению.
-	Функция пикселизации заданной прямоугольной области изображения.

**Требования:**
-	Язык разработки – Python, среда разработки – Jupiter Notebook.
-	При реализации функций можно использовать только базовые операции над изображением,
  нельзя использовать высокоуровневые функции обработки изображений.
-	Notebook должен содержать набор блоков кода, в каждом из которых реализуется одна функция
  фильтрации из поставленной задачи, и демонстрируется ее использование. Использование включает
 	загрузку исходного изображения, применение функции фильтрации, отображение исходного и отфильтрованного изображения.
-	Перед каждым блоком кода в Notebook должно быть описание алгоритма реализации фильтра.
-	В шапке Notebook-файла необходимо указать название практической работы:
  "Практическая работа №1. Обработка изображений с использованием библиотеки OpenCV".
-	Результаты выполнения практической работы должны быть выложены в репозиторий курса. При этом
  директория практической работы содержит Notebook (файл в формате .ipynb), сконвертированный
 	Notebook в html-формат.

## Практическая работа №2. Классификация изображений с использованием библиотеки OpenCV.

Порядок выдачи: после лекции 3.

**Задача.** Разработать два приложения для классификации изображений набора данных XXX.
-	Первое приложение должно реализовывать алгоритм «мешок слов».
-	Второе приложение должно использовать глубокие модели для классификации изображений.
Каждое приложение должно состоять из двух основных частей:
-	Реализация алгоритма.
-	Вычисление показателя качества решения задачи классификации на тестовой выборке.

**Требования:**
-	Язык разработки – Python, среда разработки – Jupiter Notebook.
-	Перед каждым блоком кода в Notebook должно быть описание реализованного алгоритма.
-	В шапке Notebook-файла необходимо указать название практической работы:
  "Практическая работа №2. Классификация изображений с использованием библиотеки OpenCV".
-	Результаты выполнения практической работы должны быть выложены в репозиторий курса. При этом
  директория практической работы содержит Notebook (один файл в формате .ipynb на каждое приложение),
 	сконвертированный Notebook в html-формат.

## Практическая работа №3. Детектирование объектов на изображениях с использованием библиотеки OpenCV.

Порядок выдачи: после лекции 4 (постобработка после лекции 6).

**Задача.** Разработать приложение для детектирования объектов с использованием обученной нейронной сети XXX.

**Требования:**
- Язык разработки – Python, среда разработки – Jupiter Notebook.
-	При реализации необходимо использовать модуль DNN библиотеки OpenCV.
-	Приложение должно содержать функцию детектирования объектов, а также демонстрацию его использования.
  Демо загружает изображение, вызывает функцию детектирования объектов, отображает изображение, на котором
 	отрисованы прямоугольниками разных цветов объекты разных классов (цвет соответствует классу объектов),
 	и выводит статистику (число объектов каждого класса). При отображении в левом верхнем углу каждого
 	прямоугольника необходимо написать название класса и достоверность наличия объекта в этом прямоугольнике
 	(точность отображения вещественного числа – три знака после запятой).
-	В шапке Notebook-файла необходимо указать название практической работы: "Практическая работа №3.
  Детектирование объектов на изображениях с использованием библиотеки OpenCV".
-	Результаты выполнения практической работы должны быть выложены в репозиторий курса. При этом директория
  практической работы содержит Notebook (файл в формате .ipynb), сконвертированный Notebook в html-формат.
