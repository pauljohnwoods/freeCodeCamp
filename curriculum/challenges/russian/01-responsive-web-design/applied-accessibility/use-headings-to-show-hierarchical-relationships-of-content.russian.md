---
id: 587d774d367417b2b2512a9e
title: Use Headings to Show Hierarchical Relationships of Content
challengeType: 0
videoUrl: ''
localeTitle: Использовать заголовки для отображения иерархических отношений содержимого
---

## Description
<section id="description"> Заголовки (элементы <code>h1</code> <code>h6</code> ) являются тегами рабочей лошади, которые помогают обеспечить структуру и маркировку вашего контента. Считыватели экрана могут быть настроены на чтение только заголовков на странице, чтобы пользователь получал сводку. Это означает, что для ярлыков заголовков в вашей разметке важно иметь семантический смысл и относиться друг к другу, а не просто выбирать их значения размера. <em>Семантическое значение</em> означает, что тег, который вы используете вокруг содержимого, указывает тип информации, который он содержит. Если бы вы писали статью с введением, телом и выводом, то не имело бы смысла делать вывод в виде подраздела тела в вашей схеме. Это должен быть его собственный раздел. Точно так же теги заголовков на веб-странице должны идти в порядке и указывать иерархические отношения вашего контента. Заголовки с равным (или более высоким) рангом запускают новые подразумеваемые разделы, заголовки с младшими ранговыми подразделами предыдущего. Например, страница с элементом <code>h2</code> за которой следуют несколько подразделов с меткой <code>h4</code> будет путать пользователя с экрана. С шестью вариантами заманчиво использовать тег, потому что он выглядит лучше в браузере, но вы можете использовать CSS для редактирования относительного размера. В последнем случае на каждой странице всегда должен быть один (и только один) элемент <code>h1</code> , который является основным предметом вашего контента. Этот и другие заголовки частично используются поисковыми системами, чтобы понять тему страницы. </section>

## Instructions
<section id="instructions"> Camper Cat хочет, чтобы страница на его сайте была посвящена тому, чтобы стать ниндзя. Помогите ему исправить заголовки, чтобы его разметка придавала семантическому смыслу содержание и показывала правильные отношения между родителями и дочерними элементами его разделов. Измените все теги <code>h5</code> на соответствующий уровень заголовка, чтобы указать, что они являются подразделами <code>h2</code> . </section>

## Tests
<section id='tests'>

```yml
tests:
  - text: Ваш код должен иметь шесть тегов <code>h3</code> .
    testString: 'assert($("h3").length === 6, "Your code should have six <code>h3</code> tags.");'
  - text: В вашем коде не должно быть тегов <code>h5</code> .
    testString: 'assert($("h5").length === 0, "Your code should not have any <code>h5</code> tags.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<h1>How to Become a Ninja</h1>
<main>
  <h2>Learn the Art of Moving Stealthily</h2>
  <h5>How to Hide in Plain Sight</h5>
  <h5>How to Climb a Wall</h5>

  <h2>Learn the Art of Battle</h2>
  <h5>How to Strengthen your Body</h5>
  <h5>How to Fight like a Ninja</h5>

  <h2>Learn the Art of Living with Honor</h2>
  <h5>How to Breathe Properly</h5>
  <h5>How to Simplify your Life</h5>
</main>

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
