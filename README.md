# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
  <!-- react installation steps -->
  Step 1
  Create A folder, give it any name and Open that folder on your terminal, and run the following command to create a new Vite project

npm init vite@latest
Type y
y means yes
Give it any name example

my-project
Yes
React
what else did you see on the screen after that
: Just typescript
: Just hit enter key
Let’s go to step 2
: Navigate to the newly created project directory:

cd my-project
: Step 3 now
: Install the necessary dependencies:

npm install
: just npm install and wait, don't do any other thing. 🙄
: Open your project folder
: the react installation
: Then open the package.json file

You should see something like this
:Lastly, before I show you how to setup your folder structure to start doing projects. Run this command

npm run dev
: Don’t touch any file yet… just run that command first
: npm run dev
: done?
: Now copy that link and paste on your browser
: Congratulations
:welcome to react
: You can give your folder any kind of name.

But make sure your main react project folder (my-project) is housing all your JavaScript code.

That is the rule, as long as that folder is concerned, it has it own server which is running on your local host.
