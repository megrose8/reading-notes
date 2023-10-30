# Readings: Images, Color, Text
## Things I want to know more about: 
*Is there a time when determining width/height of an image in HTML would be better than determining it in CSS?*  
*Will font shadows decrease accessibility for someone with eye difficulties?*

## HTML: 
* HTML images:   
    * `<img>` `src= URL` `alt=IMG DESCRIPT`
    * src attribute can be relative or absolute URL. Suggested to host the images on wanted on your site.
    * alt is where the image description lives. This is helpful since it will placehold the image if it does not load. Further, it increases accessibility for people who use screen readers.  
        * Other uses: SEO optimization, users who turn off image leading, browser doesn't support file type.  
        * `alt` should include all data that you would want if the image doesn't show up. 
    * Images can also include attributes surrounding width, height, and titles (titles are not recommended for accessibility purposes)
    * Figure elements can create semantic containers for figures and clearly link the figure to the caption.  
    `<figure>`  
    image here  
    `<figcaption>`   
    text caption  
    `</figcaption>`
    `</figure>`

* Types of file types:   
    * GIF: Graphics Interchange Format. Used for simple images and animations  
    * SVG: Scalable Vector Graphics. Idesl for icons, interface, elements. For content that needs to be drawn accurately at different sizes.

## CSS
* `Color` Property: Foreground of HTML elements color. Text, text decoration
* `background-color` : Background of element. Text background color. Also used in areas of element that have no foreground content (in boxes). 
* Font Styles: Sizes, bold, italics, font applied to text.
* Text layout: Spaces between letters, lines, and alignment.
* Font Families: Only a certain number of fonts are available across all background. Use "web safe fonts." Families allow browsers to have multiple fonts to choose from. If one font isn't available, it will choose the next stacked font that works.
`font-style` Italics on/off  
`font-weight` Uppercase/Lowercase/Etc.  
`text=decoration` under line, overline, line through
`text-shadow` up to four values surrounding horizontal offset with length and size units, vertical offset, blur radius, and base color

##### For greater expansion of options see: [MDN Font Styling](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)

