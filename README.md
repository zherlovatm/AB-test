### Анализ гипотез, проведение А/В теста
### Задача:
Приоритизировать гипотезы, запустить A/B-тест и проанализируйте результат с целью увеличения выручки интернет-магазина

### Библиотеки:
pandas, numpy, matplotlib, scipy.stats

### Вывод:
есть статистически значимые различия по конверсии между группами и по «сырым» (В больше А на 13,8%), и по данным после фильтрации аномалий (В больше А на 18,8%)
по графику различия конверсий между группами также видно, что конверсия группы В больше группы А на 10-20%
нет статистически значимого различия по среднему чеку между группами ни по «сырым», ни по данным после фильтрации аномалий, по очищенным данным средний чек группы В больше среднего чека группы А на 5,8%
график среднего чека неравномерен, бывают периоды когда группа В превышает группу А, а бывает наоборот. Во второй половине исследуемого периода, средний чек группы В значительно выше среднего чека группы А, но данная разница сокращается
т.к. данные по конверсии показывают преимущество группы В, а средний чек на данный момент - не показывает значительного преимущества группы В, я бы рекомендовала продолжть тест. Если же основной целью тестирования была проверка показателя конверсии - то данный тест можно остановить, и зафиксировать победу группы В
проверяя приоритезацию гипотез методами ICE и RICE были обнаружены различия в результатах. Т.к. метод RICE учитывает дополнительную важную характеристику - охват пользователей, данные полученные этим фрэймворком я считаю более достоверными: приоритетна гипотеза №7 "Добавить форму подписки на все основные страницы".
