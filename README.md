# Here are some interesting solutions to Skillbox tasks

Evgeii Golovin  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  oct-2023.

> ВЫДЕРЖКИ ИЗ УЧЕБНОГО ПРОЕКТА
>  по профессии   «**Data Scientist - ML**»

тема:
> «Исследование оттока клиентов мобильного оператора - применение снижения размерности»

![иллюстрация pca из моего скрипта](/crs/templates/pca_1.png)

Предлагается применить PCA к трехмерным данным по оттоку (/data/client_segmentation.csv). В файле содержится информация о клиентах оператора: как изменилось потребление услуг оператора за два месяца:

## Содержание
- [Технологии](#технологии)
- [Начало работы](#использование)
- [Исходные условия](#исходные-условия)
- [To do](#to-do)
- [Исполнитель проекта](#исполнитель-проекта)

## Технологии
- [Python 3.7](https://www.python.org/downloads/release/python-370/)
- [pandas](https://www.pandas.pydata.org/)
- [numpy](https://www.numpy.org/)
- [matplotlib](https://www.matplotlib.org/)
- [scikit-learn](https://www.scikit-learn.org/stable/)
- [jupyter notebook](https://www.jupyter.org/)
- [pycharm community](https://www.jetbrains.com/pycharm/)
- [Flask](https://www.dashboard.render.com/)

## Использование

Репозиторий содержит исходный скрипт в jupyter ноутбуке, html-страницу c этим скриптом и необходимые для запуска файлы с и данными и изображениями

> /notebooks/Dim_reduction_on_clients_churn_and_image_compression.ipynb
> /crs/Dim_reduction_on_clients_churn_and_image_compression.html

В соседней папке data требуются файлы:
- [x] client_segmentation.csv (база данных по оттоку с разметкой)
- [x] dorian_grey.png (исходное изображение для сжатия)
- [x] output_conda.png и output_vscode.png (картинки для сравнения версий sklearn) 

Запуск - для перезапуска отткрыть jupyter notebook **notebooks/Dim_reduction_on_clients_churn_and_image_compression.ipynb** в клонированном репозитории.
Для просмотра - достаточно html.

## Исходные условия

**На входе** имеется учебная задача на снижение размерности.

**Актуальность:** разумеется, снижение размерности прекрасно улучшает результаты регрессии на многомерных входных параметрах, сохраняя основную часть смысла данных что проиллюстрировано на примере сжатия картинки. Сжатие 2-мерных и 3-мерных данных иллюстрирует, как работают алгоритмы.

**Датасет** содержит информацию о клиентах оператора: как изменилось потребление услуг оператора за два месяца:

call_diff доля звонков
sms_diff доля смс
доля интернет-трафика traffic_diff

В последней колонке customes_class содержится метка по оттоку:

0 - активный пользователя
1 - "спящий" пользователь (редко пользуется услугами)
2 - пользователь, который ушел в отток


[https://drive.google.com/file/d/1B1s5gBlvgU81H9GGolLQVw_SOi-vyNf2/view?usp=sharing](https://drive.google.com/file/d/1B1s5gBlvgU81H9GGolLQVw_SOi-vyNf2/view?usp=sharing)

Требуется:

 1. Решить поставленные задачи.
 2. Наглядно представить результат.
 3. По возможности выявить интересные особенности преобразователей не ограничиваясь формулировкой задания.
 4. Подчеркунть неясные детали при их обнаружении.
 5. Создать репозиторий в GitHub и разместить там код исследования. Оформить файл README.

### Зачем я разработал этот проект?
С целью демонтсрации освоенных навыков на интересном учебном проекте, позволяющем творчески подойти к решению, и даже поднять вопрос работы некоторых алгоритмов (t-SNE) в разных версиях Skikit-Learn.

## To do
- [x] Добавить крутое README
- [ ] Всё переписать :-)
- [ ] Cделать веб-приложение через Flask

## Исполнитель проекта

- [Евгений Головин]([golovin1410@gmail.com](mailto:golovin1410@gmail.com)) — DataScientist - student
![логотип Skillbox](/crs/templates/Skillbox_logo.svg.png)
