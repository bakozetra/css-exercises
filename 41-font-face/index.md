# CSS exercise 41: Font-face

Webfonts are strongly tied to a site's design and its visual identity.

But before we can use them, there are a few things we need to know:

1. There are several types of font formats, e.g. `WOFF`, `TTF`, etc.? Name at least 2 other font file formats.
2. Which of these font file formats is a good candidate to use in all browsers?
3. The font-face syntax is also different to other @-blocks. What are the differences between a `@font-face` block and `@keyframes` / `@media` queries / `@supports` blocks, etc.
4. Some fonts come with licencing restrictions. What does this mean?
5. A designer has assigned you a mockup to turn into HTML/CSS. You've tabled the list of fonts used in the document as follows:

font-family | font-weights | italic?
--- | --- | ---
'Roboto' | 400, 700 | Both
'Proxima Nova' | 100, 300, 600, 800 | No

How many font-face blocks do we need to provide if we want to support all the chosen fonts?

6. At roughly 20KB per font file, how many kilobytes of fonts would each of our users have to download in the example above?
7. If we chose to offer WOFF2 as well as WOFF, what syntax would we use? How many files would we have, according to question 5?
8. Most of our users would probably have the exact font we want to serve already installed on their devices. How can we make sure the user's browser doesn't download the fonts they might already have?
9. Sometimes we have to assign fallback fonts for our custom webfonts we add via `@font-face`. What are some things to keep in mind when it comes to selecting these fallback fonts?
10. The browser can use one of several strategies for loading the fonts, e.g. showing nothing until the font is downloaded, or using a fallback font first. What property can we use to help the browser decide on which strategy to use?

1) Name of font formats : -"cvg", "eot","otf"

2) "WOFF1" is the good  to use in all browsers .

 there are  no name on it and we need to use scr(font-face)
 this only  hve one curly bracket on it .
 It  is combinasion of font property.

4)That means download file from the browser.we have to buy if we want to use the font-face because it is not free.

5) there are two font-face  blocks. there are 8 file.


6)  we have to use 160 Kb .


 7) we need  to use font-family , font-weight ,16 file we have to use for it . because we have to use it woof1 and woof2 .(8 file bt it  is times to)
 syntax we use scr : url()format(),
                 url()format();
   we have to put woof2 first becausse it is the choosen .

 8) We have to use  local function , or system name .Local(systeme name)

 9)we have to use
  "roboto", arial ,helvetica,sans-serif;
  we have to use  same characteristic of the property we are going to use .


 10)1 -Renders
      -fallback
      -font
      -first

    2 -black until downloaded it .
    name of 1 ,2 font-display .or fallback, swap , optional.


