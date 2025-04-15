# web_scraping
###структура сайта со временем меняется поэтому код возможно  будет не актуален!!! 
- в данном репозитории представлены 2 функции сбора данных с сайта (https://habr.com)

1  Функция в качестве параметра принимает список запросов для поиска (['python', 'анализ данных']) и на основе материалов, попавших в результаты поиска по каждому запросу, возвращать датафрейм вида: <дата> - <заголовок> - <ссылка на материал>  
В рамках задания предполагается работа только с одной (первой) страницей результатов поисковой выдачи для каждого запроса. Материалы в датафрейме не должны дублироваться, если они попадали в результаты поиска для нескольких запросов из списка.  

2 Функция из 1 части  расширена следующим образом:
кроме списка ключевых слов для поиска необходимо объявить параметр с количеством страниц поисковой выдачи.  При передаче в функцию аргумента 4 необходимо получить материалы с первых 4 страниц результатов;
в датафрейме должны быть столбцы с полным текстом найденных материалов и количеством лайков:
<дата> - <заголовок> - <ссылка на материал> - <текст материала> - <количество лайков>
