---
title: Array Coercion
permalink: wtf/array-coercion
source:
  url: https://gist.github.com/drnugent/a7e99cd3b27580c6211e#file-equality-js
  class: github
description: Of course an array isn't equal to itself?!
---

```
[] == ![];     // true
```

Technically, empty array is falsey, just like a negated array. But thats not entirely obvious!
