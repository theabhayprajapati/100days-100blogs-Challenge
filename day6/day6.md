<!-- title: Make edit to vscode like this. -->
## How to make change to VSCode extension like this

Extension are something what makes vscode different from other editor

> and something better is that you can make change to those extension according to your own style/ needs

### use make changes to any extension from extensions tab.

**press** <kbd>Ctrl</kbd> + <kbd>,</kbd> to open setting in **VSCode**.

[![Setting tab](/day6/settingtab.png)]

### Type the name of extension you want to make changes to (e.g. better-comments)

![Better comments vscode settings](/day6/bettercomset.png)

### Click on <kbd>Edit in settings.json</kbd>

### Yeap!, now you can access the code of extension.

## Lets 🤫 make changes.

```json
// add this extra code to the end of the file

    {
        "tag": "update",
        "color": "#8C3FE2",
        "strikethrough": false,
        "underline": false,
        "backgroundColor": "transparent",
        "bold": false,
        "italic": false
    },
    // best color for check
    {
        "tag": "check",
        "color": "#00FF00",
        "strikethrough": false,
        "underline": false,
        "backgroundColor": "transparent",
        "bold": false,
        "italic": false
    },

```

### This will make sure that when ever you type ***check*** or *update* in you comments, it will be highlighted in *green* and ***purple***


## 🤪 Make sure to reload the vscode, only then it will work



# 👏🏾Clap for your self, you have successfully made changes to vscode extension


**🤝🏾Connect me on:**
**Twitter**: 🕊️[`@Abhayprajapati_`](https://twitter.com/Abhayprajapati_)
**Github**: 🐧[`@theabhayprajapati`](https://github.com/theabhayprajapati)
**Linkedin**: 📌[`@abhayprajaapati`](https://www.linkedin.com/in/abhayprajaapati/)
**Youtube**: 📺[`@Abhayprajapati`](https://www.youtube.com/channel/UCUrQHSjXEAyboKLN_M0w0Mg)