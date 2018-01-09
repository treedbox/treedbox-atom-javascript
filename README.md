# Treedbox Atom Javascript
>  How fast do you want to be to transform an idea into code?

> This is not a package that will force you to remember of some custom prefix to call the the snippets. **Treedbox Atom Javascript** was designed to serve snippets in the most logical way, delivering the most commons code structures and combinations to make your combo code very speedy and powerful.

Javascript snippets [Atom](https://atom.io) Package for a fast development.

By: [Jonimar Marques Policarpo](https://www.linkedin.com/in/treedbox/ 'LinkEdin') at [Treedbox](http://treedbox.com)

## Pages
GitHub:  https://github.com/treedbox/treedbox-atom-javascript

Atom.io: https://atom.io/packages/treedbox-atom-javascript

## What's News?
version 2.7.0: **501** javascript snippets!
- Snippets for `fetchGET`, `fetchPOST`, `fetchPUT`, `fetchDELETE`;
- Include: URL interface https://developer.mozilla.org/docs/Web/API/URL
`URLcreateObjectURL`, `URLrevokeObjectURL`;
- Snippets without semicolons; [YouTube: Semicolons cannot save you! - FunFunFunction #9](https://www.youtube.com/watch?v=Qlr-FGbhKaI), [Article: Semicolons in JavaScript: A preference](https://blog.kentcdodds.com/semicolons-in-javascript-a-preference-dd8fc8b80895);
- Fixed: typo with `parseInt`.

version 2.3.0: **480** snippets

version 1.0.0: **114** snippets

###### All Math properties and methods
Including an extra complete functions as `MathRandomCompleteFunc` or `randomCompleteFunc`:
```
const random = (min,max) => Math.floor(Math.random() * (max - min + 1)) + min
```
and many others **Extras** that you will find out when you need it :)

## How to use
#### Example:
in a `.js` file or in a `.html` file, between the HTML tag `<script></script>`,
type: `fetch` and press "**Tab/Enter**" to generate:
```
fetch(url)
  .then(response => response)
  .then(data =>{
      console.log('data:',data)
  }).catch(error => console.log('ERROR:',error.message))
 ```
 Like `fetch`, you have a lot of snippets to help you with `import`, `forEach`, `map`, `generator` and so on.

## Tested
 **Atom 1.21.0-beta2 x64**

 **Atom 1.22.0-beta2 x64**

## Meta
 Author: [Jonimar Marques Policarpo](https://www.linkedin.com/in/treedbox/ 'LinkEdin') [Front-End Web Developer]

 LinkEdin:  [Jonimar Marques Policarpo | Treedbox](https://www.linkedin.com/in/treedbox/ 'LinkEdin')

 Twitter:  [@treedbox](http://twitter.com/treedbox)

 E-mail:  [treedbox@gmail.com](mailto:treedbox@gmail.com)

 WebSite:  [treedbox.com](http://treedbox.com)

## License
 [MIT](LICENSE.md) © [TreedBox](https://github.com/treedbox)

### Offical Repository
[https://github.com/treedbox/treedbox-atom-javascript/](https://github.com/treedbox/treedbox-atom-javascript/)
