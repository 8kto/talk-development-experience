Make Babushka be proud of you

+ Enable **TypeScript** (optional)
+ **SASS** support (most likely)
+ Add **Storybook** (must have for complex UIs or designs)


# SASS
All we need is install of `gatsby-plugin-sass`
```
yarn add node-sass gatsby-plugin-sass
```

`gatsby-config.js` — is a special file with gatsby-specific options. Besides the all of other options, it has a list of active plugins.


# TypeScript

```
# Basic TS support
yarn add typescript gatsby-plugin-typescript

# Advanced TS support
yarn add gatsby-plugin-typescript gatsby-plugin-tslint &&\
yarn add --dev typescript tslint tslint-loader

# Rename all *.js files to *.tsx
find src/ -name "*.js" -exec rename 's/.js/.tsx/' {} \;
```

**Nice articles about TypeScript integration**
+ https://medium.com/maxime-heckel/getting-started-with-typescript-on-gatsby-8544b47c1d27
+ https://medium.com/@thetrevorharmon/how-to-make-a-super-fast-static-site-with-gatsby-typescript-and-sass-3742c00d4524


# Storybook

```
npm install -g @storybook/cli
yarn add --dev @storybook/react @storybook/addon-knobs @storybook/addon-viewport @storybook/addon-options storybook-readme ts-loader  @types/node @types/react @types/react-dom @types/react-helmet @types/react-redux @types/storybook__addon-actions @types/storybook__addon-knobs @types/storybook__addon-options @types/storybook__react

cd my-awesome-gatsby-project
sb init

```

https://www.gatsbyjs.org/docs/visual-testing-with-storybook/
  


