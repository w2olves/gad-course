# Аркуш стандартів: що означає «можна імпортувати»

Користуйся цим аркушем щоразу, коли передаєш інструмент або згенерований район у чужий проєкт. Студія зможе імпортувати твою роботу лише тоді, коли вона дотримується таких правил.

## Рушій і плагіни
- Саме Unreal Engine **5.8**. Назви кожен плагін, потрібний твоїй роботі (наприклад PCG, Water, Editor Scripting Utilities, Python Editor Script Plugin), у своєму README.
- Жодних змін рушія й жодного C++, який треба компілювати, якщо проєкт-одержувач цього не просив.

## Масштаб і розміщення
- Справжній масштаб: **1 одиниця Unreal = 1 см**. Двері приблизно 210 см заввишки, людина приблизно 180 см.
- Опорні точки (pivot) стоять на основі й по центру, окрім стін і плиток набору (там вони в куті сітки).
- Нічого не висить у повітрі й нічого не провалюється: кожен згенерований елемент стоїть на землі або на іншому елементі.
- Коридори польоту лишаються вільними: жоден згенерований елемент не потрапляє в об'єм чи сплайн зони-винятку.

## Назви й теки
- Префікси: `BP_` Blueprint, `EUW_` Editor Utility Widget, `PDA_` Primary Data Asset (бланк), `DA_` Data Asset (заповнений бланк), `S_` структура, `DT_` Data Table, `PCG_` граф PCG, `PCGE_` власний елемент PCG, `MPC_` Material Parameter Collection, `SM_` static mesh, `M_` матеріал, `MI_` екземпляр матеріалу, `T_` текстура, `L_` рівень, `LS_` Level Sequence, `MF_` функція матеріалу, `HLOD_` шар HLOD, `UCX_` форма колізії, зроблена в Blender.
- Усе для одного інструмента лежить в одній теці або в одному плагіні лише з контентом, щоб його можна було скопіювати за один раз.
- Без пробілів і спеціальних символів у назвах асетів; після префікса CamelCase (`BP_TownGenerator`).

## Перевірки мешів (що тестує check_assets.py)
- Розмір: найдовша сторона габаритної рамки меша від **5 см до 50 м**. Менше чи більше зазвичай означає неправильний масштаб імпорту.
- Колізія: щонайменше одна проста форма колізії (box, sphere, capsule або convex), якщо тільки це не декор, якого не можна торкнутися.
- Деталізація: **Nanite увімкнено**, або щонайменше **2 LOD**, коли Nanite вимкнено.
- Текстури: **2048 px** або менше з кожного боку.
- Назви: префікс зі списку вище. Усе, що ти пропускаєш навмисно, потрапляє в список ALLOW у скрипті, а причину ти пишеш у fix_notes.md або у свій звіт перевірки (validation_report.md).

## Продуктивність
- 1920 x 1080: середній час кадру менше 16,6 мс (60 fps), 95-й перцентиль менше 33,3 мс, виміряно вздовж маршруту польоту.
- Повторювані елементи інстансуються. Статичні речі ніколи не використовують Tick.
- Згенерований контент можна запакувати або перетворити на статичний перед випуском.
- Текстури 2048 x 2048 або менше, якщо тільки головному елементу не потрібно більше (поясни чому).

## Ліцензії й подяки
- Лише асети власної роботи, безкоштовні асети, чия ліцензія дозволяє використання в грі, або асети, якими проєкт-одержувач уже володіє.
- Файл `CREDITS.md` перелічує кожен сторонній асет: назва, автор, посилання на джерело, ліцензія.
- Ніколи не додавай платний чи нелегальний контент.
- Паки з Fab за ліцензією Fab Standard License можна використовувати у своєму проєкті, але не можна передавати їхні вихідні файли іншим: не клади їх у ZIP для передачі й у жоден репозиторій, яким ти ділишся з іншими. Запиши їх у `CREDITS.md` і напиши, де отримувачу їх узяти.
- Дані OpenStreetMap мають ліцензію ODbL: у подяках і в кінці відео напиши «© OpenStreetMap contributors» і посилання https://www.openstreetmap.org/copyright.

## Що передати
- Інструмент (тека з контентом або плагін), `README.md` (що він робить, як його встановити, кожне налаштування, відомі обмеження), скриншоти, демовідео на 60 секунд і звіт про продуктивність.
- Тест: установи його в чистий проєкт Unreal 5.8 і запусти один раз, перш ніж передавати.

---

## English

# Standards sheet: what "importable" means

Use this sheet whenever you hand a tool or a generated district to someone else's project. A studio can only import your work if it follows rules like these.

## Engine and plugins
- Unreal Engine **5.8** exactly. Name every plugin your work needs (for example PCG, Water, Editor Scripting Utilities, Python Editor Script Plugin) in your README.
- No engine changes, no C++ that needs compiling, unless the receiving project asked for it.

## Scale and placement
- Real scale: **1 Unreal unit = 1 cm**. A door is about 210 cm tall; a person about 180 cm.
- Pivots at the base, centred unless the piece is a wall or kit tile (then at a grid corner).
- Nothing floating, nothing sinking: every generated piece is placed on the ground or on another piece.
- Flight corridors stay clear: no generated piece inside a keep-out volume or spline.

## Names and folders
- Prefixes: `BP_` Blueprint, `EUW_` Editor Utility Widget, `PDA_` Primary Data Asset (the form), `DA_` Data Asset (a filled-in form), `S_` structure, `DT_` Data Table, `PCG_` PCG graph, `PCGE_` custom PCG element, `MPC_` Material Parameter Collection, `SM_` static mesh, `M_` material, `MI_` material instance, `T_` texture, `L_` level, `LS_` Level Sequence, `MF_` material function, `HLOD_` HLOD layer, `UCX_` collision shape made in Blender.
- Everything for one tool lives in one folder or one content-only plugin, so it can be copied in one go.
- No spaces or special characters in asset names; CamelCase after the prefix (`BP_TownGenerator`).

## Mesh checks (what check_assets.py tests)
- Size: the largest side of a mesh's bounding box is between **5 cm and 50 m**. Smaller or larger usually means a wrong import scale.
- Collision: at least one simple collision shape (box, sphere, capsule or convex), unless the piece is decoration you can never touch.
- Detail: **Nanite on**, or at least **2 LODs** when Nanite is off.
- Textures: **2048 px** or smaller on each side.
- Names: a prefix from the list above. Anything you skip on purpose goes in the script's ALLOW list, and you write the reason in fix_notes.md or your validation report (validation_report.md).

## Performance
- 1920 x 1080: average frame time under 16.6 ms (60 fps), 95th percentile under 33.3 ms, measured along a flight route.
- Repeated pieces are instanced. Static things never use Tick.
- Generated content can be packed or converted to static before shipping.
- Textures 2048 x 2048 or smaller unless a hero piece needs more (say why).

## Licences and credits
- Only assets you made, free assets whose licence allows use in a game, or assets the receiving project already owns.
- A `CREDITS.md` lists every outside asset: name, author, source link, licence.
- Never include paid or unlicensed content.
- Fab packs under the Fab Standard License may be used in your project, but their source files may not be passed on: keep them out of the hand-over zip and out of any repository you share with others. List them in `CREDITS.md` and say where the receiver can get them.
- OpenStreetMap data is under the ODbL licence: in the credits and at the end of the video write "© OpenStreetMap contributors" with the link https://www.openstreetmap.org/copyright.

## What to hand over
- The tool (content folder or plugin), a `README.md` (what it does, how to install it, every setting, known limits), screenshots, a 60-second demo video, and the performance report.
- A test: install it in a fresh Unreal 5.8 project and run it once before you hand it over.
