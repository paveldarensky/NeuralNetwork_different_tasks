"ПРИМЕНЕНИЕ ИСКУССТВЕННЫХ НЕЙРОННЫХ СЕТЕЙ ДЛЯ ОБРАБОТКИ ИНФОРМАЦИИ"

"APPLICATION OF ARTIFICIAL NEURAL NETWORKS FOR INFORMATION PROCESSING"

Ниже приведён список решенных задач.
Везде я использовал искуственную нейронную сетку, написанную мной ранее (в репозитории уже обновленная версия сетки, в некоторых задачах используется старая версия).
Используемая сетка: https://github.com/paveldarensky/MyNeuralNetwork.git

1.	С помощью нейронной сети необходимо перекодировать пропис- ные буквы в строчные (маленькие – в большие). На вход сети пода- ется код «маленькой» буквы, с выхода «снимается» код соответст- вующей «большой» буквы.
2.	Перевод нот из одной тональности в другую называется транспо- нированием. С помощью нейронной сети транспонируйте ноты на один тон выше. На вход сети подается код ноты, с выхода «снима- ется» код ноты на тон выше, октаву учитывать не нужно.
3.	Реализуйте с помощью нейронной сети преобразование градусов в радианы.
4.	Реализуйте с помощью нейронной сети конвертер валют из долла- ров в евро.
5.	Имеется сеть с двумя входами, двумя выходами и некоторым коли- чеством скрытых нейронов. Необходимо настроить сеть таким об- разом, чтобы сигналы со входа менялись на выходе сети местами. То есть, если на вход поступили числа 0,75 и 0,34, то на выходе должны быть числа 0,34 и 0,75.
6.	Научите нейронную сеть осуществлять операцию сложения двух чисел.
7.	С помощью нейронной сети реализуйте определение знака зодиака по числу и месяцу. Знак зодиака определяется по величине сигнала выходного нейрона сети.
8.	Дан набор точек (табл. 6).
Аппроксимируйте данную зависимость полиномом второй степени с помощью нейронной сети. В отчете необходимо представить гра- фик с изображением исходных точек и кривой, полученной с по- мощью нейронной сети.
![изображение](https://github.com/user-attachments/assets/1391a580-4648-4a5c-8dea-d3a51aa8d257)
9.	Реализуйте с помощью нейронной сети операцию умножения трех чисел из диапазона [0, 1].
10.	На основании данных из табл. 7 продолжите числовой ряд с помо- щью механизма предсказания на основе нейронной сети. Ряд может содержать отрицательные числа.
![изображение](https://github.com/user-attachments/assets/03ff15a5-d4b5-47c5-a98d-68c212f5780e)
Правильный ответ: – 0.5, – 0.707, … (синусоида)
11.	Создайте нейронную сеть, которая правильно классифицирует объ- екты, пользуясь данными из табл. 8.
Ответ: Если «Параметр 1» = 1, то 1-й класс, если «Параметр 2» =
«Параметр 3», то 2-й класс, в противном случае – 3-й класс.
![изображение](https://github.com/user-attachments/assets/45bc21ca-6e8d-443e-b02c-54be7a5951ad)
12.	Имеется физическая система с переменными объемом и внутренним давлением. Необходимо создать нейросетевой регулятор, поддержи- вающий постоянную температуру внутри этой системы. На вход ре- гулятора подается изменение давления и объема, на выходе – изме- нение температуры, компенсирующее действие изменяющихся па- раметров. Начальные условия: V0=15 дм3, P0=100 Па, Т0=280o К. Расчет требуемого изменения температуры производится по фор- муле:
![изображение](https://github.com/user-attachments/assets/36fe054e-dc96-4ed7-8933-a6d15b2f08bc)
где ΔV – изменение объема, а ΔP – изменение давления.
13.	Реализуйте с помощью нейронной сети сжатие бинарных изобра- жений размером 16х16 пикселей с коэффициентом сжатия 2.
14.	Научите нейронную сеть распознавать цифры от 0 до 9, заданные в матричном виде 5 × 7 (рис. 18).
![изображение](https://github.com/user-attachments/assets/43b66dc9-7d09-4028-9429-a7b7ee964b06)
