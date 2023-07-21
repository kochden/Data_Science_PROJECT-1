
![](https://raw.githubusercontent.com/AndreyRysistov/DatasetsForPandas/main/hh%20label.jpg)
# <center> Анализ резюме из HeadHunter </center>
## Оглавление
1. [Описание проекта](#Описание-проекта)
2. [Описание данных](#Описание-данных)
3. [Зависимости](#Зависимости)
4. [Установка проекта](#Установка-проекта)
5. [Использование проекта](#Использование-проекта)
6. [Автор](#Автор)
7. [Выводы](Использование-проекта)

## Описание проекта

> **Анализ резюме из HeadHunter** – Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Наша задача подготовить данные для построения модели.

**Основные этапы проекта:**
* Исследование структуры данных;
* Преобразование данных;
* Исследование зависимостей в данных;
* Очистка данных.

**Цель проекта** — продемонстирировать методы работы с данными и навыки их анализа.

**О структуре проекта:**
* [data](./data) - папка с исходными табличными данными.
* [Project-1._Ноутбук-шаблон.ipynb](./Project-1._Ноутбук-шаблон.ipynb) - jupyter-ноутбук, содержащий основной код проекта, в котором демонстрируются методы и подходы решения задачи.

## Описание данных
В этом проекте используется база резюме, выгруженная с сайта поиска вакансий hh.ru.  
Исходный датасет представляет собой набор данных из таблицы с информацией о соискателях вакансий, их ворасте, месте жительства, образовании, месте жительства, предполагаемом уровне заработной платы и др.  
Так же в нашем проекте используются данные о курсах валют, которые мы использовали для перевода желаемой заработной платы указанной в иностранных валютах в рублевый эквивалент.  
Датасет с базой резюме можно взять [здесь](https://disk.yandex.ru/d/NDm38MEK2fwRcw).
Датасет с курсами валют предварительно скачанный с ресурса [MDF.RU](https://mfd.ru/export/#Alias=false&Period=1&timeframeValue=1&timeframeDatePart=day&StartDate=04.10.2021&EndDate=04.10.2021&SaveFormat=0&SaveMode=0&FieldSeparator=%253b&DecimalSeparator=.&DateFormat=yyyyMMdd&TimeFormat=HHmmss&AddHeader=true&RecordFormat=0&Fill=false) можно взять [здесь](https://disk.yandex.ru/d/zSdaEFcAthj_Vw).

## Используемые зависимости
* Python (3.11.2):
    * [numpy (1.24.2)](https://numpy.org)
    * [pandas (1.5.3)](https://pandas.pydata.org)
    * [matplotlib (3.7.1)](https://matplotlib.org)
    * [seaborn (0.12.2)](https://seaborn.pydata.org)

## Установка проекта

```
git clone https://github.com/SkillfactoryDS/DataCleaningProject
```

## Использование проекта
Вся информация о работе представлена в jupyter-ноутбуке [Project-1._Ноутбук-шаблон.ipynb](./Project-1._Ноутбук-шаблон.ipynb).

## Автор
Кочергин Денис Николаевич  
KocherginDN@rshb.ru

## Выводы

Благодаря данному проекту, мною изучены и продемонстированы практические навыки исследования, преобразования, очистки и анализа данных.