# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.






Problems faced:
    Issue 1: 20-03-25
        Context:
            Tailwind released its version 4 recently. Following the documentation, it automates many things. using tailwind css v4 does not create a tailwind.config.css file. It installs a dev dependency called @tailwind/vite. Daisy UI also is updated recently to version 5.
        Problem 1:
            The main issue was firstly to configure tailwind css file in a different manner.
        Solution 1:
            Solve by following the documentation of Tailwind and Daisy Ui
        Problem 2:
            Themes integration was not working following the the former approach.
        Solution:
            Downgrade tailwind css to version 3 and Daisy UI to version 4 and follow corressponding documentations.
    Issue 2:


    
