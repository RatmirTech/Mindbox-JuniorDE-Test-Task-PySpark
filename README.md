# Mindbox-JuniorDE-Test-Task-PySpark

Тестовое задание на позицию Junior Data Engineer в ООО Mindbox (задание 2 на PySpark).

---

## Задание

В PySpark приложении датафреймами (`pyspark.sql.DataFrame`) заданы продукты, категории и их связи.  
Каждому продукту может соответствовать несколько категорий или ни одной.  
А каждой категории может соответствовать несколько продуктов или ни одного.

**Требуется:**  
Написать метод на PySpark, который в одном датафрейме вернёт все пары  
«Имя продукта – Имя категории» и имена всех продуктов, у которых нет категорий.

---

## Реализация

- Решение оформлено в Jupyter Notebook (`ProductCategoryNotebook.ipynb`) для удобства.
- Для демонстрации работы добавлены несколько CSV-файлов:
  - `products.csv` — список продуктов
  - `categories.csv` — список категорий
  - `product_categories.csv` — связи между продуктами и категориями

---