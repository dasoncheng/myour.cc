---
title: TypeScript的面向对象编程之旅
date: 2018-04-22
categories:
  - [cs, language, typescript]
tags:
  - typescript
---

- 封装、继承、多态
- 接口、抽象

```ts
class Greeter {
  greeting: string;
  constructor(message: string) {
    this.greeting = message;
  }
  greet() {
    return "Hello, " + this.greeting;
  }
}

let greeter = new Greeter("world");
```
