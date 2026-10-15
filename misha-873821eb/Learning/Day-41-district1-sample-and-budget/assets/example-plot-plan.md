# Приклад плану ділянки: район 1, набережна 200 x 200 м

Вигаданий приклад плану, за яким можна будувати, написаний так, як мають бути написані твої `plot_plan_d1.md` і `plot_plan_d2.md`. Твій план має ще й картинку (`plot_plan_d1.png`, 800 x 800 px, 4 px = 1 м); тут картинку описано словами.

## Ділянка

- 200 x 200 м навколо гавані вигаданого острова: район 1, набережна, сучасність.
- Метри острова (з твого `map_notes.md`): початок координат у північно-західному куті карти island_map, X росте на схід, Y росте на південь. Кути ділянки: (800, 900), (1000, 900), (1000, 1100), (800, 1100).
- Майданчик запуску 10 x 10 м: центр (770, 1000), на захід від ділянки. Мальовничий маршрут заходить у район із заходу, в точці (800, 1000).

## Що показує plot_plan_d1.png

- Стрілка півночі (угору) і масштабна лінійка 50 м (200 px).
- Контур ділянки й сітка 10 м, яку видно, поки малюєш; метри острова підписано в кутах і кожні 50 м.
- Шари: base, water and shore, roads and paving, buildings, planting, furniture, lanes, cameras, labels.
- Море вздовж південного боку; прямий край набережної на y = 1060 (її збудовано людьми, тож він може бути прямим). Берег на захід від набережної ламаний і нерівний, бо обходить каміння (природний, тож ніколи не прямий).
- Портова дорога вздовж y = 1010 і доріжка-набережна завширшки близько 16 м між магазинами й краєм води.
- Будівлі як підписані прямокутники: чотири портові будинки на півночі, три фасади магазинів уздовж набережної.
- Пірс, що йде від набережної на південь у воду, з поруччям з обох боків.
- Групи насаджень як кола з видом і кількістю; голий камінь і суха трава лишаються відкритими.
- Два коридори для дрона як підписані смуги з висотами (не вужчі за 4 x 4 м); п'ять стрілок камер C1-C5, кожна з висотою й головним фото (hero photo), яке вона повторює.

## Таблиця

| Елемент | Кількість | Де (метри острова) | Крок або щільність | Джерело |
|---|---|---|---|---|
| Край набережної | 120 м (30 деталей) | від (840, 1060) до (960, 1060) | деталі по 4 м встик | твій набір: SM_QuayEdge_4m |
| Пірс | 10 секцій (40 м) | від (900, 1060) до (900, 1100) | секції по 4 м встик | твій набір: SM_PierDeck_4m |
| Поруччя пірса | 40 деталей (80 м) | обидва боки пірса, x 898 і 902 | деталі по 2 м | твій набір: SM_Railing_2m |
| Портова дорога | 1, 200 м завдовжки, 6 м завширшки | від (800, 1010) до (1000, 1010) | - | твоя SM_RoadStrip_8m як сплайн-меш |
| Причальні тумби | 12 | уздовж краю набережної, y 1058, x від 845 до 955 | кожні 10 м | твоя SM_Bollard |
| Лавки | 10 | набережна, y 1052, x від 830 до 965, обличчям до моря | кожні 15 м | твоя SM_Bench |
| Смітники | 5 | біля кожної другої лавки | - | твоя SM_Bin |
| Ліхтарі | 9 | набережна, y 1045, x від 830 до 970 | кожні 17,5 м | твоя SM_LampPost |
| Фасади магазинів із навісами | 3 | ряд на y 1030, x 850, 862 і 874, обличчям на південь | через 12 м | твій набір: SM_ShopFront_A із SM_Awning_A |
| Столи й стільці кафе | 6 комплектів | перед фасадами магазинів, x від 850 до 876, y 1040 | - | знайти на Дні 24 (безкоштовного паку немає: grey-box заміна) |
| Портові будинки | 4 | північніше дороги, y 985, x 830, 870, 910 і 950 | через 40 м | твій LI_HarbourHouse (День 10) |
| Човни-скіфи | 3 | причал 1 (865, 1063), причал 2 (880, 1063), причал 3 (925, 1063) | - | зроблено мною на Дні 43: SM_Skiff_5m |
| Навігаційні буї | 2 | по одному з кожного боку входу в гавань: (830, 1096) і (970, 1096) | - | безкоштовний пак: Lateral Navigation Buoy |
| Вуличні дерева | 5 | уздовж північного краю набережної, y 1041, x від 885 до 965, не в одну лінію | через 10-20 м | безкоштовний пак: зразок Free Nanite Plants |
| Групи чагарників | 6 груп по 5-9 кущів | за портовими будинками, y від 950 до 975 | 1 кущ на 1,5 м, ніколи не рядами | безкоштовний пак: Free Shrubs Pack |
| Камені | 10 | вздовж західного краю, x від 800 до 815, y від 1045 до 1100, нерівно | - | Free Sample Realistic Rock Set (Ancraite) або Megascans Limestone Rocks |

## Коридори для дрона

- Коридор A: заходить із заходу в точці (800, 1000), іде на схід уздовж портової дороги, висота 8 м, ширина 8 м; з початку коридору видно каплицю на пагорбі поза ділянкою, у точці (1040, 880).
- Коридор B: уздовж краю набережної із заходу на схід, висота 10 м, ширина 5 м, подалі від голів ліхтарів і крон дерев.

## Камери

- C1: підхід з моря, на висоті 20 м, погляд на північ на набережну й фасади магазинів; повторює 03_harbour_from_sea.jpg.
- C2: будівлі, на висоті 12 м над дорогою, погляд на фасади магазинів і портові будинки; повторює 06_shop_fronts.jpg.
- C3: головна окраса, пірс зі скіфами, на висоті 6 м; повторює 07_pier_boats.jpg.
- C4: широкий, на висоті 40 м над північно-західним кутом, погляд на південний схід; повторює 01_aerial_harbour.jpg.
- C5: близько до землі біля краю набережної: тумби й соляна лінія, на висоті 2 м; повторює 02_quay.jpg.

## Записана помилка

У першій побудові скіф на причалі 2 стояв на каменях набережної, а не у воді. У таблиці було «причал 2», але човен розмістили на око. Скріншот видом зверху, накладений на plot_plan_d1.png, впіймав би це за секунди. Виправлення: розміщуй кожен елемент за введеними координатами (метри острова x 100 = Location у сантиметрах), потім перевір вид зверху поверх плану.

## Перевірка за правилами

- Лише сучасність: так.
- Речі там, де їх ставлять фото: так (тумби вздовж краю набережної, лавки обличчям до моря, скіфи біля причалів, як на 4 головних фото).
- Жодних прямих ліній у природі: західний берег ламаний, чагарники, дерева й каміння нерівні; край набережної, пірс і дорога прямі, бо їх збудували люди.
- Відкрите питання: чи ставити дерева рядом? Вирішено: ні, через 10-20 м і зі зсувом, бо фото 05_promenade.jpg показує нерівний крок.

## Журнал змін

- День 23: накреслено план r1.
- День 25: після перевірки з тьютором коридор B зсунуто на 2 м на південь, подалі від голів ліхтарів; лавки повернуто на 10 градусів до моря.

---

## English

# Example plot plan: district 1, a 200 x 200 m waterfront

A made-up example of a buildable plan, written the way your own `plot_plan_d1.md` and `plot_plan_d2.md` should be. Your plan also has a picture (`plot_plan_d1.png`, 800 x 800 px, 4 px = 1 m); here the picture is described in words.

## The plot

- 200 x 200 m around the harbour of a made-up island: district 1, the waterfront, present day.
- Island metres (from your `map_notes.md`): origin at the north-west corner of the island_map, X grows east, Y grows south. Plot corners (800, 900), (1000, 900), (1000, 1100), (800, 1100).
- Launch pad 10 x 10 m: centre (770, 1000), west of the plot. The scenic route enters the district from the west, at (800, 1000).

## What plot_plan_d1.png shows

- North arrow (up) and a 50 m scale bar (200 px).
- The plot outline and a 10 m grid that you see while you draw; island metres written at the corners and every 50 m.
- Layers: base, water and shore, roads and paving, buildings, planting, furniture, lanes, cameras, labels.
- The sea along the south side; a straight quay edge at y = 1060 (people built it, so it may be straight). The shore west of the quay is a broken, irregular line that goes round rocks (natural, so never straight).
- The harbour road along y = 1010 and a promenade about 16 m wide between the shops and the water's edge.
- Buildings as labelled boxes: four harbour houses in the north, three shop fronts along the promenade.
- A pier running south from the quay into the water, with a railing on both sides.
- Planting groups as circles with kind and count; bare rock and dry grass left open.
- Two drone lanes as labelled bands with heights (no narrower than 4 x 4 m); five camera arrows C1 to C5, each with its height and the hero photo it matches.

## Table

| Item | Count | Where (island metres) | Spacing or density | Source |
|---|---|---|---|---|
| Quay edge | 120 m (30 pieces) | from (840, 1060) to (960, 1060) | 4 m pieces end to end | your own kit: SM_QuayEdge_4m |
| Pier | 10 sections (40 m) | from (900, 1060) to (900, 1100) | 4 m sections end to end | your own kit: SM_PierDeck_4m |
| Pier railing | 40 pieces (80 m) | both sides of the pier, x 898 and 902 | 2 m pieces | your own kit: SM_Railing_2m |
| Harbour road | 1, 200 m long, 6 m wide | from (800, 1010) to (1000, 1010) | - | your SM_RoadStrip_8m as a spline mesh |
| Mooring bollards | 12 | along the quay edge, y 1058, x 845 to 955 | every 10 m | your own SM_Bollard |
| Benches | 10 | promenade, y 1052, x 830 to 965, facing the sea | every 15 m | your own SM_Bench |
| Bins | 5 | beside every second bench | - | your own SM_Bin |
| Lamp posts | 9 | promenade, y 1045, x 830 to 970 | every 17.5 m | your own SM_LampPost |
| Shop fronts with awnings | 3 | a row at y 1030, x 850, 862 and 874, facing south | 12 m apart | your own kit: SM_ShopFront_A with SM_Awning_A |
| Café tables and chairs | 6 sets | in front of the shop fronts, x 850 to 876, y 1040 | - | find on Day 24 (no free pack covers them: a grey-box stand-in) |
| Harbour houses | 4 | north of the road, y 985, x 830, 870, 910 and 950 | 40 m apart | your LI_HarbourHouse (Day 10) |
| Skiffs | 3 | berth 1 (865, 1063), berth 2 (880, 1063), berth 3 (925, 1063) | - | made by me on Day 43: SM_Skiff_5m |
| Navigation buoys | 2 | one on each side of the harbour mouth: (830, 1096) and (970, 1096) | - | free pack: Lateral Navigation Buoy |
| Street trees | 5 | along the promenade's north edge, y 1041, x 885 to 965, not in a line | 10 to 20 m apart | free pack: Free Nanite Plants sample |
| Scrub groups | 6 groups of 5 to 9 shrubs | behind the harbour houses, y 950 to 975 | 1 shrub per 1.5 m, never in rows | free pack: Free Shrubs Pack |
| Rocks | 10 | along the west edge, x 800 to 815, y 1045 to 1100, irregular | - | Free Sample Realistic Rock Set (Ancraite) or Megascans Limestone Rocks |

## Drone lanes

- Lane A: enters from the west at (800, 1000) and runs east along the harbour road, 8 m high, 8 m wide; from its start you can see the hill-top chapel outside the plot, at (1040, 880).
- Lane B: along the quay edge from west to east, 10 m high, 5 m wide, clear of the lamp heads and the tree crowns.

## Cameras

- C1: the approach from the sea, 20 m up, looking north at the quay and the shop fronts; matches 03_harbour_from_sea.jpg.
- C2: the buildings, 12 m up over the road, looking at the shop fronts and the harbour houses; matches 06_shop_fronts.jpg.
- C3: the main feature, the pier with its skiffs, 6 m up; matches 07_pier_boats.jpg.
- C4: wide, 40 m up over the north-west corner, looking south-east; matches 01_aerial_harbour.jpg.
- C5: close on the ground at the quay edge: the bollards and the salt line, 2 m up; matches 02_quay.jpg.

## The recorded fault

In the first build the skiff at berth 2 sat on the quay stones, not in the water. The table said "berth 2", but the boat was placed by eye. A top-view screenshot laid over plot_plan_d1.png would have caught it in seconds. Fix: place every item by its typed coordinates (island metres x 100 = Location in centimetres), then check a top view over the plan.

## Rules check

- Present day only: yes.
- Things where the photos put them: yes (bollards along the quay edge, benches facing the sea, skiffs at their berths, as in 4 hero photos).
- No straight lines in nature: the west shore is broken, scrub, trees and rocks irregular; the quay edge, pier and road are straight because people built them.
- Open question: should the trees stand in a row? Settled: no, 10 to 20 m apart and offset, because photo 05_promenade.jpg shows uneven spacing.

## Change log

- Day 23: plan r1 drawn.
- Day 25: after the review with the tutor, lane B moved 2 m south, clear of the lamp heads; benches turned 10 degrees toward the sea.
