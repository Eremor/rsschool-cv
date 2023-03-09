# Artem Smirnov

## Junior Frontend Developer

## Contact information:
* __City:__ Kazan
* __Email:__ eremidz@yahoo.com
* __Skype:__ set..13
* __Discord:__ ArtemS#5304
* __Telegram:__ [@Artem_Smi](https://t.me/Artem_Smi)
* __Github:__ [Eremor](https://github.com/Eremor)

## Summary
My main goal is to change professional activities. At the moment, I work as a systems engineer and I understand that I have come to the point where I do not have enough current work intellectually, therefore, I began to actively study programming. For these purposes, I try to allocate as much time as possible and "absorb" the information with great zeal.

## Skills
* HTML5, CCS3
* JavaScript, TypeScript
* React, Redux
* Component library: Material UI, Ant Design
* Preprocessor: SCSS
* Module bundler: Webpack
* Figma
* a little Angular and Node.js

## Code examples
```JavaScript
  export class GameField extends BaseComponent {
    private cards: Card[] = [];

    constructor() {
      super('div', ['game__field']);
    }

    public clear(): void {
      this.cards = [];
    }

    public addCards(cards: Card[]): void {
      this.cards = cards;
      this.cards.forEach((card): void => this.addChildren([card.node]));

      setTimeout(() => {
        this.cards.forEach((card) => card.flipToBack());
      }, SHOW_TIME * 1000);
    }
  }
```