# Zlatanova Irina
*******************

## Contacts
* __Russia, Kaliningrad__
* __Email__: i@zlatanova.ru
* __GitHub__: [ZlatanovaIrina](https://github.com/ZlatanovaIrina "Zlatanova Irina GitHub")

## Skills
* JavaScript Basic
* JQuery
* HTML
* CSS
* php
* SQL

## Code Examples
* __5 kyu CodeWars kata__
* __Description:__
Move the first letter of each word to the end of it, then add "ay" to the end of the word. Leave punctuation marks untouched.

__Solution:__
```
function pigIt(str){
  return str.split(' ').reduce((acc, word) => acc.concat((word.match(/[\w-]/)) ? word.replace(word[0], '').concat(`${word[0]}ay`) : word), []).join(' ');
}

```