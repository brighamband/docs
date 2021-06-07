# CSS Crash Course

<br />

## In-line CSS (simple yet unconventional)

When making an element, just add `style=""` within the opening tag.
Inside the "", place the appropriate styling here.

For instance, here's how to change of text color of an `<h1>` header tag to red:

- ```
  <h1 style="color: red">Header 1</h1>
  ```

Result:

  <h1 style="color: red">Header 1</h1>

<br />

## CSS in a Separate File (conventional)

It's better to separate content (HTML) and styling (CSS). Here's how to do it:

- Make a new file called `styles.css` and store it in the same directory as your `index.html` file.

<br />

## Selectors

1. Name selectors (`html`, `body`, `div`, `p`)

   ```
   html {

   }
   ```

2. Class selectors

   ```
   .class-name {

   }
   ```

3. ID selectors

   ```
   #id-name {

   }
   ```

## Properties

`color: red;`

<p style="color: red">Changed the text color</p>

`background-color: red;`

<p style="background-color: yellow">Changed the background color</p>

`margin: 2rem;`

<p style="background-color: lightGray; margin: 2rem">Added a margin around the text</p>

`padding: 2rem;`

<p style="background-color: lightGray; padding: 2rem">Added padding around the text</p>

`border: 2px solid blue;`

<p style="background-color: lightGray; border: 2px solid blue;">Added border around the text</p>

`text-align: center;`

<p style="text-align: center">Aligned the text center</p>

`text-align: right;`

<p style="text-align: right">Aligned the text right</p>

`font-size: x-large;`

<p style="font-size: x-large">Made text extra large</p>

`font-weight: bold;`

<p style="font-weight: bold">Made text bold</p>

`font-style: italic;`

<p style="font-style: italic">Made text italicized</p>
