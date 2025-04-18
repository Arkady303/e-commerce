# Кейс – E-Commerce

Этот проект посвящен анализу данных в сфере e-commerce.

Работа выполнена на *Python* с использованием *Jupyter Notebook*.

---

## Задачи проекта

- Определить количество пользователей, которые совершили только одну покупку.
- Рассчитать среднее число недоставленных заказов в месяц и определить причины их отмены.
- Выявить, в какой день недели чаще всего покупают каждый из товаров.
- Рассчитать среднее количество покупок в неделю для каждого пользователя (по месяцам).
- Провести когортный анализ пользователей с января по декабрь и определить когорту с наибольшим retention на третий месяц.
- Используя *Python*, выполнить RFM-сегментацию пользователей для оценки аудитории.

---

## Описание данных

### `olist_customers_datase.csv` – информация о пользователях

| Поле | Описание |
|------|----------|
| customer_id | Идентификатор пользователя для конкретного заказа |
| customer_unique_id | Уникальный идентификатор пользователя |
| customer_zip_code_prefix | Почтовый индекс пользователя |
| customer_city | Город доставки |
| customer_state | Штат доставки |

### `olist_orders_dataset.csv` – информация о заказах

| Поле | Описание |
|------|----------|
| order_id | Уникальный идентификатор заказа |
| customer_id | Идентификатор пользователя для конкретного заказа |
| order_status | Статус заказа (создан, подтверждён, доставлен и т. д.) |
| order_purchase_timestamp | Дата создания заказа |
| order_approved_at | Дата подтверждения оплаты |
| order_delivered_carrier_date | Дата передачи заказа логистической службе |
| order_delivered_customer_date | Дата доставки заказа пользователю |
| order_estimated_delivery_date | Ожидаемая дата доставки |

### `olist_order_items_dataset.csv` – данные о товарных позициях

| Поле | Описание |
|------|----------|
| order_id | Уникальный идентификатор заказа |
| order_item_id | Идентификатор товара в заказе |
| product_id | Уникальный идентификатор товара |
| seller_id | Уникальный идентификатор продавца |
| shipping_limit_date | Крайний срок отправки заказа продавцом |
| price | Цена за единицу товара |
| freight_value | Стоимость доставки |

---

## Реализация проекта

- Проведел предварительный анализ данных и их предобработку.
- Использовал *API* для загрузки датасетов.
- Исследовал поведение пользователей и эффективность доставки.
- Проведел когортный анализ пользователей.
- Выполнил *RFM-сегментацию* пользователей для оценки их ценности.
