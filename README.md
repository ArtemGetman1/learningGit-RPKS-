<h1>Лабораторна робота 1: Вивчення git</h1>

Налаштування глобальних параметрів Git для коректної обробки закінчень рядків. Команда `git config --global core.autocrlf true` забезпечує автоматичну конвертацію закінчень рядків, а `core.safecrlf warn` попереджає про можливі проблеми з конвертацією.

<p align="center">
  <img src="Screenshots/(1).png" alt="(1)"/>
</p>

<hr>

Створення робочого середовища проекту. Команда `mkdir work` створює нову директорію, а `cd work` виконує перехід до неї для подальшої роботи.

<p align="center">
  <img src="Screenshots/(2).png" alt="(2)"/>
</p>

<hr>

Створення першого файлу проекту hello.html з базовим текстом "Hello, World" за допомогою команди `touch`, що ініціалізує пустий файл в робочій директорії.

<p align="center">
  <img src="Screenshots/(3).png" alt="(3)"/>
</p>

<hr>

Налаштування ідентифікації користувача в Git. Команди встановлюють ім'я користувача (`git config --global user.name getmanartem`) та електронну пошту (`git config --global user.email getmanart24@gmail.com`) для майбутніх комітів.

<p align="center">
  <img src="Screenshots/(4).png" alt="(4)"/>
</p>

<hr>

Встановлення назви основної гілки проекту. Команда `git config --global init.defaultBranch main` визначає 'main' як назву гілки за замовчуванням для всіх нових репозиторіїв.

<p align="center">
  <img src="Screenshots/(5).png" alt="(5)"/>
</p>

<hr>


Перевірка статусу репозиторію за допомогою команди `git status`. На даний момент немає змін для коміту, робоче дерево чисте.

<p align="center">
 <img src="Screenshots/(6).png" alt="(6)"/>
</p>

<hr>

Додавання HTML-тегу h1 з текстом "Hello, World" до файлу hello.html для створення базової структури веб-сторінки.

<p align="center">
 <img src="Screenshots/(7).png" alt="(7)"/>
</p>

<hr>

Повторна перевірка статусу репозиторію. Git показує, що файл hello.html був змінений, але зміни ще не додані до індексу (not staged).

<p align="center">
 <img src="Screenshots/(8).png" alt="(8)"/>
</p>

<hr>

Ініціалізація нового Git репозиторію в поточній директорії за допомогою команди `git init`. Створюється прихована директорія .git для зберігання всієї службової інформації.

<p align="center">
 <img src="Screenshots/(9).png" alt="(9)"/>
</p>

<hr>

Додавання файлу hello.html до індексу за допомогою `git add` та створення першого коміту з повідомленням "Initial Commit" використовуючи команду `git commit -m`.

<p align="center">
 <img src="Screenshots/(10).png" alt="(10)"/>
</p>

<hr>

Створення коміту зі змінами в файлі hello.html. Було додано тег h1, що підтверджується статистикою: 1 файл змінено, 1 вставка, 1 видалення.

<p align="center">
 <img src="Screenshots/(11).png" alt="(11)"/>
</p>

<hr>

Перевірка статусу репозиторію після коміту. Git показує, що робоче дерево чисте - всі зміни збережені.

<p align="center">
 <img src="Screenshots/(12).png" alt="(12)"/>
</p>

<hr>

Оновлення структури HTML-документа. Додано базові теги `<html>` і `<body>` для створення валідної HTML-сторінки.

<p align="center">
 <img src="Screenshots/(13).png" alt="(13)"/>
</p>

<hr>

Додавання оновленого файлу hello.html до індексу. Git показує, що файл готовий до коміту.

<p align="center">
 <img src="Screenshots/(14).png" alt="(14)"/>
</p>

<hr>

Відображення вікна редактора для введення повідомлення коміту. Git показує які файли будуть включені до коміту та очікує на введення опису змін.

<p align="center">
 <img src="Screenshots/(15).png" alt="(15)"/>
</p>
<hr>

Створення коміту з доданням стандартних HTML тегів. Команда підтверджує зміни: 1 файл змінено, 5 вставок та 1 видалення. Після коміту Git показує наявність нових незафіксованих змін у файлі.

<p align="center">
 <img src="Screenshots/(16).png" alt="(16)"/>
</p>

<hr>

Використання команди `git add .` для додавання всіх змінених файлів до індексу. Статус показує, що зміни готові до коміту.

<p align="center">
 <img src="Screenshots/(17).png" alt="(17)"/>
</p>

<hr>

Додавання конкретного файлу hello.html до індексу за допомогою команди `git add hello.html`.

<p align="center">
 <img src="Screenshots/(18).png" alt="(18)"/>
</p>

<hr>

Додавання тегу `<head>` до структури HTML-документа, що робить його більш стандартизованим та готовим до подальших модифікацій.

<p align="center">
 <img src="Screenshots/(19).png" alt="(19)"/>
</p>

<hr>

Перевірка статусу репозиторію, яка показує, що файл hello.html має зміни як в індексі (staged), так і в робочій директорії (not staged).

<p align="center">
 <img src="Screenshots/(20).png" alt="(20)"/>
</p>
<hr>

Перегляд історії комітів у скороченому форматі за допомогою команди `git log --pretty=oneline`. Показує ID комітів та їх повідомлення в одному рядку.

<p align="center">
 <img src="Screenshots/(21).png" alt="(21)"/>
</p>

<hr>

Демонстрація різних параметрів команди `git log`:
- `--max-count=2` - обмеження кількості показаних комітів
- `--since="5 minutes ago"` - фільтрація за часом створення
- `--until="5 minutes ago"` - фільтрація до вказаного часу
- `--author="getmanartem"` - фільтрація за автором
- `--all` - показ всіх комітів

<p align="center">
 <img src="Screenshots/(22).png" alt="(22)"/>
</p>

<hr>

Використання розширеного формату виводу історії з часовими мітками та інформацією про автора за допомогою команди `git log --all --pretty-format:"%h %cd %s (%an)" --since="7 days ago"`.

<p align="center">
 <img src="Screenshots/(23).png" alt="(23)"/>
</p>

<hr>

Створення нового коміту з повідомленням "Added HTML header". Git підтверджує зміну 1 файлу з 2 вставками.

<p align="center">
 <img src="Screenshots/(24).png" alt="(24)"/>
</p>

<hr>

Детальний перегляд історії комітів з відображенням повної інформації: автор, дата, email та опис змін для кожного коміту.

<p align="center">
 <img src="Screenshots/(25).png" alt="(25)"/>
</p>
<hr>

Використання команди `git checkout v1^` для перегляду стану проекту на момент створення тегу v1. Система переходить в стан 'detached HEAD', що дозволяє експериментувати з кодом без впливу на основну гілку.

<p align="center">
 <img src="Screenshots/(26).png" alt="(26)"/>
</p>

<hr>

Налаштування формату виводу логу за допомогою команд:
- `git config --global format.pretty '%h %ad | %s%d [%an]'`
- `git config --global log.date short`
Це змінює формат виводу дат та інформації про коміти.

<p align="center">
 <img src="Screenshots/(27).png" alt="(27)"/>
</p>

<hr>

Перехід до початкового коміту за допомогою `git checkout 8bd1197`. Команда показує стан проекту на момент його створення, коли був лише простий текст "Hello, World".

<p align="center">
 <img src="Screenshots/(28).png" alt="(28)"/>
</p>

<hr>

Повернення до основної гілки за допомогою `git switch main`. Перегляд поточного стану файлу hello.html, який містить повну HTML структуру.

<p align="center">
 <img src="Screenshots/(29).png" alt="(29)"/>
</p>

<hr>

Створення тегу v1 та перегляд історії комітів, де тепер видно позначку тегу в логах. Це допомагає відзначити важливі етапи розробки.

<p align="center">
 <img src="Screenshots/(30).png" alt="(30)"/>
</p>
<hr>

Повернення до гілки main з режиму перегляду тегу v1-beta. Git підтверджує успішне переключення на основну гілку розробки.

<p align="center">
 <img src="Screenshots/(31).png" alt="(31)"/>
</p>

<hr>

Додавання коментаря "This is a bad comment. We want to revert it." до файлу hello.html. Цей коментар буде використано для демонстрації відміни змін.

<p align="center">
 <img src="Screenshots/(32).png" alt="(32)"/>
</p>

<hr>

Переміщення між тегами за допомогою команди `git checkout`. Спочатку перехід до тегу v1, потім до v1-beta, що демонструє різні стани проекту.

<p align="center">
 <img src="Screenshots/(33).png" alt="(33)"/>
</p>

<hr>

Перегляд доступних тегів у репозиторії за допомогою команди `git tag`. Показано два створені теги: v1 та v1-beta.

<p align="center">
 <img src="Screenshots/(34).png" alt="(34)"/>
</p>

<hr>

Використання команди `git log main --all` для перегляду повної історії комітів, включаючи інформацію про теги та гілки.

<p align="center">
 <img src="Screenshots/(35).png" alt="(35)"/>
</p>
<hr>

Використання `git checkout hello.html` для відміни небажаних змін у файлі. Після виконання команди Git підтверджує оновлення файлу та показує чисте робоче дерево.

<p align="center">
 <img src="Screenshots/(36).png" alt="(36)"/>
</p>

<hr>

Додавання коментаря "This is an unwanted but staged comment" до секції head файлу hello.html для демонстрації роботи з індексом.

<p align="center">
 <img src="Screenshots/(37).png" alt="(37)"/>
</p>

<hr>

Додавання змін до індексу за допомогою команди `git add hello.html` для подальшого комміту.

<p align="center">
 <img src="Screenshots/(38).png" alt="(38)"/>
</p>

<hr>

Перевірка статусу репозиторію після додавання змін. Git показує, що файл готовий до коміту (зміни в індексі).

<p align="center">
 <img src="Screenshots/(39).png" alt="(39)"/>
</p>

<hr>

Повторна перевірка статусу, яка показує наявність змін у файлі hello.html, які ще не додані до індексу (not staged).

<p align="center">
 <img src="Screenshots/(40).png" alt="(40)"/>
</p>
<hr>

Використання команди `git revert` для створення нового коміту, який скасовує зміни попереднього небажаного коміту, підтверджуючи зміну 1 файлу.
<p align="center">
 <img src="Screenshots/(41).png" alt="(41)"/>
</p>
<hr>

Виконання команди `git reset HEAD hello.html` для скидання змін з індексу, повертаючи файл до попереднього стану. Git підтверджує, що файл було "unstaged".
<p align="center">
 <img src="Screenshots/(42).png" alt="(42)"/>
</p>
<hr>

Використання `git checkout hello.html` для відновлення файлу з останнього коміту, після чого виконання `git status` показує чисте робоче дерево без змін.
<p align="center">
 <img src="Screenshots/(43).png" alt="(43)"/>
</p>
<hr>

Перегляд вмісту файлу hello.html у редакторі коду, який містить базову HTML структуру з заголовком "Hello, World!" та закоментованим рядком про небажану але закомічену зміну.
<p align="center">
 <img src="Screenshots/(44).png" alt="(44)"/>
</p>
<hr>

Додавання файлу hello.html до індексу та створення нового коміту з повідомленням "oops, we didn't want this commit", що підтверджує додавання одного файлу.
<p align="center">
 <img src="Screenshots/(45).png" alt="(45)"/>
</p>
<hr>

Виконання команди `git reset --hard v1` для жорсткого скидання HEAD до тегу v1, що відображає стан проекту на момент додавання HTML заголовку.
<p align="center">
<img src="Screenshots/(46).png" alt="(46)"/>
</p>
<hr>

Перегляд історії комітів за допомогою `git log`, що показує хронологію змін від початкового коміту до додавання HTML заголовку.
<p align="center">
<img src="Screenshots/(47).png" alt="(47)"/>
</p>
<hr>

Використання `git log --all` для перегляду повної історії комітів, включаючи revert-коміт та коміт з небажаними змінами. Після цього видалення тегу 'oops' командою `git tag -d oops`.
<p align="center">
<img src="Screenshots/(48).png" alt="(48)"/>
</p>
<hr>

Повторний перегляд історії комітів, що підтверджує успішне видалення тегу 'oops' та збереження всіх інших комітів та тегів.
<p align="center">
<img src="Screenshots/(49).png" alt="(49)"/>
</p>
<hr>

Створення нового тегу 'oops' та перевірка історії комітів для підтвердження успішного створення тегу.
<p align="center">
<img src="Screenshots/(50).png" alt="(50)"/>
</p>
<hr>

Додавання інформації про автора в файл hello.html у вигляді коментаря, що містить ім'я та email.
<p align="center">
<img src="Screenshots/(51).png" alt="(51)"/>
</p>
<hr>

Додавання змін до індексу за допомогою `git add hello.html` та створення коміту з повідомленням про додавання інформації про авторські права та email.
<p align="center">
<img src="Screenshots/(52).png" alt="(52)"/>
</p>
<hr>

Перегляд історії комітів за допомогою `git log`, що показує новий коміт з доданою інформацією про авторські права.
<p align="center">
<img src="Screenshots/(53).png" alt="(53)"/>
</p>
<hr>

Модифікація коментаря автора у файлі hello.html, видалення email адреси для спрощення.
<p align="center">
<img src="Screenshots/(54).png" alt="(54)"/>
</p>
<hr>

Створення нового коміту зі зміненим коментарем автора та перегляд оновленої історії комітів за допомогою `git log`.
<p align="center">
<img src="Screenshots/(55).png" alt="(55)"/>
</p>
<hr>

Додавання посилання на CSS файл до HTML документу за допомогою тегу link, що вказує на зовнішній файл стилів style.css.
<p align="center">
<img src="Screenshots/(56).png" alt="(56)"/>
</p>
<hr>

Створення нової гілки 'style' за допомогою команди `git switch -c style` для роботи над стилізацією проекту.
<p align="center">
<img src="Screenshots/(57).png" alt="(57)"/>
</p>
<hr>

Створення нового файлу style.css за допомогою команди `touch style.css` для додавання стилів.
<p align="center">
<img src="Screenshots/(58).png" alt="(58)"/>
</p>
<hr>

Додавання CSS правила для зміни кольору заголовку h1 на червоний у файлі style.css.
<p align="center">
<img src="Screenshots/(59).png" alt="(59)"/>
</p>
<hr>

Додавання файлу style.css до індексу та створення коміту з повідомленням про додавання таблиці стилів.
<p align="center">
<img src="Screenshots/(60).png" alt="(60)"/>
</p>
<hr>

Перемикання на гілку 'main' та перегляд вмісту файлу hello.html, який не містить посилання на таблицю стилів.
<p align="center">
<img src="Screenshots/(61).png" alt="(61)"/>
</p>
<hr>

Перемикання назад на гілку 'style' та перевірка вмісту файлу hello.html, який містить доданий тег link для підключення style.css.
<p align="center">
<img src="Screenshots/(62).png" alt="(62)"/>
</p>
<hr>

Перегляд історії змін файлів hello.html та style.css за допомогою `git log [filename]`, що показує відповідні коміти для кожного файлу.
<p align="center">
<img src="Screenshots/(63).png" alt="(63)"/>
</p>
<hr>

Додавання змін у файлі hello.html до індексу та створення коміту з повідомленням про включення таблиці стилів.
<p align="center">
<img src="Screenshots/(64).png" alt="(64)"/>
</p>
<hr>

Перегляд повної історії комітів за допомогою `git log --all`, що показує всі зміни в обох гілках, включаючи додавання стилів.
<p align="center">
<img src="Screenshots/(65).png" alt="(65)"/>
</p>
<hr>
Створення нової директорії 'css' та переміщення файлу style.css до неї за допомогою команди `git mv`. Також перегляд історії змін файлу за допомогою `git log --follow`.
<p align="center">
<img src="Screenshots/(66).png" alt="(66)"/>
</p>
<hr>

Створення файлу README з базовим описом проекту, що пояснює його призначення як навчального прикладу з туторіалу GitHowTo.
<p align="center">
<img src="Screenshots/(67).png" alt="(67)"/>
</p>
<hr>

Перемикання на гілку 'main', додавання файлу README до індексу та створення коміту з описовим повідомленням.
<p align="center">
<img src="Screenshots/(68).png" alt="(68)"/>
</p>
<hr>

Використання команди `git show v1` для перегляду змін, які були внесені в коміті з тегом v1, що додав HTML заголовок.
<p align="center">
<img src="Screenshots/(69).png" alt="(69)"/>
</p>
<hr>

Перейменування файлу hello.html на index.html за допомогою команди `mv` та оновлення індексу Git для відстеження змін.
<p align="center">
<img src="Screenshots/(70).png" alt="(70)"/>
</p>
<hr>

Оновлення вмісту HTML файлу: додавання заголовку сторінки та параграфу з текстом про вивчення Git.
<p align="center">
<img src="Screenshots/(71).png" alt="(71)"/>
</p>
<hr>

Використання команди `git log --all --graph` для візуалізації історії комітів у вигляді графу, що показує взаємозв'язки між гілками та комітами.
<p align="center">
<img src="Screenshots/(72).png" alt="(72)"/>
</p>
<hr>

Перемикання на гілку 'style' за допомогою команди `git switch style` для подальшої роботи над стилізацією.
<p align="center">
<img src="Screenshots/(73).png" alt="(73)"/>
</p>
<hr>

Автоматичне злиття (merge) гілки 'main' в гілку 'style' з використанням стратегії 'ort', що додає файл README.
<p align="center">
<img src="Screenshots/(74).png" alt="(74)"/>
</p>
<hr>

Перемикання назад на гілку 'main' для продовження роботи над основною версією проекту.
<p align="center">
<img src="Screenshots/(75).png" alt="(75)"/>
</p>
<hr>

Виникнення конфлікту при злитті гілок через одночасні зміни у файлі index.html. Git відображає різні версії файлу для порівняння.
<p align="center">
<img src="Screenshots/(76).png" alt="(76)"/>
</p>
<hr>

Скасування процесу злиття за допомогою команди `git merge --abort` та перевірка статусу репозиторію.
<p align="center">
<img src="Screenshots/(77).png" alt="(77)"/>
</p>
<hr>

Додавання файлу hello.html та створення нового коміту з повідомленням про додавання мета-заголовку.
<p align="center">
<img src="Screenshots/(78).png" alt="(78)"/>
</p>
<hr>

Перегляд історії комітів у вигляді графу за допомогою `git log --all --graph`, що показує нову зміну та структуру гілок.
<p align="center">
<img src="Screenshots/(79).png" alt="(79)"/>
</p>
<hr>

Спроба злиття гілки main в style, що призводить до конфлікту в файлі index.html через одночасні зміни в обох гілках.
<p align="center">
<img src="Screenshots/(80).png" alt="(80)"/>
</p>
<hr>

Вирішення конфлікту злиття шляхом вибору потрібних змін, додавання файлу до індексу та створення коміту з повідомленням про вирішення конфлікту.
<p align="center">
<img src="Screenshots/(81).png" alt="(81)"/>
</p>
<hr>

Використання команди `git reset --hard HEAD~2` для скидання HEAD на два коміти назад, до моменту перейменування файлу hello.html.
<p align="center">
<img src="Screenshots/(82).png" alt="(82)"/>
</p>
<hr>

Перегляд історії комітів у вигляді графу після скидання HEAD, що показує поточний стан гілки.
<p align="center">
<img src="Screenshots/(83).png" alt="(83)"/>
</p>
<hr>

Спроба злиття гілки main, що призводить до конфлікту в файлі index.html через різні зміни в обох гілках.
<p align="center">
<img src="Screenshots/(84).png" alt="(84)"/>
</p>
<hr>

Остаточний вигляд файлу index.html після вирішення конфлікту злиття, що містить всі необхідні зміни з обох гілок.
<p align="center">
<img src="Screenshots/(85).png" alt="(85)"/>
</p>
<hr>

Підготовка файлу hello.html до злиття, що включає заголовок сторінки та підключення таблиці стилів.
<p align="center">
<img src="Screenshots/(86).png" alt="(86)"/>
</p>
<hr>

Використання команди `git add .` для додавання всіх змін до індексу.
<p align="center">
<img src="Screenshots/(87).png" alt="(87)"/>
</p>
<hr>

Перегляд статусу та історії комітів після додавання змін, що показує оновлений стан репозиторію.
<p align="center">
<img src="Screenshots/(88).png" alt="(88)"/>
</p>
<hr>

Спроба виконати rebase гілки main, що призводить до конфліктів у файлі hello.html через одночасні зміни.
<p align="center">
<img src="Screenshots/(89).png" alt="(89)"/>
</p>
<hr>

Відображення конфліктних змін у файлі hello.html з можливістю вибору між поточними та вхідними змінами.
<p align="center">
<img src="Screenshots/(90).png" alt="(90)"/>
</p>
<hr>

Перехід на рівень вище в директорії за допомогою команди `cd ..` та перегляд поточного шляху.
<p align="center">
<img src="Screenshots/(91).png" alt="(91)"/>
</p>
<hr>

Клонування репозиторію work в нову директорію home за допомогою команди `git clone`.
<p align="center">
<img src="Screenshots/(92).png" alt="(92)"/>
</p>
<hr>

Перехід до склонованого репозиторію та перегляд його вмісту, що містить README, директорію css та файл index.html.
<p align="center">
<img src="Screenshots/(93).png" alt="(93)"/>
</p>
<hr>

Перемикання на гілку main та злиття змін з гілки style, що призводить до оновлення файлів та їх перейменування.
<p align="center">
<img src="Screenshots/(94).png" alt="(94)"/>
</p>
<hr>

Перегляд повної історії комітів у вигляді графу після успішного злиття гілок, що показує всі зміни в проекті.
<p align="center">
<img src="Screenshots/(95).png" alt="(95)"/>
</p>
<hr>

Перегляд усіх гілок репозиторію, включаючи віддалені, за допомогою команди `git branch -a`.
<p align="center">
<img src="Screenshots/(96).png" alt="(96)"/>
</p>
<hr>

Перехід до оригінального репозиторію work за допомогою команди `cd ../work`.
<p align="center">
<img src="Screenshots/(97).png" alt="(97)"/>
</p>
<hr>

Перегляд повної історії комітів за допомогою `git log --all`, що показує всі зміни включно з віддаленими гілками.
<p align="center">
<img src="Screenshots/(98).png" alt="(98)"/>
</p>
<hr>

Перегляд налаштувань віддаленого репозиторію за допомогою команд `git remote` та `git remote show origin`.
<p align="center">
<img src="Screenshots/(99).png" alt="(99)"/>
</p>
<hr>

Перевірка поточної гілки за допомогою команди `git branch`, що показує активну гілку main.
<p align="center">
<img src="Screenshots/(100).png" alt="(100)"/>
</p>
<hr>

Перегляд вмісту файлу README за допомогою команди `cat`, що містить опис проекту.
<p align="center">
<img src="Screenshots/(101).png" alt="(101)"/>
</p>
<hr>

Злиття змін з віддаленої гілки origin/main, що оновлює файл README.
<p align="center">
<img src="Screenshots/(102).png" alt="(102)"/>
</p>
<hr>

Оновлений вміст файлу README з доданим текстом "(changed in origin)".
<p align="center">
<img src="Screenshots/(103).png" alt="(103)"/>
</p>
<hr>

Додавання змін файлу README та створення коміту з повідомленням про зміни в оригінальному репозиторії.
<p align="center">
<img src="Screenshots/(104).png" alt="(104)"/>
</p>
<hr>

Перехід до директорії home та отримання змін з віддаленого репозиторію за допомогою `git fetch`, після чого перегляд оновленої історії комітів.
<p align="center">
<img src="Screenshots/(105).png" alt="(105)"/>
</p>
<hr>

Перехід до директорії work та додавання нового віддаленого репозиторію з назвою shared.
<p align="center">
<img src="Screenshots/(106).png" alt="(106)"/>
</p>
<hr>

Перегляд оновленого вмісту файлу README з відміткою про зміни в origin.
<p align="center">
<img src="Screenshots/(107).png" alt="(107)"/>
</p>
<hr>

Виконання команди `git pull` для отримання змін з віддаленого репозиторію, яка показує, що локальна версія вже актуальна.
<p align="center">
<img src="Screenshots/(108).png" alt="(108)"/>
</p>
<hr>

Налаштування відстеження віддаленої гілки style та перегляд останніх двох комітів за допомогою `git log --max-count=2`.
<p align="center">
<img src="Screenshots/(109).png" alt="(109)"/>
</p>
<hr>

Створення чистого клону репозиторію work за допомогою команди `git clone --bare` та перегляд його структури.
<p align="center">
<img src="Screenshots/(110).png" alt="(110)"/>
</p>
<hr>

Запуск Git демона в режимі verbose для забезпечення мережевого доступу до репозиторію.
<p align="center">
<img src="Screenshots/(111).png" alt="(111)"/>
</p>
<hr>

Клонування репозиторію з локального сервера за допомогою протоколу git:// в нову директорію network_work.
<p align="center">
<img src="Screenshots/(112).png" alt="(112)"/>
</p>
<hr>

Перегляд оновленого вмісту файлу README з відміткою про зміни в origin та shared репозиторіях.
<p align="center">
<img src="Screenshots/(113).png" alt="(113)"/>
</p>
<hr>

Додавання змін до файлу README, створення коміту та відправлення змін до віддаленого репозиторію shared.
<p align="center">
<img src="Screenshots/(114).png" alt="(114)"/>
</p>
<hr>

Налаштування відстеження гілки shared/main та отримання змін з віддаленого репозиторію за допомогою git pull.
<p align="center">
<img src="Screenshots/(115).png" alt="(115)"/>
</p>
<hr>
