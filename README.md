# Кварто-квинтовый круг · Circle of Fifths · 五度圈

**[Русский](#русский)** · **[English](#english)** · **[中文](#中文)**

---

# Русский

## Что это

Это учебная программа по музыке, которая открывается в браузере. Она помогает понять и запомнить, как устроены ноты, интервалы, аккорды и лады, а потом проверить себя на тренажёрах.

Вся программа — один файл `circle_of_fifths - 128.html`. Устанавливать ничего не нужно: скачайте файл и откройте его в браузере. Работает на компьютере и на телефоне.

### Что на экране

В центре экрана — **круг из двух колец**, разделённых на 12 ячеек каждое. В каждой ячейке — название ноты.

- В музыке 12 разных нот. Они обозначаются буквами: C, D, E, F, G, A, B. Знак ♯ (диез) означает «чуть выше», знак ♭ (бемоль) — «чуть ниже».
- **Внешнее кольцо** — «мажорное» (светлое, бодрое звучание): C, G, D, A, E, B, F♯, D♭, A♭, E♭, B♭, F.
- **Внутреннее кольцо** — «минорное» (грустное, мягкое звучание): Am, Em, Bm, F♯m, C♯m, G♯m, D♯m, B♭m, Fm, Cm, Gm, Dm. Буква `m` после ноты означает минор.
- Ноты на круге стоят не подряд, а в особом порядке. Благодаря ему ноты, которые хорошо звучат вместе, оказываются рядом. Поэтому аккорд или лад на круге — это простая фигура из соседних ячеек, которую легко запомнить глазами.

Рядом с кругом можно показать **клавиатуру пианино** или **гриф** гитары, скрипки, альта, виолончели, контрабаса — чтобы видеть те же ноты на настоящем инструменте.

### Короткий словарь

| Слово | Простое объяснение |
|---|---|
| Нота | Один звук определённой высоты |
| Интервал | Расстояние между двумя нотами |
| Аккорд | Несколько нот (3 и больше), которые звучат вместе |
| Тоника | Главная нота, от которой строится аккорд или лад |
| Обращение | Те же ноты аккорда, но в другом порядке снизу вверх |
| Drop 2, Drop 3 | Аккорд, у которого одна из нот перенесена вниз |
| Лад | Набор из 5–7 нот, из которых составляют мелодии. У каждого лада своё настроение |
| Тональность | Лад, построенный от конкретной ноты (например, C мажор) |
| Ступень | Номер ноты или аккорда внутри тональности (I, II, III…) |
| Модуляция | Переход из одной тональности в другую |
| Голосоведение | Как перейти от аккорда к аккорду, сдвинув как можно меньше нот |
| MIDI | Способ подключить к компьютеру музыкальную клавиатуру |
| DAW | Программа для записи музыки на компьютере |

---

## 1. Функции приложения

Программа состоит из трёх вкладок.

### Вкладка «Обучение» — справочник

Здесь нет вопросов. Вы нажимаете на ноту и сразу видите ответ: на круге, на клавиатуре и на грифе. В настройках выбирается, что именно показывать.

**1. Интервалы.** Нажимаете ноту — программа показывает вторую ноту на выбранном расстоянии. Есть 11 интервалов (от малой секунды до большой септимы), вверх и вниз. Есть схема всех интервалов (значок `?`).

**2. Аккорды.** Нажимаете ноту — видите аккорд от неё. Доступно 32 вида аккордов:

- простые из трёх нот: Мажор, Минор, dim, Sus2, Sus4, aug;
- из четырёх нот: 7, maj7, m7, m(Maj7), 7b5, 7#5, 7sus4, dim7, m7b5;
- большие: add9, m(add9), 9, maj9, m9, m(Maj9), 6/9, add11, m(add11), 11, maj11, m11, m(Maj11), 13, maj13, m13, m(Maj13).

Ноты аккорда показываются стрелками или цветом. У каждой ноты аккорда свой цвет — по её роли (тоника, терция, квинта и т.д.). Под клавиатурой — кнопки обращений и дропов. У каждой кнопки аккорда есть подсказка `i` с его формулой.

**3. Лады.** Нажимаете ноту — видите лад от неё: цепочку соседних ячеек на круге. Доступно 11 ладов: Лидийский, Мажор, Миксолидийский, Дорийский, Минор, Фригийский, Локрийский, Гармонический минор, Мелодический минор, Мажорная пентатоника, Минорная пентатоника. Дополнительно показывается:

- сколько в ладу диезов или бемолей;
- какие именно ноты с диезами и бемолями (линия вокруг круга);
- «родственные лады» — другие лады из тех же самых нот;
- схема, как лады связаны между собой (значок `?`).

**4. Голосоведение.** Схема: в центре — аккорд, вокруг — аккорды, в которые из него можно перейти, сдвинув от 1 до 4 нот. Цвет линии показывает, сколько нот сдвигается. Нажали на соседний аккорд — он встал в центр.

**5. Модуляция.** Выбираете две тональности — программа раскрашивает круг: аккорды только первой, только второй и общие для обеих. Общие аккорды — это «мостики» для перехода из одной тональности в другую.

### Вкладка «Ноты» — тренажёр нот

Программа задаёт вопрос, вы отвечаете. После верного ответа сразу идёт следующий вопрос.

**1. Ноты на инструменте.** Для тех, кто начинает с нуля. Показывается название ноты — нужно нажать её клавишу. Или наоборот: подсвечена клавиша — нужно назвать ноту.

**2. Ноты.** В центре круга — название ноты, нужно найти её ячейку на круге. Режим «Пары» — нужно найти ячейку-пару на другом кольце.

**3. Интервалы.** Показана нота и интервал — нужно нажать сначала эту ноту, потом вторую. Режим «Назови интервал» — наоборот: показаны две ноты, нужно выбрать название интервала.

### Вкладка «Аккорды/Лады» — тренажёр аккордов и ладов

**1. Аккорды.** В центре — название аккорда (например, `Cmaj7`), нужно нажать все его ноты по порядку. Режим «Назови аккорд» — наоборот: аккорд показан, нужно выбрать его название. Можно ограничить вопросы аккордами одной тональности.

**2. Лады.** В центре — нота и название лада, нужно нажать все ноты лада. Режим «Назови лад» — наоборот.

**3. Ступени тональности.** Три вида вопросов: какой аккорд стоит на такой-то ступени; на какой ступени стоит такой-то аккорд; какой общий аккорд связывает две тональности.

**4. Голосоведение.** Показаны два аккорда — нужно сыграть первый, а потом второй, сдвинув только те ноты, которые меняются. Режим «Прогрессия» — аккорды идут по заданной цепочке.

### Общие возможности

- **Три способа отвечать:** мышью (или пальцем на телефоне), буквами на клавиатуре компьютера, на подключённой музыкальной MIDI-клавиатуре.
- **Подсчёт ошибок:** окно показывает, сколько было вопросов, сколько из них без ошибок и на чём вы ошибаетесь чаще всего.
- **Программа следит, чтобы вопросы не повторялись слишком часто.**
- **Звук:** без звука, встроенный синтезатор, тембры настоящих инструментов (нужен интернет) или отправка нот в программу для записи музыки (DAW).
- **3 языка:** русский, английский, китайский.
- **5 тем оформления**, включая светлую.
- **Два способа называть ноты:** буквами (ABC) или слогами (кнопка «До ре ми»).
- **Все настройки запоминаются** в браузере.
- **Работает без интернета** (кроме тембров с пометкой «сэмпл из интернета»).

### Запуск

1. Скачайте файл `circle_of_fifths - 128.html`.
2. Откройте его в браузере.
3. Окно настроек открывается и закрывается клавишей `Y` или правой кнопкой мыши.

Чтобы работала MIDI-клавиатура, браузер должен поддерживать Web MIDI. Если файл открыт прямо с диска и браузер не даёт доступ к MIDI, запустите файл через локальный сервер: в папке с файлом выполните `python -m http.server 8000` и откройте `http://localhost:8000/`.

---

## 2. Горячие клавиши

В скобках — та же клавиша на русской раскладке.

### Работают везде

| Клавиша | Что делает |
|---|---|
| `Y` (`Н`), `Shift + F10`, правая кнопка мыши | Открыть / закрыть настройки |
| `V` (`М`) | Спрятать курсор мыши (появится, когда мышь сдвинется) |
| `+` | Увеличить круг |
| `-` | Уменьшить круг |
| `Shift + -` | Вернуть обычный размер круга |
| `]` (`Ъ`) | Увеличить клавиатуру рядом с кругом |
| `[` (`Х`) | Уменьшить клавиатуру |
| `Shift + [` | Вернуть обычный размер клавиатуры |

### Ноты

| Клавиша | Что делает |
|---|---|
| `A` `B` `C` `D` `E` `F` `G` | Нота |
| `Shift` + буква | Нота с диезом |
| `Пробел`, затем буква | Нота с бемолем |

### Вкладка «Обучение»

| Клавиша | Что делает |
|---|---|
| Та же буква ещё раз | Перейти на внутреннее (минорное) кольцо |
| `1` `2` `3` `4` `5` `6` `7` `8` `9` `0` | Мажор, Минор, Sus2, Sus4, 7, maj7, m7, m(Maj7), add9, m(add9) |
| `Пробел`, затем `1`…`0` | 9, maj9, m9, m(Maj9), add11, m(add11), 11, maj11, m11, m(Maj11) |
| `1`…`9`, когда выбраны лады | Лады по порядку кнопок |
| `1`…`0` и `Пробел + 1`, когда выбраны интервалы | Интервалы по порядку кнопок |
| `M` (`Ь`) | Основной вид аккорда; у интервалов — «Вверх» |
| `,` (`Б`) | 1-е обращение; у интервалов — «Вниз» |
| `.` (`Ю`) | 2-е обращение |
| `/` | 3-е обращение |
| `←` `→` | Повернуть круг |
| `Q` (`Й`) | Показывать «Стрелками» |
| `W` (`Ц`) | Показывать «Цветом» |
| Колесо мыши | Двигать выбранную ноту по кругу |

### Вкладка «Ноты», интервалы

| Клавиша | Что делает |
|---|---|
| `Z` (`Я`) | Подсказка на круге |
| `1`…`0`, `Пробел + 1` | Добавить / убрать интервал; в «Назови интервал» — ответ по номеру |

### Вкладка «Аккорды/Лады»

| Клавиша | Что делает |
|---|---|
| `Z` (`Я`) | Подсказка на круге |
| `1`…`0`, `Пробел` + цифра | Добавить / убрать вид аккорда (порядок как в «Обучении») |
| `1`…`9`, когда выбраны лады | Добавить / убрать лад |
| «Назови аккорд», «Назови лад»: `1`…`0`, `Пробел` + цифра | Ответы с 1-го по 20-й |
| «Ступени тональности»: `1`…`5` | Ответы с 1-го по 5-й |
| «Ступень» с галкой «Цифрами на клавиатуре от 1 до 7»: `1`…`7` | Номер ступени |

### Голосоведение

| Клавиша | Что делает |
|---|---|
| Буквы нот | Ноты аккорда снизу вверх |
| `Z` (`Я`) | Показать правильные ноты (вкладка «Аккорды/Лады») |
| `1`…`7` | Аккорд ступени, если выбрана тональность (вкладка «Обучение») |
| `M`, `,`, `.`, `/` | Основной вид и обращения (вкладка «Обучение») |
| `Backspace` / `Enter` / `Esc` | В окне «Выбрать прогрессию»: стереть последний / готово / закрыть |

### MIDI-клавиатура

| Действие | Что делает |
|---|---|
| Колесо Pitch Bend вверх / вниз | Внешнее (мажорное) / внутреннее (минорное) кольцо |
| Белые клавиши C–B в «Назови аккорд», «Назови лад», «Назови интервал» | Ответы с 1-го по 7-й |
| Белые клавиши C–G в «Ступенях тональности» | Ответы с 1-го по 5-й |

Тот же список есть в самой программе: «Остальные настройки» → «Все горячие клавиши» → значок `i`.

---

## 3. Что можно поменять через меню

Меню настроек открывается клавишей `Y`. Вверху — три кнопки вкладок. Ниже — категории под заголовком «Что изучаем (включена одна категория)»: галка слева включает категорию, стрелка справа раскрывает её настройки.

### Вкладка «Обучение»

| Категория | Что можно поменять |
|---|---|
| **1. Интервалы** | Какой интервал показывать · показывать «Стрелками» или «Цветом» · схему «Рядом» или «На круге» |
| **2. Аккорды** | Вид аккорда · «Стрелками» или «Цветом» · «Показать drop2 и 3» · схему расположения нот: «С бемолями\диезами» или «Правильно» · «Показывать буквы аккорда под нотами» · «Показать ступени аккорда» · «Показывать ступени тональности» · «Привязать тональность» |
| **3. Лады** | Лад · порядок кнопок: «Классический» или «От светлого к тёмному» · «Показать стрелкой диезы\бемоли» · «Родственные лады» · «Реальные ноты лада» · «По музыкальным правилам» |
| **4. Голосоведение** | «Выбрать тональность» (лад и тоника) · какие аккорды участвуют · сколько нот может меняться (1, 2, 3, 4) · «Показать drop2 и 3» · «Аккорды второго уровня» · «Окно с разницей в аккордах» · «Показать подсказку с цветами нот» · «Не менять масштаб» · «Скорость анимации, мс» |
| **5. Модуляция** | Лад каждой из двух тональностей (рядом с кругом) |

### Вкладка «Ноты»

| Категория | Что можно поменять |
|---|---|
| **1. Ноты на инструменте** | Какие ноты участвуют в вопросах |
| **2. Ноты** | Какие ноты участвуют (круг выбора, кнопки «Мажор», «Минор», «Очистить все») · «Пары» · «Скрыть круг» |
| **3. Интервалы** | Какие интервалы участвуют · направление: «Вверх», «Вниз» · схему «Рядом» или «На круге» · «Назови интервал» · «Скрыть круг» · от каких нот строить |
| Общее | «Чёрточки» («Под кругом» / «Над кругом») · «Отвечать с помощью»: «Клик мыши» или «На MIDI/ПК клавиатуре» · «Показать окно с ошибками» |

### Вкладка «Аккорды/Лады»

| Категория | Что можно поменять |
|---|---|
| **1. Аккорды** | Какие виды аккордов участвуют · «Выбрать тональность» · «Выбор обращения»: схема и какие обращения и дропы выпадают · «Назови аккорд» · «Скрыть круг» · «Шрифт верхней строки» и «Шрифт нижней строки» · от каких нот строить |
| **2. Лады** | Какие лады участвуют · порядок кнопок · «Назови лад» · «Скрыть круг» · свои размеры шрифта · от каких нот строить |
| **3. Ступени тональности** | Вид вопроса: «Аккорд», «Ступень», «Модуляция» · «Цифрами на клавиатуре от 1 до 7» · для модуляции: «Тоника та же», «Ноты те же», «Любые», «Из тональности», какие лады участвуют · размеры шрифта · какие тональности участвуют |
| **4. Голосоведение** | «Выбрать тональность» · «Прогрессия» · «Окно с разницей в аккордах» · «Показать клавиатуру» · какие аккорды участвуют · «Трезвучия и септаккорды отдельно» · сколько нот может меняться · «Добавить дроп 2\3» · «После ошибки не возвращать к предыдущему аккорду» · «Не показывать предыдущий аккорд» («в кругу», «на клавиатуре») · «Скорость анимации, мс» · от каких нот строить |
| Общее | «Чёрточки» · «Показать окно с ошибками» |

### «Остальные настройки» (есть на каждой вкладке)

| Настройка | Что меняет |
|---|---|
| «Показывать клавиатуру» | Клавиатура пианино рядом с кругом · место: «Слева», «Снизу», «Справа» · «Расстояние до круга» · «Компактный вид» (в «Обучении») |
| «Показать гриф» | Гриф вместо клавиатуры · инструмент: Гитара, Скрипка, Альт, Виолончель, Контрабас (во вкладке «Аккорды/Лады» — только гитара) · место: «Слева», «Снизу», «Справа» · «Весь гриф» · «Расстояние до круга» · «Полутона на грифе» (для смычковых) |
| «Жирный шрифт нот на круге» | Только в «Обучении» |
| «Язык» | Русский, English, 中文 |
| «MIDI» | «Количество MIDI входов» (от 1 до 7) · «MIDI-вход» · «MIDI-выход» · «Подключить MIDI» |
| «Звук» | «Без звука», «Онлайн», «DAW» · «Сыграть за раз» или «Сыграть по очереди» · для «Онлайн»: «Громкость» и «Тембр» · для «DAW»: «Интервал между нотами (сек)», «Velocity», «Разделить сигнал на каналы» |
| «Тема оформления» | Тёмная, Серо-жёлтая, Тёмно-синяя, Чёрно-оранжевая, Светлая |
| «Размер шрифта» | Размер названий нот на круге «Обучения» (от 5 до 40) |
| «Отображать настройки» | Где стоит окно настроек: «Слева», «По центру», «Справа» |
| «Показать альтернативную ноту…» | Второе название ноты на ячейке (например, G♭ рядом с F♯) — в «Обучении» |
| «Название нот» | «ABC» или «До ре ми» |

Размер круга и клавиатуры меняется клавишами (см. раздел 2).

---

## 4. Что можно поменять внутри файла

Эти настройки в меню не вынесены. Чтобы их поменять, откройте файл в любом текстовом редакторе (например, в Блокноте), найдите поиском (`Ctrl + F`) нужное название, поменяйте число или цвет, сохраните файл и обновите страницу в браузере.

Перед правкой сделайте копию файла.

### Цвета и шрифт

Находятся в самом начале файла, в блоке `:root{ … }`.

| Название | Что это | Сейчас |
|---|---|---|
| `--font` | Шрифт всей программы | `Arial, sans-serif` |
| `--bg` | Цвет фона | `#141414` |
| `--app-text-color` | Цвет всего текста | `#D0D0D0` |
| `--green` | Цвет тоники и верного ответа | `#689461` |
| `--red` | Красный на круге | `#ffcccc` |
| `--red-flash` | Цвет неверного ответа | `rgba(255,204,204,0.5)` |
| `--keysig-line` | Цвет линии диезов и бемолей | `#4d9de0` |
| `--tip-formula-red` | Цвет формул в подсказках `i` | `rgba(250, 82, 86, 1)` |
| `--blue`, `--cyan`, `--yellow` и другие | Цвета стрелок и нот аккорда | — |

Цвета остальных тем — в блоках `body.theme-light`, `body.theme-t1`, `body.theme-t2`, `body.theme-t4`.

### Размер круга

| Название | Что это | Сейчас |
|---|---|---|
| `ZOOM_DEFAULT` | Обычный размер круга в «Обучении» | `130` |
| `ZOOM_DEFAULT_NOTES` | Обычный размер круга в «Нотах» | `130` |
| `ZOOM_DEFAULT_CHORDS` | Обычный размер круга в «Аккорды/Лады» | `130` |
| `ZOOM_MIN` | Самый маленький круг | `100` |
| `ZOOM_STEP` | На сколько меняет размер одно нажатие `+` или `-` | `10` |

### Текст в центре круга

| Название | Что это | Сейчас |
|---|---|---|
| `CENTER_NOTE_CONFIG` → `fontSize` | Размер ноты в центре | `47` |
| `CENTER_NOTE_CONFIG` → `color`, `fontFamily` | Цвет и шрифт ноты в центре | — |
| `CENTER_MODE_LABEL_CONFIG` → `fontSize` | Размер подписи под нотой (название лада) | `20` |
| `CENTER_MODE_LABEL_CONFIG` → `gapBelowNote` | Расстояние между нотой и подписью | `7` |
| `CENTER_MODE_LABEL_CONFIG` → `maxWidth` | Наибольшая ширина подписи | `160` |

### «Чёрточки» — блок `CROSSHAIR_CONFIG`

| Название | Что это | Сейчас |
|---|---|---|
| `length` | Длина одной чёрточки | `11` |
| `gap` | Расстояние между чёрточками | `25` |
| `thickness` | Толщина | `1.6` |
| `color`, `opacity` | Цвет и прозрачность | `0.3` |
| `innerRadius` | Пустая зона вокруг центра | `87` |
| `reach` | Как далеко тянутся чёрточки | `257` |

### Положение окон и клавиатуры

| Название | Что это | Сейчас |
|---|---|---|
| `--err-box-top` | Окно с ошибками: отступ от верха круга | `-207px` |
| `--err-box-offset-x` | Окно с ошибками: отступ от края круга | `100px` |
| `--train-below-circle-up` | «Обучение», клавиатура снизу: насколько поднять круг | `12vh` |
| `--train-below-piano-gap` | «Обучение»: расстояние от круга до клавиатуры снизу | `-77px` |
| `--train-below-guitar-gap`, `--train-below-violin-gap`, `--train-below-viola-gap`, `--train-below-cello-gap`, `--train-below-bass-gap` | То же для грифов | `-77px` |
| `--practice-below-circle-up` | «Ноты» и «Аккорды/Лады»: насколько поднять круг | `12vh` |
| `--l3-below-piano-gap`, `--l3-below-guitar-gap` | «Аккорды/Лады»: расстояние до клавиатуры и грифа снизу | `-77px` |
| `--notes-below-piano-gap`, `--notes-below-guitar-gap` и другие | То же для «Нот» | `-77px` |
| `--train-legend-top`, `--train-legend-offset-x` | Положение окна «Показать ступени аккорда» | — |
| `--legend-font-size`, `--legend-swatch-size`, `--legend-padding` | Размер текста, квадратиков и отступов этого окна | — |
| `--train-inv-offset-x`, `--train-inv-offset-y` | Положение кнопок обращений под клавиатурой | `6px`, `14px` |
| `--train-inv-btn-width`, `--train-inv-btn-gap` | Ширина кнопок обращений и расстояние между ними | `96px`, `6px` |

Расстояние до клавиатуры и грифа можно менять и через меню — поле «Расстояние до круга».

### Лады в «Обучении»

| Название | Что это | Сейчас |
|---|---|---|
| `TRAIN_KEYSIG_COUNT_RADIUS` | Расстояние от центра круга до числа знаков | `245` |
| `TRAIN_KEYSIG_COUNT_FONT_SIZE` | Размер числа знаков | `16` |
| `TRAIN_KEYSIG_COUNT_COLOR` | Цвет числа знаков | `var(--green)` |
| `TRAIN_KEYSIG_COUNT_RADIUS_MINOR` | То же расстояние для внутреннего кольца | `88` |
| `TRAIN_KEYSIG_ARC_OFFSET` | Отступ линии знаков от числа | `36` |
| `TRAIN_KEYSIG_ARC_WIDTH` | Толщина линии знаков | `3` |
| `TRAIN_KEYSIG_BADGE_RADIUS`, `TRAIN_KEYSIG_BADGE_FONT_SIZE` | Кружок с номером на линии | `8`, `11` |
| `TRAIN_KEYSIG_NOTE_FONT_SIZE`, `TRAIN_KEYSIG_NOTE_GAP` | Названия нот у линии | `15`, `12` |
| `TRAIN_REAL_MODE_NOTE_COLOR` | Цвет подписей «Реальные ноты лада» | `#C85A5A` |
| `TRAIN_REL_MODES_SCALE` | Размер клавиатуры в окне «Родственные лады» | `1.17` |
| `TRAIN_REL_MODES_GAP` | Отступ этого окна от круга | `40` |

### Гриф

| Название | Что это | Сейчас |
|---|---|---|
| `GTR_FRET_W` | Ширина одного лада | `50` |
| `GTR_FULL_FRET_W` | Ширина лада при «Весь гриф» | `34` |
| `GTR_STRING_GAP` | Расстояние между струнами | `18` |
| `GTR_DOT_R` | Размер точки ноты | `8.5` |
| `GTR_WINDOW_FRETS` | Сколько ладов видно у аккорда и лада | `5` |
| `GTR_NECK_FRETS` | Сколько ладов видно во вкладке «Ноты» | `12` |

### Остальное

| Название | Что это | Сейчас |
|---|---|---|
| `HOTKEYS_HELP_TEXT` | Текст подсказки «Все горячие клавиши» (на трёх языках) | — |
| `I18N` | Все надписи программы на трёх языках | — |
| `ERR_TOP_COUNT` | Сколько строк в списке «Чаще всего ошибки» | `5` |
| `SETTINGS_SAVE_DELAY_MS` | Через сколько миллисекунд после изменения настройки записываются (при закрытии страницы — сразу) | `10000` |
| `L3_MIDI_CHORD_DELAY_MS` | Сколько миллисекунд программа ждёт остальные ноты аккорда с MIDI-клавиатуры | `100` |
| `CHORD_LETTERS_RADIUS_OFFSET_RATIO` | Положение строки «буквы аккорда» внутри ячейки | `0.72` |

---

# English

## What it is

This is a music learning program that opens in a web browser. It helps you understand and memorise how notes, intervals, chords and modes work, and then test yourself with trainers.

The whole program is one file, `circle_of_fifths - 128.html`. Nothing needs to be installed: download the file and open it in a browser. It works on a computer and on a phone.

### What is on the screen

In the centre there is a **circle made of two rings**, each divided into 12 cells. Each cell holds a note name.

- Music has 12 different notes. They are written with letters: C, D, E, F, G, A, B. The sign ♯ (sharp) means "a little higher", the sign ♭ (flat) means "a little lower".
- **The outer ring** is "major" (bright, cheerful sound): C, G, D, A, E, B, F♯, D♭, A♭, E♭, B♭, F.
- **The inner ring** is "minor" (sad, soft sound): Am, Em, Bm, F♯m, C♯m, G♯m, D♯m, B♭m, Fm, Cm, Gm, Dm. The letter `m` after a note means minor.
- Notes on the circle are not placed in a row but in a special order. Because of it, notes that sound good together end up next to each other. So a chord or a mode on the circle is a simple shape of neighbouring cells that is easy to remember visually.

Next to the circle you can show a **piano keyboard** or a **fingerboard** of a guitar, violin, viola, cello or double bass, to see the same notes on a real instrument.

### Short glossary

| Word | Plain explanation |
|---|---|
| Note | One sound of a certain pitch |
| Interval | The distance between two notes |
| Chord | Several notes (3 or more) sounding together |
| Tonic | The main note a chord or a mode is built from |
| Inversion | The same chord notes in a different order from bottom to top |
| Drop 2, Drop 3 | A chord with one of its notes moved down |
| Mode | A set of 5–7 notes used to build melodies. Each mode has its own mood |
| Key | A mode built from a specific note (for example, C major) |
| Degree | The number of a note or a chord inside a key (I, II, III…) |
| Modulation | Moving from one key to another |
| Voice leading | How to go from chord to chord moving as few notes as possible |
| MIDI | A way to connect a music keyboard to a computer |
| DAW | A program for recording music on a computer |

---

## 1. Features

The program has three tabs.

### "Training" tab — a reference

There are no questions here. You press a note and immediately see the answer: on the circle, on the keyboard and on the fingerboard. In the settings you choose what to show.

**1. Intervals.** Press a note — the program shows the second note at the chosen distance. There are 11 intervals (from minor second to major seventh), up and down. A diagram of all intervals is available (the `?` icon).

**2. Chords.** Press a note — you see the chord built from it. 32 chord types are available:

- simple three-note chords: Major, Minor, dim, Sus2, Sus4, aug;
- four-note chords: 7, maj7, m7, m(Maj7), 7b5, 7#5, 7sus4, dim7, m7b5;
- larger chords: add9, m(add9), 9, maj9, m9, m(Maj9), 6/9, add11, m(add11), 11, maj11, m11, m(Maj11), 13, maj13, m13, m(Maj13).

Chord notes are shown with arrows or with colour. Each chord note has its own colour according to its role (tonic, third, fifth and so on). Under the keyboard there are buttons for inversions and drops. Each chord button has an `i` hint with its formula.

**3. Modes.** Press a note — you see the mode built from it: a chain of neighbouring cells on the circle. 11 modes are available: Lydian, Major, Mixolydian, Dorian, Minor, Phrygian, Locrian, Harmonic minor, Melodic minor, Major pentatonic, Minor pentatonic. The program also shows:

- how many sharps or flats the mode has;
- which notes exactly have sharps and flats (a line around the circle);
- "relative modes" — other modes made of the very same notes;
- a diagram of how modes are related (the `?` icon).

**4. Voice leading.** A map: a chord in the centre, and around it the chords you can move to by shifting 1 to 4 notes. The line colour shows how many notes move. Click a neighbouring chord — it moves to the centre.

**5. Modulation.** Choose two keys — the program colours the circle: chords of the first key only, of the second key only, and chords common to both. Common chords are "bridges" for moving from one key to the other.

### "Notes" tab — note trainer

The program asks a question, you answer. After a correct answer the next question appears at once.

**1. Notes on the instrument.** For complete beginners. A note name is shown — press its key. Or the other way round: a key is highlighted — name the note.

**2. Notes.** A note name is in the centre of the circle — find its cell on the circle. "Pairs" mode — find the matching cell on the other ring.

**3. Intervals.** A note and an interval are shown — press this note first, then the second one. "Name the interval" mode works the other way round: two notes are shown, choose the interval name.

### "Chords/Modes" tab — chord and mode trainer

**1. Chords.** A chord name is in the centre (for example, `Cmaj7`) — press all its notes in order. "Name the chord" mode works the other way round: the chord is shown, choose its name. Questions can be limited to chords of one key.

**2. Modes.** A note and a mode name are in the centre — press all notes of the mode. "Name the mode" works the other way round.

**3. Key degrees.** Three kinds of questions: which chord stands on a given degree; on which degree a given chord stands; which common chord links two keys.

**4. Voice leading.** Two chords are shown — play the first one, then the second one, moving only the notes that change. "Progression" mode — chords follow a given chain.

### Common features

- **Three ways to answer:** with the mouse (or a finger on a phone), with letters on the computer keyboard, or on a connected MIDI music keyboard.
- **Mistake counter:** a window shows how many questions there were, how many were answered without mistakes, and where you make mistakes most often.
- **The program makes sure questions do not repeat too often.**
- **Sound:** no sound, a built-in synth, timbres of real instruments (internet required), or sending notes to a music recording program (DAW).
- **3 languages:** Russian, English, Chinese.
- **5 colour themes**, including a light one.
- **Two ways to name notes:** letters (ABC) or syllables (the "Do re mi" button).
- **All settings are remembered** in the browser.
- **Works without internet** (except timbres marked as samples from the internet).

### How to run

1. Download `circle_of_fifths - 128.html`.
2. Open it in a browser.
3. The settings window opens and closes with the `Y` key or the right mouse button.

For a MIDI keyboard the browser must support Web MIDI. If the file is opened straight from disk and the browser refuses MIDI access, run the file through a local server: in the folder with the file run `python -m http.server 8000` and open `http://localhost:8000/`.

---

## 2. Hotkeys

### Work everywhere

| Key | What it does |
|---|---|
| `Y`, `Shift + F10`, right mouse button | Open / close settings |
| `V` | Hide the mouse cursor (it returns when the mouse moves) |
| `+` | Enlarge the circle |
| `-` | Shrink the circle |
| `Shift + -` | Default circle size |
| `]` | Enlarge the keyboard next to the circle |
| `[` | Shrink the keyboard |
| `Shift + [` | Default keyboard size |

### Notes

| Key | What it does |
|---|---|
| `A` `B` `C` `D` `E` `F` `G` | Note |
| `Shift` + letter | Note with a sharp |
| `Space`, then a letter | Note with a flat |

### "Training" tab

| Key | What it does |
|---|---|
| The same letter again | Switch to the inner (minor) ring |
| `1` `2` `3` `4` `5` `6` `7` `8` `9` `0` | Major, Minor, Sus2, Sus4, 7, maj7, m7, m(Maj7), add9, m(add9) |
| `Space`, then `1`…`0` | 9, maj9, m9, m(Maj9), add11, m(add11), 11, maj11, m11, m(Maj11) |
| `1`…`9` when modes are selected | Modes in button order |
| `1`…`0` and `Space + 1` when intervals are selected | Intervals in button order |
| `M` | Root position; for intervals — "Up" |
| `,` | 1st inversion; for intervals — "Down" |
| `.` | 2nd inversion |
| `/` | 3rd inversion |
| `←` `→` | Rotate the circle |
| `Q` | Show with "Arrows" |
| `W` | Show with "Color" |
| Mouse wheel | Move the selected note around the circle |

### "Notes" tab, intervals

| Key | What it does |
|---|---|
| `Z` | Hint on the circle |
| `1`…`0`, `Space + 1` | Add / remove an interval; in "Name the interval" — answer by number |

### "Chords/Modes" tab

| Key | What it does |
|---|---|
| `Z` | Hint on the circle |
| `1`…`0`, `Space` + digit | Add / remove a chord type (same order as in "Training") |
| `1`…`9` when modes are selected | Add / remove a mode |
| "Name the chord", "Name the mode": `1`…`0`, `Space` + digit | Answers 1 to 20 |
| "Key degrees": `1`…`5` | Answers 1 to 5 |
| "Degree" with "Digits 1 to 7 on the keyboard": `1`…`7` | Degree number |

### Voice leading

| Key | What it does |
|---|---|
| Note letters | Chord notes from bottom to top |
| `Z` | Show the correct notes ("Chords/Modes" tab) |
| `1`…`7` | Chord of the degree, if a key is chosen ("Training" tab) |
| `M`, `,`, `.`, `/` | Root position and inversions ("Training" tab) |
| `Backspace` / `Enter` / `Esc` | In "Choose a progression": delete the last one / done / close |

### MIDI keyboard

| Action | What it does |
|---|---|
| Pitch Bend wheel up / down | Outer (major) / inner (minor) ring |
| White keys C–B in "Name the chord", "Name the mode", "Name the interval" | Answers 1 to 7 |
| White keys C–G in "Key degrees" | Answers 1 to 5 |

The same list is inside the program: "Other settings" → "All hotkeys" → the `i` icon.

---

## 3. What can be changed through the menu

The settings menu opens with the `Y` key. At the top there are three tab buttons. Below are categories under the title "What to study (one category is on)": the checkbox on the left turns a category on, the arrow on the right unfolds its settings.

### "Training" tab

| Category | What can be changed |
|---|---|
| **1. Intervals** | Which interval to show · show with "Arrows" or "Color" · scheme "Nearby" or "On the circle" |
| **2. Chords** | Chord type · "Arrows" or "Color" · "Show drop2 and 3" · note layout scheme: "With flats\sharps" or "Correct" · "Show chord letters under notes" · "Show chord degrees" · "Show key degrees" · "Lock key" |
| **3. Modes** | Mode · button order: "Classic" or "Bright to dark" · "Show sharps\flats with a line" · "Relative modes" · "Real notes of the mode" · "By music theory rules" |
| **4. Voice leading** | "Choose key" (mode and tonic) · which chords take part · how many notes may change (1, 2, 3, 4) · "Show drop2 and 3" · "Second-level chords" · "Chord difference window" · "Show the note color hint" · "Keep the scale" · "Animation speed, ms" |
| **5. Modulation** | The mode of each of the two keys (next to the circle) |

### "Notes" tab

| Category | What can be changed |
|---|---|
| **1. Notes on the instrument** | Which notes appear in questions |
| **2. Notes** | Which notes take part (selection circle, buttons "Major", "Minor", "Clear all") · "Pairs" · "Hide circle" |
| **3. Intervals** | Which intervals take part · direction: "Up", "Down" · scheme "Nearby" or "On the circle" · "Name the interval" · "Hide circle" · which notes to build from |
| Common | "Crosshair ticks" ("Under circle" / "Above circle") · "Answer using": "Mouse click" or "On MIDI/computer keyboard" · "Show mistakes window" |

### "Chords/Modes" tab

| Category | What can be changed |
|---|---|
| **1. Chords** | Which chord types take part · "Choose key" · "Choose inversion": the scheme and which inversions and drops appear · "Name the chord" · "Hide circle" · "Top line font" and "Bottom line font" · which notes to build from |
| **2. Modes** | Which modes take part · button order · "Name the mode" · "Hide circle" · its own font sizes · which notes to build from |
| **3. Key degrees** | Question kind: "Chord", "Degree", "Modulation" · "Digits 1 to 7 on the keyboard" · for modulation: "Same tonic", "Same notes", "Any", "From key", which modes take part · font sizes · which keys take part |
| **4. Voice leading** | "Choose key" · "Progression" · "Chord difference window" · "Show keyboard" · which chords take part · "Triads and seventh chords separately" · how many notes may change · "Add drop 2\3" · "After a mistake, do not return to the previous chord" · "Do not show the previous chord" · "Animation speed, ms" · which notes to build from |
| Common | "Crosshair ticks" · "Show mistakes window" |

### "Other settings" (on every tab)

| Setting | What it changes |
|---|---|
| "Show keyboard" | A piano keyboard next to the circle · position: "Left", "Below", "Right" · "Distance to circle" · "Compact view" (in "Training") |
| "Show fingerboard" | A fingerboard instead of the keyboard · instrument: Guitar, Violin, Viola, Cello, Double bass (in the "Chords/Modes" tab — guitar only) · position: "Left", "Below", "Right" · "Whole fingerboard" · "Distance to circle" · "Semitones on the fingerboard" (bowed instruments) |
| "Bold note names on the circle" | "Training" only |
| "Language" | Русский, English, 中文 |
| "MIDI" | "Number of MIDI inputs" (1 to 7) · "MIDI input" · "MIDI output" · "Connect MIDI" |
| "Sound" | "No sound", "Online", "DAW" · "Play together" or "Play in sequence" · for "Online": "Volume" and "Timbre" · for "DAW": "Interval between notes (sec)", "Velocity", "Split signal into channels" |
| "Theme" | Dark, Gray-yellow, Dark blue, Black-orange, Light |
| "Font size" | Size of note names on the "Training" circle (5 to 40) |
| "Show settings" | Where the settings window stands: "Left", "Center", "Right" |
| "Show alternate note…" | A second note name in a cell (for example, G♭ next to F♯) — in "Training" |
| "Note naming" | "ABC" or "Do re mi" |

The size of the circle and of the keyboard is changed with keys (see section 2).

---

## 4. What can be changed inside the file

These settings are not in the menu. To change them, open the file in any text editor (for example, Notepad), find the name with search (`Ctrl + F`), change the number or the colour, save the file and reload the page in the browser.

Make a copy of the file before editing.

### Colours and font

Located at the very beginning of the file, in the `:root{ … }` block.

| Name | What it is | Now |
|---|---|---|
| `--font` | Font of the whole program | `Arial, sans-serif` |
| `--bg` | Background colour | `#141414` |
| `--app-text-color` | Colour of all text | `#D0D0D0` |
| `--green` | Colour of the tonic and of a correct answer | `#689461` |
| `--red` | Red on the circle | `#ffcccc` |
| `--red-flash` | Colour of a wrong answer | `rgba(255,204,204,0.5)` |
| `--keysig-line` | Colour of the sharps and flats line | `#4d9de0` |
| `--tip-formula-red` | Colour of formulas in `i` hints | `rgba(250, 82, 86, 1)` |
| `--blue`, `--cyan`, `--yellow` and others | Colours of arrows and chord notes | — |

Colours of the other themes are in the blocks `body.theme-light`, `body.theme-t1`, `body.theme-t2`, `body.theme-t4`.

### Circle size

| Name | What it is | Now |
|---|---|---|
| `ZOOM_DEFAULT` | Default circle size in "Training" | `130` |
| `ZOOM_DEFAULT_NOTES` | Default circle size in "Notes" | `130` |
| `ZOOM_DEFAULT_CHORDS` | Default circle size in "Chords/Modes" | `130` |
| `ZOOM_MIN` | The smallest circle | `100` |
| `ZOOM_STEP` | How much one press of `+` or `-` changes the size | `10` |

### Text in the centre of the circle

| Name | What it is | Now |
|---|---|---|
| `CENTER_NOTE_CONFIG` → `fontSize` | Size of the note in the centre | `47` |
| `CENTER_NOTE_CONFIG` → `color`, `fontFamily` | Colour and font of the note in the centre | — |
| `CENTER_MODE_LABEL_CONFIG` → `fontSize` | Size of the label under the note (mode name) | `20` |
| `CENTER_MODE_LABEL_CONFIG` → `gapBelowNote` | Distance between the note and the label | `7` |
| `CENTER_MODE_LABEL_CONFIG` → `maxWidth` | Maximum label width | `160` |

### "Crosshair ticks" — the `CROSSHAIR_CONFIG` block

| Name | What it is | Now |
|---|---|---|
| `length` | Length of one tick | `11` |
| `gap` | Distance between ticks | `25` |
| `thickness` | Thickness | `1.6` |
| `color`, `opacity` | Colour and transparency | `0.3` |
| `innerRadius` | Empty zone around the centre | `87` |
| `reach` | How far the ticks extend | `257` |

### Position of windows and the keyboard

| Name | What it is | Now |
|---|---|---|
| `--err-box-top` | Mistakes window: offset from the top of the circle | `-207px` |
| `--err-box-offset-x` | Mistakes window: offset from the edge of the circle | `100px` |
| `--train-below-circle-up` | "Training", keyboard below: how much to raise the circle | `12vh` |
| `--train-below-piano-gap` | "Training": distance from the circle to the keyboard below | `-77px` |
| `--train-below-guitar-gap`, `--train-below-violin-gap`, `--train-below-viola-gap`, `--train-below-cello-gap`, `--train-below-bass-gap` | The same for fingerboards | `-77px` |
| `--practice-below-circle-up` | "Notes" and "Chords/Modes": how much to raise the circle | `12vh` |
| `--l3-below-piano-gap`, `--l3-below-guitar-gap` | "Chords/Modes": distance to the keyboard and fingerboard below | `-77px` |
| `--notes-below-piano-gap`, `--notes-below-guitar-gap` and others | The same for "Notes" | `-77px` |
| `--train-legend-top`, `--train-legend-offset-x` | Position of the "Show chord degrees" window | — |
| `--legend-font-size`, `--legend-swatch-size`, `--legend-padding` | Text size, colour square size and padding of that window | — |
| `--train-inv-offset-x`, `--train-inv-offset-y` | Position of inversion buttons under the keyboard | `6px`, `14px` |
| `--train-inv-btn-width`, `--train-inv-btn-gap` | Width of inversion buttons and the gap between them | `96px`, `6px` |

The distance to the keyboard and fingerboard can also be changed in the menu — the "Distance to circle" field.

### Modes in "Training"

| Name | What it is | Now |
|---|---|---|
| `TRAIN_KEYSIG_COUNT_RADIUS` | Distance from the circle centre to the number of signs | `245` |
| `TRAIN_KEYSIG_COUNT_FONT_SIZE` | Size of the number of signs | `16` |
| `TRAIN_KEYSIG_COUNT_COLOR` | Colour of the number of signs | `var(--green)` |
| `TRAIN_KEYSIG_COUNT_RADIUS_MINOR` | The same distance for the inner ring | `88` |
| `TRAIN_KEYSIG_ARC_OFFSET` | Offset of the signs line from the number | `36` |
| `TRAIN_KEYSIG_ARC_WIDTH` | Thickness of the signs line | `3` |
| `TRAIN_KEYSIG_BADGE_RADIUS`, `TRAIN_KEYSIG_BADGE_FONT_SIZE` | The numbered dot on the line | `8`, `11` |
| `TRAIN_KEYSIG_NOTE_FONT_SIZE`, `TRAIN_KEYSIG_NOTE_GAP` | Note names next to the line | `15`, `12` |
| `TRAIN_REAL_MODE_NOTE_COLOR` | Colour of "Real notes of the mode" labels | `#C85A5A` |
| `TRAIN_REL_MODES_SCALE` | Keyboard size in the "Relative modes" window | `1.17` |
| `TRAIN_REL_MODES_GAP` | Offset of that window from the circle | `40` |

### Fingerboard

| Name | What it is | Now |
|---|---|---|
| `GTR_FRET_W` | Width of one fret | `50` |
| `GTR_FULL_FRET_W` | Fret width with "Whole fingerboard" | `34` |
| `GTR_STRING_GAP` | Distance between strings | `18` |
| `GTR_DOT_R` | Size of a note dot | `8.5` |
| `GTR_WINDOW_FRETS` | How many frets are visible for a chord or a mode | `5` |
| `GTR_NECK_FRETS` | How many frets are visible in the "Notes" tab | `12` |

### Other

| Name | What it is | Now |
|---|---|---|
| `HOTKEYS_HELP_TEXT` | Text of the "All hotkeys" hint (in three languages) | — |
| `I18N` | All texts of the program in three languages | — |
| `ERR_TOP_COUNT` | Number of rows in the most frequent mistakes list | `5` |
| `SETTINGS_SAVE_DELAY_MS` | How many milliseconds after a change the settings are written (at once when the page is closed) | `10000` |
| `L3_MIDI_CHORD_DELAY_MS` | How many milliseconds the program waits for the remaining chord notes from a MIDI keyboard | `100` |
| `CHORD_LETTERS_RADIUS_OFFSET_RATIO` | Position of the "chord letters" line inside a cell | `0.72` |

---

# 中文

## 这是什么

这是一个在浏览器中打开的音乐学习程序。它帮助你理解并记住音符、音程、和弦和调式的构成，然后用练习器检验自己。

整个程序只有一个文件 `circle_of_fifths - 128.html`。无需安装：下载文件并用浏览器打开即可。电脑和手机都能使用。

### 屏幕上有什么

屏幕中央是一个**由两个圆环组成的圆**，每个圆环分为 12 个格子，每个格子里是一个音名。

- 音乐中有 12 个不同的音，用字母表示：C、D、E、F、G、A、B。符号 ♯（升号）表示"稍高一点"，符号 ♭（降号）表示"稍低一点"。
- **外环**是"大调"（明亮、欢快的声音）：C、G、D、A、E、B、F♯、D♭、A♭、E♭、B♭、F。
- **内环**是"小调"（忧伤、柔和的声音）：Am、Em、Bm、F♯m、C♯m、G♯m、D♯m、B♭m、Fm、Cm、Gm、Dm。音名后面的字母 `m` 表示小调。
- 圆上的音不是按顺序排列的，而是按一种特殊顺序排列。这样，一起听起来和谐的音就挨在一起。因此和弦或调式在圆上就是由相邻格子组成的简单图形，很容易用眼睛记住。

圆的旁边可以显示**钢琴键盘**，或吉他、小提琴、中提琴、大提琴、低音提琴的**指板**，以便在真实乐器上看到同样的音。

### 简短词汇表

| 词 | 通俗解释 |
|---|---|
| 音符 | 一个有确定高度的声音 |
| 音程 | 两个音之间的距离 |
| 和弦 | 同时发声的几个音（3 个或更多） |
| 主音 | 和弦或调式由它构成的主要的音 |
| 转位 | 和弦的音相同，但从低到高的顺序不同 |
| Drop 2、Drop 3 | 把其中一个音移到下方的和弦 |
| 调式 | 用来组成旋律的 5–7 个音。每种调式有自己的色彩 |
| 调性 | 从某个具体的音构成的调式（例如 C 大调） |
| 音级 | 音或和弦在调性中的编号（I、II、III……） |
| 转调 | 从一个调性转到另一个调性 |
| 声部进行 | 如何移动尽量少的音，从一个和弦过渡到另一个和弦 |
| MIDI | 把音乐键盘连接到电脑的方式 |
| DAW | 在电脑上录制音乐的软件 |

---

## 1. 功能

程序有三个标签页。

### 「训练」标签页——参考手册

这里没有题目。点击一个音，立刻在圆上、键盘上和指板上看到答案。在设置中选择要显示的内容。

**1. 音程。** 点击一个音，程序显示与它相隔所选距离的第二个音。共有 11 种音程（从小二度到大七度），上行和下行。可查看全部音程的示意图（`?` 图标）。

**2. 和弦。** 点击一个音，看到由它构成的和弦。共有 32 种和弦：

- 三个音的简单和弦：大调、小调、dim、Sus2、Sus4、aug；
- 四个音的和弦：7、maj7、m7、m(Maj7)、7b5、7#5、7sus4、dim7、m7b5；
- 更大的和弦：add9、m(add9)、9、maj9、m9、m(Maj9)、6/9、add11、m(add11)、11、maj11、m11、m(Maj11)、13、maj13、m13、m(Maj13)。

和弦的音用箭头或颜色显示。每个和弦音按其作用（主音、三音、五音等）有自己的颜色。键盘下方是转位和 Drop 的按钮。每个和弦按钮都有带公式的 `i` 提示。

**3. 调式。** 点击一个音，看到由它构成的调式：圆上一串相邻的格子。共有 11 种调式：利底亚、大调、混合利底亚、多利亚、小调、弗里几亚、洛克里亚、和声小调、旋律小调、大调五声音阶、小调五声音阶。还会显示：

- 调式中有几个升号或降号；
- 具体哪些音带升号和降号（圆周围的一条线）；
- "关系调式"——由完全相同的音组成的其他调式；
- 调式之间关系的示意图（`?` 图标）。

**4. 声部进行。** 示意图：中间是一个和弦，周围是移动 1 到 4 个音就能到达的和弦。线的颜色表示移动几个音。点击旁边的和弦，它就移到中间。

**5. 转调。** 选择两个调性，程序给圆着色：只属于第一个调性的和弦、只属于第二个调性的和弦，以及两者共有的和弦。共同和弦是从一个调性转到另一个调性的"桥梁"。

### 「音符」标签页——音符练习器

程序出题，你作答。答对后立刻出下一题。

**1. 乐器上的音符。** 适合零基础的人。显示音名，需要按下对应的琴键。或者反过来：某个琴键被高亮，需要说出音名。

**2. 音符。** 圆的中央是音名，需要在圆上找到它的格子。"配对"模式：需要在另一个环上找到与之配对的格子。

**3. 音程。** 显示一个音和一个音程，需要先按这个音，再按第二个音。"说出音程"模式相反：显示两个音，需要选择音程名称。

### 「和弦/调式」标签页——和弦与调式练习器

**1. 和弦。** 中央是和弦名称（例如 `Cmaj7`），需要按顺序按下它的全部音。"说出和弦"模式相反：显示和弦，需要选择它的名称。可以把题目限制在某一个调性的和弦内。

**2. 调式。** 中央是音名和调式名称，需要按下调式的全部音。"说出调式"相反。

**3. 调性音级。** 三种题目：某个音级上是哪个和弦；某个和弦在哪个音级上；哪个共同和弦连接两个调性。

**4. 声部进行。** 显示两个和弦，需要先弹第一个，再弹第二个，只移动发生变化的音。"和弦进行"模式：和弦按给定的序列出现。

### 通用功能

- **三种作答方式：** 鼠标（手机上用手指）、电脑键盘上的字母、连接的 MIDI 音乐键盘。
- **错误统计：** 窗口显示共有多少题、其中多少题无错误、以及最常出错的地方。
- **程序会避免题目过于频繁地重复。**
- **声音：** 静音、内置合成器、真实乐器音色（需要联网），或把音符发送到音乐录制软件（DAW）。
- **3 种语言：** 俄语、英语、中文。
- **5 种主题**，包括浅色主题。
- **两种音符命名方式：** 字母（ABC）或唱名（"do re mi"按钮）。
- **所有设置都会保存**在浏览器中。
- **无需联网即可使用**（标有"网络采样"的音色除外）。

### 如何运行

1. 下载 `circle_of_fifths - 128.html`。
2. 用浏览器打开。
3. 按 `Y` 键或鼠标右键打开和关闭设置窗口。

使用 MIDI 键盘时，浏览器必须支持 Web MIDI。如果文件是直接从磁盘打开的，而浏览器不允许访问 MIDI，请通过本地服务器运行：在文件所在文件夹中执行 `python -m http.server 8000`，然后打开 `http://localhost:8000/`。

---

## 2. 快捷键

### 通用

| 按键 | 作用 |
|---|---|
| `Y`、`Shift + F10`、鼠标右键 | 打开 / 关闭设置 |
| `V` | 隐藏鼠标光标（移动鼠标后重新出现） |
| `+` | 放大圆 |
| `-` | 缩小圆 |
| `Shift + -` | 恢复圆的默认大小 |
| `]` | 放大圆旁边的键盘 |
| `[` | 缩小键盘 |
| `Shift + [` | 恢复键盘的默认大小 |

### 音符

| 按键 | 作用 |
|---|---|
| `A` `B` `C` `D` `E` `F` `G` | 音符 |
| `Shift` + 字母 | 带升号的音 |
| `空格`，然后按字母 | 带降号的音 |

### 「训练」标签页

| 按键 | 作用 |
|---|---|
| 再次按同一个字母 | 切换到内环（小调环） |
| `1` `2` `3` `4` `5` `6` `7` `8` `9` `0` | 大调、小调、Sus2、Sus4、7、maj7、m7、m(Maj7)、add9、m(add9) |
| `空格`，然后 `1`…`0` | 9、maj9、m9、m(Maj9)、add11、m(add11)、11、maj11、m11、m(Maj11) |
| 选择调式时按 `1`…`9` | 按按钮顺序选择调式 |
| 选择音程时按 `1`…`0` 和 `空格 + 1` | 按按钮顺序选择音程 |
| `M` | 原位；音程时为"上行" |
| `,` | 第一转位；音程时为"下行" |
| `.` | 第二转位 |
| `/` | 第三转位 |
| `←` `→` | 旋转圆 |
| `Q` | 用"箭头"显示 |
| `W` | 用"颜色"显示 |
| 鼠标滚轮 | 沿圆移动所选的音 |

### 「音符」标签页，音程

| 按键 | 作用 |
|---|---|
| `Z` | 圆上的提示 |
| `1`…`0`、`空格 + 1` | 添加 / 移除音程；在"说出音程"中按编号作答 |

### 「和弦/调式」标签页

| 按键 | 作用 |
|---|---|
| `Z` | 圆上的提示 |
| `1`…`0`、`空格` + 数字 | 添加 / 移除和弦类型（顺序与「训练」相同） |
| 选择调式时按 `1`…`9` | 添加 / 移除调式 |
| "说出和弦"、"说出调式"：`1`…`0`、`空格` + 数字 | 第 1 到第 20 个答案 |
| "调性音级"：`1`…`5` | 第 1 到第 5 个答案 |
| "音级"并勾选"用键盘数字 1 到 7"：`1`…`7` | 音级编号 |

### 声部进行

| 按键 | 作用 |
|---|---|
| 音名字母 | 从低到高输入和弦音 |
| `Z` | 显示正确的音（「和弦/调式」标签页） |
| `1`…`7` | 已选择调性时，该音级的和弦（「训练」标签页） |
| `M`、`,`、`.`、`/` | 原位和转位（「训练」标签页） |
| `Backspace` / `Enter` / `Esc` | 在"选择和弦进行"窗口中：删除最后一个 / 完成 / 关闭 |

### MIDI 键盘

| 操作 | 作用 |
|---|---|
| 弯音轮向上 / 向下 | 外环（大调）/ 内环（小调） |
| 在"说出和弦"、"说出调式"、"说出音程"中按白键 C–B | 第 1 到第 7 个答案 |
| 在"调性音级"中按白键 C–G | 第 1 到第 5 个答案 |

程序内也有同样的列表："其他设置" → "全部快捷键" → `i` 图标。

---

## 3. 通过菜单可以更改什么

按 `Y` 键打开设置菜单。顶部是三个标签页按钮。下面是"学习内容（只启用一个类别）"标题下的各个类别：左边的勾选框启用类别，右边的箭头展开它的设置。

### 「训练」标签页

| 类别 | 可以更改的内容 |
|---|---|
| **1. 音程** | 显示哪个音程 · 用"箭头"还是"颜色"显示 · 方案"相邻"或"在五度圈上" |
| **2. 和弦** | 和弦类型 · "箭头"或"颜色" · "显示 drop2 和 3" · 音的排列方案："降号\升号"或"正确" · "在音符下方显示和弦字母" · "显示和弦音级" · "显示调性音级" · "锁定调性" |
| **3. 调式** | 调式 · 按钮顺序："经典"或"由明到暗" · "用线显示升号\降号" · "关系调式" · "调式实际音名" · "按乐理规则" |
| **4. 声部进行** | "选择调性"（调式和主音） · 哪些和弦参与 · 可以变化几个音（1、2、3、4） · "显示 drop2 和 3" · "二级和弦" · "和弦差异窗口" · "显示音符颜色提示" · "不改变比例" · "动画速度（毫秒）" |
| **5. 转调** | 两个调性各自的调式（在圆的旁边） |

### 「音符」标签页

| 类别 | 可以更改的内容 |
|---|---|
| **1. 乐器上的音符** | 哪些音出现在题目中 |
| **2. 音符** | 哪些音参与（选择圆，按钮"大调"、"小调"、"全部清除"） · "配对" · "隐藏圆圈" |
| **3. 音程** | 哪些音程参与 · 方向："上行"、"下行" · 方案"相邻"或"在五度圈上" · "说出音程" · "隐藏圆圈" · 从哪些音构成 |
| 通用 | "准星刻度"（"圆环下方" / "圆环上方"） · "使用以下方式作答"："鼠标点击"或"MIDI/电脑键盘" · "显示错误窗口" |

### 「和弦/调式」标签页

| 类别 | 可以更改的内容 |
|---|---|
| **1. 和弦** | 哪些和弦类型参与 · "选择调性" · "选择转位"：方案以及出现哪些转位和 Drop · "说出和弦" · "隐藏圆圈" · "上行字体"和"下行字体" · 从哪些音构成 |
| **2. 调式** | 哪些调式参与 · 按钮顺序 · "说出调式" · "隐藏圆圈" · 独立的字体大小 · 从哪些音构成 |
| **3. 调性音级** | 题目类型："和弦"、"音级"、"转调" · "用键盘数字 1 到 7" · 转调时："主音相同"、"音相同"、"任意"、"从调性"，哪些调式参与 · 字体大小 · 哪些调性参与 |
| **4. 声部进行** | "选择调性" · "和弦进行" · "和弦差异窗口" · "显示键盘" · 哪些和弦参与 · "三和弦与七和弦分开" · 可以变化几个音 · "添加 drop 2\3" · "出错后不返回上一个和弦" · "不显示前一个和弦" · "动画速度（毫秒）" · 从哪些音构成 |
| 通用 | "准星刻度" · "显示错误窗口" |

### "其他设置"（每个标签页都有）

| 设置 | 更改的内容 |
|---|---|
| "显示键盘" | 圆旁边的钢琴键盘 · 位置："左侧"、"下方"、"右侧" · "与圆圈的距离" · "紧凑视图"（在「训练」中） |
| "显示指板" | 用指板代替键盘 · 乐器：吉他、小提琴、中提琴、大提琴、低音提琴（「和弦/调式」标签页中只有吉他） · 位置："左侧"、"下方"、"右侧" · "整个指板" · "与圆圈的距离" · "指板上的半音"（弓弦乐器） |
| "圆上音名加粗" | 仅「训练」 |
| "语言" | Русский、English、中文 |
| "MIDI" | "MIDI 输入数量"（1 到 7） · "MIDI 输入" · "MIDI 输出" · "连接 MIDI" |
| "声音" | "静音"、"在线"、"DAW" · "同时播放"或"依次播放" · "在线"时："音量"和"音色" · "DAW"时："音符间隔（秒）"、"Velocity"、"将信号分配到不同通道" |
| "主题" | 深色、灰黄色、深蓝色、黑橙色、浅色 |
| "字体大小" | 「训练」圆上音名的大小（5 到 40） |
| "显示设置" | 设置窗口的位置："左侧"、"居中"、"右侧" |
| "显示替代音符…" | 格子里的第二个音名（例如 F♯ 旁边的 G♭）——在「训练」中 |
| "音符命名" | "ABC"或"do re mi" |

圆和键盘的大小用按键更改（见第 2 节）。

---

## 4. 在文件内部可以更改什么

这些设置不在菜单里。要更改它们，请用任意文本编辑器（例如记事本）打开文件，用搜索（`Ctrl + F`）找到所需的名称，修改数字或颜色，保存文件并在浏览器中刷新页面。

修改前请先备份文件。

### 颜色和字体

位于文件最开头的 `:root{ … }` 块中。

| 名称 | 含义 | 当前值 |
|---|---|---|
| `--font` | 整个程序的字体 | `Arial, sans-serif` |
| `--bg` | 背景颜色 | `#141414` |
| `--app-text-color` | 所有文字的颜色 | `#D0D0D0` |
| `--green` | 主音和正确答案的颜色 | `#689461` |
| `--red` | 圆上的红色 | `#ffcccc` |
| `--red-flash` | 错误答案的颜色 | `rgba(255,204,204,0.5)` |
| `--keysig-line` | 升降号线的颜色 | `#4d9de0` |
| `--tip-formula-red` | `i` 提示中公式的颜色 | `rgba(250, 82, 86, 1)` |
| `--blue`、`--cyan`、`--yellow` 等 | 箭头和和弦音的颜色 | — |

其他主题的颜色在 `body.theme-light`、`body.theme-t1`、`body.theme-t2`、`body.theme-t4` 块中。

### 圆的大小

| 名称 | 含义 | 当前值 |
|---|---|---|
| `ZOOM_DEFAULT` | 「训练」中圆的默认大小 | `130` |
| `ZOOM_DEFAULT_NOTES` | 「音符」中圆的默认大小 | `130` |
| `ZOOM_DEFAULT_CHORDS` | 「和弦/调式」中圆的默认大小 | `130` |
| `ZOOM_MIN` | 最小的圆 | `100` |
| `ZOOM_STEP` | 按一次 `+` 或 `-` 改变多少 | `10` |

### 圆中央的文字

| 名称 | 含义 | 当前值 |
|---|---|---|
| `CENTER_NOTE_CONFIG` → `fontSize` | 中央音名的大小 | `47` |
| `CENTER_NOTE_CONFIG` → `color`、`fontFamily` | 中央音名的颜色和字体 | — |
| `CENTER_MODE_LABEL_CONFIG` → `fontSize` | 音名下方标注（调式名称）的大小 | `20` |
| `CENTER_MODE_LABEL_CONFIG` → `gapBelowNote` | 音名与标注之间的距离 | `7` |
| `CENTER_MODE_LABEL_CONFIG` → `maxWidth` | 标注的最大宽度 | `160` |

### "准星刻度"——`CROSSHAIR_CONFIG` 块

| 名称 | 含义 | 当前值 |
|---|---|---|
| `length` | 一个刻度的长度 | `11` |
| `gap` | 刻度之间的距离 | `25` |
| `thickness` | 粗细 | `1.6` |
| `color`、`opacity` | 颜色和透明度 | `0.3` |
| `innerRadius` | 中心周围的空白区域 | `87` |
| `reach` | 刻度延伸多远 | `257` |

### 窗口和键盘的位置

| 名称 | 含义 | 当前值 |
|---|---|---|
| `--err-box-top` | 错误窗口：距圆顶部的偏移 | `-207px` |
| `--err-box-offset-x` | 错误窗口：距圆边缘的偏移 | `100px` |
| `--train-below-circle-up` | 「训练」，键盘在下方：圆上移多少 | `12vh` |
| `--train-below-piano-gap` | 「训练」：圆到下方键盘的距离 | `-77px` |
| `--train-below-guitar-gap`、`--train-below-violin-gap`、`--train-below-viola-gap`、`--train-below-cello-gap`、`--train-below-bass-gap` | 指板的同类设置 | `-77px` |
| `--practice-below-circle-up` | 「音符」和「和弦/调式」：圆上移多少 | `12vh` |
| `--l3-below-piano-gap`、`--l3-below-guitar-gap` | 「和弦/调式」：到下方键盘和指板的距离 | `-77px` |
| `--notes-below-piano-gap`、`--notes-below-guitar-gap` 等 | 「音符」的同类设置 | `-77px` |
| `--train-legend-top`、`--train-legend-offset-x` | "显示和弦音级"窗口的位置 | — |
| `--legend-font-size`、`--legend-swatch-size`、`--legend-padding` | 该窗口的文字大小、色块大小和内边距 | — |
| `--train-inv-offset-x`、`--train-inv-offset-y` | 键盘下方转位按钮的位置 | `6px`、`14px` |
| `--train-inv-btn-width`、`--train-inv-btn-gap` | 转位按钮的宽度和间距 | `96px`、`6px` |

到键盘和指板的距离也可以在菜单中更改——"与圆圈的距离"输入框。

### 「训练」中的调式

| 名称 | 含义 | 当前值 |
|---|---|---|
| `TRAIN_KEYSIG_COUNT_RADIUS` | 圆心到升降号数量的距离 | `245` |
| `TRAIN_KEYSIG_COUNT_FONT_SIZE` | 升降号数量的字号 | `16` |
| `TRAIN_KEYSIG_COUNT_COLOR` | 升降号数量的颜色 | `var(--green)` |
| `TRAIN_KEYSIG_COUNT_RADIUS_MINOR` | 内环的同类距离 | `88` |
| `TRAIN_KEYSIG_ARC_OFFSET` | 升降号线与数量之间的偏移 | `36` |
| `TRAIN_KEYSIG_ARC_WIDTH` | 升降号线的粗细 | `3` |
| `TRAIN_KEYSIG_BADGE_RADIUS`、`TRAIN_KEYSIG_BADGE_FONT_SIZE` | 线上带编号的圆点 | `8`、`11` |
| `TRAIN_KEYSIG_NOTE_FONT_SIZE`、`TRAIN_KEYSIG_NOTE_GAP` | 线旁的音名 | `15`、`12` |
| `TRAIN_REAL_MODE_NOTE_COLOR` | "调式实际音名"标注的颜色 | `#C85A5A` |
| `TRAIN_REL_MODES_SCALE` | "关系调式"窗口中键盘的大小 | `1.17` |
| `TRAIN_REL_MODES_GAP` | 该窗口与圆的间距 | `40` |

### 指板

| 名称 | 含义 | 当前值 |
|---|---|---|
| `GTR_FRET_W` | 一个品的宽度 | `50` |
| `GTR_FULL_FRET_W` | "整个指板"时品的宽度 | `34` |
| `GTR_STRING_GAP` | 琴弦之间的距离 | `18` |
| `GTR_DOT_R` | 音符圆点的大小 | `8.5` |
| `GTR_WINDOW_FRETS` | 和弦和调式显示几个品 | `5` |
| `GTR_NECK_FRETS` | 「音符」标签页显示几个品 | `12` |

### 其他

| 名称 | 含义 | 当前值 |
|---|---|---|
| `HOTKEYS_HELP_TEXT` | "全部快捷键"提示的文字（三种语言） | — |
| `I18N` | 程序的全部文字（三种语言） | — |
| `ERR_TOP_COUNT` | 最常出错列表的行数 | `5` |
| `SETTINGS_SAVE_DELAY_MS` | 更改后多少毫秒写入设置（关闭页面时立即写入） | `10000` |
| `L3_MIDI_CHORD_DELAY_MS` | 程序等待 MIDI 键盘其余和弦音的毫秒数 | `100` |
| `CHORD_LETTERS_RADIUS_OFFSET_RATIO` | "和弦字母"一行在格子内的位置 | `0.72` |
