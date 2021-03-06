# Изучение поведения пользователей приложения для продажи продуктов питания

<b>Цель проекта:</b>
Необходимо разобраться, как ведут себя пользователи мобильного приложения, изучить воронку продаж. Исследовать результаты A/A/B-эксперимента.

<b>Выводы исследования:</b>
- количество уникальных пользователей - 7551 человек
- примерно 20 событий приходится на одного пользователя
- в логи заносится 5 событий, самым популярным из которых является MainScreenAppear (главный экран), наименее популярным - Tutorial (обучение)
- наиболее полные данные представлены за первую неделю августа - с 1 августа по 7 августа 2019 года
- последовательность действий пользователя (цепочка выглядит как MainScreenAppear (главный экран) > OffersScreenAppear (экран предложения) > CartScreenAppear (корзина) > PaymentScreenSuccessful (страница успешной оплаты))
- на втором шаге воронки (MainScreenAppear > OffersScreenAppear) теряем больше всего пользователей
- до PaymentScreenSuccessful доходит не более 50% пользователей приложения
- результаты А-А/Б - тестирования показали, что новые шрифты, которые показывали пользователям из экспериментальной группы,  не повлияли на поведение пользователей внутри приложения и доля пользователей, совершивших покупки, осталась практически без изменений.

<b>Рекомендации:</b>

Так как изменение шрифта не оказало значимого эффекта на поведение пользователей, то его можно заменить

<b>Стек:</b>
numpy, pandas, matplotlib.pyplot, seaborn, plotly, datetime, math, scipy
