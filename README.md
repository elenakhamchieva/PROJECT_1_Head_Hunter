
# <center> Анализ резюме из HeadHunter </center>
## Оглавление
1. [Описание проекта](#Описание-проекта)
2. [Описание данных](#Описание-данных)
3. [Зависимости](#Зависимости)
4. [Установка проекта](#Установка-проекта)
5. [Использование проекта](#Использование-проекта)
6. [Авторы](#Автор)
7. [Выводы](#Выводы)

## Описание проекта

Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Но, прежде чем построить модель, данные необходимо преобразовать, исследовать и очистить. 

Проблематика: часть соискателей не указывает желаемую заработную плату, когда составляет своё резюме.
Это является помехой для рекомендательной системы HeadHunter, которая подбирает соискателям список наиболее подходящих вакансий, а работодателям — список наиболее подходящих специалистов.

Основные этапы проекта:
* базовый анализ структуры данных.
* преобразование данных.
* разведывательный анализ с помощью средств визуализации.
* очистка данных.

**О структуре проекта:**
* [ExchangeRates.csv](./ExchangeRates.csv) - файл с данным о курсах валют
* [Plotly_diagrams](./Plotly_diagrams) - папка с диаграммами Plotly в формате html
* [Project-1._Ноутбук-шаблон.ipynb](./Project-1._Ноутбук-шаблон.ipynb) - jupyter-ноутбук, содержащий основной код проекта.


## Описание данных
В этом проекте используются база резюме, выгруженная с сайта поиска вакансий hh.ru.

Файл с данными можно найти [здесь](https://drive.google.com/file/d/18oSAn1lEla44dFCkSLricLxzgEH1HZDj/view?usp=sharing).

## Зависимости
* Python (3.9.10):
    * [numpy (1.26.4)](https://numpy.org)
    * [pandas (2.2.1)](https://pandas.pydata.org)
    * [matplotlib (3.8.4)](https://matplotlib.org)
    * [seaborn (0.13.2)](https://seaborn.pydata.org)
    * [plotly (v2.32.0)](https://plotly.com/)

## Установка проекта

```
git clone https://github.com/elenakhamchieva/PROJECT_1_Head_Hunter
```

## Использование проекта
Вся информация о работе представлена в jupyter-ноутбуке Project-1._Ноутбук-шаблон.ipynb.

## Автор

* Елена Хамчиева

## Выводы

Средний возраст соискателей составляет 32 года. 
Подавляющее большинство (почти 81 процент) - мужчины.
Три четверти имеют высшее образование.
Опыт работы большинства соискателей составляет примерно 7 лет.
У соискателей с высшим образованием самые высокие зарплатные ожидания в любом возрасте.
У мужчин зарплатные ожидания выше, чем у женщин и это не зависит от уровня образования.
Кандидаты, готовые к командировкам имеют более высокие зарплатные ожидания, чем готовые к переезду.
Зарплатные ожидания в зависимости от города распределены следующим образом в порядке убывания: Москва, Санкт-Петербург, города-миллионники и другие города.
