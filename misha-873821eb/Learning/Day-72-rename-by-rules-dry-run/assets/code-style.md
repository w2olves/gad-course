# Стиль коду для Blueprint і Python

Інструменти читають набагато частіше, ніж пишуть. Ці правила роблять твій код зрозумілим тобі за місяць і будь-кому вже сьогодні.

## Назви
- Змінні кажуть, що вони містять: `Count`, `Spacing`, `Seed`, `RoadWidth`, а не `A`, `Num2`, `Temp`.
- Булеві змінні читаються як запитання «так/ні»: `Has Shop`, `Is Night` (Blueprint) або `has_shop`, `is_night` (Python).
- Функції починаються з дієслова: `BuildRow`, `ClearAll`, `PickStyle` (Blueprint); `rename_assets`, `read_csv` (Python).
- Файли, функції та змінні Python пишуться в стилі lower_case_with_underscores; налаштування, які можна міняти, стоять угорі ВЕЛИКИМИ літерами (`DRY_RUN`, `FOLDER`, `MAX_TEXTURE`).
- Асети Blueprint мають свій префікс і CamelCase: `BP_` Blueprint, `PDA_` Primary Data Asset, `DA_` Data Asset, `S_` структура, `DT_` Data Table, `EUW_` Editor Utility Widget (повний список у standards-sheet.md).

## Blueprint
- Кожне налаштування інструмента має Instance Editable, Category (наприклад Tool, Layout, Variety), підказку (tooltip) і безпечний Value Range.
- Групуй вузли коментарями (виділи вузли, натисни C) і одним рядком пиши, що робить кожна група.
- Тримай дроти короткими й прямими; замість довгих дротів, що перетинаються, використовуй вузли reroute (подвійний клік по дроту).
- Повторювані ланцюжки вузлів виноси в функцію. Якщо граф не вміщується на одному екрані, розділи його.
- Без Tick для речей, що не рухаються. Для інструментів редактора віддавай перевагу Construction Script або кнопці (Call In Editor).

## Python
- Починай кожен скрипт із заголовка в 3 рядки коментарів:
  ```python
  # place_from_csv.py: places props from a CSV around a selected anchor.
  # Run: select the anchor, then File > Execute Python Script.
  # Changes the level: yes, in one undo step (set DRY_RUN = True to only print the plan).
  ```
- Усе, що перейменовує, переміщує чи видаляє, має угорі перемикач `DRY_RUN = True`, який лише виводить, що сталося б.
- Загортай зміни рівня в один `unreal.ScopedEditorTransaction("Description")`, щоб один Ctrl+Z скасовував їх.
- Виводь зрозумілі повідомлення: що зроблено, скільки елементів, що пропущено і чому.
- Без «магічних чисел»: давай їм імена вгорі (`MAX_TEXTURE = 2048`).

## Зерно й різноманітність
- Кожен генератор має налаштування `Seed`; те саме зерно завжди дає той самий результат.
- Використовуй Random Stream (Blueprint) або `random.Random(seed)` (Python), ніколи вузли чи функції випадковості без зерна.

## Перш ніж вважати роботу завершеною
- Протестуй найменші й найбільші значення налаштувань, повернутий актор і скасування дії.
- Прочитай власний граф або скрипт один раз згори донизу так, ніби бачиш його вперше.

---

## English

# Code style for Blueprints and Python

Tools are read far more often than they are written. These rules keep yours readable by you in a month and by anyone else today.

## Names
- Variables say what they hold: `Count`, `Spacing`, `Seed`, `RoadWidth`, not `A`, `Num2`, `Temp`.
- Booleans read as a yes/no question: `Has Shop`, `Is Night` (Blueprint) or `has_shop`, `is_night` (Python).
- Functions start with a verb: `BuildRow`, `ClearAll`, `PickStyle` (Blueprint); `rename_assets`, `read_csv` (Python).
- Python files, functions and variables use lower_case_with_underscores; settings you may change sit at the top in CAPITALS (`DRY_RUN`, `FOLDER`, `MAX_TEXTURE`).
- Blueprint assets use their prefix plus CamelCase: `BP_` Blueprint, `PDA_` Primary Data Asset, `DA_` Data Asset, `S_` structure, `DT_` Data Table, `EUW_` Editor Utility Widget (the full list is in standards-sheet.md).

## Blueprints
- Every tool setting is Instance Editable, has a Category (for example Tool, Layout, Variety) and a tooltip, and a safe Value Range.
- Group nodes with comment boxes (select nodes, press C) and write what each group does in one line.
- Keep wires short and straight; use reroute nodes (double-click a wire) instead of long crossing wires.
- Move repeated node chains into a function. If a graph does not fit on one screen, split it.
- No Tick for things that do not move. Prefer the Construction Script or a button (Call In Editor) for editor tools.

## Python
- Start every script with a 3-line comment header:
  ```python
  # place_from_csv.py: places props from a CSV around a selected anchor.
  # Run: select the anchor, then File > Execute Python Script.
  # Changes the level: yes, in one undo step (set DRY_RUN = True to only print the plan).
  ```
- Anything that renames, moves or deletes has a `DRY_RUN = True` switch at the top that only prints what would happen.
- Wrap changes to the level in one `unreal.ScopedEditorTransaction("Description")`, so one Ctrl+Z undoes them.
- Print clear messages: what was done, how many items, and anything skipped and why.
- No magic numbers: name them at the top (`MAX_TEXTURE = 2048`).

## Seeds and variety
- Every generator has a `Seed` setting; the same seed always gives the same result.
- Use a Random Stream (Blueprint) or `random.Random(seed)` (Python), never the unseeded random nodes or functions.

## Before you call it done
- Test the smallest and largest settings, a rotated actor, and undo.
- Read your own graph or script once from top to bottom as if you had never seen it.
