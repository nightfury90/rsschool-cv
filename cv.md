#1. Dmitriy An

##2. Contacts

- Email: ya.snakeeye@yandex.ru
- Phone: +998 91 135 03 56
- Telegram: @pancake90

##3. Summary

Results-oriented and highly interested in studying web development tools self-taught young man. Spending a lot of time on internet surfing, it was always interesting for me how do the websites work. I have patience when it comes to studying something new, and I like it. It’s important for me to do what I like and understand well what I’m doing.

## 4.Skills

### Soft skills
- Collaboration
- Communication skills

### Hard skills

- HTML & CSS
- Bootstrap
- JS Basics
- Preprocessors (SASS/SCSS)

## 5.Code examples

### JS
```JS
// UI controller
const UIController = (function () {
  class Field {
    constructor(size) {
      this.size = size;
    }

  }

  //  more scalable code for using id selectors
  const UISelectors = {
    resizeBtn: '.btn-resize',
    clearBtn: '.btn-clear',
    blackBtn: '.btn-black',
    coloredBtn: '.btn-colored',
    sprayBtn: '.btn-spray',
    container: '.container',
    items: '.item',
  }

  return {
    buildField: function (size) {
      const field = new Field(size);

      const container = document.querySelector(UISelectors.container);

      container.style.gridTemplateRows = `repeat(${size}, 1fr)`;
      container.style.gridTemplateColumns = `repeat(${size}, 1fr)`;

      for (let i = 1; i <= size ** 2; i++) {
        const item = document.createElement('div');

        item.classList = 'item';
        container.appendChild(item);
        item.style.backgroundColor = 'white';
      }
      return field;
    },
    getSelectors: function () {
      return UISelectors;
    },
    removeItems: function () {
      const items = document.querySelectorAll(UISelectors.items);
      items.forEach(function (item) {
        item.remove();
      });
    },
    // getSize: function () {
    //   return this.size;
    // }
  }
})();
```

##6.Experience

Unfortunately, I have no experience in Web Development.

##7.Education

*2010-2015* – Master of Arts: Psychology, Moscow State University.

Online courses: (htmlacademy, freecodecamp, udemy, codecademy, youtube channels).

##8.English
Pre-intermediate (can clearly understand any videos and literature,but have some problems with speaking English)
