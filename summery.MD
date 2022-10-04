# CSS CHEAT SHEET
## This is a css cheat sheet made by Idan Zehavi

1. [Units and sizes](#units)
2. [Box Model](#Box)
3. [Typography](#typography)

---

## Units and sizes<a name="units">
| Unit | Description |
|------|-------------|
|px    | amount of pixels on the display|
|%     |persentage of the parent size|
|rem   | root element size|
|em    | parent element size|
|ch    | amount of charcters|
|vw    | view width - width of screen in percentage|
|vh    | view height - height of screen in percentage|

* There's a disadvantage to using an absolute unit like px , when the user tries to increase the font on the browser side , the font will remain the same , making the user expiriance 
* very unpleasent , we would usually use px with borders or stuff that we need to remain the same regardless of the browser settings

* Percentage is usually used to set the sizing of different elements

* rem ,em usually used for font size

---

## Box Model <a name="Box">
> In css everything is a Box
There are layers to every element on the screen and it goes as follows:
1. The element itself
2. padding - every element has a "box surrounding it , that box is considered the boundry of an element , meaning where it ends , this is the padding
3. The border - the border itself which defines the end of an element and is defined as its width
4. Margin - the margin is another "Box" that defines the minimal distance of the closest elements

* You can define the width of all of these properties
* the margin is dependent on the size of the element and will increase or decrease accordingly

---

## Typography <a name="typography">

* Preferrably , should never use absolute font size like "px" to let the user decide the font size , thus making the user expiriance better as was explained previously and should use "rem" most of the time

* Text Decorations has many ways to decorate and improve a paragraph or any text.

> text-decoration: underline;

* This will add an underline to the text
there are also "overline" , "line-through" etc...

* Text transform is another way to change the appearance of a text but rather then adding things this changes the text itself.
> text-transform:

* This changes the text itself in many ways , for example:
"capitalize" , "lowercase" , "uppercase" , "inherit" , "initial" etc....