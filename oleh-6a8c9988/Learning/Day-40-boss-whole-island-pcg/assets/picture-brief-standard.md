# Стандарт брифу з картинками

Бриф із картинками це те, що ти даєш моделеру (або собі як план, перш ніж відкрити Blender), щоб з першого разу зробити правильну річ. Він має дві частини: **набір картинок** і **письмовий опис**. Обидві дотримуються правил нижче.

## Набір картинок

- Чотири вигляди об'єкта: спереду, збоку, ззаду й у три чверті (приблизно з 15 градусів зверху).
- Кожен вигляд 2048 x 2048 px, на однотонному нейтральному світло-сірому тлі.
- Те саме світло, масштаб, відстань камери й центр у кожному вигляді. Нічого не може зсуватися, віддзеркалюватися чи змінювати колір між виглядами.
- Фотореалістично: справжнє зношення, пил, вигорання й м'які контактні тіні. Ніяких контурів, мультяшних кольорів, чистого білого чи чистого чорного.
- Нічого зайвого: без тексту, логотипів, цін, цифр, людей, основи, п'єдесталу чи диска землі.

## Письмовий опис: сім частин, у такому порядку

1. **Рядок реалізму**: «Фотореалістичний, сучасний ...» (скажи це просто, один раз).
2. **Справжній предмет із розмірами**: що це і його справжні розміри в метрах (ширина x глибина x висота), взяті з двох джерел.
3. **Повний опис поверхні**: кожен матеріал і його стан: «шліфована нержавіюча сталь із плямами від води», «синє полотно, вигоріле на сонці, з пошарпаним краєм».
4. **Природна поза**: як він стоїть під час використання: «навіс розкритий, два ящики стоять біля дверей».
5. **Сцена, в якій він стоїть**: один рядок про те, де він стоїть: «на набережній гавані, під відкритим небом».
6. **Винятки**: «без тексту, без логотипів, без людей, без основи, без п'єдесталу, без диска землі».
7. **Рядок моделі**: частини, які треба тримати окремо, бюджет трикутників, колізія та назва файлу.

## Розібраний приклад 1: відхилений набір фасаду магазину

Для моделера намалювали фасад кафе біля гавані. Набір було відхилено, бо:

- на вигляді спереду були товсті чорні контури й плоскі яскраві кольори, тож він читався як мультфільм;
- вигляд збоку показував навіс на 20 % виступаючим далі, ніж випливало з вигляду спереду, тож вигляди суперечили один одному;
- фасад стояв на круглому сірому диску, який моделер збудував би як частину моделі;
- на ньому була намальована дошка меню з читабельними цінами, тож текст був би запечений у текстуру.

Друга версія виправила всі чотири: перемальовані рендери зі справжнім зношенням, одна камера на поворотному столі, без диска й порожнє лице дошки як окрема частина.

## Розібраний приклад 2: плоский виріз

Дерев'яний човен-скіф описали одним гарним малюнком збоку й більше нічим. Модель повернулася плоскою, як виріз із фанери: не було жодної інформації про його ширину та форму корпусу. Вигляд спереду чи зверху одразу показав би проблему. Одного вигляду ніколи не досить.

## Розібраний приклад 3: набір, який залишили

Набір паркової лавки: чотири узгоджені вигляди 2048 px на світло-сірому, розміри зі сторінки виробника та фото з людиною (1,80 x 0,60 x 0,80 м, сидіння на 0,45 м), трохи вивітрені дерев'яні рейки й темні металеві бокові рами з порошковим покриттям, без тексту, без основи. Опис дотримувався семи частин і закінчувався так:

«Рядок моделі: рейки й бокові рами як один меш, не більше 3 000 трикутників, два бокси UCX (сидіння й спинка: UCX_SM_Bench_00 і UCX_SM_Bench_01), файл SM_Bench.fbx.»

## Перевір перед тим, як передати

- [ ] Чотири вигляди, однакові масштаб, світло, кольори й центр
- [ ] Фотореалістично, без контурів, без чистого білого чи чорного
- [ ] Без тексту, логотипа, людей, основи, п'єдесталу чи диска землі
- [ ] В описі всі сім частин, зі справжніми розмірами в метрах
- [ ] Кожен розмір має два джерела

---

## English

# Picture brief standard

A picture brief is what you give a modeller (or yourself, as the plan before you open Blender) so the right thing is built the first time. It has two parts: a **picture set** and a **written description**. Both follow the rules below.

## The picture set

- Four views of the object: front, side, back and three-quarter (from about 15 degrees above).
- Each view 2048 x 2048 px, on a plain, neutral light-grey background.
- The same light, scale, camera distance and centre in every view. Nothing may move, flip or change colour between views.
- Photoreal: real wear, dust, fading and soft contact shadows. No outlines, no cartoon colours, no pure white or pure black.
- Nothing extra: no text, logos, prices, numbers, people, base, pedestal or ground disc.

## The written description: seven parts, in this order

1. **Realism line**: "A photoreal, present-day ..." (say it plainly, once).
2. **Real subject with sizes**: what it is and its real sizes in metres (width x depth x height), taken from two sources.
3. **Full surface description**: every material and its condition: "brushed stainless steel with water spots", "sun-faded blue canvas, frayed at the hem".
4. **Natural pose**: how it stands when in use: "awning rolled out, two crates stacked beside the door".
5. **The scene it lives in**: one line on where it stands: "on a harbour quay, under open sky".
6. **Exclusions**: "no text, no logos, no people, no base, no pedestal, no ground disc".
7. **Model line**: the parts to keep separate, the triangle budget, collision, and the file name.

## Worked example 1: a rejected shop-front set

A harbour café shop front was drawn for a modeller. The set was rejected because:

- the front view had thick black outlines and flat, bright colours, so it read as a cartoon;
- the side view showed the awning reaching 20 % further out than the front view implied, so the views disagreed;
- the shop front stood on a round grey disc, which a modeller would build as part of the model;
- a menu board with readable prices was painted on, so text would be baked into the texture.

The second version fixed all four: painted-over renders with real wear, one camera on a turntable, no disc, and a blank board face kept as a separate part.

## Worked example 2: the flat cut-out

A wooden skiff was briefed with one beautiful side picture and nothing else. The model came back flat, like a shape cut from plywood: there was no information about its width or the shape of its hull. A front or top view would have shown the problem at once. One view is never enough.

## Worked example 3: a set that was kept

A park bench set: four matching views at 2048 px on light grey, sizes from a maker's product page and a photo with a person in it (1.80 x 0.60 x 0.80 m, seat at 0.45 m), slightly weathered timber slats and dark powder-coated metal side frames, no text, no base. The description followed the seven parts and ended:

"Model line: slats and side frames as one mesh, 3,000 triangles or fewer, two UCX boxes (seat and back: UCX_SM_Bench_00 and UCX_SM_Bench_01), file SM_Bench.fbx."

## Check before you hand it over

- [ ] Four views, same scale, light, colours and centre
- [ ] Photoreal, no outlines, no pure white or black
- [ ] No text, logo, people, base, pedestal or ground disc
- [ ] Description has all seven parts, with real sizes in metres
- [ ] Every size has two sources
