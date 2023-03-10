# Исследование надежности заемщиков

**Описание:**

Исследование, направленное на вычисление факторов влияния на возврат кредита в срок заёмщиками.

Результаты исследования предполагается учесть в модели кредитного скоринга.

**Цель:** 

Выяснить, существует ли зависимость между принадлежностью клиентов к определённой категории и их способностью возврата кредита в срок.

**Описание данных:**

Входные данные от банка — статистика о платёжеспособности клиентов.

- children — количество детей в семье

- days_employed — общий трудовой стаж в днях

- dob_years — возраст клиента в годах

- education — уровень образования клиента

- education_id — идентификатор уровня образования

- family_status — семейное положение

- family_status_id — идентификатор семейного положения

- gender — пол клиента

- income_type — тип занятости

- debt — имел ли задолженность по возврату кредитов

- total_income — ежемесячный доход

- purpose — цель получения кредита

**План работы:**

1. Изучить общую информацию о данных.


2. Предобработка данных:

2.1 Удаление пропусков

2.2 Обработка аномальных значений

2.3 Удаление пропусков(продолжение)

2.4 Изменение типов данных

2.5 Обработка дубликатов

2.6 Категоризация данных

3. Исследование данных и ответы на вопросы:

3.1 Зависимость между количеством детей и возвратом кредита в срок

3.2 Зависимость между семейным положением и возвратом кредита в срок

3.3 Зависимость между уровнем дохода и возвратом кредита в срок

3.4 Как разные цели кредита влияют на его возврат в срок

4. Общий вывод

## Используемые библиотеки

pandas