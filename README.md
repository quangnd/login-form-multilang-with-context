# Login form with React Contexts for theme and multi-language 👔
See in action at [Login form](https://romantic-einstein-bdd4e0.netlify.com/)

[![Netlify Status](https://api.netlify.com/api/v1/badges/1993d3d9-d4f6-49c1-98dc-1ede13963738/deploy-status)](https://app.netlify.com/sites/romantic-einstein-bdd4e0/deploys)

## What is Context?

- Context provides a way to pass data through the component tree without having to pass props down manually at every level.
- Context lets you “broadcast” such data, and changes to it, to all components below. Common examples where using context might be simpler than the alternatives include managing the current locale, theme, or a data cache.

## When to use Context?

- Context is designed to share data that can be considered "global" for a tree of React components, such as the **current authenticated user**, **theme**, or **preferred language**.
- Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse *more difficult*. If you only want to avoid passing some props through many levels, [component composition](https://reactjs.org/docs/composition-vs-inheritance.html) is often a simpler solution than context.

## References

- [Official Context document](https://reactjs.org/docs/context.html)
- [Context API](https://reactjs.org/docs/context.html#api)




