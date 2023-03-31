<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<p align="center">
  <a href="https://www.gatsbyjs.com">
    <img alt="Gatsby" src="https://www.gatsbyjs.com/Gatsby-Monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby's hello-world starter with theme-ui
</h1>

gatsby-plugin-theme-ui is a Gatsby plugin that provides a simple way to implement a design system using the Theme UI library. It allows developers to define a theme object with design tokens such as colors, typography, and spacing, and generates CSS styles based on those tokens. The plugin also provides a set of React components for easy implementation of the design system in the application. It promotes consistency and ease of customization across the application's design.

Kick off your project with this hello-world boilerplate. This starter ships with the main Gatsby configuration files you might need to get up and running blazing fast with the blazing fast app generator for React.

_Have another more specific idea? You may want to check out our vibrant collection of [official and community-created starters](https://www.gatsbyjs.com/docs/gatsby-starters/)._

## 🚀 Quick start

1. **Create a Gatsby site.**

   Use the Gatsby CLI ([install instructions](https://www.gatsbyjs.com/docs/tutorial/part-0/#gatsby-cli)) to create a new site, specifying the hello-world starter.

   ```shell
   # create a new Gatsby site using the hello-world starter
   gatsby new my-hello-world-starter https://github.com/gatsbyjs/gatsby-starter-hello-world
   ```

2. **Theme UI.**

   gatsby-plugin-theme-ui is a plugin for the Gatsby framework that enables easy theming and styling of web applications. It uses Theme UI, a library that provides a set of customizable design tokens such as colors, typography, spacing, and layout, and allows developers to create consistent, cohesive designs across their applications.

   With gatsby-plugin-theme-ui, developers can define a theme object that includes their design tokens and pass it to the plugin, which will generate CSS styles based on those tokens. The plugin also provides a set of React components that can be used to implement the design system, such as a Box component for layout, a Text component for typography, and various input and form components.

   One of the benefits of using gatsby-plugin-theme-ui is that it allows for easy customization and theming of an application, as developers can simply update their theme object to change the design of the entire application. It also encourages the use of design systems and consistency across an application, which can lead to a better user experience.

   Overall, gatsby-plugin-theme-ui is a powerful tool for developers who want to create well-designed, responsive web applications using Gatsby and Theme UI.

   ```shell
   npm install theme-ui @theme-ui/mdx gatsby-plugin-theme-ui @emotion/react @mdx-js/react
   ```

   gatsby-config.js

   ```shell
   module.exports = {
   plugins: ["gatsby-plugin-theme-ui"],
   }
   ```

3. **Open the source code and start editing!**

## 🧐 What's inside?

    .
    ├── node_modules
    ├── src
    ├── .gitignore
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── gatsby-ssr.js
    ├── LICENSE
    ├── package.json
    └── README.md

<!-- AUTO-GENERATED-CONTENT:END -->
