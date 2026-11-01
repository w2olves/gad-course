# Безкоштовні паки для сучасного прибережного острова

Безкоштовні джерела, які використовує цей курс. Паки обираєш і додаєш з Дня 24; далі повертайся до цього списку за потреби до кінця курсу. Усі були перевірені на Fab як безкоштовні, а не як пропозиція на обмежений час, у жовтні 2026; перш ніж додати пак, відкрий його сторінку й перевір, що там досі стоїть **Free**. У цьому курсі нічого не купується.

Посилання на запис: `https://www.fab.com/listings/<id>`. Додай пак зі своїм безкоштовним акаунтом Epic: відкрий запис, **Add to My Library**, потім в Epic Games Launcher: Unreal Engine > Library > Fab Library > **Add to Project**. Якщо IslandCourse немає в списку, постав галочку **Show all projects** і вибери найновішу версію рушія, яку пропонує пак. Старі паки не гарантовано відкриваються чисто в 5.8: перевір кожен, перш ніж будувати на ньому плани. Елементи FBX чи glTF завантажуються й імпортуються вручну.

**Ліцензії.** «Standard» означає Fab Standard License: безкоштовно для особистого й комерційного використання, згадка автора не обов'язкова, але ти все одно вносиш пак у credits.md. «CC-BY» означає безкоштовно з **обов'язковою вказівкою автора**: вказуй автора скрізь, де показуєш свою роботу.

## Вбудоване в Unreal

Starter Content більше не постачається з Unreal 5.8, і цьому курсу він не потрібен.

- **Базові форми** (є завжди: панель Place Actors > Shapes, або папка /Engine/BasicShapes, коли в Settings у Content Browser стоїть галочка Show Engine Content): Cube, Sphere, Cylinder, Cone, Plane і матеріал BasicShapeMaterial.
- **LevelPrototyping** (є в кожному проєкті з шаблону Games > Third Person, у /Game/LevelPrototyping/): меші SM_Cube, SM_ChamferCube, SM_Cylinder, SM_Plane, SM_Ramp, SM_QuarterCylinder, SM_QuarterCylinderOuter; матеріали M_PrototypeGrid, MI_PrototypeGrid_Gray, MI_PrototypeGrid_Gray_02, MI_PrototypeGrid_TopDark, MI_DefaultColorway, M_FlatCol; двері SM_Door і SM_DoorFrame_Edge у /Game/LevelPrototyping/Interactable/Door/Meshes.
- **Плагін Water** (вбудований; ти вмикаєш його на Дні 0: Edit > Plugins > Water, галочка й перезапуск редактора; потім у Place Actors: Water Body Lake, Water Body River, Water Body Ocean). Для маленької тренувальної води досить Water Body Lake або площини (Plane) з власним синьо-зеленим матеріалом: Blend Mode Translucent, Roughness від 0,05 до 0,1, Opacity близько 0,7.

Добре для блокаутів, замінників і перевірок масштабу. Прості замінники матеріалів землі, бетону, дерева, металу й скла дають інстанси твого M_Master (наприклад MI_Stone, MI_Wood, MI_PaintedMetal, MI_Paving), за потреби з іншим Tint.

## Будівлі

| Пак | Автор | Ліцензія | Формат | Посилання |
|---|---|---|---|---|
| [Modular Housing Basic (22 meshes)](https://www.fab.com/listings/9e7a1479-01e2-45cc-8898-590445d538f6) | imbrock | Standard | UE 5.6 | https://www.fab.com/listings/9e7a1479-01e2-45cc-8898-590445d538f6 |
| [Modular Courtyard 1.0 (110 meshes)](https://www.fab.com/listings/ecd3dc8a-5888-4421-91b5-a18390ed4828) | Dan4eZ | Standard | UE 4.27, 5.0-5.4 | https://www.fab.com/listings/ecd3dc8a-5888-4421-91b5-a18390ed4828 |
| [Modern House Pack Vol.1 (84 meshes)](https://www.fab.com/listings/47ebf30c-a2a8-45f8-b282-7c5f424ced4f) | MeikWModels | CC-BY | UE 4.27, 5.3-5.8 | https://www.fab.com/listings/47ebf30c-a2a8-45f8-b282-7c5f424ced4f |
| [Modular Urban houses (41 meshes)](https://www.fab.com/listings/c6a42d9c-f2c5-4155-8ced-b1d6d1592f41) | Replex | CC-BY | UE 5.0-5.4 | https://www.fab.com/listings/c6a42d9c-f2c5-4155-8ced-b1d6d1592f41 |
| [Modular Building Balcony (перевір, чи ще безкоштовний у день використання; якщо ні, пропусти)](https://www.fab.com/listings/141afb0c-f352-4048-8fc4-4add7a1644e2) | Quixel Megascans | Standard | FBX / glTF | https://www.fab.com/listings/141afb0c-f352-4048-8fc4-4add7a1644e2 |

## Вуличні меблі

| Пак | Автор | Ліцензія | Формат | Посилання |
|---|---|---|---|---|
| [City Street Props](https://www.fab.com/listings/717d655e-923f-4c03-bc0b-3509fd1b0ec8): вивіски, маркізи, банери, рекламні стенди, годинники, риштування, ящики (без лавок, смітників, ліхтарів і меблів кафе) | Dekogon Studios | Standard | UE 5.0-5.8 | https://www.fab.com/listings/717d655e-923f-4c03-bc0b-3509fd1b0ec8 |
| [Street Props Pack Vol.1](https://www.fab.com/listings/c1dae76b-8c31-486f-8333-a3958dd4b8f3): лавки, смітники, стовпчики, дорожні знаки, зупинка, бар'єри, конуси (без меблів кафе й ліхтарів) | MeikWModels | CC-BY | UE 4.27, 5.3-5.8 | https://www.fab.com/listings/c1dae76b-8c31-486f-8333-a3958dd4b8f3 |

Спершу бери власні SM_Bollard, SM_Bench, SM_LampPost і SM_Bin (Дні 1-4); деталі з паків лише для прогалин, як дорожні знаки чи бар'єри.

Після додавання відкрий папку кожного паку й запиши в packs_review.md, що в ньому насправді є (5-10 найкращих деталей); плануй за цим, а не за здогадами.

## Набережна й гавань

| Пак | Автор | Ліцензія | Формат | Посилання |
|---|---|---|---|---|
| [Tee Mooring Bollard 30t](https://www.fab.com/listings/c65ec8c6-5e9a-48b3-8c3c-9210ae0710ce) | Model Studio | Standard | FBX, 8,8 MB | https://www.fab.com/listings/c65ec8c6-5e9a-48b3-8c3c-9210ae0710ce |
| [Lateral Navigation Buoy](https://www.fab.com/listings/7eb5ff54-7166-41b6-aa54-3bd42964ce6a) | Model Studio | Standard | FBX, 5,7 MB | https://www.fab.com/listings/7eb5ff54-7166-41b6-aa54-3bd42964ce6a |

Безкоштовного сучасного рибальського човна чи набору для набережної не знайдено: кромку набережної SM_QuayEdge_4m ти моделюєш на Дні 7, а простий човен SM_Skiff_5m — на Дні 43. Безкоштовний пак Smuggler's Cove (Poly Haven) містить кораблі XVII століття та дерев'яний пірс, тож не підходить сучасному містечку.

## Каміння та поверхні

| Пак | Автор | Ліцензія | Формат | Посилання |
|---|---|---|---|---|
| [Limestone Rocks (перевір, чи ще безкоштовний у день використання; якщо ні, пропусти)](https://www.fab.com/listings/e55754f9-21fa-4cba-865b-d9a101df1c89) | Quixel Megascans | Standard | FBX | https://www.fab.com/listings/e55754f9-21fa-4cba-865b-d9a101df1c89 |
| [Quarry Cliff (перевір, чи ще безкоштовний у день використання; якщо ні, пропусти)](https://www.fab.com/listings/1184ba2c-4fde-49a2-b770-ba5de21fe91a) | Quixel Megascans | Standard | FBX | https://www.fab.com/listings/1184ba2c-4fde-49a2-b770-ba5de21fe91a |
| [Free Sample Realistic Rock Set (Limestone Rock Strata)](https://www.fab.com/listings/d2c74eb7-4278-40ab-861a-fdca41855f5a) | Ancraite | Standard | UE 5.4-5.7 | https://www.fab.com/listings/d2c74eb7-4278-40ab-861a-fdca41855f5a |
| [Stucco Wall (матеріал) (перевір, чи ще безкоштовний у день використання; якщо ні, пропусти)](https://www.fab.com/listings/e2f69285-c695-4aa8-851c-1b6492b79b74) | Quixel Megascans | Standard | текстури | https://www.fab.com/listings/e2f69285-c695-4aa8-851c-1b6492b79b74 |
| [Cobblestone (матеріал) (перевір, чи ще безкоштовний у день використання; якщо ні, пропусти)](https://www.fab.com/listings/904d4710-9fe2-402d-853d-f042fe95b3f5) | Quixel Megascans | Standard | текстури | https://www.fab.com/listings/904d4710-9fe2-402d-853d-f042fe95b3f5 |

Більшість Megascans платні з 2025 року; безкоштовні лише ті, що показані як Free у фільтрі Free на Fab.

## Рослини

| Пак | Автор | Ліцензія | Формат | Посилання |
|---|---|---|---|---|
| [Free Shrubs Pack (Ultra Realistic Wind)](https://www.fab.com/listings/7ca465ab-fb9c-4d6b-bddb-82c20f604657) | Greenleaf Vision | Standard | UE 5.4-5.8 | https://www.fab.com/listings/7ca465ab-fb9c-4d6b-bddb-82c20f604657 |
| [Free Nanite Plants Tree Grass Shrub Sample Collection](https://www.fab.com/listings/728a2a8b-9702-4525-afa5-b4a9b3fb636f) | 3DGardenPlants | Standard | UE 5.5-5.8 | https://www.fab.com/listings/728a2a8b-9702-4525-afa5-b4a9b3fb636f |
| [Megaplants: Beach Rose (необов'язково, потрібен експериментальний Procedural Vegetation Editor)](https://www.fab.com/listings/d70e1181-f58e-4e8d-b22a-e6c1864770e8) | Quixel Megaplants | Standard | UE 5.7-5.8 | https://www.fab.com/listings/d70e1181-f58e-4e8d-b22a-e6c1864770e8 |

Безкоштовних оливи, кипариса, агави чи пальми не знайдено. Бери найближчу безкоштовну рослину й запиши заміну в summary.md.

## Poly Haven (текстури, HDRI, моделі)

https://polyhaven.com : безкоштовно, ліцензія CC0, акаунт не потрібен. Звідси на Дні 24 береш текстури землі для Дня 28 (скеля, трава, пісок). Усе одно запиши кожен ресурс у credits.md.

## Electric Dreams (завантаження з Дня 24, робота з Дня 34)

Безкоштовний зразок від Epic: https://www.fab.com/listings/d79688f5-29be-4fb2-a650-2d4a813f5306 . Це окремий проєкт, ElectricDreamsSample (близько 57-60 ГБ). Покрокова інструкція: ACCOUNTS-AND-INSTALLS.html у головній папці курсу.

---

## English

# Free packs for your present-day coastal island

Free sources this course uses. You choose and add packs from Day 24; after that, come back to this list whenever you need it until the end of the course. All were checked on Fab as free, not as a time-limited offer, in October 2026; before you add one, open its page and check it still says **Free**. Nothing in this course is bought.

Listing link: `https://www.fab.com/listings/<id>`. Add a pack with your free Epic account: open the listing, **Add to My Library**, then in the Epic Games Launcher: Unreal Engine > Library > Fab Library > **Add to Project**. If IslandCourse isn't listed, tick **Show all projects** and pick the newest engine version the pack offers. Older packs are not guaranteed to open cleanly in 5.8: test each one before you plan around it. FBX or glTF items are downloaded and imported by hand.

**Licences.** "Standard" means the Fab Standard License: free for personal and commercial use, no credit required, but you still list it in credits.md. "CC-BY" means free with **attribution required**: credit the author wherever you show your work.

## Built into Unreal

Starter Content no longer ships with Unreal 5.8, and this course doesn't need it.

- **Basic shapes** (always there: the Place Actors panel > Shapes, or the /Engine/BasicShapes folder once Show Engine Content is ticked in the Content Browser's Settings): Cube, Sphere, Cylinder, Cone, Plane and the material BasicShapeMaterial.
- **LevelPrototyping** (in every project made from the Games > Third Person template, in /Game/LevelPrototyping/): meshes SM_Cube, SM_ChamferCube, SM_Cylinder, SM_Plane, SM_Ramp, SM_QuarterCylinder, SM_QuarterCylinderOuter; materials M_PrototypeGrid, MI_PrototypeGrid_Gray, MI_PrototypeGrid_Gray_02, MI_PrototypeGrid_TopDark, MI_DefaultColorway, M_FlatCol; a door, SM_Door and SM_DoorFrame_Edge, in /Game/LevelPrototyping/Interactable/Door/Meshes.
- **The Water plugin** (built in; you switch it on on Day 0: Edit > Plugins > Water, tick it and restart the editor; then in Place Actors: Water Body Lake, Water Body River, Water Body Ocean). For small practice water, a Water Body Lake is enough, or a Plane with your own blue-green material: Blend Mode Translucent, Roughness 0.05 to 0.1, Opacity about 0.7.

Good for blockouts, stand-ins and scale checks. Simple ground, concrete, wood, metal and glass stand-ins come from instances of your M_Master (for example MI_Stone, MI_Wood, MI_PaintedMetal, MI_Paving), with another Tint if you need one.

## Buildings

| Pack | Author | Licence | Format | Link |
|---|---|---|---|---|
| [Modular Housing Basic (22 meshes)](https://www.fab.com/listings/9e7a1479-01e2-45cc-8898-590445d538f6) | imbrock | Standard | UE 5.6 | https://www.fab.com/listings/9e7a1479-01e2-45cc-8898-590445d538f6 |
| [Modular Courtyard 1.0 (110 meshes)](https://www.fab.com/listings/ecd3dc8a-5888-4421-91b5-a18390ed4828) | Dan4eZ | Standard | UE 4.27, 5.0 to 5.4 | https://www.fab.com/listings/ecd3dc8a-5888-4421-91b5-a18390ed4828 |
| [Modern House Pack Vol.1 (84 meshes)](https://www.fab.com/listings/47ebf30c-a2a8-45f8-b282-7c5f424ced4f) | MeikWModels | CC-BY | UE 4.27, 5.3 to 5.8 | https://www.fab.com/listings/47ebf30c-a2a8-45f8-b282-7c5f424ced4f |
| [Modular Urban houses (41 meshes)](https://www.fab.com/listings/c6a42d9c-f2c5-4155-8ced-b1d6d1592f41) | Replex | CC-BY | UE 5.0 to 5.4 | https://www.fab.com/listings/c6a42d9c-f2c5-4155-8ced-b1d6d1592f41 |
| [Modular Building Balcony (check it's still free on the day; skip it if not)](https://www.fab.com/listings/141afb0c-f352-4048-8fc4-4add7a1644e2) | Quixel Megascans | Standard | FBX / glTF | https://www.fab.com/listings/141afb0c-f352-4048-8fc4-4add7a1644e2 |

## Street furniture

| Pack | Author | Licence | Format | Link |
|---|---|---|---|---|
| [City Street Props](https://www.fab.com/listings/717d655e-923f-4c03-bc0b-3509fd1b0ec8): shop signs, awnings, banners, poster stands, clocks, scaffolding, crates (no benches, bins, lamps or café furniture) | Dekogon Studios | Standard | UE 5.0 to 5.8 | https://www.fab.com/listings/717d655e-923f-4c03-bc0b-3509fd1b0ec8 |
| [Street Props Pack Vol.1](https://www.fab.com/listings/c1dae76b-8c31-486f-8333-a3958dd4b8f3): benches, bins, bollard posts, traffic signs, a bus shelter, barriers, cones (no café furniture or lamps) | MeikWModels | CC-BY | UE 4.27, 5.3 to 5.8 | https://www.fab.com/listings/c1dae76b-8c31-486f-8333-a3958dd4b8f3 |

Use your own SM_Bollard, SM_Bench, SM_LampPost and SM_Bin first (Days 1 to 4); pieces from packs only for gaps, such as traffic signs or barriers.

Open each pack's folder after adding it and write in packs_review.md what it really holds (its 5 to 10 best pieces); plan from that, not from guesses.

## Quay and harbour

| Pack | Author | Licence | Format | Link |
|---|---|---|---|---|
| [Tee Mooring Bollard 30t](https://www.fab.com/listings/c65ec8c6-5e9a-48b3-8c3c-9210ae0710ce) | Model Studio | Standard | FBX, 8.8 MB | https://www.fab.com/listings/c65ec8c6-5e9a-48b3-8c3c-9210ae0710ce |
| [Lateral Navigation Buoy](https://www.fab.com/listings/7eb5ff54-7166-41b6-aa54-3bd42964ce6a) | Model Studio | Standard | FBX, 5.7 MB | https://www.fab.com/listings/7eb5ff54-7166-41b6-aa54-3bd42964ce6a |

No free present-day fishing boat or quay kit was found: you model the quay edge SM_QuayEdge_4m on Day 7 and a simple boat, SM_Skiff_5m, on Day 43. The free Smuggler's Cove pack (Poly Haven) has 17th-century ships and a wooden pier, so it does not fit a present-day town.

## Rocks and surfaces

| Pack | Author | Licence | Format | Link |
|---|---|---|---|---|
| [Limestone Rocks (check it's still free on the day; skip it if not)](https://www.fab.com/listings/e55754f9-21fa-4cba-865b-d9a101df1c89) | Quixel Megascans | Standard | FBX | https://www.fab.com/listings/e55754f9-21fa-4cba-865b-d9a101df1c89 |
| [Quarry Cliff (check it's still free on the day; skip it if not)](https://www.fab.com/listings/1184ba2c-4fde-49a2-b770-ba5de21fe91a) | Quixel Megascans | Standard | FBX | https://www.fab.com/listings/1184ba2c-4fde-49a2-b770-ba5de21fe91a |
| [Free Sample Realistic Rock Set (Limestone Rock Strata)](https://www.fab.com/listings/d2c74eb7-4278-40ab-861a-fdca41855f5a) | Ancraite | Standard | UE 5.4 to 5.7 | https://www.fab.com/listings/d2c74eb7-4278-40ab-861a-fdca41855f5a |
| [Stucco Wall (material) (check it's still free on the day; skip it if not)](https://www.fab.com/listings/e2f69285-c695-4aa8-851c-1b6492b79b74) | Quixel Megascans | Standard | textures | https://www.fab.com/listings/e2f69285-c695-4aa8-851c-1b6492b79b74 |
| [Cobblestone (material) (check it's still free on the day; skip it if not)](https://www.fab.com/listings/904d4710-9fe2-402d-853d-f042fe95b3f5) | Quixel Megascans | Standard | textures | https://www.fab.com/listings/904d4710-9fe2-402d-853d-f042fe95b3f5 |

Most Megascans cost money since 2025; only the items shown as Free under Fab's Free filter are free.

## Plants

| Pack | Author | Licence | Format | Link |
|---|---|---|---|---|
| [Free Shrubs Pack (Ultra Realistic Wind)](https://www.fab.com/listings/7ca465ab-fb9c-4d6b-bddb-82c20f604657) | Greenleaf Vision | Standard | UE 5.4 to 5.8 | https://www.fab.com/listings/7ca465ab-fb9c-4d6b-bddb-82c20f604657 |
| [Free Nanite Plants Tree Grass Shrub Sample Collection](https://www.fab.com/listings/728a2a8b-9702-4525-afa5-b4a9b3fb636f) | 3DGardenPlants | Standard | UE 5.5 to 5.8 | https://www.fab.com/listings/728a2a8b-9702-4525-afa5-b4a9b3fb636f |
| [Megaplants: Beach Rose (optional, needs the experimental Procedural Vegetation Editor)](https://www.fab.com/listings/d70e1181-f58e-4e8d-b22a-e6c1864770e8) | Quixel Megaplants | Standard | UE 5.7 to 5.8 | https://www.fab.com/listings/d70e1181-f58e-4e8d-b22a-e6c1864770e8 |

No free olive, cypress, agave or palm was found. Use the closest free plant and note the swap in summary.md.

## Poly Haven (textures, HDRIs, models)

https://polyhaven.com : free, licence CC0, no account needed. On Day 24 you take the ground textures for Day 28 from here (rock, grass and sand). Still write every item in credits.md.

## Electric Dreams (download from Day 24, work from Day 34)

Epic's free sample: https://www.fab.com/listings/d79688f5-29be-4fb2-a650-2d4a813f5306 . It is a separate project, ElectricDreamsSample (about 57 to 60 GB). Step-by-step help: ACCOUNTS-AND-INSTALLS.html in the course's main folder.
