## small typescript / gql test environment

It is based on the free newline.co guide to building your first graphql server with node and typescript.

I use yarn v2 (to save space and be quick) with pnp config and vs code as editor. Editor is configured to use typescript with yarn's version. You need to regenerate sdk's for vscode if you add or remove any new packages. "gensdk" in package.json does this.

To install: `yarn install`  
To start: `yarn start`  
To regen sdk for vscode: `yarn gensdk`
