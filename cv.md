# Evgeny Prikhodko

## Contacts

discord: eprikhodko
phone: +7 (952) 369-68-64
Telegram: @evgenyprikhodko
mail: evgenyprikhodkodev@gmail.com
github: https://github.com/eprikhodko

## About me

In 2021 I learned frontend development at [Scrimba](https://scrimba.com/). During my learning jorney I discovered the world of web development and learned about modern ways to make a quality website that is easy to maintain and develop.

My goal now is to find a cool team and get good experience. I'd like to grow into a good, aspiring middle developer in a year.

Interests: amateur photography on a small Fuji, hiking in the city.

## Skills

- React
- JavaScript (ES6+)
- Styled Components
- React Router
- Google Firebase
- HTML
- CSS
- Git / Github

## Code example

```javascript
String.prototype.toJadenCase = function () {
  // split string into array of words
  const arrayOfWords = this.split(" ");
  // map array of words
  const jadenCasedArray = arrayOfWords.map((word) => {
    // make first letter of the word upper case
    const firstLetter = word.slice(0, 1).toUpperCase();
    // take rest of a word
    const restOfWord = word.slice(1);
    // return full word with uppercased first letter
    return firstLetter + restOfWord;
  });

  // return JadenCased string
  return jadenCasedArray.join(" ");
};
```
