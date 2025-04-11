## Годовой отчёт для компании «Бест Мебель»


![Power BI](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![SQL Server](https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

Анализ продаж мебели содержит полные годовые данные о продажах из вымышленной компании. Набор данных включает подробную информацию о каждом заказе, например, дату оформления заказа, коллекции и категории мебели, цены. Ассортимент товаров взят с реальных сайтов популярных компаний.

## Предосмотр
![](https://github.com/Nadezhda2024/-/blob/main/%D0%BF%D1%80%D0%B5%D0%B4%D0%BE%D1%81%D0%BC%D0%BE%D1%82%D1%80-%D0%B3%D0%BE%D0%B4%D0%BE%D0%B2%D0%BE%D0%B9-%D0%BE%D1%82%D1%87%D0%B5%D1%82%20%D0%B3%D0%B8%D1%84%D0%BA%D0%B0.gif)
## Ссылка на дашборд
<b>[Dashboard-of-the-annual-report-for-the-company](https://app.powerbi.com/links/rQo8bNyIV2?ctid=b820ef4f-c5fc-4e01-b3e4-6d2ad14931c8&pbi_source=linkShare)

## Обзор набора данных

Набор данных содержит ценную информацию, которая может помочь оптимизировать деятельность компании:
- Интегрирация CRM с базой данных.
- Таблицы со справочником номенклатуры.
- Таблица со справочником клиентов.
- Таблица со справочником поставщиков.
- Таблица со справочником коллекций и категорий товара, прайс товаров.
- Таблица со справочником со всеми заказами за 2021 год.
- Таблица со справочником купонов.
- Таблица со справочником скидок.
- Таблица со справочником причины отказа.

## Подготовка данных

1. **Исследование данных с помощью SQL**
  - Установка SQLite 3 ODBC Driver
  - Подключение БД в консоли SQLite3 и Valentino Studio
  - Выявление ошибок в данных
  - Исправление ошибок в данных
  - Добавление купона на 250 рублей шестому доставленному заказу

### [Отчет_SQL_запросов](https://github.com/Nadezhda2024/Dashboard-of-the-annual-report-for-the-company/blob/main/%D0%9E%D1%82%D1%87%D0%B5%D1%82-SQL-%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81%D0%BE%D0%B2.pdf)

2. **Работа с данными в Power BI**
  - Power Query — подключение к источникам данных (ODBC, Excel, CSV)
  - Power Pivot — создание модели данных. Протягивание связей между столбцами отдельных таблиц, для создания интерактивности будущего дашборда
  - Языки DAX, М - создание «Расчетных столбцов», «Расчетных таблиц» и «Мер», которые помогут рассчитать значение для любого показателя
  - Power View — рисование графиков и диаграмм.





