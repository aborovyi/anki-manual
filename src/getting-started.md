# Початок роботи

<!-- toc -->

## Встановлення та оновлення

Скористайтеся інструкціями для своєї системи:

- [Windows](./platform/windows/installing.md)
- [Mac](./platform/mac/installing.md)
- [Linux](./platform/linux/installing.md)

## Відео

Щоб швидше ознайомитися з Anki, перегляньте наступні вступні відео (англійською
мовою). Деякі з них записано для попередніх версій Anki, однак викладені
поняття залишаються незмінними.

- [Спільні колоди та основи пригадування](http://www.youtube.com/watch?v=QS2G-k2hQyg&yt:cc=on)

- [Синхронізація](https://www.youtube.com/watch?v=YkiM4DPzSVc&list=PLGgmaKOIHykFoomqkBJAyGiDQ2kyiuTao&yt:cc=on)

- [Зміна порядку карт](http://www.youtube.com/watch?v=DnbKwHEQ1mA&yt:cc=on)

- [Зміна стилю карт](http://www.youtube.com/watch?v=F1j1Zx0mXME&yt:cc=on)

- [Введення відповіді](http://www.youtube.com/watch?v=5tYObQ3ocrw&yt:cc=on)

Якщо у Вашій країні немає доступу до YouTube, ви можете
[завантажити відео](https://apps.ankiweb.net/downloads/archive/screencasts/2.0/).

## Основні поняття

### Картки

Запитання та відповідь формують пару, яка називається 'карткою'. Цей термін
походить від паперової навчальної картки, на якій з однієї сторони знаходиться
запитання, а з іншої - відповідь. Картка у Anki не виглядає так, як справжня
картка, і, типово, коли Ви бачите відповідь, запитання теж видно.
Наприклад, якщо Ви вивчаєте основи хімії, то можете зустріти таке запитання:

    П: Яким хімічним знаком позначається кисень?

Трішки подумавши, і вирішивши, що відповіддю буде О, Ви натискаєте на кнопку
відображення відповіді, і Anki каже:

    П: Яким хімічним знаком позначається кисень?
    В: О

Переконавшись у правильності відповіді, Ви можете сказати Anki наскільки добре
запам'ятали картку, і Anki вирішить коли її показати наступного разу.

#### Типи карток

- **Нова:** Новою є картка, яку Ви завантажити або створили, однак іще ні
разу не вивчали.

- **Запам'ятовувальна:** Картки, які Ви бачили вперше нещодавно і їх все ще
треба запам'ятати.

- **Пригадувальна:** Картки, які було вивчено раніше, а тепер їх слід
пригадати, щоб не забути.
  Існує два типи пригадувальних карток:
- **Молода:** Молодою є картка, яка має інтервал повторювання менше 21 дня,
і не є запам'ятовувальною.
- **Досвідчена:** Досвідченою є картка, яка має інтервал повторювання 21 день
або більше.

- **Перезапам'ятовувальна:** Перезапам'ятовувальною є картка, на якій Ви
помилилися у режимі пригадування, а тому вона повернулась у режим
запам'ятовування для повторного вивчення.

### Колоди

'Колода' є групою карток. Картки можна розкласти в різні колоди, щоб вивчати
лише якусь частину, а не всі картки одночасно. Кожна колода має окремі
налаштування, як от щоденна кількість нових карток для запам'ятовування чи
скільки чекати перед наступним показом картки.

Колоди можуть містити інші колоди, утворюючи дерева колод. Anki використовує
"::" щоб відокремлювати рівні. Наприклад, колода "Китайська::Ханьцзи" є
колодою "Ханьцзи", яка знаходиться в колоді "Китайська". Якщо Ви оберете
"Ханьцзи", тоді для вивчення будуть доступні лише ханьцзи картки; якщо ж
оберете "Китайська", тоді будуть показувати всі китайські картки, включно з
картками ханьцзи.

Розмістити колоду в дереві можна двома способами: або в її імені є "::", які
будуть відділяти рівні, або ж її можна перетягнути у переліку колод. Колоди,
які знаходяться всередині інших колод (ті, які мають у своїй назві принаймні
одні "::") часто називаються 'підколодами', а колоди найвищого рівня -
'суперколодами' або 'батьківськими колодами'.

Anki запускається з колодою, яка називається "default" (типова); до неї
потраплятиме будь-яка картка, яка не входить до іншої колоди. Anki сховає
типову колоду, щойно у ній не буде жодної картки і Ви маєте інші колоди.
Також Ви можете перейменувати цю колоду та використовувати її для інших карток.

Колоди розташовуються у переліку колод в алфавітному порядку. Цей порядок може
виглядати дивним, якщо Ваші колоди містять числа. До прикладу, "Моя колода 10"
з'явиться перед "Моя колода 9", оскільки 1 знаходиться перед 9. Якщо Ви бажаєте
пронумерувати свої колоди, додавайте "0" перед одно цифровими числами, напр.
"Колода 01", "Колода 02" ... "Колода 10".

Колоди краще підходять для того, щоб охоплювати широкі категорії карток,
а не окремі теми, як от "дієслова пов'язані з їжею" чи "урок 1". Більше
інформації щодо цього наведено у параграфі
[правильне використання колод](editing.md#правильне-використання-колод).

Те, як колоди визначають порядок показу карток, описано у параграфі
[порядок показу](studying.md#порядок-показу)

### Нотатки та поля

При створенні навчальних карток, щоб зв'язати між собою інформацію, часто
потрібно створити більше аніж одну картку. Наприклад, якщо Ви вивчаєте
французьку, і ви вивчили, що слово "bonjour" означає "привіт", Ви можете
хотіти створити одну картку, яка показує "bonjour" і просить Вас
запам'ятати, що це - "привіт", й іншу картку, яка показує "привіт"
і просить запам'ятати "bonjour". Перша картка перевіряє здатність розпізнати
іншомовне слово, а інша - вміння його відтворити.

Використовуючи паперові навчальні картки, єдине, що можна зробити - записати
інформацію двічі: по одному разу для кожної картки. Деякі програми навчальних
карток спрощують життя, надаючи можливість поміняти передню і задню сторони.
Це суттєве покращення порівняно з паперовими картками, однак, існують два
головних недоліки:

- Оскільки такі програми не відстежують окремо Ваш поступ у розпізнаванні та
відтворенні, картки можуть з'являтися у не оптимально. Як наслідок, Ви будете
забувати більше ніж Вам хотілося б, або ж, вчити більше, аніж потрібно.

- Обертання питання і відповіді працює лише, коли Ви маєте абсолютно ідентичний
вміст на кожній стороні. До прикладу, таким чином неможливо показати додаткову
інформацію на зворотній стороні кожної картки.

Anki розв'язує цю задачі, дозволяючи розділити вміст карток на окремі блоки
інформації. Ви можете сказати Anki, які частини інформації показувати на
кожній стороні картки, і Anki подбає про створення Ваших карток та їх 
оновлення, якщо Ви внесете в майбутньому зміни.

Уявіть, що ми вчимо французький словник, і хочемо показувати на зворотній
стороні кожної картки номер сторінки. Наша картка мала б виглядати отак:

    П: Bonjour
    В: Привіт
       ст. №12

І:

    П: Привіт
    В: Bonjour
       ст. №12

У цьому прикладі, ми маємо три блоки зв'язаної інформації: слово французькою,
український відповідник і номер сторінки. Якщо ми складемо їх разом, вони
виглядатимуть наступним чином:

    Французька: Bonjour
    Українська: Привіт
    Сторінка: 12

У Anki, така пов'язана інформація називається 'нотаткою', а кожна частина
інформації - 'полем'. Отже, ми можемо сказати, що цей тип нотатки має три поля:
Французька, Англійська і Сторінка.

Щоб додати та редагувати поля, під час додавання або редагування нотатки, 
натисніть на кнопку “Поля…​”. Більше інформації про роботу з полями
можна знайти у параграфі
[Пристосовування полів](editing.md#пристосовування-полів).

### Card Types

In order for Anki to create cards based on our notes, we need to give it
a blueprint that says which fields should be displayed on the front or
back of each card. This blueprint is called a 'card type'. Each type of
note can have one or more card types; when you add a note, Anki will
create one card for each card type.

Each card type has two 'templates', one for the question and one for the
answer. In the above French example, we wanted the recognition card to
look like this:

    Q: Bonjour
    A: Hello
       Page #12

To do this, we can set the question and answer templates to:

    Q: {{French}}
    A: {{English}}<br>
       Page #{{Page}}

By surrounding a field name in double curly brackets, we tell Anki to
replace that section with the actual information in the field. Anything
not surrounded by curly brackets remains the same on each card. (For
instance, we don’t have to type “Page \#” into the Page field when
adding material – it’s added automatically to every card.) &lt;br&gt; is
a special code that tells Anki to move to the next line; more details
are available in the [templates](templates/intro.md) section.

The production card templates work in a similar way:

    Q: {{English}}
    A: {{French}}<br>
       Page #{{Page}}

Once a card type has been created, every time you add a new note, a card
will be created based on that card type. Card types make it easy to keep
the formatting of your cards consistent and can greatly reduce the
amount of effort involved in adding information. They also mean Anki can
ensure related cards don’t appear too close to each other, and they
allow you to fix a typing mistake or factual error once and have all the
related cards updated at once.

To add and edit card types, click the “Cards…​” button while adding or
editing notes. For more information on card types, please see the [Cards and Templates](templates/intro.md) section.

### Note Types

Anki allows you to create different types of notes for different
material. Each type of note has its own set of fields and card types.
It’s a good idea to create a separate note type for each broad topic
you’re studying. In the above French example, we might create a note
type called “French” for that. If we wanted to learn capital cities, we
could create a separate note type for that as well, with fields such as
“Country” and “Capital City”.

When Anki checks for duplicates, it only compares other notes of the
same type. Thus if you add a capital city called “Orange” using the
capital city note type, you won’t see a duplicate message when it comes
time to learn how to say “orange” in French.

When you create a new collection, Anki automatically adds some standard
note types to it. These note types are provided to make Anki easier for
new users, but in the long run it’s recommended you define your own note
types for the content you are learning. The standard note types are as
follows:

- **Basic**
  Has Front and Back fields, and will create one card. Text you enter in
  Front will appear on the front of the card, and text you enter in Back
  will appear on the back of the card.

- **Basic (and reversed card)**\
  Like Basic, but creates two cards for the text you enter: one from
  front→back and one from back→front.

- **Basic (optional reversed card)**
  This is a front→back card, and optionally a back→front card. To do this,
  it has a third field called “Add Reverse.” If you enter any text into
  that field, a reverse card will be created. More information about this
  is available in the [Cards and Templates](templates/intro.md) section.

- **Basic (type in the answer)**
  This is essentially Basic, with an extra text box on the front where you
  can type your answer in, after flipping to the back your input would be
  checked and compared with the answer. More information is available in the
  [Checking Your Answer](templates/fields.md#checking-your-answer) section.

- **Cloze**\
  A note type which makes it easy to select text and turn it into a cloze
  deletion (e.g., “Man landed on the moon in \[…​\]” → “Man landed on the
  moon in 1969”). More information is available in the [cloze deletion](editing.md#cloze-deletion) section.

To add your own note types and modify existing ones, you can use Tools →
Manage Note Types from the main Anki window.

Notes and note types are common to your whole collection rather than
limited to an individual deck. This means you can use many different
types of notes in a particular deck, or have different cards generated
from a particular note in different decks. When you add notes using the
Add window, you can select what note type to use and what deck to use,
and these choices are completely independent of each other. You can also
change the note type of some notes [after you’ve already created them](browsing.md).

### Collection

Your 'collection' is all the material stored in Anki – your cards,
notes, decks, note types, deck options, and so on.

## Shared Decks

You can watch [a video about Shared Decks and Review
Basics](http://www.youtube.com/watch?v=QS2G-k2hQyg&yt:cc=on) on YouTube.

The easiest way to get started with Anki is to download a deck of cards
someone has shared:

1. Click the “Get Shared” button at the bottom of the deck list.

2. When you’ve found a deck you’re interested in, click the “Download”
   button to download a deck package.

3. Double-click on the downloaded package to load it into Anki, or
   File→Import it.

Please note that it’s not currently possible to add shared decks
directly to your AnkiWeb account. You need to import them with the
desktop program, then synchronize to upload them to AnkiWeb.

Creating your own deck is the most effective way to learn a complex
subject. Subjects like languages and the sciences can’t be understood
simply by memorizing facts — they require explanation and context to
learn effectively. Furthermore, inputting the information yourself
forces you to decide what the key points are, leading to a better
understanding.

If you are a language learner, you may be tempted to download a long
list of words and their translations, but this won’t teach you a
language any more than memorizing scientific equations will teach you
astrophysics. To learn properly, you need textbooks, teachers, or
exposure to real-world sentences.

    Do not learn if you do not understand.
    --SuperMemo

Most shared decks are created by people who are learning material
outside of Anki – from textbooks, classes, TV, etc. They select the
interesting points from what they learn and put them into Anki. They
make no effort to add background information or explanations to the
cards, because they already understand the material. So when someone
else downloads their deck and tries to use it, they’ll find it very
difficult as the background information and explanations are missing.

That is not to say shared decks are useless – simply that for complex
subjects, they should be used as a 'supplement' to external material,
not as a 'replacement' for it. If you’re studying textbook ABC and
someone has shared a deck of ideas from ABC, that’s a great way to save
some time. And for simple subjects that are basically a list of facts,
such as capital city names or pub quiz trivia, you probably don’t need
external material. But if you attempt to study complex subjects without
external material, you will probably meet with disappointing results.
