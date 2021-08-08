# Rules for importing and exoprting ES6 modules :

- > In html `script` tag don't forget to add **`type="module"`** attribute.

- > While you use `import` keyword in modules don't forget to use **`.js` or `.mjs`** extension with filename.

- > **`package.json`** file is important ,if you want to use file with **`.js`** extension. Keep this file in **root directory**. Also don't forget to add , the below lines in **`package.json`** file.

  ```javascript
    {"type":"module"}
  ```

- > There is an alternative , if you don't want to have **`package.json`** in your **root directory** , and that is to name all your **_javascript_** files with **`.mjs`** extension.
