# Разработка индикатора для прогнозирования цен активов на основе приближения их тренда цен
Целью данной бакалаврской работы является разработка и исследование индикаторов технического анализа, которые основаны на приближении тренда цен, с последующим сравнением их эффективности в прогнозировании для выявления наиболее точных инструментов.
Для достижения поставленной цели были выполнены следующие задачи:
1)	Рассмотрение методов прогнозирования.  
2)	Изучение основ технического анализа.
3)	Исследование технических индикаторов.
4)	Построение трендовых индикаторов и индикаторов на основе приближения тренда цен интерполяционными полиномами. 
5)	Проведение бэк-тестирования индикаторов на примере акций золотодобывающей компании «Полюс» с помощью программы, написанной на языке программирования Python 3.10.
6)	Анализ прогнозной силы индикаторов по полученным результатам.
Объект исследования – трендовые индикаторы технического анализа и индикаторы на основе приближения цен интерполяционными полиномами. 	
Предмет исследования – акции золотодобывающей компании «Полюс».
Бакалаврская работа состоит из введения, шести основных разделов, заключения, списка литературы и приложения. 
В первом разделе рассматриваются методы исследования рынка ценных бумаг, основные понятия технического анализа, виды и методы прогнозирования. 
Второй раздел посвящён обзору некоторых трендовых индикаторов рынка ценных бумаг, их особенностям структуры при использовании и построении. 
Третий раздел содержит постановку задачи – математическую часть, включающую принципы построения индикаторов на основе интерполяции с помощью полиномов Лагранжа и Чебышева. 
В четвертом разделе представлены схемы построения и бэк-тестирования индикаторов на исторических данных для анализа финансового результата. Главной частью этого раздела является план проведения вычислительных экспериментов, содержащий поэтапный алгоритм действий, а завершает раздел описание программной разработки. 
В пятом разделе рассматриваются тенденции спроса и предложения на рынке золота, а также описаны инвестиционные стратегии. 
Шестой раздел отражает итоги вычислительных экспериментов на примере цен закрытия акций золотодобывающей компании «Полюс» с 06.04.2020 по 04.04.2024 с использованием индикаторов, реализованных на языке Python 3.10, а также анализ полученных результатов.  
 
Для проведения экспериментов была написана программа на языке Python 3.10 (Приложение Б) в облачной среде Google Colab (Colaboratory) с использованием библиотеки ipywidgets для создания интерактивного приложения, позволяющего пользователю настраивать параметры индикатора и просматривать результаты. Данная облачная среда предназначена для разработки, вычисления и обучения моделей машинного обучения, предоставляющее бесплатный доступ к вычислительным ресурсам GPU и TPU. Программа получает на вход файл, в котором заранее сохранены цены акций. При запуске программа строит ценовой график. Затем создаются функции для расчета рассматриваемых индикаторов: простое скользящее среднее, тройное экспоненциальное скользящее среднее, индикаторы, основанные на методах интерполяции Лагранжа и Чебышева. Также, реализуются вспомогательные функции для расчета отклонений прогнозных значений от исходных, обнаружения сигналов входа и выхода из сделок, получаемых от индикаторов, подсчета доходности и нахождения максимальных и минимальных значений доходности торговой стратегии при различных значениях параметра n. 

<img width="482" alt="image" src="https://github.com/user-attachments/assets/c8ab2468-495b-4cf2-bafb-80a47f049b95">
