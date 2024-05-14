<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [CSS BOX MODEL DOCUMENTATION](#css-box-model-documentation)
  - [Some types of css](#some-types-of-css)
    - [CSS Selectors](#css-selectors)
    - [CSS colors](#css-colors)
    - [](#)
    - [CSS Background](#css-background)
    - [padding:](#padding)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# CSS BOX MODEL DOCUMENTATION
introduction to css <br>
CSS stands for Cascading Style Sheets. It's a style sheet language used for describing the presentation of a document written in a markup language like HTML. CSS describes how elements should be rendered on screen, in print, or in other media   
## Some types of css
1. Inline CSS: This type of CSS is applied directly to the HTML element using the style attribute. For example:

   ```html
   <p style="color: red; font-size: 16px;">This is a paragraph.</p>
2. Internal CSS: Internal CSS is defined within the HTML document itself, typically within the style element in the  section. It applies styles to elements within that specific document. For example:

```html
   <head>
    <style>
        p {
            color: blue;
            font-size: 18px;
        }
    </style>
    </head> 
```  
3. External CSS: External CSS is defined in a separate CSS file and linked to the HTML document using the <link> element. This allows you to apply the same styles to multiple HTML documents. For example:

```html
<head>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
```  
### CSS Selectors
 A CSS selector is a pattern used to select and style one or more HTML elements based on various criteria such as element type, class, ID, attributes, or their relationship with other elements.

 1. Class Selector: Selects elements with a specific class attribute. Classes are denoted by a dot (.) followed by the class name. For example, to select all elements with the class "highlight":
  ```css
    .highlight {
    /* CSS styles */
     }
 ```

 2. ID Selector: Selects a single element with a specific ID attribute. IDs are denoted by a hash (#) followed by the ID name. For example, to select an element with the ID "header":

 ```css
   #header {
    /* CSS styles */
   }
```

### CSS colors
  - CSS supports various ways to specify colors
###
1. Color Keywords: CSS provides predefined color keywords that represent common colors. For example:

 ```css 
  css code:
   color: red;
background-color: blue;
```
2. RGB Function: Colors can also be specified using the RGB function, which allows you to define colors by specifying the intensity of red, green, and blue. This function takes three comma-separated values between 0 and 255 or percentages. For example:  
  
  ```css
  css code:
   color: rgb(255, 0, 0); /* red */
background-color: rgb(0, 0, 255); /* blue */
```  
3. RGBA Function: Similar to RGB, the RGBA function allows you to specify colors with an additional alpha (transparency) value. The alpha value is a number between 0 and 1.

```css
  color: rgba(255, 0, 0, 0.5); /* semi-transparent red */
background-color: rgba(0, 0, 255, 0.7); /* semi-transparent blue */
```
### CSS Background
  css backgrond is used too replace the background image of your webpage  using css style this helps to make the webpage to be more atracting to human eyes.  
   ```css
   background-image: url(image path)
   ```
### padding:  
Padding is the distance from the element to the content this can be on the:  
  - left  
  - bottom  
  - Right  
  - top  
    
```css
/* Set equal padding on all sides */
.element {
    padding: 20px;
}

/* Set different padding on each side */
.element {
    padding-top: 10px;
    padding-right: 20px;
    padding-bottom: 15px;
    padding-left: 25px;
}
```

  

 
   
  