# CSSRevisionPoints

## Q - 1 What is CSS?
- CSS allows you to apply styles to web pages
- It provides powerful control over the presentation of an HTML document.

## Q - 2 Why do we use CSS?
- To make HTML File more presentable to the users 
- **CSS saves time:** You can write CSS once and reuse the same sheet on multiple HTML pages.
- **Easy Maintenance:** To make a global change simply change the style, and all elements in all the webpages will be updated automatically.
- CSS is considered a clean coding technique, which means search engines won’t have to struggle to “read” its content.

## Q - 3 What are the advantages of CSS?
- CSS plays an important role, by using CSS you simply got to specify a repeated style for an element once & use it multiple times because CSS will automatically apply the required styles.
- Cascading sheet not only simplifies website development but also simplifies maintenance as a change of one line of code affects the whole website and maintenance time
- It is less complex therefore the effort is significantly reduced.
- It has the power for re-positioning. It helps us to determine the changes within the position of web elements that are there on the page.

## Q - 4 What are the disadvantages of CSS?
- With CSS, what works with one browser might not always work with another. The web developers need to test for compatibility, running the program across multiple browsers.
- Browser compatibility (some style sheets are supported and some are not).
- After making the changes we need to confirm the compatibility if they appear. A similar change affects all the browsers.

## Q - 5 How is CSS different from CSS 3?

| CSS | CSS3 |
| --- | ---- |
| CSS cannot be split into modules. | Whereas, whereas CSS3 can be breakdown into modules. |
| Using CSS, we cannot build 3D animation and transformation. | But in CSS3 we can perform all kinds of animation and transformations as it supports animation and 3D transformations.
| CSS is very slow as compared to CSS3 | Whereas, CSS3 is faster than CSS. |
| Responsive designing is not supported in CSS | CSS3 is the latest version, hence it supports responsive design. |


## Q - 6 What is the syntax for CSS?
- A CSS style rule consists of a selector, property, and its value. The selector points to the HTML element where CSS style is to be applied. The CSS property is separated by semicolons.
```css
selector { 
    Property: value; 
}

```

## Q - 7  In how many ways can we add CSS to our HTML file?
- **Inline CSS:-** = Inline CSS contains the CSS property in the body section attached with the element known as inline CSS.This kind of style is specified within an HTML tag using the style attribute.
- **Internal CSS:-** = The CSS ruleset should be within the HTML file in the head section i.e the CSS is embedded within the HTML file.
- **External CSS:-** = External CSS contains a separate CSS file which contains only style property with the help of tag attributes.CSS property is written in a separate file with .css extension and should be linked to the HTML document using the link tag


## Q - 8 Which type of CSS holds the highest priority?
- inline css > internal css > external css

## Q - 9 What are CSS Selectors?
- CSS Selectors are a way to target an html element by either element name, id, class name or attribute.
- **Types:-**
  - **Element Selector** = The element selector in CSS is used to select HTML elements which are required to be styled.
  - **id selector:-** = The #id selector is used to set the style of the given id. The id attribute is the unique identifier in an HTML document.
  - **class selector:-** = The .class selector is used to select all elements which belong to a particular class attribute. To select the elements with a particular class, use the (.) character with specifying the class name.
  

## Q - 10 What does the ‘a’ in rgba mean?
- stands for alpha that represents transparency of an element ranges from 0(full transparent) to 1(not transparent)


## Q - 11 What are CSS HSL Colors?
- HSL stands for Hue, Saturation, and Lightness respectively. This format uses the cylindrical coordinate system.
- **Hue:** Hue is the degree of the color wheel. Its value lies between 0 to 360 where 0 represents red, 120 represents green and 240 represents a blue color.
- **Saturation:** It takes a percentage value, where 100% represents completely saturated, while 0% represents completely unsaturated (gray).
- **Lightness:** It takes a percentage value, where 100% represents white, while 0% represents black.

## Q - 12 background-attachement vs background-position?

- **background-attachment:** This property is used to fix the background ground image. The image will not scroll with the page.
- **background-position:** This property is used to set the image to a particular position.

## Q - 13 Margin Vs Paddding

| Margin | Padding |
| ------ | ------- |
| Space between elements | space between element and its border |
| can take negative values | can't take negative values |
| can set to auto | can't set  to auto |

## Q - 14 What is CSS Box Model?
- The CSS box model is a container that contains multiple properties including borders, margin, padding, and the content itself.
- The web browser renders every element as a rectangular box according to the CSS box model.

## Q - 15 What is the difference between CSS border and outline?
- CSS border properties allow us to set the style, color, and width of the border.
- CSS outline property allows us to draw a line around the element, outside the border.Outline do not allow to set each edge differenty


## Q - 16  How can we format text in CSS?
- CSS text formatting includes the following properties:

  1. Text-color
  2. Text-alignment
  3. Text-decoration
  4. Text-transformation
  5. Text-indentation
  6. Letter spacing
  7. Line height
  8. Text-direction
  9. Text-shadow
  10. Word spacing

## Q - 17 What are the different CSS link states?
- Links can exist in different states and they can be styled using pseudo-classes.
- a:link: This is a normal, unvisited link.
- a:visited: This is a link visited by a user at least once
- a:hover: This is a link when the mouse hovers over it
- a:active: This is a link that is just clicked.


## Q - 18 Can we add an image as a list item marker?

- To add an image as the list-item marker in a list, we use the list-style-image property in CSS. 

```css
list-style-image: none | url | initial | inherit;
```
## Q - 19 visibility:hidden vs display:none:
- visibility doesn't remove space occupied by element while display removes the space after hiding the content.

## Q - 19 what is Z-index?
- The z-index property is used to displace elements on the z-axis i.e in or out of the screen. It is used to define the order of elements if they overlap with each other.


## Q - 19 What are the various positioning properties in CSS?
- 5 positions in css are:-
  - **Fixed:-** = An element with fixed positioning allows it to remain at the same position even as we scroll the page. We can set the position of the element using the top, right, bottom, and left.
  - **static:-** = The element will be positioned with the normal flow of the page.
  - **Relative:** = An element with position: relative is positioned relatively with the other elements which are sitting at top of it.
  - **Absolute:-** = An element with position: absolute will be positioned with respect to its parent. The positioning of this element does not depend upon its siblings or the elements which are at the same level.
  -  Element with position: sticky and top: 0 played a role between fixed & relative based on the position where it is placed.If the element is placed in the middle of the document then when the user scrolls the document, the sticky element starts scrolling until it touches the top.

## Q - 20 What is CSS overflow?
- The CSS overflow controls the big content. It tells whether to clip content or to add scroll bars. 


1. Visible: The content is not clipped and is visible outside the element box.

2. Hidden: The overflow is clipped and the rest of the content is invisible.

3. Scroll: The overflow is clipped but a scrollbar is added to see the rest of the content. The scrollbar can be horizontal or vertical.

4. Auto: It automatically adds a scrollbar whenever it is required.


## Q - 21 What does the CSS float property do?
- The float property defines the flow of content.


## Q - 22 What does display:inline-block do?
- This feature uses both properties: block and inline. So, this property aligns the div inline but the difference is it can edit the height and the width of the block.


## Q - 23 How to center a text ?
```css
div {
    height: 200px;
    line-height: 200px;
    text-align: center;
    border: 2px dashed #f69c55;
}
```

## Q - 24 What are CSS Combinators?
- CSS combinators are explaining the relationship between two selectors.
- Child Selector(>): This selector is used to select the element that is the immediate child of the specified tag.
- Adjacent selector(+): The Adjacent sibling selector is used to select the element that is adjacent or the element that is next to the specified selector tag. This combinator selects only **one** tag that is just next to the specified tag.
- Descendant selector(space): This selector is used to select all the child elements of the specified tag. The tags can be the direct child of the specified tag or can be very deep in the specified tag.
- General Sibling selector (~) : The general sibling selector is used to select the element that follows the first selector element and also shares the same parent as the first selector element.
```css
former_element ~ target_element { style properties }

```

## Q - 25 What are pseudo-classes in CSS?
- A Pseudo class in CSS is used to define the special state of an element.
- It can be combined with a CSS selector to add an effect to existing elements based on their states. 
- :hover, :active, :focus, :visited

## Q - 26 What are pseudo-elements in CSS?
- Pseudo-element in CSS is used to add style to specified parts of an element.
- indicated by ::
- ::before Pseudo-element: It is used to add some CSS property before an element when that element is called.
- ::after Pseudo-element: It is used to add some CSS property after an element when that element is called.
- ::first-letter Pseudo-element: It is used to make changes to the first letter of an element.
- ::first-line Pseudo-element: It is used to make changes to the first line of an element.


## Q - Can we add 2D transformations to our project using CSS?
- transform property can translate(),scale(),rotate(),skew()

## Q - 39. What are CSS transitions?
- Transitions in CSS allow us to control the way in which transition takes place between the two states of the element. 
- transition-property: This property allows you to select the CSS properties which you want to animate during the transition(change).
- transition-duration: This property allows you to determine how long it will take to complete the transition from one CSS property to the other.
- transition-timing-function: This property allows you to determine the speed of change and the manner of change, during the transition. Like, the change should be fast at the beginning and slow at the end, etc.
- transition-delay: This property allows you to determine the amount of time to wait before the transition actually starts to take place.

## Q - 40 What does the CSS box-sizing property do?
- CSS property defines how the user should calculate the total width and height of an element i.e. padding and borders, are to be included or not.
- content-box is default-value, in which the specified height and width will be applied to the content but not border and padding, border and padding will be included during rendered
- border-box includes content+border+padding which means if set width as 200px then it will be only 200px included all the things


## Q - 41 What is CSS flexbox?
-  It is basically a layout model that provides an easy and clean way to arrange items within a container.
- **Flex Properties:-**
  - flex-direction - whether the content is column wise or row wise
  - flex-wrap - wrap or not
  - flex-flow - shorthand for flex-direction and flex-wrap
  - justify-content - alignments of items according to main axis
  - align-items - alignments of items according to cross axis
  - align-content - The CSS align-content property sets the distribution of space between and around content items along a flexbox's cross-axis
  
## Q - 44. What is CSS Grid?
- It is a CSS property that offers a grid-based layout system, with rows and columns, making it easier to design web pages without floats and positioning.

## Q - 45  What is the difference between flexbox and grid?
- Being one-dimensional, Flexbox only deals with either columns or rows.The grid has two-dimension layout capabilities which allow flexible widths as a unit of length. 

- @import rule: The @import rule is used to import one style sheet into another style sheet.


## Q - 46 What is !important?
- The !important rule in CSS is used to add more importance to a property/value than normal.
- In fact, if you use the !important rule, it will override ALL previous styling rules for that specific property on that element!


## Q - 47 What is specificity in CSS?
- When more than one set of CSS rules applies to the same element, the browser will have to decide which specific set will be applied to the element. 

- Specificity Hierarchy: Every element selector has a position in the Hierarchy.

  - Inline style: Inline style has the highest priority.
  - Identifiers(ID): ID has the second-highest priority.
  - Classes, pseudo-classes, and attributes: Classes, pseudo-classes, and attributes have come next.
  - Elements and pseudo-elements: Elements and pseudo-elements have the lowest priority.

## Q - 48 What is attribute selector?
- The CSS Attribute Selector is used to select an element with some specific attribute or attribute value. 
  - [attribute] Selector: This type of attribute selector is used to select all the elements that have the specified attribute and applies the CSS property to that attribute. For example, the selector [class] will select all the elements with the style attribute.
  - [attribute = “value”] Selector: This selector is used to select all the elements whose attribute has the value exactly the same as the specified value.
  - [attribute~=”value”] Selector: This selector is used to select all the elements whose attribute value is a list of space-separated values, one of which is exactly equal to the specified value.
  - [attribute|=”value”] Selector: This selector is used to select all the elements whose attribute has a hyphen-separated list of values beginning with the specified value. The value has to be a whole word either alone or followed by a hyphen.
  - [attribute*=”value”] Selector: This selector selects all the elements whose attribute value contains the specified value present anywhere. The value doesn’t need to be a whole word.
  
  
  
## What are Storage Classes?
- Storage Classes are used to describe the features of a variable/function.
- These features include scope,visibility, and the lifetime of variable througout the program.
- It Has 4 classes:-
  - **auto:-** 
    - This is the default storage class for all the variables declared inside a function or a block. 
    - They are assigned a garbage value by default whenever they are declared. 
    - Auto variables can be only accessed within the block/function they have been declared and not outside them (which defines their scope). Of course, these can be accessed within nested blocks within the parent block/function in which the auto variable was declared.
  - **static:-**
    - This storage class is used to declare static variables 
    - Static variables have the property of preserving their value even after they are out of their scope!
    - Hence, static variables preserve the value of their last use in their scope. So we can say that they are initialized only once and exist till the termination of the program.
  - **register:-**
    - This storage class declares register variables that have the same functionality as that of the auto variables.
    - The only difference is that the compiler tries to store these variables in the register of the microprocessor if a free registration is available.
    - This makes the use of register variables to be much faster than that of the variables stored in the memory during the runtime of the program. 
  - **extern:-**
    - Extern storage class simply tells us that the variable is defined elsewhere and not within the same block where it is used. 
    - an extern variable is nothing but a global variable initialized with a legal value where it is declared in order to be used elsewhere.
    - The main purpose of using extern variables is that they can be accessed between two different files which are part of a large program. 
    
    
    
    
    
    
    
    
  
  
  
