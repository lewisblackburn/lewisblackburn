# Hello there 👋

![visitors](https://visitor-badge.laobi.icu/badge?page_id=lewisblackburn)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)

```ts
class Person {
  name: string;
  hobbies: string[];

  greeting(): void {
    console.log("Hi, I'm " + this.name + ". Nice to meet you!");
  }
}

class Developer extends Person {
  languages: string[];
  tools: string[];
  databases: string[];

  constructor(name: string, languages: string[]) {
    super();

    this.name = name;
    this.languages = languages;
  }

  displayInformation(): void {
    console.log("Name : " + this.name + ", Languages : " + this.languages);
  }
}

var lewis = new Developer("Lewis J.A Blackburn", ["React", "TypeScript"]);
lewis.greeting();
lewis.displayInformation();
```
