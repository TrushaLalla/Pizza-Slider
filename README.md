# React + Vite

This is a React-based animated pizza slider built with Vite for fast development and Framer Motion for smooth animations.
I use React’s useState hook to track the currently active pizza, rotation angle, and slider position. When the user clicks navigation arrows, the state updates, and Framer Motion animates the UI accordingly.
What exactly controls the UI are: 

activeIndex
→ determines which pizza (image, title, description, background) is displayed

rotation
→ controls pizza image rotation animation

stepIndex
→ controls circular indicator movement.
Rather than manually manipulating the DOM, UI updates are entirely driven by React state. When state changes, React re-renders the component and Framer Motion animates the transition.
Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
