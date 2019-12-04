<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Workspace for gatsby-theme-styled-mdx
</h1>

## Development

**gatsby-theme-styled-mdx** is a Gatsby theme, which works as a dependency installed on another Gatsby site. This means you have to work in an environment that supports editing relative node modules, like Yarn Workspaces. To expedite development, there is a "workspace" repo that you can clone to replicate this environment easily.

1. Clone the workspace repo: `git clone git@github.com:whoisryosuke/gatsby-theme-styled-mdx-workspace.git`
1. Clone the example repo (inside workspace folder): `git clone git@github.com:whoisryosuke/gatsby-theme-styled-mdx-example.git`
1. Clone the theme (inside workspace folder): `git clone git@github.com:whoisryosuke/gatsby-theme-styled-mdx.git`
1. Install all dependencies by running `yarn` in the workspace root.
1. Start the development server (in workspace root): `yarn develop`

> If you have any strange issues when renaming project folders, try clearing all the cached folders from the workspace and nested projects (`node_modules`, `.cache`, and `public`). Then re-install the dependencies from the workspace root and run the Gatsby development server again. This should clear up some common issues, such as Markdown images interpeting as `String` instead of `File` types.

## Layout

```shell
📦
├── 📄 README.md
├── 📂 gatsby-theme-styled-mdx
│   ├── 📄 README.md
│   ├── 📄 gatsby-config.js
│   ├── 📄 index.js
│   └── 📄 package.json
├── 📂 gatsby-theme-styled-mdx-example
│   ├── 📄 README.md
│   ├── 📄 gatsby-config.js
│   ├── 📄 package.json
│   └── 📂 src
├── 📄 package.json
└── 📄 yarn.lock
```
