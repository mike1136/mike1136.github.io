# Web Dev Reminders


# HTML
Keep in mind: 
1. Always remember to declare  the  character set to  Unicode with:
 ``` html
    <meta charset="utf-8"><!--Unicode Charset-->;
```

## Important Links
1. [List of special HTML character](https://dev.w3.org/html5/html-author/charref), those are to use them in text.
2. [List of Global attributes](https://www.w3.org/wiki/HTML/Attributes/_Global)
3. List of Atrributes [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes) or [W3C](https://www.w3.org/wiki/HTML/Attributes/_Global). 
4. [How to Declare HTML Lang](https://www.w3.org/International/questions/qa-html-language-declarations)


## StyleGuide 

* [Google Stylesguide for HTML + CSS](https://google.github.io/styleguide/htmlcssguide.html)
* [JQuery Styleguide for HTML](https://contribute.jquery.org/style-guide/html/)

## About Text
 1. **Case matters, except when it doesn't** - case matters for some things, like strings and attributes, but not others, like tag names.


2. **White space is ignored, except when it's not**  - White space is used to separate things, but adding more than one space will be the same as just one.  White space in strings is always just as you type it.
3. **Quotation marks are not part of a string, except when they are** - Quotation marks enclose a string, but thanks to the flexibility of choice between single or double quotes, it is easy to include one or the other in your string.
4. **The important thing is to look good** - You can take advantage of flexibility in capitalization and white space to make your code more readable and organized.

## Responsive Web Design

1. Use the "viewport" meta tag to make website responsive on mobile and  desktop:
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
This make the site take the width of the device 
<br>2. Info about [Media Devices](https://www.w3.org/TR/css3-mediaqueries/)


# CSS
1. To link a CSS file to an HTML file always use
```html 
<link rel="stylesheet" href="css/my_styles.css">
```

2. The selector always goes first, then the declaration:

![alt text](https://d37djvu3ytnwxt.cloudfront.net/assets/courseware/v1/7aeb1eae7e4bc674083b56e47c0fa9f1/asset-v1:W3Cx+HTML5.0x+1T2017+type@asset+block/select-declare.jpg "Selector-Declaration")

## Important Links
1. List of [CSS properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
2. [Use `rem` for Global Sizing; Use `em` for Local Sizing](https://css-tricks.com/rem-global-em-local/)
3. [New CSS3 Units: Root EM and Viewport Units](http://www.cssmine.com/ebook/css3-units)
4. [CSS Values and Units Module](https://www.w3.org/TR/css3-values/#viewport-relative-lengths)


# VS Code 

## List of Recommended Addons:(<b>CTRL + P </b> to install)
1. [AutoFillName](https://marketplace.visualstudio.com/items?itemName=JerryHong.autofilename): Suggest the file on root folders when placing double quotation marks 
```
    ext install AutoFileName
```

2. [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify): Orginize the files 
```
ext install beautify
```

3. [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) : Makes the color code text same as selected color.
```
ext install color-highlight
```
4. [Dash/Zeal intregration](https://marketplace.visualstudio.com/items?itemName=deerawan.vscode-dash): Makes it easier to read documentation from Dash/Zeal (requires external program)
```
ext install vscode-dash
```

5. [Debbuger for Chrome ](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome): Debugs Chrome within VSCode
```
ext install debugger-for-chrome
```
6. [ESlint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): Fix your code for styling + bug issues. MUST HAVE ESLINT +NPM INSTALLED [Check link to set up].
```
ext install vscode-eslint
``` 
7. [Git Easy](https://marketplace.visualstudio.com/items?itemName=bibhasdn.git-easy):Add more git commands to the command palette.
```
ext install git-easy
```
8. [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory): Lets you visually sii your git commits.
```
ext install githistory
```
9. [HTML](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets): Add Snippets of HTML code.
```
ext install html-snippets
```
10. [HTMLhint](https://marketplace.visualstudio.com/items?itemName=mkaufman.HTMLHint): Integrates with HTMLlint. (Check link to set up)
```
ext install HTMLHint
```

11. [Icon Fonts](https://marketplace.visualstudio.com/items?itemName=idleberg.icon-fonts): Makes popular icon packages avaiable on  the autocomplete form.
```
ext install icon-fonts
```

12. [IntelliSense for CSS class names](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion): Makes all the CSS class names available with autocomplete 
```
ext install html-css-class-completion
```
13. [Javascript (ES6)code Snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets): Add Javascript snippets.
```
ext install JavaScriptSnippets
```
14. [Jquery code Snippets](https://marketplace.visualstudio.com/items?itemName=donjayamanne.jquerysnippets): Add Jquery code Snippets to be usable.
```
ext install jquerysnippets
```
15. [JShint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.jshint): Adds JShint lint to VSCode
```
ext install jshint
```
16. [JSON Tools](https://marketplace.visualstudio.com/items?itemName=eriklynd.json-tools): Makes JSON Files pretty or ugly.
```
ext install json-tools
```

17. [Open in Browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser): Gives the ability to Open the current HTML file in a Browser
```
ext install open-in-browser
```
18. [Stylelint](https://marketplace.visualstudio.com/items?itemName=shinnn.stylelint):Adds CSS lint  (Check link for set up)
```
ext install stylelint
```


# Important Shortcuts to keep in mind 
1. <b>CTRL + P </b>: Search and run commands. 
2. <b> F1</b>: Opens command palette.
3. <b>CTRL+K then CTRL+S</b>:Opens Keyboard Shortcut Commands 
4. <b>CTRL+ SHIFT+B</b>:  Runs the Beautify Command (Must be manually set: Open Keyboard Shortcuts then search beautify file)
4. <b>CTRL+ H</b>: [DASH] It will search for current specific documentation depends on language.
5. <b>CTRL + ALT + H</b>: [DASH] It will search for all documentation.
6. <b>CTRL + ALT+M</b>: JSON pretty.
7. <b>ALT + M </b>: JSON minify.
8. <b>ALT + B</b>: Open in default browser.
9. <b>ALT + SHIFT + B</b>: Open in another browser.
 
 # Usefult snippets
 1. Helper function to convert NodeLists to Arrays
 ```javascript
 // Helper function to convert NodeLists to Arrays
  function slice(nodes) {
    return Array.prototype.slice.call(nodes);
  }
  ```

  ### Unorganized thoughts

  * 48dp minimal touch  target size
  * 32dp margin around touch target