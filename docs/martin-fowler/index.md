---
layout: doc
---

# Martin Fowler Code Smells

Semua contoh dalam repository ini dibagi dalam dua package. `before` dan `after`. Sesuai dengan namanya, `before` adalah contoh code yang memiliki code smell yang akan dibahas, `after` adalah hasil setelah di-refactor.

Semua test case dalam repository ini menggunakan JUnit 5.
```java
function test() {
  console.log("notice the blank line before this function?");
}
```
![An image](./1.jpg)


## Penjelasan Smell

- [Bloaters](bloaters/)
- [Object-Orientation Abusers](oo-abusers/)
- [Change Preventers](change-preventers/)
- [Dispensables](dispensables/)
- [Couplers](couplers/)
