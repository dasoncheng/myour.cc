---
title: TypeScript的面向对象编程之旅
date: 2018-4-12 17:52:55
categories:
  - [cs, language, typescript]
tags:
  - typescript
---

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
