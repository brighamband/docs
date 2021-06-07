# HTML Crash Course

<br />

## File Creation

1. Make a new folder/directory called `HtmlCrashCourse`.
2. Inside that folder, make a new file called `index.html`.

<br />

## Boilerplate

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
</body>
</html>
```

<br/>

## Give document a new title _(see Chrome tab)_

`<title>My Website</title>`

<br/>

## Text (`<h1-6>`, `<p>`)

- ### Add a header (many sizes)

  - `<h1>Biggest header</h1-6>`
    <h1>Biggest header</h1>

  - `<h6>Smallest header</h6>`
    <h6>Smallest header</h6>

- ### Add a paragraph

  - `<p>Lorem ipsum dolor sit amet...</p>`

    ```
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    ```

<br />

## `<button>`

- `<button>Click Me<button>`

  <button>Click Me</button>

## `<link>`

- `<a href="google.com">Visit Google</a>`

  <a href="https://www.google.com">Visit Google</a>

<br />

## `<input>`

- ### Add text input

  `<input type="text">`

  <input type="text">

- ### Add number input _(Notice the counters on the right, non-numbers aren't allowed)_

  `<input type="number">`

  <input type="number">

- ### Add date input

  `<input type="date">`

  <input type="date">

- ### Add time input

  `<input type="time">`

  <input type="time">

- ### Add password input

  `<input type="password">`

  <input type="password">

- ### Add checkbox input

  `<input type="checkbox">`

  _Ex:_

  <input type="checkbox">
  <label>Keep me logged in</label>

- ### Add radio input

  `<input type="radio">`

  _Ex:_

  <input type="radio" id="mdale" name="gender" value="mfdale">
  <label for="male">Male</label><br>
  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label><br>

<br/>

## Dropdowns (`<select>`, `<option>`)

- ```
  <select name="cars">
    <option value="toyota">Toyota</option>
    <option value="honda">Honda</option>
    <option value="chevy">Chevy</option>
  </select>
  ```

  <select name="cars">
    <option value="toyota">Toyota</option>
    <option value="honda">Honda</option>
    <option value="chevy">Chevy</option>
  </select>

  <br />

## `<div>` (rectangular containers)

- `<div>Content inside rectangle</div>`

  _Ex:_

  <div style="background: gray">Content inside rectangle</div>
