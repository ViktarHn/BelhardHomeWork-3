# BelhardHomeWork-3
Домашняя работа №3
1. Выберите любой открытый датасет и скачайте открытый датасет, соответствующий вашим интересам или области обучения.
2. Создайте новую базу данных в системе управления базами данных (например, SQLite, PostgreSQL).
3. Создайте таблицу (или несколько таблиц) в базе данных с различными типами данных (INTEGER, TEXT, DATE), которые требуются для вашего датасета. Импортируйте данные из датасета в созданные таблицы.
4. Напишите несколько SQL-запросов для извлечения данных из таблиц базы данных. Используйте условия фильтрации (например, WHERE) для получения нужных данных.
5. Напишите SQL-запросы, использующие агрегатные функции (SUM, AVG, COUNT) для выполнения расчетов по данным таблицы.
6. Визуализируйте данные. Используйте библиотеки Python, такие как Matplotlib или Seaborn, для визуализации данных, извлеченных из базы данных. Постройте графики или диаграммы, которые помогут проанализировать и понять данные.

	create_db.py: Создает базу данных wines.db, таблицу wines и импортирует данные из CSV-файла winemag-data-130k-v2.csv.

	exam.py: Проверяет структуру и содержимое базы данных, выводя информацию о таблице и первых 5 записях.

	highprice 10.py: Выводит топ-10 самых дорогих вин из базы данных.

	import.py: Импортирует данные из CSV-файла в базу данных.

	skip.py: Очищает данные от пропусков и дубликатов, выводя информацию о пропусках и дубликатах.

	VizCountries.py: Визуализирует распределение цен по странам с использованием гистограммы.

	VizCountriesPieChart.py: Визуализирует долю вин по странам в виде круговой диаграммы.

	VizCountriespoints.py: Визуализирует распределение оценок по странам с использованием boxplot.

	VizCountriesprice.py: Визуализирует распределение цен и долю вин по странам с использованием гистограммы и круговой диаграммы.

	VizHeatmap.py: Визуализирует тепловую карту корреляции между оценками и ценами.

	VizHighprice.py: Визуализирует топ-10 самых дорогих вин в виде горизонтальной столбчатой диаграммы.

	VizPointsprice.py: Визуализирует зависимость цены от оценки с использованием scatter plot.
	VizVarietyprice.py: Визуализирует распределение цен по сортам винограда с использованием violin plot.
	wine_analysis.py: Анализирует зависимость цены от оценки и визуализирует данные с использованием scatter plot.
	VizPairplot.py анализирует взаимосвязи между оценками (points), ценами (price) и странами (country) для вин.
