---
title: "TypeScript"
draft: false
weight: 7
---

axios includes [TypeScript](http://typescriptlang.org) definitions and a type guard for axios errors.

```typescript
let user: User = null;
try {
  const { data } = await axios.get("/user?ID=12345");
  user = data.userDetails;
} catch (error) {
  if (axios.isAxiosError(error)) {
    handleAxiosError(error);
  } else {
    handleUnexpectedError(error);
  }
}
```
