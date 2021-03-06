# Оптимизатор боёвки в настольно-ролевых играх

## Цель: 
🎲 Есть большое количество различных механик в настольно-ролевых игр, основанных на бросании костей (с 4, 6, 8, 10, 12 и 20 сторонами). В идеале игроку хочется иметь максимально сильного персонажа, чтобы чувствовать себя лучше, а мастеру нужно уметь оценить, как долго будет идти бой, насколько сложное это сражение. Всё это в строгом смысле слова основывается на аппарате теории вероятностей (мат ожидание, среднее значение), хочется иметь относительно универсальный инструмент, позволяющий оптимизировать процесс анализа бросков кубов/модификаторов. 🎲

## Задачи:

- [ ] Ввод кубиков, подсчёт среднего значения суммы кубов
- [ ] Short notation запись для введённых кубиков (Пример: 2d6 + 1d8)
- [ ] Вероятность выпадения величин >= x, <= x
- [ ] Добавить механику добрасывания кубов (перебрасывание первых k значений, броски с помехой/преимуществом)
- [ ] Ввод персонажей/врагов
- [ ] Мат ожидание урона за 1 атаку по врагу
- [ ] Мат ожидание урона за 1 раунд по врагу
- [ ] Расчёт "кто победит в сражении"? - и за сколько раундов

## Не основные задачи:

- [ ] Графики
- [ ] Расширение для механики НРИ Ведьмак (TRPG Witcher)
- [ ] Добавить при расчёте сражения группы персонажей
- [ ] Добавить при расчёте сражения возможность восстанавливать здоровье
