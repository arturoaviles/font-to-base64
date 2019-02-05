# Convert Font to Base64

Used Font Squirrel website to get the CSS properties converted. (https://www.fontsquirrel.com/tools/webfont-generator)

## Steps to get the CSS file

1. Download the font you want to convert.
2. Go to the website.
3. Upload the font.
4. Select the EXPERT option in the Font Squirrel Configuration.
5. Check the Font Squirrel Base64 option.
6. Check the Font Squirrel Agreement.
7. Download the file.

Also make sure to __define/change__ the __NAME__ of the font (In this case I called it __Montserrat__):

```css
@font-face {
    font-family: 'Montserrat';
    src: ...
}
```

## Check if it is working

Use __main1.css main2.css main3.css__ and __index.html__ to verify that it is actually using your font.

__main1.css:__ In this file you need to change the __import URL__ to the one you are using from Google Fonts

__main2.css:__ In this file you need to change the __BASE64__, the __font name__, and the __font used for the body tag__

__main3.css:__ This file has __arial__ as the default font.

__index.html:__ This file calls the CSS files.

In order to check, you need to __serve__ the __html__ and change the __css file__ used. 
