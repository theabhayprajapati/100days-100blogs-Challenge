# Make your Own VsCode Snippets

Snippets are aer very useful for quickly creating code, but do you know it's more AWESOME to make one ?

## Make your own snippets in [`VsCode`](https://code.visualstudio.com/download)

    1. Open VsCode and type

<code><p>Press <kbd>Ctrl</kbd> + <kbd>Shift </kbd> + <kbd>P</kbd> to Open Command Palette in VsCode.</p></code>


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/7n3geyx8ervk4rbqflx6.png)

    1. type Configure User Snippets

💥 <kbd style="color: red">Enter</kbd>

    1. type Select the language you want to create snippets for
<!--make a list of languages -->
- java
- javascript
- python
- css
....
Let's <kbd> Enter</kbd> Javascript.
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ievhuzfh5fao5t39gyxn.png)
```javascript
{
    // ↓ this is name of snippet
    "Print to console": {
        // ↓ this is prefix the command will be typed to use it.
	 	"prefix": "log",
        //  ↓ this is the snippet itself, body of the snippet
	 	"body": [
            //  $1 is the placeholder for the first argument, $number defines tabindex for the snippet.
	 		"console.log('$1');",
	 		"$2"
	 	],
        //  ↓ this is the description of the snippet.
	 	"description": "Log output to console"
	 }
}
```


    1. type Save the snippet/ Close the file.
    2. Make a file index.js
    3. use the prefix to type the snippet.
    4. type log and hit enter.


### you can also add more functionality like *filename*, *<span style="color: blue">foldername</span>*, *cursor position*, to your snippets, as a adding variables to your snippets

### Read more variables in snippets from [`VsCode snippets docs.`](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_variables)

## Share which snippets you are gonna create with this


Thanks for reading.
Share your snippets with everyone.
comment about topics you like.

**🤝🏾Connect me on:**
**Twitter**: 🕊️[`@Abhayprajapati_`](https://twitter.com/Abhayprajapati_)
**Github**: 🐧[`@theabhayprajapati`](https://github.com/theabhayprajapati)
**Linkedin**: 📌[`@abhayprajaapati`](https://www.linkedin.com/in/abhayprajaapati/)
**Youtube**: 📺[`@Abhayprajapati`](https://www.youtube.com/channel/UCUrQHSjXEAyboKLN_M0w0Mg)