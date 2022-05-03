---
title: "Non-null Assertion Operator"
---

```typescript
const student = {
  id: 1,
  name: "Betty"
}

student!.id
```

In [typescript](notes/code/typescript.md) this exclamation point says: trust me, even though the reference to the left _might_ not exist, I know it will at this point so trust me.

- [Non-null assertion operator](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-2-0.html#non-null-assertion-operator)