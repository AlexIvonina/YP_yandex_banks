# YP_yandex_banks
# Банки (Предобработка данных) Исследование надежности заемщиков.

---
Второй проект  в ЯПрактикум.

---

Заказчик — кредитный отдел банка. 
В ходе работы нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок.

Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

**Цель исследования**
Входные данные от банка — статистика о платёжеспособности клиентов. На их основе мы ответим на следующие вопросы:
1. Есть ли зависимость между количеством детей и возвратом кредита в срок?
2. Есть ли зависимость между семейным положением и возвратом кредита в срок?
3. Есть ли зависимость между уровнем дохода и возвратом кредита в срок?
4. Как разные цели кредита влияют на его возврат в срок?

**Ход исследования**

Данные о поведении пользователей мы получаем из файла `/datasets/data.csv`. О качестве данных ничего не известно. Поэтому перед проверкой гипотез понадобится обзор данных. 

Мы проверим данные на ошибки и оценим их влияние на исследование. Затем, на этапе предобработки мы поищем возможность исправить самые критичные ошибки данных.
 
Таким образом, исследование пройдёт в три этапа:
 1. [Обзор данных.](#explore) 
 2. [Предобработка данных.](#preprocessing)
 3. [Ответы на вопросы и выводы.](#conclusion)
