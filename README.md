# Оптимизатор боёвки в настольно-ролевых играх

## Цель: 
🎲 Есть большое количество различных механик в настольно-ролевых игр, основанных на бросании костей (с 4, 6, 8, 10, 12 и 20 сторонами). В идеале игроку хочется иметь максимально сильного персонажа, чтобы чувствовать себя лучше, а мастеру нужно уметь оценить, как долго будет идти бой, насколько сложное это сражение. Всё это в строгом смысле слова основывается на аппарате теории вероятностей (мат ожидание, среднее значение), хочется иметь относительно универсальный инструмент, позволяющий оптимизировать процесс анализа бросков кубов/модификаторов. 🎲

## Задачи:

- [x] Ввод кубиков, подсчёт среднего значения суммы кубов
- [x] Short notation запись для введённых кубиков (Пример: 2d6 + 1d8)
- [x] Добавить модификаторы
- [x] Максимальная сумма на кубах
- [x] Вероятность выпадения величин >= x, <= x, = x (+ массив возможных исходов)
- [x] Добавить механику добрасывания кубов (перебрасывание первых k значений, броски с помехой/преимуществом)
- [ ] Ввод персонажей/врагов
- [ ] Мат ожидание урона за 1 атаку по врагу при фиксированном AC
- [x] Добавить подробный help

## Не основные задачи:

- [x] Графики
- [ ] Расширение для механики НРИ Ведьмак (TRPG Witcher) - "взрывающиеся" кубы
- [ ] Добавить процентили

## Баги, которые надо пофиксить (не баг, а фича):

- [x] Разнести код по кодстайлу
- [x] В numpy array нет лонгинта питоновского, а количество исходов при подсчёте вероятности растёт очень быстро, из-за чего крашится на тестах :(
- [x] Вынести общие функции из класса
- [ ] Дописать общие функции для вероятность выпадения >=, ==, <=
- [ ] Добавить комментарии (а надо ли?)
