# Контрольний список перевірки інструмента

Пройди його разом зі своїм тьютором, перш ніж вважати інструмент завершеним. Біля кожного рядка запиши результат: OK, виправлено або «ще ні: чому».

## Чи він працює?
1. Він робить те, що сказано в його README, з типовими налаштуваннями.
2. Найменші й найбільші значення працюють (наприклад Count 1 і Count 50).
3. Повернутий, переміщений і масштабований актор усе одно працює.
4. Ctrl+Z скасовує те, що він зробив, якщо можна, одним кроком.
5. Те саме зерно двічі дає той самий результат.

## Чи він безпечний?
6. Усе, що перейменовує, переміщує чи видаляє, має пробний запуск (dry run), і цей запуск нічого не змінює.
7. Помилкові вхідні дані дають зрозуміле повідомлення (порожній меш, відсутня таблиця даних, дорога менш ніж із 2 точок), а не збій і не тишу.
8. Він ніколи не зберігає й не видаляє асети без попередження.

## Чи він дешевий?
9. Повторювані елементи інстансуються.
10. Ніщо не використовує Tick, якщо воно насправді не рухається.
11. Кількість інстансів і час кадру до та після використання записано.

## Чи він читабельний?
12. Назви відповідають code-style.md.
13. Налаштування мають Category, підказки й безпечні діапазони.
14. Графи згруповано коментарями; скрипти мають заголовок-коментар.
15. Без магічних чисел.

## Чи його можна імпортувати?
16. Він відповідає standards-sheet.md (масштаб, назви, теки, плагіни, ліцензії).
17. Він працює в чистому проєкті після копіювання лише його теки або плагіна.

## Одне покращення
18. Запиши одну річ, яку варто змінити, якби був ще один день, і чому.

---

## English

# Tool review checklist

Go through this with your tutor before you call a tool finished. Write the result next to each line: OK, fixed, or "not yet: why".

## Does it work?
1. It does what its README says, with the default settings.
2. Smallest and largest settings work (for example Count 1 and Count 50).
3. A rotated, moved and scaled actor still works.
4. Ctrl+Z undoes what it did, in one step if possible.
5. The same seed gives the same result twice.

## Is it safe?
6. Anything that renames, moves or deletes has a dry run, and the dry run changes nothing.
7. Bad input gives a clear message (empty mesh, missing data table, a road with fewer than 2 points), not a crash or silence.
8. It never saves or deletes assets without telling you.

## Is it cheap?
9. Repeated pieces are instanced.
10. Nothing uses Tick unless it really moves.
11. You wrote down instance counts and the frame time before and after using it.

## Is it readable?
12. Names follow code-style.md.
13. Settings have Categories, tooltips and safe ranges.
14. Graphs are grouped with comments; scripts have a header comment.
15. No magic numbers.

## Is it importable?
16. It follows standards-sheet.md (scale, names, folders, plugins, licences).
17. It works in a fresh project after copying only its folder or plugin.

## One improvement
18. Write one thing you would change if you had another day, and why.
