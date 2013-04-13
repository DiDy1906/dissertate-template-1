# Introducing the Pandoc + LaTeX dissertation template

This repository provides files needed to support the production and typesetting of a PhD dissertation. Write in Pandoc (a Markdown variant), sprinkle LaTeX wherever you see fit, and you'll end up with a beautiful pdf. The code currently supports Harvard.

# Getting started
1. Install the default font, EB Garamond. The files are provided in `fonts/EB Garamond`.
2. Pick your school. Edit line 29 of `pandoc-LaTeX-dissertation.cls' so that it points to your university's package file (e.g., `packages/Harvard').
3. Personalize the document by filling out your name and all the other info in the file `frontmatter/personalize.md`.
4. Build your dissertation with `build.command`, located in the `scripts' directory (e.g., you can `cd` into the main directory and then run `./scripts/build.command`).

# License

This software is free and is covered under the MIT License, given here:

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.