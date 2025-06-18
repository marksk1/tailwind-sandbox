# Tailwind Sandbox

A place to try out new things with tailwind css

Tailwind docs: `https://tailwindcss.com/docs/installation/using-vite`

## How it works
- The tailwindcss CLI watches our HTML code, Javascript components, and any other templates for class names
- It then generates the corresponding styles and writes them to a static CSS file

## Installation (tailwindcss v4)
- Install the tailwindcss CLI as a dev dependency via npm: `npm install -D tailwindcss @tailwindcss/cli`

<!-- v3 only, optional in v4:
- Create a tailwind css config file by:
  - generating one with the cli `npx tailwindcss-cli@latest init`
  - creating one manually and copy the config from https://tailwindcss.com/docs/theme -->

- Create a tailwind css input file:
  - create `input.css` and inside it write `import "tailwindcss";`

- For convenience, add tailwind build and watch CLI commands as script to the package.json
  
  - build: `npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css`
  - watch: `npx @tailwindcss/cli -i ./input.css -o ./output.css --watch`
  - note, we can customize the paths of the input and output files as necessary

- ensure `./output.css` is linked within your HTML file
  
- run `npm run watch`
- add tailwind classes to your html and watch them take effect!
  
### To get vscode auto-suggestions when typing tailwind classes:
- Install vscode extension: Tailwind CSS IntelliSense

### Configurations such as Breakpoints and Theme
https://tailwindcss.com/blog/tailwindcss-v4#css-first-configuration


## Tutorial 1:
Video: https://www.youtube.com/watch?v=dFgzHOX84xQ
Repo: https://github.com/bradtraversy/tailwind-landing-page/tree/main

## Licensing
### Is Tailwind free to use commercially?
Tailwind CSS is an open-source CSS framework that provides utility classes to help developers build custom user interfaces rapidly. It is entirely free to use, even for commercial projects.

The creators of Tailwind CSS have released it under the MIT license, which allows users to freely use, modify, distribute and even sell the framework or anything built on top of it. There are no restrictions around commercial applications.

Some key things to note regarding the commercial use of Tailwind CSS:

### You can use Tailwind CSS commercially without paying anything
There are no fees or licensing associated with leveraging Tailwind CSS commercially. The open-source framework can be used to build commercial sites, web apps, SaaS products and more without paying the creators anything.

### Commercial products can be built with Tailwind CSS
Companies use Tailwind CSS to build commercial products and SaaS solutions regularly. There are no limitations on releasing commercial work or products as long as you comply with the MIT license.

### Customization is fully supported
Tailwind CSS is designed for configuration and customization from the start. Developers can freely modify Tailwind to meet their or their commercial clients' specific needs without restriction.

So in summary - yes, you can absolutely use Tailwind CSS in commercial applications and products completely free of charge. The open-source framework places no restrictions around commercial usage.