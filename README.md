# All3DP Eblast Templates

This repository contains example templates written in MJML to create mailchimp complient templates.

## Prerequisits

* NodeJS >= 16.x
* PNPM 7.x
* *Recommended:* [Visual Studio Code Extention for MJML](https://marketplace.visualstudio.com/items?itemName=mjmlio.vscode-mjml)

Execute "`pnpm i`" to install the nessesary nodejs modules.

## Doc`s:

* [MJML template syntax](https://documentation.mjml.io/)
* [Mailchimp merge tags cheat sheet](https://mailchimp.com/help/all-the-merge-tags-cheat-sheet/)

## Scripts:

The Eblast template are located in the "`/src`-folder". To build all templates execute "`yarn build`". The output of the buildprocess goes to "`/.output`".

- use `pnpm dev` to enter MJML watch mode. Template output goes to `/.output`
- use `pnpm test` to validate your templates
- use `pnpm build` to build templates. The output goes to `/.output`

## Preview changes

To preview your changes first start `pnpm dev` to build the templates and then execute `open .output/[tempalte].html` in a terminal (e.g. `open /Users/username/all3dp-eblast-templates/.output/base.html`) to preview changes in your browser.

### Templates:

Templates are based on MJML syntax, see https://mjml.io for details.

*  `basic.mjml` - contains a basic eblast.
*  `minimal.mjml` - contains a minimal eblast template with a header and footer.
