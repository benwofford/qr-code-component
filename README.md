# Frontend Mentor - QR code component solution

This is my solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [License](#license)

## Overview

### Screenshot

![qr element](/images/qr-main.png)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/qr-component-card-gXbxzncvQ)
- Live Site URL: [Live Site](https://benwofford.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS
- Flexbox

### What I learned

I had difficulty with centering the component vertically. After applying the `align-items` property to flex container, I realized that it won't work without it's height defined. But after defining the height to `100vh` it scrolled too far vertically so I reset it by making the margin and padding zero.

```
body {
  background-color: hsl(212, 45%, 89%);
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
  padding: 0;
}
```

## Author

- Website - [Ben Wofford](https://benwofford.github.io/react-portfolio/)
- Frontend Mentor - [@benwofford](https://www.frontendmentor.io/profile/benwofford)
- Github - [@benwofford](https://github.com/benwofford)

## License

MIT License

Copyright (c) 2022 Ben Wofford

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
