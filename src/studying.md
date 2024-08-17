# Навчання

<!-- toc -->

Щойно Ви знайшли колоду, яка Вам сподобалась, або ж зробили декілька нотаток,
настає час розпочати навчання.

## Колоди

Навчання у Anki відбувається в межах обраної колоди та вкладених у неї колод.

Ваші колоди та колоди всередині них будуть показуватися у вікні колод списком.
Також, для поточного дня тут буде показано кількість карток
[Нові, Навчальні та Пригадувальні](getting-started.md#Типи-карток).

![Decks screen](media/decks_screen.png)

Колода стане 'поточною колодою', щойно Ви клацнете на ній, а Anki перемкнеться
до вікна навчання. Повернутися до списку колод, щоб змінити поточну колоду на
іншу, можна у будь-який час, клацнувши на "Колоди" у верхній частині головного
вікна. (Щоб обрати нову колоду за допомогою клавіатури, можна скористатися меню
"Вчити колоду". Розпочати вивчення поточної колоди можна, натиснувши
<kbd>s</kbd>.)

Значок коліщатка, який знаходиться праворуч від колоди, дозволяє перейменувати,
видалити змінити [налаштування](deck-options.md) або
[експортувати](exporting.md) її.

## Огляд навчання

Клацнувши на колоді для навчання, Ви побачите екран з кількістю карток на
сьогодні. Він називається 'Огляд навчання':

![Study overview](media/study_overview.png)

Картки діляться на [три типи](getting-started.md#Типи-карток): Нові,
Запам'ятати, Пригадати. Якщо у налаштуваннях колоди увімкнено опцію
[Відкласти сестринські картки](#Сестринські-картки-та-відкладання), Ви можете
побачити кількість відкладених карток, які позначені сірим кольором:

![Study overview (Buried Cards)](media/study_overview_buried_cards.png)

Щоб розпочати навчальну сесію, натисніть на кнопку **Вчити зараз**. Anki
почне показувати Вам картки до тих пір, допоки картки, показ яких було
заплановано на сьогодні, не закінчаться.

Під час навчання, Ви можете повернутися до вікна огляду, натиснувши на
клавіатурі клавішу <kbd>s</kbd>.

## Запитання

Коли картка з'являється, Ви бачите лише запитання. Після того, як Ви подумали
про ймовірну відповідь, клацніть на **Показати відповідь** або ж натисніть
клавішу пробілу. Тоді з'явиться відповідь. Абсолютно нормально, якщо Вам слід
трішки подумати над відповіддю, однак, зазвичай, якщо відповідь не спала Вам на
гадку протягом 10 секунд, краще відкрити її, аніж мучитися з тим, щоб її
пригадати.

Коли відповідь з'явиться, Вам слід порівняти власну відповідь з показаною, і
сказати Anki наскільки добре Ви її запам'ятали. Якщо Ви не довіряєте собі
у визначенні правильності відповіді, то можете вказати Anki, щоб вона
[попросила Вас вдрукувати відповідь](templates/fields.md#Перевірка-відповіді)
замість того щоб просто її показати.

## Вивчення/повторне вивчення карток

Коли Ви вивчаєте нові картки, або повторно вивчаєте забуті, Anki показує картку
один або декілька разів, щоб допомогти Вам її запам'ятати. Кожен показ
називається 'кроком навчання'. Типово існує два кроки: 1 хвилина та 10 хвилин.
Ви можете змінити кількість кроків та затримки між ними у
[налаштуваннях колоди](deck-options.md#Нові-картки).

Протягом навчання показується чотири кнопки для оцінювання:

- **Знову** переміщує картку на перший крок.

- **Тяжко** повторює поточний крок.
  - Якщо картка знаходиться на першому кроці, затримка визначатиметься як
    середнє значення між Знову та Добре.
  - Після першого кроку, Тяжко повторює попередню затримку.

- **Добре** переносить картку на
  [наступний крок](deck-options.md#learning-steps). Якщо картка була на
  останньому кроці, тоді картка перетворюється у картку для пригадування (вона
  'випускається'). Типово, щойно картка досягає кінця кроків навчання, її буде
  показано наступного дня знову, а потім проміжки між показами будуть зростати
  (дивіться наступний параграф).

- **Легко** одразу ж перетворює картку у картку для повторювання, навіть якщо
  попереду були ще кроки для навчання.
  [Типово](deck-options.md#Легкий-інтервал), якщо Ви перебуваєте у режимі
  повторювання, картка з'явиться знову через 4 дні, а далі проміжки між
  показами будуть зростати. У планувальнику першої версії, кнопка "Легко" не
  буде показуватися у режимі повторювання оскільки вона буде використовувати
  той же інтервал, що й кнопка "Добре". У
  [планувальнику версії 2 і
  вище](https://faqs.ankiweb.net/the-anki-2.1-scheduler.html)
  коли картка перебуває у режимі повторювання, кнопка "Легко" буде збільшувати
  проміжок на один день.

Коли картки показуються вперше, вони знаходяться на першому кроці. Таким чином,
якщо першою відповіддю на картку буде "Добре", наступного разу її буде показано
через 10 хвилин, а початковий однохвилинний крок буде пропущено. Якщо ж Ви
натиснете на кнопку "Знову", тоді картка з'явиться знову через одну хвилину.

Щоб вибрати потрібну кнопку, Ви можете натискати на клавіатурі клавіші
<kbd>1</kbd>, <kbd>2</kbd>, <kbd>3</kbd> та <kbd>4</kbd>, де <kbd>1</kbd>
відповідає кнопці **Знову**. Натискання клавіш <kbd>Пробіл</kbd> або
<kbd>Enter</kbd> рівносильне натисканню кнопки **Добре**.

Якщо для показу не залишилося більше карток, тоді Anki знову покаже картки для
вивчення, навіть, якщо таймер затримки показу ще не скінчився. Якщо Ви бажаєте
чекати на повну затримку для навчання, змініть цю поведінку у меню
[Інструменти > Налаштування > Повторювання > Планувальник > 
Обмежити навчання наперед](preferences.md).

## Пригадування карток

Коли, вивчену раніше, картку слід пригадати, оцінити свою відповідь можна за
допомогою чотирьох кнопок:

- **Знову** позначає відповідь неправильною та просить Anki показувати
  картку у майбутньому частіше. Така картка позначається 'невдалою'. Ви
  знайдете більше інформації про те, як опрацьовуються невдалі пригадування у
  параграфі [Невдачі](deck-options.md#Невдачі).

- **Тяжко**, типово, показує картку з
  [трішки більшою затримкою](deck-options.md#Інтервал-тяжкості) ніж
  попереднього разу, і каже Anki показувати картку у майбутньому частіше.

- **Добре** вказує Anki, що останній інтервал вибрано вдало, і складність
  вивчення картки не слід змінювати ані в сторону легкості, ані складності.
  При [типовій початковій складності](deck-options.md#Початкова-складність),
  картка буде показуватися знову приблизно через вдвічі з половиною довший
  інтервал аніж попереднього разу. Отже, якщо попереднього разу картка
  з'явилась через 10 днів, то наступний показ відбудеться через 25 днів.

- **Легко** каже Anki, що обраний інтервал був надто коротким. Наступний показ
  картки буде заплановано
  [значно пізніше, порівняно з 'Добре'](deck-options.md#Бонус-складності), і
  Anki запланує значно рідші майбутні покази. Оскільки 'Легко' дуже сильно
  збільшує інтервали, найкраще її використовувати для найлегших карток.
  Зазвичай, Ви будете відповідати 'Добре'.

Так само, як і у випадку з навчальними картками, Ви можете використовувати
клавіші <kbd>1</kbd>, <kbd>2</kbd>, <kbd>3</kbd> та <kbd>4</kbd> щоб обрати
відповідь. Натискання клавіш <kbd>Пробіл</kbd> або <kbd>Enter</kbd> рівносильне
натисканню кнопки **Добре**.

Щоб дізнатися більше про роботу алгоритму перегляньте
[Налаштування колоди](deck-options.md) та
[ЧаПи](https://faqs.ankiweb.net/what-spaced-repetition-algorithm.html).

## Лічильники очікуваних карток

Коли показано лише запитання, Αnki виводить внизу екрану три числа, напр. 6 + 9
+59. Вони відповідають новим (синій колір), запам'ятовувальним (помаранчевий
колір) та пригадувальним (зелений колір) карткам. Якщо Ви не хочете бачити ці
числа, їх можна вимкнути у [налаштуваннях Anki](preferences.md).

![Лічильники очікуваних карток](media/due_counts.png)

У планувальнику першої версії, числа показують _кількість пригадувань_ до
завершення вивчення всіх карток у даній черзі, а не загальну кількість
_карток_. Якщо ж у Вас, для невдалих карток було налаштовано декілька кроків
навчання, тоді ці числа збільшуються більш аніж на одиницю коли Ви зазнаєте
невдачі з карткою, адже картку треба буде показати знову декілька разів.

Починаючи з другої версії планувальника, числа показують _картки_, а тому
лічильник завжди збільшується на одиницю, незалежно від того, скільки кроків
навчання ще залишилося.

Разом з показаною відповіддю, Anki зазначає під кожною кнопкою приблизний
час, коли картка з'явиться наступного разу. Якщо Ви не хочете бачити ці
показники, їх можна відключити у [налаштуваннях Anki](preferences.md).

## Фактор розмиття

Якщо, пригадуючи картку, Ви натискаєте на кнопку Легко, Anki додаватиме
трішки випадкового «розмиття» щоб запобігти ситуації, коли декілька
одночасно доданих карток з однаковим рейтингом чіпляються одна за одну
та завжди з'являються для пригадування у той самий день. Таке розмиття буде
з'являтися на кнопках відповідей коли увімкнено
[планувальник версії 3](https://faqs.ankiweb.net/the-2021-scheduler.html). Тому
якщо Ви використовуєте попередню версію і помічаєте невелику різницю між
тим що Ви обираєте та фактичними інтервалами появи карток, то причиною може
бути саме це.

Додаткова затримка додається і для запам'ятовувальних карток, щоб вони не 
завжди з'являлися в однаковому порядку, однак на кнопках відповіді про це не
згадується. Цю функціональність неможливо вимкнути.

## Редагувати та Більше

Щоб відредагувати поточну нотатку слід натиснути на кнопку **Редагувати**, яка
знаходиться в лівому нижньому кутку вікна. Завершивши редагування, Ви
повернетесь до навчання. Вікно редагування працює схожим чином до вікна
[додати нотатку](editing.md).

В правому нижньому кутку вікна пригадування знаходиться кнопка **Більше**. Вона
надає доступ до ряду інших дій над поточною карткою або нотаткою:

- [**Позначити Картку**](editing.md#Використання-прапорців): Додає до картки
  кольоровий прапорець або ж забирає його. Прапорець з'являтиметься протягом
  навчання, а у вікні Навігатора за ним можна шукати позначені картки.
  Використання прапорця є корисним, коли ви хочете попрацювати над карткою
  пізніше, скажімо,   знайти слово, коли повернетесь додому. Прапорці можна
  перейменувати у [Навігаторі](browsing.md), якщо Ви використовуєте Anki
  2.1.45+.

- **Відкласти Картку / Нотатку**: Відкладає до наступного дня пригадування
  картки або всіх карток нотатки. (Якщо Ви хочете відновити картки швидше, слід
  клацнути на кнопці "повернути" у вікні
  [Огляд навчання](studying.md#Огляд-навчання)). Відкладання є корисним, якщо
  Ви не можете дати відповідь на картку зараз або ж хочете повернутися до неї
  пізніше. Також відкладання може
  [відбуватися автоматично](studying.md#Сестринські-картки-та-відкладання) для
  карток тієї ж самої нотатки.

  У старому планувальнику, якщо навчальні картки відкладалась, вони поверталися
  до черги нових карток або черги пригадувальних карток перед тим як
  відкластися.

  Однак, у
  [планувальнику версії 2.1](https://faqs.ankiweb.net/the-anki-2.1-scheduler.html),
  відкладання карток не скидає кроки вивчення картки.

- **Забути картку**: Перемістити поточну картку до
  [кінця нової черги](browsing.md#Картки).

  Починаючи з версії 2.1.50+, Anki запам'ятовує початкове місце появи нової
  картки якщо її вперше вивчалось за допомогою планувальника версії 3. Опція
  "Відновити початкову позицію" дозволяє повернути картку на її початкове місце
  появи, коли Ви її забули.

  Увімкнення опції "Скинути лічильники повторювань та провалів" скине картці
  лічильники пригадувань та помилок. Ця опція не видаляє історії
  пригадувань, яку показано внизу інформаційного вікна картки.

- **Вказати дату пригадування**: Розміщує картки у черзі пригадування та
  [показує, що вони очікуються на певну дату.](browsing.md#Картки)

- **Призупинити картку / нотатку**: Приховує пригадування картки або всіх
  карток нотатки допоки їх не буде відновлено вручну (для цього у навігаторі
  слід клацнути на кнопку призупинення). Ця опція є корисною, якщо Ви хочете
  уникати пригадування нотатки протягом певного часу, однак не бажаєте її
  видалити.
  У старому планувальнику, якщо навчальні картки призупинялися, вони
  поверталися до черги нових карток або черги пригадувальних карток перед тим
  як їх призупиняли.

  Однак, у
  [планувальнику версії 2.1](https://faqs.ankiweb.net/the-anki-2.1-scheduler.html),
  призупинення карток не скидає кроки вивчення картки.

- **Налаштування**: Редагування [налаштувань](deck-options.md) для поточної
  колоди.

- **Інформація про картку**: Показує
  [статистичні дані](stats.md#Інформація-про-картку) картки.

- **Інформація про попередню картку**: Показує
  [статистичні дані](stats.md#Інформація-про-картку) попередньої картки.

 - [**Позначити нотатку**](editing.md#Мітка-позначено): Додає до поточної
  картки мітку "позначено", щоб її легко знайти у навігаторі. Ця поведінка
  схожа на позначення окремих карток, однак натомість працює з міткою. Якщо
  нотатка має декілька карток, всі вони з'являться у результатах пошуку для
  позначеної мітки. Натомість більшість користувачів захоче скористатися
  прапорцями.

- **Створити копію**: Відкриває [дублікат](browsing.md#Пошук-дублікатів)
  поточної нотатки у редакторі, який можна змінювати для легшого формування
  різновиду карток. Типово, дубльована картка створиться у тій самій колоді,
  що й оригінальна.

- **Видалити нотатку**: Видаляє нотатку та всі її картки.

- **Повторити аудіо**: Якщо картка має аудіо на передній чи зворотній сторонах,
  відтворити його знову.

- **Призупинити аудіо**: Призупиняє аудіо, яке відтворюється.

- **Аудіо -5s / +5s**: Перемотати поточне відтворення аудіо назад / вперед на
  5 секунд.

- **Записати власний голос**: Запишіть звук з мікрофону щоб перевірити вимову.
  Цей запис буде тимчасовим і зникне, щойно Ви перейдете до наступної картки.
  Скористайтеся вікном редагування, щоб додати запис на постійній основі.

- **Повторити власний голос**: Повторити попередньо зроблений запис власного
  голосу (ймовірно, після показу відповіді).

## Порядок показу

В процесі навчання картки будуть показуватися як з обраної колоди так і з її підколод.
Отже, обравши колоду "Французька", Ви побачите вміст підколод "Французька::Словник" та
"Французька::Книжка::Урок 1".

The way Anki fetches cards from the decks depends on the algorithm used:

- With the v1 scheduler, when a deck has subdecks, the cards will appear from
[each deck in turn](studying.md#Порядок-показу).

- With the [v2 scheduler](https://faqs.ankiweb.net/the-anki-2.1-scheduler.html),
  when a deck has subdecks, reviews are taken from all children decks
  at once. The review limit of the child decks is ignored - only the limit of the
  deck you clicked on applies.

- With the [v3 scheduler](https://faqs.ankiweb.net/the-2021-scheduler.html)
  each child deck's limit is also enforced, and you do not need to see the cards
  in deck order either. See the [deck options](deck-options.md#review-sort-order) section of the manual for more information.

By default, for new cards, Anki fetches cards from the decks in
alphabetical order. So in the above example, you would get cards first
from “French”, then “My Textbook”, and finally “Vocab”. You can use this
to control the order cards appear in, placing high priority cards in
decks that appear higher in the list. When computers sort text
alphabetically, the “-” character comes before alphabetical characters,
and “\~” comes after them. So you could call the deck “-Vocab” to make
them appear first, and you could call the other deck “\~My Textbook” to
force it to appear after everything else.

New cards and reviews are fetched separately, and Anki won’t wait until
both queues are empty before moving on to the next deck, so it’s
possible you’ll be exposed to new cards from one deck while seeing
reviews from another deck, or vice versa. If you don’t want this, click
directly on the deck you want to study instead of one of the parent
decks.

Since cards in learning are somewhat time-critical, they are fetched
from all decks at once and shown in the order they are due.

To control the order reviews from a given deck appear in, or change new
cards from ordered to random order, please see the [deck options](deck-options.md). For more fine-grained ordering of new cards, you
can change the order in the [browser](browsing.md).

## Сестринські картки та відкладання

Recall from [the basics](getting-started.md) that Anki can create more than one
card for each thing you input, such as a front→back card and a
back→front card, or two different cloze deletions from the same text.
These related cards are called 'siblings'.

When you answer a card that has siblings, Anki can prevent the card’s
siblings from being shown in the same session by automatically 'burying'
them. Buried cards are hidden from review until the clock rolls over to
a new day or you manually unbury them using the “Unbury” button that’s
visible at the bottom of the [deck overview](studying.md#Огляд-навчання) screen. Anki
will bury siblings even if the siblings are not in the same deck (for
instance, if you use the [deck override](templates/intro.md) feature).

You can enable burying from the [deck options](deck-options.md) screen -
there are separate settings for new cards and reviews.

Anki will only bury siblings that are new or review cards. It will not
hide cards in learning, as time is of the essence for those cards. On
the other hand, when you study a learning card, any new/review siblings
will be buried.

Note: A card cannot be buried and suspended at the same time. Suspending a
buried card will unbury it. Burying a suspended card does not work on Anki
2.1.49+, whereas on earlier versions, it will unsuspend the card.

## Keyboard Shortcuts

Most of the common operations in Anki have keyboard shortcuts. Most of
them are discoverable in the interface: menu items list their shortcuts
next to them, and hovering the mouse cursor over a button will generally
show its shortcut in a tooltip.

When studying, either <kbd>Space</kbd> or <kbd>Enter</kbd> will show the answer. When the
answer is shown, you can use <kbd>Space</kbd> or <kbd>Enter</kbd> to select the Good button.
You can use the <kbd>1</kbd>-<kbd>4</kbd> keys to select a specific ease button. Many people
find it convenient to answer most cards with <kbd>Space</kbd> and keep one finger
on <kbd>1</kbd> for when they forget.

The "Study Deck" item in the Tools menu allows you to quickly switch to
a deck with the keyboard. You can trigger it with the '/' key. When
opened, it will display all of your decks and show a filter area at the
top. As you type characters, Anki will display only decks matching the
characters you type. You can add a space to separate multiple search
terms, and Anki will show only decks that match all the terms. So “ja 1”
or “on1 ja” would both match a deck called “Japanese::Lesson1”.

## Falling Behind

If you fall behind in your reviews, Anki will prioritize cards that have
been waiting the longest. It does this by taking the cards that have
been waiting the longest and showing them to you in a random order up
until your daily review limit. This ordering ensures that no cards will
be left waiting indefinitely, but it means that if you introduce new
cards, their reviews won’t appear until you’ve gotten through your
backlog.

If you wish to change the order of the overdue reviews, you can do so by
creating a [filtered deck](filtered-decks.md).

When you answer cards that have been waiting for a while, Anki factors
in that delay when determining the next time a card should be shown.
Please see the section on Anki’s spaced-repetition
[algorithm](https://faqs.ankiweb.net/due-times-after-a-break.html) for more information.
