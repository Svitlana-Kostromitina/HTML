# HTML

**HTML (Hypertext Markup Language)** - це мова розмітки для створення веб-сторінок та веб-додатків. Вона використовується для створення структури веб-сторінок, описування їх зовнішнього вигляду та форматування контенту. HTML використовує теги, які вказують браузеру, як відображати різні елементи на веб-сторінці, такі як заголовки, параграфи, списки, таблиці, зображення та інші. HTML є основою для багатьох веб-технологій, таких як CSS (Cascading Style Sheets) та JavaScript, які використовуються для стилізації та динамічної поведінки веб-сторінок.

**Тег** - це елемент мови розмітки, який використовується для визначення різних елементів структури документа, таких як заголовки, абзаци, посилання, зображення тощо. Кожен тег складається з імені тегу, яке вказується в гострій дужці, і може мати додаткові атрибути, які визначають його властивості. Наприклад, тег `<p>` використовується для визначення абзаців в HTML документі, і має звичайно вигляд `<p>текст абзацу</p>`. Таким чином, теги дозволяють структурувати і форматувати вміст веб-сторінки.

Якщо порівнювати з прикладом із реального життя, то тег у HTML - це як цегла для будинку. Цегла це основний елемент, який використовується для будівництва будинку. Те ж саме і в HTML, тег це базовий елемент для створення html сторінки. За допомогою тега ми вказуємо браузеру, як правильно відобразити зміст html сторінки. Тег - це символ розмітки, що має ім'я та атрибут. Наприклад, тег `<img>` вказує браузеру, що потрібно вставити зображення на сторінку, атрибути цього тегу вказують шлях до зображення та його розміри.

**Ім'я тега** складається з літер, цифр та символів підкреслення, тире та крапки. Ім'я тега має бути унікальним для кожного тега на сторінці. Ім'я тегу визначає його роль і призначення. Наприклад, тег `<p>` використовується для відображення тексту як абзацу, а тег `<img>` використовується для відображення зображення на сторінці. Крім того, ім'я може використовуватись для звернення до тегу з CSS або JavaScript коду, щоб змінити його властивості або виконати певні дії. 
Наприклад, можна використати ім'я тегу `<div>` і задати для нього стилі з CSS, або використовувати ім'я тегу `<button>` для створення JavaScript-функцій, які будуть виконуватись при натисканні на кнопку.

**Атрибут** - це конструкція виду: ім'я атрибута = значення. Теги пишуться у трикутних дужках `<…..>`
Атрибути в HTML це параметри, які використовуються для задання додаткової інформації про елемент HTML. Кожен HTML елемент може мати набір атрибутів, які допомагають вказати параметри його відображення, взаємодії з користувачем або поведінки.
Наприклад, в тезі `<img src="image.jpg" alt="Alternative text">` атрибут src вказує шлях до зображення, атрибут alt - альтернативний текст, який буде відображено в разі, якщо зображення не може бути завантажене або для осіб з відключеним зором.
Теги у HTML використовуються для вказання типу елементів і групування різних частин вмісту на веб-сторінці. Вони завжди записуються у трикутні дужки, де перший тег вказує початок елемента, а другий - його кінець. Наприклад, `<p>Текст абзацу</p>` вказує на те, що між тегами `<p>` та `</p>` міститься текст абзацу.

**Метадані** - дані, які використовуються для опису веб-сторінки, наприклад, заголовок, ключові слова та опис.

**Контент** - текст, зображення, відео та інші елементи, що містяться в елементах.

**Базовий каркас html сторінки :**

`<!doctype html>`

`<html>`
  
`<head>` 
  
`<meta charset=”utf-8”>`
  
 `<title>Назва</title>`
  
`</head>`  
  
`<body>` 
  
 `</body>` 
  
`</html>`   

----

`<!doctype html>` - це оголошення типу документа, що вказує на те, що ця сторінка є HTML документом;

`<html>` - цей тег позначає початок HTML документа;

`<head>` - визначає заголовок документа, який містить інформацію про документ, таку як метатеги, посилання на зовнішні файли стилів та скрипти. Він не відображається в самому документі, а використовується браузером та пошуковими системами для правильного індексування та відображення документа.

`<meta charset=”utf-8”>` - цей тег визначає кодування символів, що використовується на сторінці. У даному випадку, використовується UTF-8, що дозволяє використовувати символи з будь-якої мови;

`<title>` - цей тег визначає заголовок сторінки, який відображається у вікні браузера та в результатах пошуку;

`<body>` - цей тег позначає початок основної частини сторінки, де розміщується весь контент.

### Основні HTML теги :

`<html>` - тег, який вказує на те, що документ є HTML-документом і містить усі інші теги.

`<head>` - тег, який містить інформацію про документ, що не відображається безпосередньо на сторінці. Зазвичай тут вказують заголовок документа, мета-теги (наприклад, для пошукових систем) та посилання на зовнішні ресурси (стилі, скрипти і т.д.).

`<body>` - тег, який містить весь відображуваний контент документа, такий як текст, зображення, посилання і т.д.

`<title>` - тег, який вказує заголовок документа, який відображається в рядку заголовка браузера. Цей тег розміщується в `<head>`.

`<h1>` - `<h6>` - теги, які вказують заголовки з різним рівнем важливості.( `<h1>` - найбільш важливий, `<h6>` - найменш.) Зазвичай вони використовуються для розділів або частин сторінки.

`<p>` - тег, який використовується для форматування тексту в абзац. 

`<a>` - тег, який використовується для створення посилань на інші сторінки або ресурси.

`<img>` - тег, який використовується для вставки зображення на сторінку.

`<ul>` - тег, який використовується для створення ненумерованого списку.

`<ol>` - тег, який використовується для створення нумерованого списку.

`<li>` - тег, який використовується для опису елементів списків `<ul>` або `<ol>`.

`<link>` - це тег, який використовується для підключення зовнішніх файлів стилів CSS до HTML сторінки.

`<script>` - це тег, який використовується для вставки скриптів JavaScript в HTML сторінку.

`<a href>` - це тег, який використовується для створення посилань на інші сторінки або ресурси в Інтернеті.

`<table>` - тег, який використовується для створення таблиці.

`<form>` - тег, який використовується для створення форми, яку користувач може заповнити і відправити на сервер.

`<div>` - використовується, щоб групувати блоки інформації та форматувати її за допомогою CSS.

`<span>` - для виділення деякого тексту або частини контенту. Тег `<span>` є рядковим і застосовується до внутрішніх (inline) елементів сторінки, тобто до слів, фраз, які знаходяться в межах абзацу або невеликого фрагмента тексту, змісту тощо.

`<header>` - це тег, який використовується для відображення заголовка або верхньої частини сторінки. Зазвичай, в нього включають логотип, назву сайту, посилання на розділи, контактну інформацію та інші елементи, що вважаються загальними для всієї сторінки.

`<footer>` - це тег, який використовується для відображення нижньої частини сторінки. Зазвичай, в нього включають копірайт, посилання на соціальні мережі, контактну інформацію та інші елементи, що вважаються загальними для всієї сторінки.

`<nav>` - це тег, який використовується для відображення навігаційного меню, яке містить посилання на інші сторінки сайту або на інші частини поточної сторінки.

`<article>` - це тег, який використовується для відображення статті або контенту, який може бути незалежним від іншого контенту на сторінці. Наприклад, це може бути новина, блог-пост або опис товару.

`<button>` - для створення кнопок.

`<input>` - для створення текстових полів, чекбоксів, радіокнопок і т.д.

`<label>` - для створення підписів до елементів форми.

`<select>`, `<option>` - для створення випадаючих списків.

`<textarea>` - для створення багаторядкових текстових полів.

`<video>`, `<audio>` - для вставки відео і аудіо контенту.







