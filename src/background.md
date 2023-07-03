# Передумови

<!-- toc -->

Anki це програма, яка полегшує запам'ятовування. Оскільки вона є значно
ефективнішою за традиційні методи навчання, Ви можете або суттєво зменшити час
навчання, або ж суттєво збільшити кількість вивченого матеріалу.

Отримати користь від Anki може будь-хто, у кого є потреба щоденно
запам'ятовувати. Оскільки вона не прив'язана до типу контенту та підтримує
зображення, аудіо, відео та наукове форматування (через LaTeX), її можливості
є безкінечними. Наприклад:

- вивчення мови

- підготовка до медичних та юридичних іспитів

- запам'ятовування імен та облич людей

- пригадування географії

- вивчення довгих віршів

- навіть практика гітарних акордів!

В основі Anki лежить дві прості концепції: **активна перевірка пригадування**
та **інтервальне повторення**. Незважаючи на те, що про них багато писалося в
науковій літературі протягом тривалого часу, більшості учнів вони невідомі.
Розуміння того, як вони працюють, дозволить Вам стати біль ефективним учнем.

## Активна перевірка пригадування

_Активна перевірка пригадування_ полягає в отриманні запитання та спробі
запам'ятати відповідь. На відміну від _пасивного навчання_, де ми читаємо,
дивимось або щось слухаємо не зупиняючись на перевірку того, чи ми знаємо
відповідь. Дослідження показують, що для формування сильної пам'яті, активна
перевірка пригадування є значно ефективнішою ніж пасивне навчання. Цьому є
дві причини:

- Спроба відтворення чогось _посилює_ пам'ять, збільшуючи ймовірність того, що
  ми зможемо пригадати знову.

- Коли ми не можемо відповісти на запитання, вона вказує що слід повернутися
  до матеріалу і повторити або ж наново вивчити його.

Ймовірно, Ви зустрічалися з активною перевіркою пригадування в шкільні роки
навіть не усвідомлюючи цього. Коли хороші вчителі дають Вам ряд запитань після
прочитання статті, або проводять щотижневі контрольні роботи перевірки
успішності, вони роблять це не для того, щоб просто перевірити чи Ви засвоїли
матеріал. Завдяки перевіркам вони підвищують Ваші шанси запам'ятати матеріал на
майбутнє.

Хорошим методом включення активної перевірки пригадування у Ваш навчальний
процес є використання _навчальних карток_. На звичайних паперових навчальних
картках Ви записуєте з однієї сторони запитання, а з іншої - відповідь. Не
дивлячись на зворотну сторону картки, поки Ви думаєте про відповідь, Ви можете
навчатися значно ефективніше порівняно з пасивним переглядом.

## Use It or Lose It

Our brains are efficient machines, and they rapidly discard information
that doesn't seem useful. Chances are that you don't remember what you
had for dinner on Monday two weeks ago, because this information is not
usually useful. If you went to a fantastic restaurant that day and spent
the last two weeks telling people about how great it was, however,
you're likely to still remember in vivid detail.

The brain's "use it or lose it" policy applies to everything we learn.
If you spend an afternoon memorizing some science terms, and then don't
think about that material for two weeks, you'll probably have forgotten
most of it. In fact, studies show we forget about 75% of material learnt
within a 48 hour period. This can seem pretty depressing when you need
to learn a lot of information!

The solution is simple, however: _review_. By reviewing newly-learnt
information, we can greatly reduce forgetting.

The only problem is that traditionally, reviewing has not been very practical. If
you are using paper flashcards, it's easy to flick through all of them
if you only have 30 of them to review, but as the number grows to 300 or
3000, it quickly becomes unwieldy.

## Spaced Repetition

The _spacing effect_ was reported by a German psychologist Hermann Ebbinghaus in 1885. He
observed that we tend to remember things more effectively, if we spread
reviews out over time, instead of studying multiple times in one
session. Since the 1930s, there have been a number of proposals for
utilizing the spacing effect to improve learning, in what has come to be
called _spaced repetition_.

One example was in 1972, when a German scientist called Sebastian Leitner
popularized a method of spaced repetition with paper flashcards. By
separating the paper cards into a series of boxes, and moving the
cards to a different box on each successful or unsuccessful review, it
was possible to see at a glance a rough estimate of how well a card was
known and when it should be reviewed again. This was a great improvement
over a single box of cards, and it has been widely adopted by
computerized flashcard software. It is a rather rough approach however,
as it cannot give you an exact date on which you should review something
again, and it does not cope very well with material of varying
difficulty.

The biggest developments in the last 30 years have come from the authors
of SuperMemo, a commercial flashcard program that implements spaced
repetition. SuperMemo pioneered the concept of a system that keeps track
of the ideal time to review material and optimizes itself based on the
performance of the user.

In SuperMemo's spaced repetition system, every time you answer a
question, you tell the program how well you were able to remember it —
whether you forgot completely, made a small mistake, remembered with
trouble, remembered easily, etc. The program uses this feedback to
decide the optimal time to show you the question again. Since a memory
gets stronger each time you successfully recall it, the time between
reviews gets bigger and bigger — so you may see a question for the first
time, then 3 days later, 15 days later, 45 days later, and so on.

This was a revolution in learning, as it meant material could be learnt
and retained with the absolute minimum amount of effort necessary.
SuperMemo's slogan sums it up: with spaced repetition, you can: "forget
about forgetting".

## Why Anki?

While there is no denying the huge impact SuperMemo has had on the
field, it is not without its problems. The program is often criticized
for being buggy and difficult to navigate. It only runs on Windows
computers. It is proprietary software, meaning that end-users cannot extend it
or access the raw data. And while very old versions have been made available
for free, they are quite limited for modern use.

Anki addresses these issues. There are free clients for Anki available
on many platforms, so struggling students and teachers with budgetary
constraints are not left out. Anki is open source, with an already
flourishing library of add-ons contributed by end-users. It is
multi-platform, running on Windows, macOS, Linux/FreeBSD, and some
mobile devices. And it is considerably easier to use than SuperMemo.

Anki's spaced repetition system is based on an older version of the
SuperMemo algorithm called [SM-2](faqs.md).
