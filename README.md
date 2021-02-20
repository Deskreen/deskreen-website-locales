# deskreen-website-locales
This is a project with locales for private git repo of [deskreen.com](https://deskreen.com) website

### Want to add new language or found a typo on Deskreen APP (not a website)? [Here are guides on how to help](https://github.com/pavlobu/deskreen#get-started-for-translators)

## Contents

- [Notes on editing `translation.json` files. (Applies to all contributors wether you know how to code or not)](#notes-on-edit)
- [I don't know how to code or I don't know how git works, but I want to help with fixing a typo for a language used in Deskreen  Website](#dont-know-code)
- [I know how to code and I know how git works, where should I start with fixing a typo for a language used in Deskreen Website?](#i-know-code)
- [When adding a new language important notes (Applies to all contributors wether you know how to code or not)](#adding-new-lang-important)
- [I don't know how to code or I don't know how git works, but I want to help with adding a new language support for Deskreen  Website](#dont-know-code-lang)
- [I know how to code and I know how git works, where should I start with adding a new language for Deskreen Website?](#i-know-code-lang)

<a id="notes-on-edit">
<h2>Notes on editing `translation.json` files. (Applies to all contributors wether you know how to code or not)</h2>
</a>

When editing a `translation.json` file, don't change the **left part of translation** before the `:`.
Only change the text between `"` on right side of `:` sign.

#### Example:

Some content of `translation.json`

<a id="edit-orig">
<h6>Before your change (original):</h6>
</a>

```
...
"Hello": "Hello"
...
```

##### Good example, after your change (for example Spanish language support):

```
...
"Hello": "Hola"
...
```

##### **Bad example** of your change (left side is different than in [original](#edit-orig)):

```
...
"Greetings": "Hola"
...
```

### Rule of thumb, don't edit a text on a left side of `:` sign in `translation.json` file. only edit a text between `"` on the right side from `:` symbol.

<br/>
<br/>

<a id="dont-know-code">
<h2>I don't know how to code or I don't know how git works, but I want to help with fixing a typo for a language used in Deskreen Website</h2>
</a>

Find `translation.json` file for language you need to edit in this repo subfolders (ex. `en/translation.json`, `ua/translation.json` etc.)
Then download this file
#### How to download `translation.json` file
open **Raw** `translation.json` file -> right click in browser window -> Save as..


You can use any simple text editor to edit `translation.json` file.
Good text editors for different operating systems:

- Windows (Notepad)
- MacOS (TextEdit)
- Linux (gedit, mousepad etc.)
### [make sure you are following these guides when editing a `translation.json` file](#notes-on-edit)

When you've finished editing files, 
you can send me a Google Drive link to these files for translations of Deskreen Website, or attach them to email.
Send your email with files here: pavlobu@gmail.com
Thank you very much!

<br/>
<br/>

<a id="i-know-code">
<h2>I know how to code and I know how git works, where should I start with fixing a typo for a language used in Deskreen  Website? </h2>
</a>

Find `translation.json` file for language you need to edit in this repo subfolders (ex. `en/translation.json`, `ua/translation.json` etc.)

### [make sure you are following these guides when editing a `translation.json` file](#notes-on-edit)

Fix typos and then submit your PR on this repo. Thank you!

<br/>
<br/>
<br/>
<br/>

<a id="adding-new-lang-important">
<h2>When adding a new language important notes (Applies to all contributors wether you know how to code or not)</h2>
</a>

* use `en/translation.json` as a template.
* dont miss this part at the top of the file:
   ```
    "language name": "English",
    "language": "language",
    "language flag": "🇺🇸",
   ```
   * the `language name` is how the language calls itself. For example Russian -> Русский . So this should be: `"language": "Русский"` in russian
   * `language flag` is emoji country flag where this language is the most widespread. You can search for country flag emojis here: [https://getemoji.com/](https://getemoji.com/) , then copy-paste emoji symbol. Example for ukrainian language this line should be: `"language flag": "🇺🇦"`
   * `"language": "language"` is how the word `language` translated to your target language. Example of how this look in spanish: `"language": "idioma"`
* [Follow these general guides on editing `translation.json`](#notes-on-edit)

<br/>
<br/>

<a id="dont-know-code-lang">
<h2>I don't know how to code or I don't know how git works, but I want to help with adding a new language support for Deskreen Website</h2>
</a>

You can use any simple text editor to edit `translation.json` file.
Good text editors for different operating systems:

- Windows (Notepad)
- MacOS (TextEdit)
- Linux (gedit, mousepad etc.)

You can grab English language `translation.json` file from `en/translation.json` and use it as a template

#### How to download `translation.json` file

open link -> right click in browser window -> Save as..

### [make sure you are following these guides when editing a `translation.json` while adding a new language](#adding-new-lang-important)

### When finished editing translation.json files

You can send me a Google Drive link to these files for translations of Deskreen Website, or attach them to email.
Send your email with files here: pavlobu@gmail.com
**Thank you in advance!**


<br/>
<br/>

<a id="i-know-code-lang">
<h2>I know how to code and I know how git works, where should I start with adding a new language for Deskreen Website?</h2>
</a>

Fork this repo.
Add a new subfolder with `translation.json` for your language, for example for spanish you should add `es/translation.json`.

When you've finished editing submit a PR with your changes to this repo, then it will be reviewed and merged.
**Thank you in advance!**

#### [make sure you are following these guides when editing a `translation.json` while adding a new language](#adding-new-lang-important)