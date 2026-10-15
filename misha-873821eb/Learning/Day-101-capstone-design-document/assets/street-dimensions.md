# Розміри вулиць: справжні виміри для твоїх правил

Справжні вулиці підпорядковуються мірам, які люди перевіряли довгий час. Якщо твій генератор їх використовує, місто виглядає правильно і з землі, і з дрона. У кожному рядку є **справжній діапазон**, **число, яке використовує курс**, і джерело діапазону. Справжні правила різняться між країнами й містами, тож сприймай ці числа як добрі початкові значення, а не як закон.

1 одиниця Unreal = 1 см, тож 3.5 м = 350 одиниць.

## Переріз дороги (дні 81, 85, 86)
| Частина | Справжній діапазон | Значення курсу | Джерело |
|---|---|---|---|
| Смуга руху | приблизно від 3.0 до 3.5 м; ширші смуги спонукають водіїв їхати швидше | 3.5 м (дві смуги = проїзна частина 7 м) | Essex Design Guide street types (two 3 m lanes plus a 0.75 m strip); NACTO Urban Street Design Guide, Lane Width |
| Вулиця з двостороннім рухом, мале місто | від 5.5 м (тиха під'їзна вулиця) до 6.75 м (змішане використання, автобуси) | 7 м | Essex Design Guide street-type table; Surrey Healthy Streets guide 4.14 |
| Висота бордюру | від 100 до 150 мм; 125 мм поширена у Великій Британії; знижується до 25 мм або менше на переходах | 12.5 см (Kerb Offset 0, 500, 12.5 у PCG_StreetDresser) | Oxfordshire highways standard (125 mm); Southwark standard detail DS 202 |
| Тротуар | щонайменше 2.0 м вільної ширини на тихих вулицях; 1.8 м абсолютний мінімум; 3 м або більше на торгових вулицях | 2.5 м з кожного боку, разом із бордюром (переріз дороги шириною 12 м) | UK Manual for Streets (2007), via Edinburgh's IDGO guide; Global Street Design Guide (GDCI), Sidewalks |

## Уздовж вулиці (дні 81 і 85)
| Річ | Справжній діапазон | Значення курсу | Джерело |
|---|---|---|---|
| Вуличні ліхтарі, опори 5 до 6 м | приблизно від 25 до 35 м один від одного на житлових вулицях; ближче на поворотах, перехрестях і в жвавих центрах | ліхтар кожні 20 м (яскравий центр міста) | Irish street lighting report for a housing estate (6 m columns at about 30 m); Eugene, Oregon residential spacing table; real spacing comes from a lighting calculation (BS 5489-1 in the UK) |
| Вуличні дерева | приблизно від 8 до 16 м одне від одного, залежно від виду, під'їздів і ліхтарів | дерево в проміжку після кожної лавки (місця через кожні 4 м, тож дерева стоять через 20 м) | Surrey Healthy Streets guide 7.4 (8 to 16 m); City of Los Angeles tree spacing guidelines (7.6 to 12.2 m) |
| Посадкова яма дерева | щонайменше 1.5 м завширшки, між пішохідною доріжкою й дорогою | ряд місць приблизно за 1 м від бордюру | Global Street Design Guide (GDCI) |
| Тримай дерева й високі речі подалі від кутів перехресть | приблизно 10 до 12 м від кута, щоб водії бачили дорогу | перехрестя є зонами-винятками з Дня 89: ліхтарі й дерева через PCG_KeepOuts; лавки, урни й стовпчики через PCG_JunctionKeepOuts | City of Stirling street tree placement guidelines |
| Коридор польоту | (правило гри, а не вулиці) | нічого вищого за 1.5 м усередині коридору | this course |

## Ділянки й будівлі (день 88)
| Річ | Справжній діапазон | Значення курсу | Джерело |
|---|---|---|---|
| Ширина ділянки (фасад на вулицю) у старому місті | приблизно від 5 до 18 м; часто від 5 до 10 м у ринкових містечках, подекуди 15 м | Plot Width 12 м (гавань), 18 м (вглибині суходолу) | Alresford town history (about 10 m wide plots); Stratford-upon-Avon (about 15 m average); medieval charters of 16 to 18 m, reviewed in Scottish burgh studies |
| Глибина ділянки | часто довга й вузька: від 60 до 100 м у середньовічних містах | Plot Depth 16 м (ігровий квартал менший) | ті самі джерела про бурґейдж-ділянки (burgage plots) |
| Відступ (проміжок між тротуаром і фасадною стіною) | 0 м у старих центрах (фасади просто на тротуарі); від 3 до 6 м передні садки на новіших вулицях | смуга 2 м | норми забудови різняться за містом; дивись фото свого справжнього місця |
| Верхні поверхи, житло | приблизно 3.0 м від підлоги до підлоги (приблизно 2.7 м стеля) | Floor Height 3 м | Santa Clara downtown form-based code (10 ft floor to floor); a New South Wales planning example (3.3 m with 2.7 m ceilings) |
| Магазин на першому поверсі | приблизно від 4.0 до 4.9 м від підлоги до підлоги | вітрини магазинів на першому поверсі | Glenview and Santa Clara form-based codes (15 to 16 ft ground floors) |
| Навіс над магазином | нижній край щонайменше 2.5 м над тротуаром (2.75 м у деяких містах), відсунутий від бордюру | Awning Height приблизно 250 см (день 68); підніми його, якщо нижній край навісу опиняється нижче 2.5 м | highway projection licences of BCP Council (2.5 m) and Dudley Council (2.75 m) |
| Висота будівель біля води проти суходолу | вищі біля гавані та на головних вулицях, нижчі позаду | Harbour 2 to 6 floors, Inland 1 to 3 floors | твої власні референсні фото |

## Площі (день 88)
| Річ | Справжній діапазон | Значення курсу | Джерело |
|---|---|---|---|
| Мала жвава міська площа | коротка сторона зазвичай від 14 до 18 м (45 to 60 ft), ніколи значно більше ніж 21 м (70 ft); довга сторона може бути довшою | площа навколо пам'ятки; роби її більшою, лише якщо цього потребує вигляд із дрона, і заповни деревами, лавками та кафе | Christopher Alexander, *A Pattern Language* (1977), pattern 61 "Small Public Squares" |

## Як користуватися цим аркушем
1. Перш ніж задати число в наборі правил, знайди його рядок тут і запиши поруч у нотатках справжній діапазон.
2. Подивися два фото свого справжнього місця й звір числа з ними (порахуй поверхи, відміряй ширину ділянок кроками відносно дверей, а вони приблизно 1 м завширшки).
3. Якщо береш число поза справжнім діапазоном (наприклад ліхтарі ближче для яскравішої сцени), одним рядком напиши чому.

## Посилання
Список посилань дивись в англійській частині нижче (розділ «Links»).

---

## English

# Street dimensions: real measures for your rules

Real streets follow measures that people have tested for a long time. If your generator uses them, your town looks right from the ground and from a drone. Each line gives the **real range**, the **number the course uses**, and where the range comes from. Real rules differ between countries and towns, so treat these as good starting values, not law.

1 Unreal unit = 1 cm, so 3.5 m = 350 units.

## The road section (Days 81, 85, 86)
| Part | Real range | Course value | Source |
|---|---|---|---|
| Traffic lane | about 3.0 to 3.5 m; wider lanes make drivers go faster | 3.5 m (two lanes = a 7 m carriageway) | Essex Design Guide street types (two 3 m lanes plus a 0.75 m strip); NACTO Urban Street Design Guide, Lane Width |
| Two-way street, small town | 5.5 m (quiet access street) to 6.75 m (mixed use, buses) | 7 m | Essex Design Guide street-type table; Surrey Healthy Streets guide 4.14 |
| Kerb height (upstand) | 100 to 150 mm; 125 mm is common in the UK; lowered to 25 mm or less at crossings | 12.5 cm (Kerb Offset 0, 500, 12.5 in PCG_StreetDresser) | Oxfordshire highways standard (125 mm); Southwark standard detail DS 202 |
| Pavement (footway) | at least 2.0 m clear in quiet streets; 1.8 m absolute minimum; 3 m or more in shopping streets | 2.5 m each side, kerb included (road section 12 m wide) | UK Manual for Streets (2007), via Edinburgh's IDGO guide; Global Street Design Guide (GDCI), Sidewalks |

## Along the street (Days 81 and 85)
| Thing | Real range | Course value | Source |
|---|---|---|---|
| Street lamps, 5 to 6 m columns | about 25 to 35 m apart on homes streets; closer at bends, junctions and busy centres | a lamp every 20 m (a bright town centre) | Irish street lighting report for a housing estate (6 m columns at about 30 m); Eugene, Oregon residential spacing table; real spacing comes from a lighting calculation (BS 5489-1 in the UK) |
| Street trees | about 8 to 16 m apart, depending on the species, driveways and lamps | a tree in the gap after each bench (slots every 4 m, so trees are 20 m apart) | Surrey Healthy Streets guide 7.4 (8 to 16 m); City of Los Angeles tree spacing guidelines (7.6 to 12.2 m) |
| Tree pit | at least 1.5 m wide, between the walking path and the road | the slot row about 1 m behind the kerb | Global Street Design Guide (GDCI) |
| Keep trees and tall things away from junction corners | about 10 to 12 m from a corner, so drivers can see | junctions are keep-outs from Day 89: lamps and trees through PCG_KeepOuts; benches, bins and bollards through PCG_JunctionKeepOuts | City of Stirling street tree placement guidelines |
| Flight corridor | (a game rule, not a street rule) | nothing taller than 1.5 m inside a corridor | this course |

## Plots and buildings (Day 88)
| Thing | Real range | Course value | Source |
|---|---|---|---|
| Plot width (street frontage) in an old town | about 5 to 18 m; often 5 to 10 m in market towns, 15 m in some | Plot Width 12 m (harbour), 18 m (inland) | Alresford town history (about 10 m wide plots); Stratford-upon-Avon (about 15 m average); medieval charters of 16 to 18 m, reviewed in Scottish burgh studies |
| Plot depth | often long and narrow: 60 to 100 m in medieval towns | Plot Depth 16 m (a game block is smaller) | the same burgage-plot sources |
| Setback (gap between pavement and front wall) | 0 m in old centres (fronts on the pavement); 3 to 6 m front gardens in newer streets | a 2 m strip | design codes vary by town; check photos of your real place |
| Upper floors, homes | about 3.0 m floor to floor (about 2.7 m ceiling) | Floor Height 3 m | Santa Clara downtown form-based code (10 ft floor to floor); a New South Wales planning example (3.3 m with 2.7 m ceilings) |
| Ground-floor shop | about 4.0 to 4.9 m floor to floor | shop fronts on the ground floor | Glenview and Santa Clara form-based codes (15 to 16 ft ground floors) |
| Shop awning | lowest edge at least 2.5 m above the pavement (2.75 m in some towns), kept back from the kerb | Awning Height about 250 cm (Day 68); raise it if the awning's lowest edge comes below 2.5 m | highway projection licences of BCP Council (2.5 m) and Dudley Council (2.75 m) |
| Building height near the water vs inland | taller by the harbour and main streets, lower behind | Harbour 2 to 6 floors, Inland 1 to 3 floors | your own reference photos |

## Squares (Day 88)
| Thing | Real range | Course value | Source |
|---|---|---|---|
| A small, lively town square | short side usually 14 to 18 m (45 to 60 ft), never much more than 21 m (70 ft); the long side can be longer | a square around the landmark; make it bigger only if the drone view needs it, and fill it with trees, benches and a café | Christopher Alexander, *A Pattern Language* (1977), pattern 61 "Small Public Squares" |

## How to use this sheet
1. Before you set a number in a rule set, find its line here and write the real range next to it in your notes.
2. Look at two photos of your real place and check the numbers against them (count floors, pace out plot widths against a door, which is about 1 m wide).
3. If you choose a number outside the real range (for example lamps closer for a brighter scene), write why in one line.

## Links
- Essex Design Guide, street type table: https://www.essexdesignguide.co.uk/design-details/highways-technical-manual/street-type-table/
- Surrey Healthy Streets, carriageway widths (4.14): https://www.surreycc.gov.uk/land-planning-and-development/healthy-streets/requirements-and-guidance/section?id=4.14
- Surrey Healthy Streets, street trees (7.4): https://www.surreycc.gov.uk/land-planning-and-development/healthy-streets/requirements-and-guidance/section?id=7.4
- NACTO Urban Street Design Guide, lane width: https://nacto.org/publication/urban-street-design-guide/street-design-elements/lane-width/
- Global Street Design Guide, sidewalks: https://globaldesigningcities.org/publication/global-street-design-guide/designing-streets-people/designing-for-pedestrians/sidewalks/geometry/
- Footway widths (IDGO, Edinburgh, quoting Manual for Streets): https://www.openspace.eca.ed.ac.uk/resources/idgo-design-guides/the-design-of-streets-with-older-people-in-mind/widths-of-footways-and-footpaths/
- Oxfordshire kerb details: https://m.oxfordshire.gov.uk/sites/default/files/file/roads-and-transport-policies-and-plans/TechnicalInfoSheet.pdf
- Street lighting report for a housing estate (Ireland, 6 m columns at about 30 m): https://www.pleanala.ie/publicaccess/EIAR-NIS/313253/151.%20Street%20Lighting%20Report.pdf
- Eugene, Oregon residential lighting spacing: https://coeapps.eugene-or.gov/CMOWeblink/0/doc/1420210/Page45.aspx
- City of Los Angeles tree spacing guidelines: https://streets.lacity.gov/sites/default/files/2026-05/UFD-Tree-Spacing-Guidelines-05012026.pdf
- City of Stirling street tree placement: https://stirling.wa.gov.au/awcontent/Web/Documents/Waste%20and%20Environment/Trees/Street-tree-placement-guidelines.pdf
- Alresford burgage plots: https://alresford.org/info_pages/burghage.php
- Burgage plots in Scottish towns (review): https://journals.socantscot.org/index.php/psas/article/view/9608
- Santa Clara downtown form-based code (floor heights): https://gocodebook.com/library/us/ca/santa-clara-zoning/chapter-18.26-downtown-form-based-code/6.3-standards-continued
- Glenview form-based code: https://www.glenview.il.us/business/Documents/DT-formbasedcode4.pdf
- BCP Council projection licence terms: https://bcpcouncil.gov.uk/terms-and-conditions/licence-and-permits-terms-and-conditions/projection-licence-terms-and-conditions
- Dudley Council highway projection licences: https://www.dudley.gov.uk/business/licences-registrations-and-permits/highway-licences/highway-projection-licences
- Pattern 61, Small Public Squares: https://urbigenous.net/a-pattern-language/pattern-061.html
