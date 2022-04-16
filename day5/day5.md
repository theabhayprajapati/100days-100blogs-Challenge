<!-- title: How I made first NPM  -->



```javascript
npm init -y
```
onces the package is created, make a main.js file

```javascript
touch main.js
```

> add main.js file in bin section, if it is not then create one.

```javascript
#!/usr/bin/env node
// at the top of the main.js file.
```

> go write the logic of your package, what you want to do.
> our simply write.

```javascript
console.log('hello world this is my First Package.')
```
> after doing this open command palete and type

```bash
npm login
# you will be propmt for username and password and OTP
```

```bash
npm publish
# this will publish your package to npm.
# make sure you are have unique name for your package.
```

## Updating Package:

> for updating package go to your root file (main.js) and make your update.
> After, this will update your package.

```bash
npm version patch/minor/major
# Patch: is nominal edits version updates last decimal.
# Minor: is minor bug fixed version, updates second last.
# Major: is major version updates Main.
```


## Using Package:
> for using packages in your local machine type

```bash
npm i -g <package-name>
# -g is for global package, so you can access it from anywhere in you computer
```

```bash
<package-name>
#  to run your package.
# console.log('hello world this is my First Package.')
```

## What Package I have built ? and how can you use it

This is my first package, and accutally I don't have any proper use case of this, but I am built for learning purpose

> with this package you can convert you text to slug

```bash
makeslug convert this into slug
# convert-this-into-slug
```

### How to use it
```bash
npm i -g makeslug
```

```bash
makeslug <your-text>
```

So, this is simple story of my first package.

[![View on NPM](https://upload.wikimedia.org/wikipedia/commons/thumb/d/db/Npm-logo.svg/100px-Npm-logo.svg.png?20140904162625 "title")](https://www.npmjs.com/package/makeslug)

**🤝🏾Connect me on:**
**Twitter**: 🕊️[`@Abhayprajapati_`](https://twitter.com/Abhayprajapati_)
**Github**: 🐧[`@theabhayprajapati`](https://github.com/theabhayprajapati)
**Linkedin**: 📌[`@abhayprajaapati`](https://www.linkedin.com/in/abhayprajaapati/)
**Youtube**: 📺[`@Abhayprajapati`](https://www.youtube.com/channel/UCUrQHSjXEAyboKLN_M0w0Mg)