# Segmentation-of-online-gift-store-customers

## 1.Описание проекта:
Датасет содержит все транзакции, произошедшие за период с 01/12/2010 по 09/12/2011, для базирующейся в Великобритании компании, занимающейся розничной онлайн-торговлей. Компания в основном продаёт уникальные подарки на все случаи жизни. Многие клиенты являются оптовиками.

Проект будет состоит из шести частей:

1 Базовый анализ и знакомство с данными
Первая часть проекта  посвящена знакомству с исходными данными и их структурой.

2 Предобработка и очистка данных
Подготовка датасета для кластеризации, очистка его от пропусков, дублей, выбросов и другого «мусора».

3 Разведывательный анализ данных (EDA)
Исследование данных, найдены первые закономерности и выдвинуты гипотезы.

4 RFM-сегментация клиентов. Часть I
Методом сегментации клиентов под названием RFM (Recency, Frequency, Monetary) сформирована из исходного датасета о транзакциях таблица с RFM-характеристиками клиентов и произведена их первичная сегментация.

5 RFM-сегментация клиентов. Часть II
Расширины клиентские сегменты и созданы промежуточные категории с помощью нелинейных преобразований размерности. Это позволило произвести более качественную кластеризацию и улучшило стратегии взаимодействия с клиентами.

6 RFM-сегментация клиентов. Часть III
Построена модель классификации, которая позволила автоматически определять сегмент клиента на основе нескольких транзакций.

## 2. Какой кейс решаем?
Бизнес-задача: произвести сегментацию существующих клиентов, проинтерпретировать эти сегменты и определить стратегию взаимодействия с ними.

Техническая задача: построить модель кластеризации клиентов на основе их покупательской способности, частоты заказов и срока давности последней покупки, определить профиль каждого из кластеров.

## 3. Краткая информация о данных
InvoiceNo — номер счёта-фактуры (уникальный номинальный шестизначный номер, присваиваемый каждой транзакции; буква "C" в начале кода указывает на отмену транзакции);
StockCode — код товара (уникальное пятизначное целое число, присваиваемое каждому отдельному товару);
Description — название товара;
Quantity — количество каждого товара за транзакцию;
InvoiceDate — дата и время выставления счёта/проведения транзакции;
UnitPrice — цена за единицу товара в фунтах стерлингов;
CustomerID — идентификатор клиента (уникальный пятизначный номер, однозначно присваиваемый каждому клиенту);
Country — название страны, в которой проживает клиент.
