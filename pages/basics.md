# React basics

We need to learn about component driven UIs. For that,wWhat matters is the understanding of syntax, core concepts, the what, why and how of components, working with data to display, fetch & update them based on user interaction.

The base idea is that there is no page concept. We won't be building pages, but components. We visualize the application as a bunch of components composed together to create bigger complex ones. It helps us focus on managing business logic. React helps us build reusable & reactive components.

Components are reusable building blocks. ( HTML + CSS + JS )

![Component composition](/assets/components-1.png)

Here, we can visualize the page as bunch of components

- Navbar ( which inturn has Logo, NavList, Button, Button with Icon)
- Banner ( inside of which we reuse the button component)

![Component composition](/assets/components-2.png)

By dividing the UI into components, we separate the concerns & embrace DRY ( Do not repeat yourself )
This way, different developers can work on different components and bring them together, as well as identify and isolate issues / bugs when it happens.

With react, what we do is declarative programming. We set the desired target state & let react figure out how to render them in the actual browser DOM.

## Creating a new project

`npx create-react-app project-name`

- pre requisiste is Node 16+ and optionally Git & VS Code.
-
