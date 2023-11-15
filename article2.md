
---

### Article 2: State and Props in ReactJS

```markdown
# State and Props in ReactJS

## Understanding State and Props
State and props are fundamental concepts in React. State allows components to manage and respond to data changes, while props enable data passing between components.

## Using State and Props
```jsx
import React, { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>You clicked {count} times</p>
      <button onClick={() => setCount(count + 1)}>Click me</button>
    </div>
  );
}

export default Counter;
