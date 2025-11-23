## Styling CSS in JSX

```jsx
import "./index.css";

function Menu() {
  // use className
  return (
    <main className="menu">
      <h2> Our Menu:</h2>
      <Pizza />
      <Pizza />
      <Pizza />
    </main>
  );
}
```
