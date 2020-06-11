## IMAGES
- it's better to store your website images in a folder.
` <img src="images/apple.jpg" alt="red apple" title="red apple is a kind of fruits." /> `
- to mention the width and height we use ` <img src="images/apple.jpg" alt="red apple" width="600" height="450" /> `
- we can use **adobe photoshop** or other images editors to make changes before using them.
- **JPEG** the format used when a picture has many colors 
![JPEG image](https://png.pngtree.com/thumb_back/fw800/back_our/20190617/ourmid/pngtree-hand-drawn-abstract-colorful-butterfly-h5-background-image_129049.jpg)
_ GIF & PNG is used when there is a big area with same color
![GIF & PNG](https://cdn.dribbble.com/users/1381456/screenshots/9710226/wolf.png)
- Images created for the web should be saved at
a resolution of 72 ppi. The higher the resolution
of the image, the larger the size of the file.
- You should save images at the size you will be using
them on the web page and in the appropriate format.
- Photographs are best saved as JPEGs; illustrations or
logos that use flat colors are better saved as GIFs.
## Colors

` h1 {`
`color: DarkCyan;}`
/* hex code */
`h2 {`
`color: #ee3e80;}`
/* rgb value */
`p {`
` color: rgb(100,100,90);} ` 


- colors can be choosed by rgb values , hex codes and color names.
- Every color on a computer screen is created by mixing amounts of red,
green, and blue. To find the color you want, you can use a color picker.

**opacity** 

![](https://lh3.googleusercontent.com/proxy/13O1hlVuMgYlSSwGPHgnesnB7F_8BJQ9EC9E29HsyXPfbBYrc_KmssqaBQUhBoMy7i6pwZQtlKUV9V0w5UxZlgU3eJp7AgvIqH5t7A)

- CSS3 introduces an entirely new and intuitive
way to specify colors using hue, saturation,
and lightness values.
- The hsl color property has
been introduced in CSS3 as an
alternative way to specify colors. 

 `body {`
`background-color: #C8C8C; `
`background-color: hsl(0,0%,78%);}`
`p {`
`background-color: #ffffff;`
`background-color: hsla(0,100%,100%,0.5);} `

## Text 
` body {`
 `font-family: Georgia, Times, serif;}`
 `h1, h2 {`
 `font-family: Arial, Verdana, sans-serif;}`
 `.credits {`
 `font-family: "Courier New", Courier,`
 `monospace;} `

- The font-family property
allows you to specify the
typeface that should be used for
any text inside the element(s) to
which a CSS rule applies.

` font-size: 12px;} `
- The font-size property enables
you to specify a size for the
font. 
   ` @font-face {`
`font-family: 'ChunkFiveRegular';`
`src: url('fonts/chunkfive.eot');}`
`h1, h2 {`
`font-family: ChunkFiveRegular, Georgia, serif;} `
` @font-face ~` is used to  use
a font, even if it is not installed
on the computer of the person
browsing, by allowing you to
specify a path to a copy of the
font, which will be downloaded if
it is not on the user's machine.
- font formats :
1. eot
1. woff
1. ttf/otf
1. svg 

**UpperCase &
LowerCase**
`h1 {`
`text-transform: uppercase;}`
`h2 {`
`text-transform: lowercase;}`
`.credits {`
`text-transform: capitalize;} `
**styling links**

`a:link {`
`color: deeppink;`
`text-decoration: none;}`
`a:visited {`
`color: black;}`
`a:hover {`
`color: deeppink;`
`text-decoration: underline;}`
`a:active {`
`color: darkcyan;} `
- There are properties to control the choice of font, size,
weight, style, and spacing.
- There is a limited choice of fonts that you can assume
most people will have installed.
- If you want to use a wider range of typefaces there are
several options, but you need to have the right license
to use them.
- You can control the space between lines of text,
individual letters, and words. Text can also be aligned
to the left, right, center, or justified. It can also be
indented.
- You can use pseudo-classes to change the style of an
element when a user hovers over or clicks on text, or
when they have visited a link.