# BB lang files

## How to make a translation?
1. Make Github Fork
2. Copy `lang_CODE.arb` to new lang file: change `CODE` to language code. E.g.: `fr`
3. Make git commit. It's much easier to check translations and large strings this way
4. Make translation
5. Make git push to Fithub
6. Make Pull Request



## Translation example

We have `key: value` syntax:
```
    "loginScreenSignInTitle": "Sign in",
    ...
```

Need to translate only value:
```
    "loginScreenSignInTitle": "साइन इन करें",
    ...
```

## Masks
Translation can have mask(s):
```
"dialogDeleteLibContent": "Do you want to uninstall lib \"{lib}\"?",
```

Do not translate - \"{lib}\" - it is used in the app.


## Please note:
- Do not remove commas at the end of lines
- Watch out for long lines. Better to use short strings. Long ones may not fit into the interface
