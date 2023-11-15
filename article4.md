
---

### Article 4: React Hooks

```markdown
# React Hooks

## Introduction to Hooks
Hooks are functions that let you hook into React state and lifecycle features from function components.

## Common Hooks
- **useState:** Manages state in a function component.
- **useEffect:** Performs side effects in function components.

## Hooks Example
```jsx
import React, { useState, useEffect } from 'react';

function Example() {
  const [count, setCount] = useState(0);

  useEffect(() => {
    document.title = `You clicked ${count} times`;
  });

  return (
    <div>
      <p>You clicked {count} times</p>
      <button onClick={() => setCount(count + 1)}>Click me</button>
    </div>
  );
}

export default Example;
