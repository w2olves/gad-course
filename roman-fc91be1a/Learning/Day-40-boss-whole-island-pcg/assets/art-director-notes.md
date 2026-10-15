# Читання кадрів очима вимогливого арт-директора

Арт-директор вирішує лише за скріншотами. Вимогливий не означає недобрий: нотатки короткі, конкретні й прив'язані до місця, і кожна точно каже будівельнику, що змінити. Користуйся цим аркушем, щоб переглянути власні кадри раніше за будь-кого іншого.

## На що дивиться вимогливий арт-директор

- **Реалізм як на фото з дрона**: чи міг би цей кадр бути фото, зробленим дроном над справжнім узбережжям сьогодні?
- **Сучасність**: жодних історичних пропів, жодного фентезі, нічого з іншого століття.
- **Речі там, де їм місце**: човни на воді, лавки обличчям до виду, тумби вздовж краю набережної, ніщо не висить у повітрі й не провалилося.
- **Без мультяшного вигляду**: жодних чистих кольорів, жодних бездоганно чистих поверхонь, жодних іграшкових пропорцій.
- **Збіг зі справжнім місцем**: поклади кадр поруч із найближчим до його вигляду фото зі свого references.md. Світло, колір, щільність і те, чого бракує, одразу видно.

## Три проходи на кожен кадр

1. **Погляд на 3 секунди.** Примружся. Що ти бачиш першим? Це той предмет, який мала показати камера? Чи щось впадає в око, чого не мало б (білий куб-замінник, жорсткий прямий край, неоновий колір)?
2. **Предмет.** Дивись лише на головну окрасу. Масштаб відносно людини (манекена), матеріали, зношення, чіткість силуету й деталей.
3. **Краї та земля.** Обійди межу кадру, потім уздовж землі: основи, що висять, проміжки, повтори, прямі ряди в природі, наполовину обрізані об'єкти на краю.

## Форма нотатки: бачу, чому, виправлення (з місцем)

- **Бачу**: що є в кадрі, простими словами.
- **Чому**: чому це важливо для того, хто дивиться на місце.
- **Виправлення**: одна зміна, з місцем у метрах острова або камерою, яка це показує.

## Приклади нотаток до вигаданого набору кадрів району 1 (набережна)

- C1, набережна в (884, 1012) м: «Бачу: стіна набережної з SM_QuayEdge_4m бездоганно чиста від краю до краю. Чому: справжні стіни гавані мають мокру смугу й соляну лінію, тож це читається як макет. Виправлення: декалі MI_Decal_SaltLine і MI_Decal_Algae уздовж усієї стіни, з розривами.»
- C2, набережна алея: «Бачу: шість лавок SM_Bench стоять в ідеальному ряду, однаково повернуті, однакового сірого кольору. Чому: на справжніх алеях лавки стоять трохи під кутом і зношені по-різному, тож ідеальний ряд читається як макет. Виправлення: поверни кожну лавку на кілька градусів до виду, тримай крок 12-15 м і підніми Wear на двох лавках до 0.7.»
- C3, будівля в гавані: «Бачу: на цій відстані дах, двері та стіна однакового сірого кольору, тож будівля читається як сіра коробка. Чому: пілот використовує будівлю як орієнтир з води, тож її силует має відокремлюватися від неба й набережної. Виправлення: темніша черепиця даху (MI_RoofTile), світліші рами вікон і дверей; перевір контур на тлі неба.»
- C4, широкий: «Бачу: п'ять вуличних дерев стоять в одному прямому ряду з рівним кроком. Чому: око знаходить візерунок раніше за все інше. Виправлення: варіюй крок на 1-2 м і змішай два види, або познач це на плані як парадну алею.»
- C5, поруч із землею біля причалу 2: «Бачу: SM_Skiff_5m висить на 20 см над водою, і тіні під ним немає. Чому: речі мають торкатися того, на чому стоять; основа, що висить, — перше, що помічає око. Виправлення: постав човен за координатами з plot_plan_d1.md, початок координат (origin) на ватерлінії, Z = 0, потім перевір вид збоку й зверху.»
- Усі кадри: «Бачу: вода яскравіша за небо біля горизонту. Чому: це сплющує глибину. Виправлення: одне значення експозиції для всього набору в Post Process Volume; перевір рецепт світла.»

## Як перетворити нечіткі нотатки на виправлення

| Нечітко | Конкретне виправлення |
|---|---|
| «Здається порожнім.» | Додай підраховані групи меблів, які план уже перелічує, за призначенням, перш ніж додавати щось нове. |
| «Надто нове.» | Підніми Wear на меблях набережної й фасадах магазинів до 0.6-0.8; додай декалі бруду (MI_Decal_SaltLine, MI_Decal_Puddle, MI_Decal_TyreTrack) там, де діють вода, колеса й ноги. |
| «Виглядає фальшиво.» | Порівняй із найближчим фото з references.md; спершу виправ найбільшу відмінність (зазвичай насиченість кольору або щільність). |
| «Перевантажено.» | Прибирай пропи, а не зменшуй їх; тримай одну історію на зону. |

## Вердикт

Закінчуй кожну перевірку одним рядком: **так**, або **ні, бо ...**, а далі три нотатки, які змінили б вердикт. Чесність цінніша за оптимізм: відома помилка, названа прямо, варта більше за приховану.

---

## English

# Reading shots like a demanding art director

An art director decides from screenshots alone. A demanding one is not unkind: the notes are short, concrete and located, and each one tells the builder exactly what to change. Use this sheet to review your own shots before anyone else does.

## What a demanding art director looks for

- **Realism like a drone photograph**: could this frame be a photo taken from a drone over a real coast today?
- **Present day**: no period props, no fantasy, nothing that belongs to another century.
- **Things where they belong**: boats on water, benches facing a view, bollards along the quay edge, nothing floating or sunk.
- **No cartoon look**: no pure colours, no spotless surfaces, no toy proportions.
- **A match with the real place**: put the shot beside the photo in your references.md nearest its view. Light, colour, density and what is missing all show at once.

## Three passes on every shot

1. **The 3-second glance.** Squint. What do you see first? Is it the subject the camera was meant to show? Does anything jump out that shouldn't (a white stand-in cube, a hard straight edge, a neon colour)?
2. **The subject.** Look only at the main feature. Scale against a person (the mannequin), materials, wear, clarity of the outline and the details.
3. **The edges and the ground.** Go round the frame's border, then along the ground: floating bases, gaps, repeats, straight rows in nature, half-cut objects at the edge.

## The note form: see, why, fix (with a place)

- **See**: what is in the shot, in plain words.
- **Why**: why it matters to someone looking at the place.
- **Fix**: one change, with the place in island metres or the camera that shows it.

## Example notes on a made-up set of district 1 (waterfront) shots

- C1, the quay at (884, 1012) m: "See: the quay wall made of SM_QuayEdge_4m is spotless from end to end. Why: real harbour walls carry a wet band and salt line, so this reads as a model. Fix: MI_Decal_SaltLine and MI_Decal_Algae decals along the whole wall, with breaks."
- C2, the promenade: "See: six SM_Bench benches stand in a perfect row, all facing the same way, all the same grey. Why: on real promenades benches sit at slight angles and wear unevenly, so a perfect row reads as a model. Fix: turn each bench a few degrees toward the view, keep the spacing at 12 to 15 m, and raise Wear on two benches to 0.7."
- C3, the harbour building: "See: at this distance the roof, door and wall are the same grey, so the building reads as a grey box. Why: the pilot uses a building as a landmark from the water, so its outline must separate from the sky and the quay. Fix: darker roof tile (MI_RoofTile), lighter window and door frames; check the outline against the sky."
- C4, wide: "See: the five street trees stand in one straight row at equal spacing. Why: the eye finds the pattern before anything else. Fix: vary spacing by 1 to 2 m and mix two kinds, or note it on the plan as a formal avenue."
- C5, close on the ground at berth 2: "See: SM_Skiff_5m hangs 20 cm above the water and has no shadow under it. Why: things must touch what they stand on; a floating base is the first thing the eye catches. Fix: place the boat at its coordinates from plot_plan_d1.md, origin on the waterline, Z = 0, then check a side view and a top view."
- All shots: "See: the water is brighter than the sky near the horizon. Why: it flattens the depth. Fix: one exposure value for the whole set in the Post Process Volume; check the light recipe."

## Turning vague notes into fixes

| Vague | Concrete fix |
|---|---|
| "Feels empty." | Add the counted furniture groups the plan already lists, by use, before adding anything new. |
| "Too new." | Raise Wear on the quay-side furniture and shop fronts to 0.6 to 0.8; add grime decals (MI_Decal_SaltLine, MI_Decal_Puddle, MI_Decal_TyreTrack) where water, wheels and feet act. |
| "Looks fake." | Compare with the nearest photo in references.md; fix the biggest difference first (usually colour saturation or density). |
| "Busy." | Remove props, don't shrink them; keep one story per area. |

## The verdict

End every review with one line: **yes**, or **no, because ...** followed by the three notes that would change the verdict. Honest beats hopeful: a known fault, named, is worth more than a hidden one.
