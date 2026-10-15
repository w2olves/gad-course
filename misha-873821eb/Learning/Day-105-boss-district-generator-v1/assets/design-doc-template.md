# Проєктний документ: <назва твого інструмента>

Заповни кожен розділ простими словами. Достатньо однієї сторінки; допоможе ескіз або скриншот.

## 1. Що він робить (два речення)
<Наприклад: "Будує район міста 200 x 200 м за схемою доріг, набором правил і зерном. Тримає коридори польоту вільними й дає 60 fps.">

## 2. Вхідні дані
| Вхід | Тип | Приклад | Звідки береться |
|---|---|---|---|
| Road layout (схема доріг) | CSV або Data Asset | road-layout.csv | Обведено з фрагмента мапи |
| Rules (правила) | Data Assets / Data Table | DT_StreetMix | Зроблено мною |
| Seed (зерно) | Ціле число | 42 | Задається в Details |

## 3. Вихідні дані
<Що з'являється на рівні: дороги, ділянки, будівлі, пропси, рослинність. Приблизна кількість інстансів.>

## 4. Як це працює (кроки)
1. <Прочитати вхідні дані>
2. <Побудувати дороги>
3. <Створити ділянки>
4. <Розставити будівлі>
5. <Оздобити через PCG>
6. <Перевірка: зони-винятки вільні, ніщо не висить у повітрі>

## 5. Налаштування, які може міняти користувач
| Налаштування | Діапазон | Типове значення | Що воно змінює |
|---|---|---|---|

## 6. Обмеження й ризики
<Чого він ще не вміє; що може бути повільним; що може зламатися.>

## 7. Віхи
| День | Віха | Як я перевіряю |
|---|---|---|

## 8. Стандарти, яких треба дотримати
Дотримуйся standards-sheet.md. Перелічи все, чого ще не можеш виконати, і свій план щодо цього.

## 9. «Готово» означає
<Точний доказ: скриншоти, відео, звіт про продуктивність, успішна перевірка скриптом, тест установки в чистий проєкт.>

---

## English

# Design document: <your tool's name>

Fill in every section in plain words. One page is enough; a sketch or screenshot helps.

## 1. What it does (two sentences)
<For example: "Builds a 200 x 200 m town district from a road layout, a rule set and a seed. It keeps flight corridors clear and holds 60 fps.">

## 2. Inputs
| Input | Type | Example | Where it comes from |
|---|---|---|---|
| Road layout | CSV or Data Asset | road-layout.csv | Traced from the map extract |
| Rules | Data Assets / Data Table | DT_StreetMix | Made by me |
| Seed | Integer | 42 | Set in Details |

## 3. Outputs
<What appears in the level: roads, plots, buildings, props, vegetation. How many instances roughly.>

## 4. How it works (steps)
1. <Read inputs>
2. <Build roads>
3. <Make plots>
4. <Place buildings>
5. <Dress with PCG>
6. <Check: keep-outs clear, nothing floating>

## 5. Settings the user can change
| Setting | Range | Default | What it changes |
|---|---|---|---|

## 6. Limits and risks
<What it cannot do yet; what might be slow; what could break.>

## 7. Milestones
| Day | Milestone | How I check it |
|---|---|---|

## 8. Standards to meet
Follow standards-sheet.md. List anything you cannot meet yet and your plan for it.

## 9. Done means
<The exact proof: screenshots, the video, the performance report, the checker passing, the fresh-project install test.>
