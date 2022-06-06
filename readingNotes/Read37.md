# React
## React Overview/Refresher
- JSX: creates React elements. We can use it within JS functions.
- Rendering Elements: smallest building blocks of react apps. Update the DOM to match the React elements.
- Components: bread and butter of React. Elements can display our components, passing JSX attributes and children to our components as an object called "props". Always start components with a capital letter.
- State: State is similar to props, but it is private and fully controlled by the component.

**Converting a Function into a Class, with Local State**
```
class Clock extends React.Component {
  render() {
    return (
      <div>
        <h1>Hello, world!</h1>
        <h2>It is {this.state.date.toLocaleTimeString()}.</h2>
      </div>
    );
  }
}
```
## Next.js
Takes away some of the complexity of React while keeping some of the flexibility on a per-page basis to render on client or server. Better to scale our app.

- Choose which data fetching method we want
- minify Javascript
- code splitting
- minimal HTML
- Caching builds