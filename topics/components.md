## Components

Component is the base class for the React components defined as JavaScript classes. Class components are still supported by React, but we don’t recommend using them in new code.

```jsx
function Footer() {
  const hour = new Date().getHours();
  const openHour = 12;
  const closedHour = 22;
  const isOpen = hour >= openHour && hour <= closedHour;

  console.log(isOpen);

  // if (hour >= openHour && hour <= closedHour) alert(" We are Opned");
  // else alert("Sorry we are CLosed");
  return <footer>{new Date().toLocaleTimeString()} We are open</footer>;
}
```
