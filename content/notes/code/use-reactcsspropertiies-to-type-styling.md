---
title: "Use React.CSSProperties to Type Styling"
---

## How to type styling in [react](notes/code/react.md) && [typescript](notes/code/typescript.md)

Typing CSS styling
- React built in type
- use optional type
- empty object by default

```typescript
type BoxProps = { children: React.ReactNode; style?: React.CSSProperties };

const Box = ({ children, style = {} }: BoxProps) => {
  return (
    <section style={{ padding: "1em", border: "5px solid purple", ...style }}>
      {children}
    </section>
  );
};

export default function Application() {
  return (
    <Box>
      Just a string.
      <p>Some HTML that is not nested.</p>
      <Box style={{ borderColor: "red" }}>
        <h2>Another React component with one child.</h2>
      </Box>
      <Box>
        <h2>A nested React component with two children.</h2>
        <p>The second child.</p>
      </Box>
    </Box>
  );
}
```
