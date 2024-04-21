<h1 align="left"><img src="https://raw.githubusercontent.com/yardenporat/yardenporat/master/assets/wave.gif" width="30px"><strong> Hello There, I'm <a href="https://linkedin.com/in/yarden-porat/">Yarden Porat.</a></strong>
</h1>

<h3 align="left">
I am a passionate and enthusiastic self-taught web developer.
</h3>

<a target="_blank" href="https://linkedin.com/in/yarden-porat/">
<img src="https://img.shields.io/badge/-yardenporat-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://linkedin.com/in/yardenporat/" alt="Linkedin Badge">
</a>

![Yarden Porat's GitHub Stats](https://github-readme-stats.vercel.app/api?username=yardenporat&show_icons=true&theme=tokyonight)

## Projects

<details>
  <summary>
    <strong>Contactless WhatsApp Messenger</strong>: Send whatsapp messages without adding people to your contact
  </summary>


Click on the image to view the project:
<p align="center">
  <a href="https://yardenporat.github.io/contactless-whatsapp/">
    <img src="https://github.com/YardenPorat/contactless-whatsapp/raw/main/public/logo.png" alt="Contactless WhatsApp Messenger" width="300">
  </a>
</p>
    
[Go to repository](https://github.com/YardenPorat/contactless-whatsapp)

</details>

<details>
  <summary>
     <strong>Selectors Translated</strong>: CSS selector translator and visualizer
  </summary>

Click on the image to view the application:

<p align="center">
  <a href="https://yardenporat.github.io/selector-translator/">
    <img src="./assets/selectors-translated.png" alt="Selectors Translated" width="300">
  </a>
</p>

</details>
<details>
  <summary>
     <strong>LinkedIn Frame Generator</strong>: Create custom LinkedIn avatar frames
  </summary>
<br>
Not long ago LinkedIn added a feature that allows adding a frame to your profile picture, letting everyone know if your are #hiring or #opentowork.

Now, you can create your own custom frames, adding a little more character to your LinkedIn profile.

<p align="center">
  <a href="https://yardenporat.github.io/linkedin-frame/" target="_blank"> 
    <img src="./assets/linkedin-frame-generator.png" alt="LinkedIn Frame Generator" width="300">
  </a>
</p>

</details>
<details>
  <summary>
     <strong>ESLint plugin: validate declared imports</strong>: validate typescripts globally declared modules
  </summary>
<br>

[Repository link](https://github.com/YardenPorat/eslint-plugin-validate-declared-imports)

[![test](https://github.com/yardenporat/eslint-plugin-validate-declared-imports/actions/workflows/test.yml/badge.svg)](https://github.com/yardenporat/eslint-plugin-validate-declared-imports/actions/workflows/test.yml)
[![npm](https://img.shields.io/npm/v/eslint-plugin-validate-declared-imports)](https://www.npmjs.com/package/eslint-plugin-validate-declared-imports)

When you declare modules with typescript, filepaths are not validated to be correct.

Example:

```ts
declare module "*.module.css" {
  const classes: { [key: string]: string };
  export default classes;
}
```

This will not throw an error, even though path is incorrect:

```ts
import styles from "asdasdasdasdasd.module.css";
```

### Usage

Add `validate-declared-imports` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
  "plugins": ["validate-declared-imports"]
}
```

Then configure the rules you want to use under the rules section.

```json
{
  "rules": {
    "validate-declared-imports/no-unresolved-declared-imports": [
      "error",
      {
        "fileExtensions": [
          // Asset files: png, jpeg, svg...
          ".jpg",
          // Style files
          ".module.css", // CSS Modules
          ".module.scss", // SCSS Modules
          ".module.less", // Less Modules
          ".st.css" // Stylable files
        ]
      }
    ]
  }
}
```

</details>
<details>
  <summary>
     <strong>LeanKit to GitHub: chrome extension</strong>: Add links to KanBan cards
  </summary>
<br>

[Repository link](https://github.com/YardenPorat/eslint-plugin-validate-declared-imports)

[PlanView AgilePlace \ PlanView LeanKit](https://www.planview.com/products-solutions/products/agileplace/)

A tiny chrome extension that adds GitHub links to cards which references github issue or pull request.

<p align="center">
  <img src="./assets/leankit-github.png" alt="GitHub links on a card" >
</p>
You can customize the board's title which you want to focus on, and your favorite GitHub repository which you want to go to

<p align="center">
  <img src="./assets/leankit-github-customize.png" alt="customization options" >
</p>

<br>

<details>
  <summary>
    <strong>MORE ABOUT ME</strong>
  </summary>

```ts
const yardenporat = {
  education: [
    "BA - Reichman University (IDC Herzliya)",
    "MBA - Tel Aviv University",
  ],
  languages: ["TypeScript", "Javascript", "Python", "Bash Scripts"],
  frameworks: ["Node.js", "React.js", "Next.js"],
  css: ["CSS", "Sass", "Stylable"],
  tests: ["playwright", "mocha", "chai", "sinon"],
  DBs: ["MongoDB", "SQL"],
  tools: ["Git", "Wordpress", "Electron"],
};
```

</details>

<a target="_blank" href="https://github.com/yardenporat/">
<img src="https://img.shields.io/badge/dynamic/json?url=https://api.countapi.xyz/hit/visitor-badge/yardenporat&style=for-the-badge&label=visitors&query=value&color=0F0F1A&labelColor=0F0F1A" alt="yardenporat's vistors">
</a>
