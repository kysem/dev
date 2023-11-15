
---

### Article 3: React Lifecycle Methods

```markdown
# React Lifecycle Methods

## Overview
Lifecycle methods are hooks that allow you to run code at specific points in a component's life.

## Lifecycle Methods
- **componentDidMount:** After component mounts.
- **componentDidUpdate:** After component updates.
- **componentWillUnmount:** Before component unmounts.

## Example
```jsx
import React, { Component } from 'react';

class LifecycleExample extends Component {
  componentDidMount() {
    console.log('Component mounted');
  }

  componentDidUpdate() {
    console.log('Component updated');
  }

  componentWillUnmount() {
    console.log('Component will unmount');
  }

  render() {
    return <div>Hello, world!</div>;
  }
}

export default LifecycleExample;
