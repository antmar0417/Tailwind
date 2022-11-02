<img src="https://media.giphy.com/media/3ohfFxoiP6rbEZ4nrG/giphy.gif" alt="Mario gif" width="100%"/>

# 07 - Tailwind

Tailwind CSS is a highly customizable, low-level CSS framework that gives you all of the building blocks you need to build bespoke designs without any annoying opinionated styles you have to fight to override.

Using Tailwind requires that a bit more thought goes into your HTML as the CSS will be coupled with the HTML, thus sacrificing a small amount of readability for major improvements in DX(Developer Experience) and Prototyping speed. One way to proactively manage this is to draw boxes around your Components and Subcomponents in the design. This creates a mental and visual model of your HTML tree before implementing a single line of code, and thus making Tailwind a piece of :cake: to use.

- :scissors: Examples

  - [Card](https://codepen.io/alegherix/pen/vYJYdoB)

  - [Hero](https://codepen.io/deoncardoza/pen/dyRrvZY)

  - [Flexbox](https://codepen.io/hugocsundberg/pen/poroLZO)

- :books: Documentation

  - [Documentation](https://tailwindcss.com/docs)

  - [Just-in-Time CDN](https://github.com/tailwindlabs/tailwindcss/releases/tag/v3.0.0-alpha.1#just-in-time-cdn)

- :link: Links

  - [What is a CDN?](https://www.imperva.com/learn/performance/what-is-cdn-how-it-works/)

  - [Tailwind Labs YouTube Channel](https://www.youtube.com/channel/UCOe-8z68tgw9ioqVvYM4ddQ)

- :briefcase: Component Libraries

  - [Tailwind Kit](https://www.tailwind-kit.com)

  - [Tailwind Components](https://tailwindcomponents.com)

  - [Tailwind Starter](https://www.creative-tim.com/learning-lab/tailwind-starter-kit/presentation)

  - [Kometa UI](https://kitwind.io/products/kometa)

  - [Tailwind Themes](https://www.themes.dev)

  - [Meraki UI](https://merakiui.com)

  - [Wicked Templates](https://blocks.wickedtemplates.com)

  - [Lofi UI](https://lofiui.co)

- :headphones: Videos

  - [Tailwind JIT Introduction](https://www.youtube.com/watch?v=aQS7kaje-24)

## Exercises

1.  In today´s lesson you are not allowed to use any custom CSS only Tailwind! Clone the repo, and open the `index.html` file from the resources directory which you will build upon.

2.  Create a [`<section>`](https://htmlreference.io/element/section/) element and give it a class `flex`. Center the items and align them in a row. Set the sections height to 100%.

    <details><summary>Hint #1</summary>

    - To align the items in a row use: [flex-direction](https://tailwindcss.com/docs/flex-direction) property.

    </details>

3.  Create a `<div>` element and use `h-screen` to make an element img the entire height of the viewport. The width should be 2/3 of the scrren. Add a `<img>` tag inside and give it `object-cover` property. Make the width and the height to 100% and use [this](https://images.unsplash.com/photo-1444313431167-e7921088a9d3?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1441&q=100) link to specify the path to the image. The result should be as shown in the image below.

    <details><summary>Hint #2</summary>

    - For the div use: `w-full`, `w-2/3` and `h-screen` properties.
    - For the img use: `w-full`, `h-full` and `object-cover` properties.

    </details>

    <p align="center">
    <img src="https://i.postimg.cc/hG0nBQVD/plane1.png" alt="Airplane" width="50%"/>
    </p>

4.  Continue working on the HTML document from the previous exercise. Now try to create a login form to the right of the airplane photo. See the image below. You will need an SVG image to complete this exercise placed in `resources/icons/google.svg`.

    <details><summary>Hint #3</summary>

    - Create two nested `<div>` elements after your first `<div>` element and place your form inside.

    </details>

    <p align="center">
    <img src="https://i.postimg.cc/MKHwVGVH/Screenshot-2022-10-30-at-21-30-36.png" alt="login page" width="50%"/>
    </p>

5.  **Extra**: Try to make the image 1/2 of the screen if the screen is smaller than 1280px.

6.  **Extra**: Hide the image when the screen size is smaller than 1024px.

7.  **Extra**: Try to style your project or whatever project you want using Tailwind. I recommend picking one of your earlier school projects.
