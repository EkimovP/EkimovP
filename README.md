<h1 align="center">🤝 Pavel / Павел </h1>
<h3 align="center">Languages and tools / Языки и инструменты</h3>

<div align="center">
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" height=24>
    <img src="https://img.shields.io/badge/Django-black?style=for-the-badge&logo=django&logoColor=white" height=24>
    <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black" height=24>
    <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" height=24>
    <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" height=24>
    <img src="https://img.shields.io/badge/Jupyter-orange?style=for-the-badge&logo=Jupyter&logoColor=white" height=24>
    <img src="https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=Qt&logoColor=white" height=24>
    <img src="https://img.shields.io/badge/OpenCV-red?style=for-the-badge&logo=opencv&logoColor=%230000FF&color=%23228B22" height=24>
    <br><br>
    <img src="https://img.shields.io/badge/javascript-%23000000?style=for-the-badge&logo=javascript&logoColor=%23000000&color=%23FFFF00" height=24>
    <img src="https://img.shields.io/badge/typescript-%233178C6?style=for-the-badge&logo=typescript&logoColor=white" height=24>
    <img src="https://img.shields.io/badge/html-%23FFE4B5?style=for-the-badge&logo=html5" height=24>
    <img src="https://img.shields.io/badge/CSS-%231E90FF?style=for-the-badge&logo=css3" height=24>
    <img src="https://img.shields.io/badge/bootstrap-%236A5ACD?style=for-the-badge&logo=bootstrap&logoColor=white" height=24>
    <br><br>
    <img src="https://img.shields.io/badge/Docker-%23B0E0E6?style=for-the-badge&logo=docker&logoColor=%230000FF" height=24>
    <img src="https://img.shields.io/badge/Postman-orange?style=for-the-badge&logo=postman&logoColor=white" height=24>
    <br><br>
    <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" height=24>
    <img src="https://img.shields.io/badge/-opengl-5586A4?style=for-the-badge&logo=opengl&logoColor=white" height=24>
    <img src="https://img.shields.io/badge/-MFC-090909?style=for-the-badge&logo=C%2b%2b&logoColor=6296CC" height=24>
    <img src="https://img.shields.io/badge/-Gdi+-090909?style=for-the-badge" height=24>
</div>

<!---------------------------------------------------------------------------------->
<h2 align="center"> Содержание / Проекты  </h2>
<!---------------------------------------------------------------------------------->

- [ Python ](https://github.com/EkimovP#-проекты-на-языке-python-)
- [ Дипломная работа ](https://github.com/EkimovP#-дипломная-работа-)
- [ Frontend-разработка ](https://github.com/EkimovP#-frontend-разработка-)
- [ C++ ](https://github.com/EkimovP#-проекты-на-языке-с-)

<!---------------------------------------------------------------------------------->
<h2 align="center"> Проекты на языке Python </h2> 
<!---------------------------------------------------------------------------------->

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" height=28>
    <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black" height=28>
    <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=Qt&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/OpenCV-red?style=for-the-badge&logo=opencv&logoColor=%230000FF&color=%23228B22" height=28>
</div>

### [Восстановление изображения](https://github.com/EkimovP/Image_filtering)

<img src="https://github.com/EkimovP/EkimovP/assets/125445428/4f55bd44-bed0-4cb5-b8d9-8512c903f424" style="margin-left: 20px" align="right" width=500>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;В программе можно изобразить гауссовы купола, задав их параметры, или загрузить изображение. Затем можно зашумить
исходные данные. Затем строится спектр с помощью метода быстрого преобразования Фурье (БПФ), 
удаляются значения с малой энергией, и происходит процесс восстановления.
<br> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Рассчитывается параметр восстановления, который позволяет оценить работу метода и сравнить исходное и 
восстановленное изображения.

***Алгоритм программы:***

1. **Ввод данных:** генерация гауссовых куполов или загрузка изображения. Перевод в оттенки серого. 
Так как используется БПФ, то в программе предусмотренно доведение до степени двойки: 
интерполяция, дополнение нулями.
2. **Добавление шума.** 
3. **Построение спектра.**
4. **Отображение модуля спектра.**
5. **Нахождение области с заданной энергией.** За ее пределами отсчеты зануляются.
6. **Восстановление изображения с помощью метода обратного фурье преобразования.**
7. **Расчет параметра восстановления.**
<!-------------------------------------------------------------------------------------------------------------------->

<hr>

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" height=28>
    <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black" height=28>
    <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=Qt&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/OpenCV-red?style=for-the-badge&logo=opencv&logoColor=%230000FF&color=%23228B22" height=28>
</div>

### [Восстановление сигнала из свертки](https://github.com/EkimovP/Signal_recovery)

<img src="https://github.com/EkimovP/Signal_recovery/assets/125445428/237d15d6-f356-44f4-bded-58ebc4ced11d" style="margin-left: 20px" align="right" width=500>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Данный проект предназначен для исследования итерационного алгоритма восстановления.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;В программе можно изобразить гауссовы купола, задав их параметры, или загрузить изображение.
После чего необходимо построить аппаратную функцию (ядро). 
Затем строится спектр исходного изображения и аппаратной функции с помощью метода 
быстрого преобразования Фурье (БПФ) и происходит свертка сигнала и фильтра, как процесс перемножения их
спектров. Затем можно добавить шум к свертке. После чего идет процесс восстановления.
<br> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Рассчитывается параметр восстановления, который позволяет оценить работу метода и сравнить исходное и 
восстановленное изображения.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Проводится исследование зависимости параметра восстановления от заданного диапазона шума.

***Алгоритм программы:***

1. **Ввод данных:** генерация гауссовых куполов или загрузка изображения. 
Так как используется БПФ, то необходимо брать исходное изображение *степени двойки*.
2. **Построение аппаратной функции (ядра).** 
3. **Построение спектров исходного изображения и аппаратной функции.**
4. **Свертка исходного изображения с аппаратной функцией.**
5. **Добавление шума к свертке.**
6. **Восстановление изображения с помощью итерационного алгоритма.**
7. **Расчет параметра восстановления.**
8. **Исследование зависимости параметра восстановления от шума.**

**Подпроект:** [Восстановление изображения из свертки](https://github.com/EkimovP/Image_recovery).
<!-------------------------------------------------------------------------------------------------------------------->

<hr>

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" height=28>
    <img src="https://img.shields.io/badge/Django-black?style=for-the-badge&logo=django&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/Docker-%23B0E0E6?style=for-the-badge&logo=docker&logoColor=%230000FF" height=28>
    <img src="https://img.shields.io/badge/html-%23FFE4B5?style=for-the-badge&logo=html5" height=28>
    <img src="https://img.shields.io/badge/CSS-%231E90FF?style=for-the-badge&logo=css3" height=28>
    <img src="https://img.shields.io/badge/bootstrap-%236A5ACD?style=for-the-badge&logo=bootstrap&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/javascript-%23000000?style=for-the-badge&logo=javascript&logoColor=%23000000&color=%23FFFF00" height=28>
</div>

### [Food_blog](https://github.com/EkimovP/Food_blog)

<img src="https://github.com/user-attachments/assets/af337f6f-00cc-4f31-861f-4382d1c9c8b9" style="margin-left: 20px" align="right" width=500>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Приложение предоставляет платформу на основе фреймворка Django для управления и публикации постов. 
Пользователи могут добавлять и редактировать записи, фильтровать их по категориям, а также 
взаимодействовать через обратную связь.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Проект поддерживает аутентификацию пользователей, интерфейс с динамическим контентом и управление доступом. 
Он включает базовую структуру для работы с постами, категориями и шаблонами. Данное приложение обеспечивает работу 
с базой данных SQLite (по умолчанию) с возможностью переключения на другие базы данных (PostgreSQL, MySQL).
<br> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;В проекте использовался Django Debug Toolbar для отладки данного веб-приложения. Было реализовано кэширование 
для оптимизации работы сайта и снижения нагрузки на сервер.
<!-------------------------------------------------------------------------------------------------------------------->

<hr>

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" height=28>
    <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black" height=28>
    <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=Qt&logoColor=white" height=28>
</div>

### [Оценка временной задержки сигналов](https://github.com/EkimovP/Estimation_of_the_time_delay)

<img src="https://github.com/user-attachments/assets/acc9e9a1-5b9b-4eaa-87fc-9bf1f5bab2a5" style="margin-left: 20px" align="right" width=450>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Данный проект решает задачу оценки временной задержки сигналов 
на основе метода максимального правдоподобия при многоканальном распространении.

*В программе реализовано:*
 * Моделирование распространения сигнала по двум каналам.
 * Алгоритм оценки взаимной временной задержки распространения сигнала.
 * Исследование устойчивости реализованного алгоритма к шуму.

***Алгоритм программы:***

1. **Генерация исходных данных:** 
   1. Моделирование опорного сигнала с одной из манипуляций: АМ, ФМ2 или МЧМ.
   2. Моделирование исследуемого сигнала: копия опорного сигнала, задержанная на некоторое время T.
2. **Добавление белого гауссова шума.** 
3. **Оценка временной задержки.** Реализован алгоритм оценки временной задержки распространения сигналов на основе 
метода максимального правдоподобия (ММП), который сводится к оценке взаимной корреляционной функции (ВКФ) сигналов в опорном и исследуемом каналах. 
Положение её главного максимума соответствует временной задержке.
4. **Исследование устойчивости алгоритма к шуму.** Рассчитывается и строится график зависимости доверительной вероятности правильного
определения взаимной временной задержки от отношения сигнал/шум в исследуемом канале.

**Проект по той же тематике:** [Оценка временной задержки сигналов при условии априорной неопределенности несущей частоты](https://github.com/EkimovP/Estimation_of_the_time_delay_with_apriori_uncertainty).
<!-------------------------------------------------------------------------------------------------------------------->

<hr>

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" height=28>
    <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black" height=28>
    <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=Qt&logoColor=white" height=28>
</div>

### [Декодирование ФМ4 сигнала при помощи согласованной фильтрации](https://github.com/EkimovP/Decoding_FM4_signal_using_consistent_filtering)

<img src="https://github.com/user-attachments/assets/6ad044a3-3b77-40da-8e58-9584c3a80f33" style="margin-left: 20px" align="right" width=450>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Данный проект решает задачу декодирования ФМ4 сигнала, модулированного 
последовательностью Голда, при помощи согласованной фильтрации.

*В программе реализовано:*
 * Моделирование комплексной огибающей сигнала с ФМ4 манипуляцией, каждые информационные символы которого заменены
последовательностью Голда.
 * Восстановление исходной информации, передаваемой в сигнале, при помощи согласованной фильтрации. 
 * Исследование устойчивости реализованного алгоритма к шуму.

***Алгоритм программы:***

1. **Генерация исходных данных.** Моделирование сигнала с ФМ4 модуляцией в виде комплексной огибающей (IQ-компонент).
2. **Добавление белого гауссова шума.** 
3. **Восстановление исходной информации путем согласованной фильтрации.**
4. **Исследование устойчивости алгоритма к шуму.** Рассчитывается и строится график зависимости вероятности ошибки 
определения символа от отношения сигнал/шум.
<!-------------------------------------------------------------------------------------------------------------------->

<br><br> <br><br> <br><br> <br><br>

<!---------------------------------------------------------------------------------->
<h2 align="center"> Дипломная работа </h2> 
<!---------------------------------------------------------------------------------->

*Тема:* «Нелинейный спектральный анализ в задачах обнаружения сигналов»

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Обнаружение сигналов является разделом статистической теории радиотехнических систем. 
Одним из его разделов является спектральное оценивание. 
Спектральный анализ – совокупность методов качественного и количественного определения состава объекта, 
основанная на изучении спектров взаимодействия материи с излучением, включая спектры электромагнитного излучения, 
акустических волн, распределения по массам и энергиям элементарных частиц и др.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Современная теория обнаружения является основой для построения электронных систем обработки сигнала, 
в которых происходит принятие решений и извлечения информации. Можно выделить основные группы этих систем: 
1.	Радиолокационные.
2.	Системы связи.
3.	Системы обработки звука. 
4.	Гидролокационные системы.
5.	Системы обработки изображений.
6.	Биомедицинские системы.
7.	Сейсмологические устройства.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Все эти системы объединены общей целью – они должны иметь возможность решить, когда произойдет интересующее 
нас событие и определить как можно больше информации о нем. Первая упомянутая задача и есть предмет теории обнаружения.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Целью работы** является применение методов спектрального анализа для обнаружения сигналов. Для выполнения поставленной 
задачи была разработана программа на языке Python, в которой были реализованы линейные (классические) и 
нелинейные методы спектрального оценивания.

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" height=28>
</div>

### [Обнаружение сигнала с помощью линейных и нелинейных методов](https://github.com/EkimovP/graduate_work)

<img src="https://github.com/user-attachments/assets/465b918e-d30e-4d21-8110-136a1c2498e5" style="margin-left: 20px" align="right" width=450>

***Алгоритм программы:***
1) **Построение исходных данных:** генерация сигнала с выбранными параметрами; загрузка данных из файла; загрузка аудиофайла.
2) **Выбор алгоритма обнаружения.**
3) **Построение спектра сигнала.**
4) **Построение спектрограммы сигнала.**

**По результатам моделирования были сделаны следующие выводы:**
1. Корреляционный спектральный анализ дает лучший результат на полученных данных, чем алгоритм быстрого преобразования Фурье.
2. Метод минимальной дисперсии дает лучший результат по сравнению с методом максимума энтропии и АР-моделью.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Также можно сделать выводы о том, что нелинейные методы дают более четкие границы «всплесков» по сравнению с линейными 
методами, что указывает на более точную и менее размытую временную и частотную локализацию реакции системы на внешние 
воздействия, но последние имеют преимущество в быстродействии.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Исходя из проведенных построений спектрограммы, делаем вывод о том, что методы спектрального оценивания такие, 
как корреляционный спектральный анализ и метод минимальной дисперсии являются наиболее оптимальными по сравнению с другими.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Таким образом, аргументы в пользу выбора той или иной спектральной оценки буду зависеть от того интересует ли нас 
гладкая оценка в пределах всего диапазона анализируемых частот или же нам важна более высокая степень обнаружения 
сигнала на некоторых конкретных его участках. Поэтому алгоритмы спектрального оценивания вовсе не обязательно 
являются также и хорошими алгоритмами обнаружения.
<!-------------------------------------------------------------------------------------------------------------------->

<br><br> <br><br> <br><br><br><br>

<!---------------------------------------------------------------------------------->
<h2 align="center"> Frontend-разработка </h2> 
<!---------------------------------------------------------------------------------->

<h3>Работы представлены на сайте [Codepen.io](https://codepen.io/PavelEkimov/pens/public).

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/javascript-%23000000?style=for-the-badge&logo=javascript&logoColor=%23000000&color=%23FFFF00" height=28>
    <img src="https://img.shields.io/badge/html-%23FFE4B5?style=for-the-badge&logo=html5" height=28>
    <img src="https://img.shields.io/badge/CSS-%231E90FF?style=for-the-badge&logo=css3" height=28>
</div>

### [Галерея из карточек](https://github.com/EkimovP/5_days_5_project/tree/main/Cities)

<div align="center">
    <img src="https://github.com/EkimovP/EkimovP/assets/125445428/451c42a9-a5d3-40cf-b6ea-aa3decd13de1">
</div>
<!-------------------------------------------------------------------------------------------------------------------->

<hr>

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/javascript-%23000000?style=for-the-badge&logo=javascript&logoColor=%23000000&color=%23FFFF00" height=28>
    <img src="https://img.shields.io/badge/html-%23FFE4B5?style=for-the-badge&logo=html5" height=28>
    <img src="https://img.shields.io/badge/CSS-%231E90FF?style=for-the-badge&logo=css3" height=28>
</div>

### [Drag&Drop](https://github.com/EkimovP/5_days_5_project/tree/main/Drag%20and%20Drop)

<div align="center">
    <img src="https://github.com/EkimovP/EkimovP/assets/125445428/dd5828c7-dad6-4785-a86d-b1dbcd413e1a">
</div>
<!-------------------------------------------------------------------------------------------------------------------->

<hr>

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/javascript-%23000000?style=for-the-badge&logo=javascript&logoColor=%23000000&color=%23FFFF00" height=28>
    <img src="https://img.shields.io/badge/html-%23FFE4B5?style=for-the-badge&logo=html5" height=28>
    <img src="https://img.shields.io/badge/CSS-%231E90FF?style=for-the-badge&logo=css3" height=28>
</div>

### [Мини-игра Aim Training](https://github.com/EkimovP/5_days_5_project/tree/main/Aim%20Training)
<div align="center">
    <img src="https://github.com/EkimovP/EkimovP/assets/125445428/d895a813-f5ba-4cc1-9ae1-4406bec15535">
</div>
<!-------------------------------------------------------------------------------------------------------------------->

<hr>

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/typescript-%233178C6?style=for-the-badge&logo=typescript&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/html-%23FFE4B5?style=for-the-badge&logo=html5" height=28>
    <img src="https://img.shields.io/badge/CSS-%231E90FF?style=for-the-badge&logo=css3" height=28>
</div>

### [Просмотр персонажей Rick And Morty](https://github.com/EkimovP/TheRickAndMorty)

<img src="https://github.com/user-attachments/assets/f6c8e501-1bc5-4fc8-bceb-11e34c548865" style="margin-left: 20px" align="right" width=500>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Этот проект представляет собой веб-приложение, разработанное с использованием 
HTML, TypeScript и использует API Rick And Morty для отображения информации о персонажах. Включает функции пагинации, 
фильтрации по имени персонажа и другим параметрам, а также страницы с подробной информацией о персонаже.
<br>

**В проекте реализовано следующее:** 
1. Получение данных из API Rick And Morty (использование асинхронных функций). 
2. Управление пагинацией. 
3. Поиск и фильтрация. Реализована функция для фильтрации персонажей по имени и дополнительным критериям (виду и статусу). 
4. Каждая карточка персонажа динамически генерируется на основе полученных данных.
<!-------------------------------------------------------------------------------------------------------------------->

<hr>

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/javascript-%23000000?style=for-the-badge&logo=javascript&logoColor=%23000000&color=%23FFFF00" height=28>
    <img src="https://img.shields.io/badge/html-%23FFE4B5?style=for-the-badge&logo=html5" height=28>
    <img src="https://img.shields.io/badge/CSS-%231E90FF?style=for-the-badge&logo=css3" height=28>
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" height=28>
</div>

### [Классический контрол ArrangeBox](https://github.com/EkimovP/ArrangeBox)

<img src="https://github.com/user-attachments/assets/d98a0ec2-0e86-41d3-8de7-5a61ee992927" style="margin-left: 20px" align="right" width=500>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Данный контрол представляет собой два поля, расположенных на одном горизонтальном уровне, и позволяет выбрать несколько значений из списка.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Пользователь может: перемещать, изменять, удалять, фильтровать и добавлять новые позиции в списки.
В опциях пользователь может: посмотреть все позиции в списках, вернуть контрол в исходное состояние и создать новый контрол.
<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;P.S. Проект можно запустить через сервер.
<!-------------------------------------------------------------------------------------------------------------------->

<br><br> <br><br> <br><br><br><br>

<!---------------------------------------------------------------------------------->
<h2 align="center"> Проекты на языке С++ </h2> 
<!---------------------------------------------------------------------------------->

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/-opengl-5586A4?style=for-the-badge&logo=opengl&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/-MFC-090909?style=for-the-badge&logo=C%2b%2b&logoColor=6296CC" height=28>
</div>

### [Cube openGL](https://github.com/EkimovP/Cube_openGL)

<img src="https://github.com/EkimovP/EkimovP/assets/125445428/b373cd34-9899-4fbb-bd54-4c12dbc2c652" align="right" width=350>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Отрисовка трехмерной цветной фигуры в ***OpenGl и реализация вращения.***

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;В программе заданы плоскости куба, с раскраской граней. 
<!-------------------------------------------------------------------------------------------------------------------->
<br><br> <br><br><br><br>

<hr>

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/-MFC-090909?style=for-the-badge&logo=C%2b%2b&logoColor=6296CC" height=28>
</div>

### [Фильтрация сигнала от шума на основе преобразования Фурье](https://github.com/EkimovP/Signal_filtering)

<img src="https://github.com/EkimovP/EkimovP/assets/125445428/83857bca-63c6-4cab-85a9-993493cb3644" style="margin-left: 20px" align="right" width=500>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;В данной программе реализован метод фильтрации в частотной области зашумленного сигнала с использованием алгоритма 
быстрого преобразования Фурье. В качестве полезного сигнала был использован полигармонический сигнал, который 
представляет собой сумму синусоид с разными амплитудами и частотами.
<br> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Поскольку Фурье-фильтрация предполагает различие частотных характеристик полезного сигнала и шума, предполагается, 
что сигнал является низкочастотным.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Далее к исходному сигналу необходимо добавить белый гауссов шум так, чтобы полученный зашумленный сигнал 
характеризовался заданным отношением сигнал/шум (ОСШ). Поскольку белый шум является некоррелированным с сигналом 
случайным процессом и занимает всю полосу частот, а полезный сигнал является низкочастотным, это позволяет достаточно 
эффективно очистить исходный полигармонический сигнал от шума в частотной области. Чтобы перейти в частотную область, 
необходимо выполнить преобразование Фурье зашумлённого сигнала, для чего его нужно преобразовать в комплексный сигнал, 
добавив нулевую мнимую часть.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Важно!** При реализации алгоритма фильтрации с использованием БПФ необходимо учитывать, что длина 
входной последовательности обязательно должна быть степенью двух.
<br>

***Алгоритм фильтрации низкочастотного сигнала состоит в следующем:***

1) Задается значение коэффициента (порога), определяющего долю энергии спектра сигнала, которая сохраняется 
в результате проведения фильтрации.
2) Вычисляется полная энергия спектра зашумленного сигнала. 
3) С обоих концов массива суммируется энергия спектра до достижения заданного порога. По достижении порога 
все остальные отсчёты комплексного спектра зануляются. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Идея заключается в том, чтобы сохранить частотную область, соответствующую спектральным составляющим исходного сигнала 
и отбросить шумовую составляющую.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Заключительный этап: вычислить обратное преобразование Фурье от полученного «очищенного» комплексного спектра 
и сравнить полученный сигнал во временной области с исходным сигналом.
<!-------------------------------------------------------------------------------------------------------------------->

<hr>

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/-MFC-090909?style=for-the-badge&logo=C%2b%2b&logoColor=6296CC" height=28>
</div>

### [Обнаружение гармонического сигнала методом авторегрессии](https://github.com/EkimovP/Detection_by_autoregression)

<img src="https://github.com/EkimovP/EkimovP/assets/125445428/a87dd2ed-373a-4c14-89df-64c1a6f4d186" style="margin-left: 20px" align="right" width=450>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;В данной программе требуется оценить границы фрагмента эталонного гармонического сигнала с известной частотой, 
расположенного внутри массива, содержащего гармонические сигналы с другими частотами. На первом этапе реализации 
алгоритма обнаружения эталонного сигнала необходимо сгенерировать исследуемый сигнал. 
Для этого задаются частоты исходного гармонического сигнала для обнаружения и двух других синусоидальных сигналов, 
между которыми заключен искомый сигнал.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Примечание.** Количество отсчётов может быть произвольным, рекомендуется брать примерно 1000 отсчетов.
Дополнительно при генерации исследуемого сигнала необходимо обеспечить непрерывность фазы 
(производить «сшивку» фазы на участках перехода от одного гармонического сигнала к другому), 
чтобы получился один плавный график трёх сигналов с разными частотами.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;В данной программе используется линейное предсказание для обнаружения сигнала заданной частоты. 
Линейное предсказание использует АР-модель.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Отсчеты исследуемого сигнала подставляются в формулу АР-модели второго порядка для линейного предсказания. 
Работа алгоритма предсказания начинается с третьего отсчета, поскольку предсказание зависит от двух предыдущих 
отсчетов. На основе полученных предсказанных отсчетов и имеющихся истинных отсчетов исследуемого сигнала 
вычисляется массив квадратичных ошибок предсказания, т.е. график квадратичного отклонения между предсказанием 
и фактическим отсчетом исходного сигнала. Можно заметить, что качественный вид графика ошибки напоминает вид 
синусоидального сигнала. Определить границы искомого сигнала можно пороговым методом, для чего нужно сглаживать 
ошибку предсказания.
<br> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;В данной задаче для сглаживания данных используется алгоритм сверточной фильтрации во временной области.<br>
Точки пересечения линии заданного порога с графиком сглаженной ошибки будем считать оценкой начала и конца 
искомого эталонного сигнала, соответственно.
<!-------------------------------------------------------------------------------------------------------------------->

<hr>

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/-MFC-090909?style=for-the-badge&logo=C%2b%2b&logoColor=6296CC" height=28>
</div>

### [Деконволюция свертки методом максимума энтропии](https://github.com/EkimovP/Deconvolution)

<img src="https://github.com/EkimovP/EkimovP/assets/125445428/b0dc51a4-fa84-4dd9-89d2-afe8534f4989" style="margin-left: 20px" align="right" width=540>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;В данной программе, по сути, решается не только обратная задача, но и задача прямого распространения, чтобы создать 
данные, на основе которых можно было бы решить обратную задачу. 
Входной сигнал представляет собой сумму гауссовых куполов.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Важно!** Данная задача представляет собой задачу многомерной оптимизации. Решение будет уточняться на каждой 
итерации, причём таких итераций в зависимость от требуемой точности может быть достаточно много. 
Поэтому в этой задаче стоит иметь в виду сигналы длиной не более 50 отсчетов.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;На следующем шаге необходимо определить вид импульсной характеристики. Она будет представлять собой гауссов 
купол, симметрично расположенный на концах импульсной последовательности.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Примечание.** Амплитуду можно выбрать единичную, поскольку из-за нормировки величина амплитуды на виде сигналов 
и качестве восстановленного сигнала не скажется, а является лишь масштабирующим параметром.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;В качестве заключительного шага подготовки к основной задаче необходимо с помощью циклической свертки вычислить 
выходной сигнал линейной системы с полученной импульсной характеристикой.
<br>
Дальше можно приступить к основной части задачи.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Доопределим задачу и используем теоретико-информационный подход. В качестве функционала-критерия будем использовать 
функционал информационной энтропии Шеннона, в качестве дополнительного условия будем использовать уравнение 
формирования, являющееся линейным ограничением. Функционал энтропии является выпуклым, поэтому после наложения 
линейных ограничений получим единственный минимум оптимизационной задачи, то есть единственное решение. 
На основе такого функционала выражаем входной сигнал и составим новый функционал среднеквадратичного отклонения, 
то есть сводим вариационную задачу к оптимизационной.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Условием оптимальности функционала является равенство нулю его первой вариации, то есть всех частных производных
первого порядка по всем переменным. Подставив выражение в линейное ограничение, то есть в уравнение 
формирования, получим выходной сигнал как функцию от параметра регуляризации, который можно сравнить 
с имеющимися отсчетами выходного сигнала, например в виде функционала среднеквадратичного отклонения. 
В итоге получим функционал среднеквадратичного отклонения.
<br> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Вектор неопределенных множителей Лагранжа находим методом многомерной оптимизации данного функционала, 
для чего был использован метод Хука-Дживса. На основе полученных множителей Лагранжа вычисляется 
восстановленный сигнал, который необходимо сравнить с исходным входным сигналом.
<!-------------------------------------------------------------------------------------------------------------------->

<hr>

<!-------------------------------------------------------------------------------------------------------------------->
<div align="right">
    <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" height=28>
    <img src="https://img.shields.io/badge/-MFC-090909?style=for-the-badge&logo=C%2b%2b&logoColor=6296CC" height=28>
</div>

### [Решение фазовой проблемы с помощью алгоритма Фиенупа](https://github.com/EkimovP/Phase_problem)

<img src="https://github.com/EkimovP/EkimovP/assets/125445428/1905b341-1cf2-4a25-a8b4-bcf13c6c645c" style="margin-left: 20px" align="right" width=500>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Поскольку для применения алгоритма Фиенупа изначально должен быть известен модуль спектра, в качестве подготовительного
шага предстоит получить модуль спектра некоторого известного сигнала, 
модуль спектра которого будет служить входными данными алгоритма. 
В данной программе был сгенерирован сигнал, состоящий из трех гауссовых куполов.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Примечание.** Для получения лучшего результата рекомендуется брать достаточно узкие купола, не перекрывающиеся 
друг с другом.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Вычислив модуль преобразования Фурье этого сигнала, получим модуль спектра, фазу которого в дальнейшем 
требуется восстановить с помощью алгоритма Фиенупа.

***Итерационная схема алгоритма состоит из следующих шагов:***

1) **Инициализация.** Из известного модуля строится комплексная последовательность чисел, имеющихся известный модуль 
и случайную фазу с равномерным распределением в интервале [0, 2𝜋].
2) **Применение ограничений во временной области.** Можем восстановить сигнал по построенному комплексному 
спектру и во временной области применить ограничение на неотрицательность сигнала.
3) **Замена модуля в частотной области на известный.** Применение ограничения на неотрицательность во 
временной области влечет за собой определённые изменения в спектральной области, в том числе модуля спектра. 
Из-за этого возникает необходимость замены модуля на известный модуль спектра.
4) **Проверка сходимости итерационной схемы.** Повторяются шаги (2) и (3) пока изменения сигнала не перестали 
превышать заданный порог среднеквадратичного отклонения на один отсчет.
<!-------------------------------------------------------------------------------------------------------------------->
