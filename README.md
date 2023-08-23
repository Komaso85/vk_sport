# vk_sport
Задача: На основе заданного набора постов определите, какой вид спорта обсуждается в выбранном сообществе VK.



Данные представлены на платформе kaggle по ссылке 

[vk_competition data](https://www.kaggle.com/datasets/mikhailma/russian-social-media-text-classification)

Мной была использован только файл train.csv
В качестве целевой метрики выбрана Accuracy, так как данные сбалансированы

Данный датасет состоит из 3 колонок и 38740 строк.
Название колонок
oid - id сообщества - int64
category - вид спорта (таргет) - object
text - текст поста - object
В данных представлены посты спортивных сообществ VK ввиде текста в колонке text, каждое сообщество представлено 10 постами. Всего в данных 3874 сообщества. Каждое сообщество имеет уникальную категорию.
Категорий в данном датасете 13: athletics, autosport, basketball, boardgames, esport, extreme, football, hockey, martial arts, motosport, tennis, volleyball, winter_sport
Датасет сбалансирован, но имеются дубликаты.
