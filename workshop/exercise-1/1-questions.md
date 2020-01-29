# HTML Comprehension Questions


## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [false] `<ul></ul><img/><ol><li>one</li></ol>`


## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

According to [Wikipedia](https://en.wikipedia.org/wiki/Screen_reader):
>"a screen reader is a form of assistive technology that is essential to people who are blind, as well as useful to people who are visually impaired, illiterate, or have a learning disability. Screen readers are software applications that attempt to convey what people with normal eyesight see on a display to their users via non-visual means, like text-to-speech,sound icons,or a Braille device."


## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation.

 `<img/>`tags or:
 ```
<figure>
    <img src="something.jpg" alt="Something"/>
    <figurecaption/>Some caption</figurecaption>
</figure>
 ```
 I could also use `<div>` as wrappers for my `<img>`tags depending on the layout

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

`<ol>` or `<ul>`, `li` and `a`. For example:

```
    <ul>
        <li><a href="https://www.moma.org">Moma</a></li>
        <li><a href="https://www.amnh.org">NY Museum of National History</a></li>
    </ul>
```

c) You want to sell designer hats. You need to receive orders from the user.

I would create some `<a>`tags for users to click on the specific content to be added to their shopping list. This `<a>` tag would be wrapping a `<div>` wich would contain an `<img>`tag with the picture of the hat. On click, the user would be adding that to their shopping list. The shopping list would be an `<ol>` with `<li>`tags.

## Q4 - Can a button be a child of a button? Explain your reasoning

[MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button) documentation points out that the permitted content of a button should be "Phrasing content but there must be no Interactive content".

However, there are some use cases such as:
```
    <button>
        <img src="tiny_birthday_cake.png" alt="">
        Submit
    </button>
```
More on that: https://css-tricks.com/use-button-element/

## Q5 - What is the most generic tag you can use?

`<div>`


## Q6 - What do the following achronyms stand for?

a) `a` anchor tag

b) `ol` ordered list

c) `ul` unordered list

d) `li` list

e) `tr` table row

f) `th` table header

g) `td` table data


## Q7 - Usually, `td` elements are children of what kind of elements?

`<tr>`

## Q8 - What is the difference between td and th?

`<th>` is for the column names and `<td>`is the content

## Q9 - Which tag makes the text appear bigger: h1 or h3?

`<h1>`

## Q10 - In which situation can you use self closing tags?

When you have void-elements, which don't have content such as `<img />`and `<br />`. More on that can be found at: https://www.456bereastreet.com/archive/201005/void_empty_elements_and_self-closing_start_tags_in_html/

## Q11 - What is autofilling and why is it important?

It's a feature for filling in forms on browsers. Browsers like Chrome fills in entire forms based on a user's Autofill profile.
More on that can be found at:
- https://developers.google.com/web/updates/2015/06/checkout-faster-with-autofill?hl=en
- https://cloudfour.com/thinks/autofill-what-web-devs-should-know-but-dont/

## Q12 - Which attributes are always present in an img element?

`src` and `alt`

## Q13 - Which attribute is always present for an anchor tag?

`href`


