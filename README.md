# All3DP Newsletter Templates

## Prerequisits

* NodeJS >= 16
* Yarn 1.x
* *Recommended:* [Visual Studio Code Extention for MJML](https://marketplace.visualstudio.com/items?itemName=mjmlio.vscode-mjml)

Execute "`yarn add`" to install the nessesary nodejs modules.

## Doc`s:

* [MJML template syntax](https://documentation.mjml.io/)
* [Mailchimp merge tags cheat sheet](https://mailchimp.com/help/all-the-merge-tags-cheat-sheet/)

## Scripts:

The newsletter template are located in the "`/src`-folder". To build all templates execute "`yarn build`". The output of the buildprocess goes to "`/.output`".

- use `yarn dev` to enter MJML watch mode. Template output goes to `/.output`
- use `yarn test` to validate your templates
- use `yarn build` to build templates. The output goes to `/.output`

### Templates:

Templates are based on MJML syntax, see https://mjml.io for details.

*  `basic.mjml` - contains a basic newsletter.

## License

  The MIT License (MIT)

  Copyright (c) 2022 All3DP GmbH
  https://all3dp.com/

  Permission is hereby granted, free of charge, to any person obtaining a copy
  of this software and associated documentation files (the "Software"), to deal
  in the Software without restriction, including without limitation the rights
  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  copies of the Software, and to permit persons to whom the Software is
  furnished to do so, subject to the following conditions:

  The above copyright notice and this permission notice shall be included in
  all copies or substantial portions of the Software.

  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
  LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
  THE SOFTWARE.
