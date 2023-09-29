This week I've been reviewing React js library using a platform called Scrimba. I must admit when I started learning React after vanilla javascript I was so confused and overwhelmed.
My React instructor at Juno College told us how much she loved react and I never understood why. But after reviewing react again, it is gradually growing on me!
What I'm learning is, with regular coding practice and repetition, and reviewing and understanding the concepts, is really the key to mastering React and any other coding language.
So there is no point in giving up unless you commit yourself to regular practice!

Below is a React Quiz I completed as i'm currently building a mobile responsive airbnb app through scrimba!

1. What do props help us accomplish?
  - Props, short for properties, are a fundamental concept in React that allows you to pass data from a parent component to a child component. 
  - They help make components more reusable by allowing you to configure a component's behavior and appearance dynamically.

2. How do you pass a prop into a component?
  - To pass a prop into a component, you include it as an attribute when rendering the component. 
  - In my example, `<MyAwesomeHeader title="whatever" />`, the prop/property "title" is passed to the "MyAwesomeHeader" component.

3. Can I pass a custom prop (e.g. `blahblahblah={true}`) to a native DOM element?
  - No, you cannot pass custom props to native DOM elements. 
  - JSX for native DOM elements is translated into real HTML elements, and those elements only accept attributes defined in the HTML specification. 
  - Custom props like `blahblahblah` are only applicable to React components.

4. How do I receive props in a component?
   - In a functional component, you can receive props as a parameter in the component's function. In your example:
   
     function Navbar(props) {
         console.log(props.blahblahblah);
         return (
             <header>
                 ...
             </header>
         );
     }
  
