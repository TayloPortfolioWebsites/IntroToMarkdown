# INTRODUCTION TO MARKDOWN CHEATSHEET

<!-- HEADING -->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

---

<!-- Italics -->
_This is going to be a paragraph in italicized format._

*This is going to be a paragraph in italicized format.*

---

<!-- STRONG -->
This is an example of **strong text**. Anything between two opening asterisks and two closing asterisks will be displayed as a **strong text**.

This is another example of a way to have __strong text__ in our document. Anything betwwen the two double opening underscore and closing underscore will be displayed as __strong text__.

---

<!-- STRIKE THROUGH -->
This is an example of ~~strike through~~ text. Anything in between the double tilde opening characters and double tilde closing characters will be displayed as ~~strike through~~.

---

<!-- HORIZONTAL RULE -->
We can add triple hypens to be able to create a horizontal rule for content separation.

---
Another way to create horizontal rules is by using three underscores.

___

<!-- ESCAPE CHARACTER RULES USING BACKSLASH -->
This is an example of *text with an asterisk*. When we don't want it to be italicized, we want to use the backslash \ to escape the rule of using an opening \*asterisk* and closing \*asterisk* to enclose the text content. 

---

<!-- BLOCKQUOTE RULE -->
> We us the greater than symbol to display a block of text as a quote with a background and line on the left side.

> *"You don't have to be great to start, but you need to start to be great."* __-Unknown Author__

---

<!-- LINKS RULE -->
**NOTE**: We would want to put the link description inside of square brackets and the link to the resouce inside of two open and close parenthesis.

[MyFacebookPage](http://www.facebook.com/imhazeltaylo)

__NOTE__: We can add a baloon title description to our link by using double quotes after the link to the resource.

[MyFacebookPage](http://www.facebook.com/imhazeltaylo "This is my FB Page")

---

<!-- LIST ITEM RULES -->

<!-- Unordered List -->
* Item 1 - this is our list item 1
  * This is our list item 1 child item 1
  * This is our list item 1 child item 2
* Item 2 - this is our list item 2
  * This is our list item 2 child item 1
  * This is our list item 2 child item 2
* Item 3 - this is our list item 3
  * This is our list item 3 child item 1
  * This is our list item 3 child item 2
* Item 4 - this is our list item 4
  * This is our list item 4 child item 1
  * This is our list item 4 child item 2
* Item 5 - this is our list item 5
  * This is our list item 5 child item 1
  * This is our list item 5 child item 2

<!-- Ordered List -->
1. Item 1 - this is our list item 1

     1.1. This is our list item 1 child item 1
     
     3.2. This is our list item 1 child item 2
2. Item 1 - this is our list item 1

     2.1. This is our list item 2 child item 1
     
     4.2. This is our list item 2 child item 2
3. Item 3 - this is our list item 3

     3.1. This is our list item 3 child item 1
     
     5.2. This is our list item 3 child item 2
4. Item 4 - this is our list item 4

     4.1. This is our list item 4 child item 1
     
     6.2. This is our list item 4 child item 2
5. Item 5 - this is our list item 5

     5.1. This is our list item 5 child item 1
     
     7.2. This is our list item 5 child item 2

---

<!-- CODE BLOCK INLINE RULE -->

**NOTE**: *__Backtics__ will allow us to show the code block or the paragraph tags in this example. It is located below the tilde character and on top of the tab key*

`<p> This is a paragraph tag with an inline code block example opening and closing tags </p>`

---

<!-- IMAGE RULE -->

![This is an image](https://i.redd.it/scb530bd10y11.png)

---

<!-- GITHUB FLAVOR SET OF CODE BLOCK -->

```bash
npm install

npm start
```
---

**NOTE**: You can specify some syntax code blocks for different languages.

```javascript
function testAdd(num1,num2){
 return num1 + num2
}
```

```python
def pythonAdd(num1,num2);
  return num1 + num2
```

```C#
public static int Sum(int num1, int num2)
 {
  int total;
  total = num1 + num2;
  return total;
 }
```

---

<!-- TABLE RULES -->

| Name | Nickname | Email |
|------|----------|-------|
|Tiffany|Tiff     |hazeltiffany.taylo@gmail.com|
|Steven |Ven      |stevenjohnson@gmail.com|
|Clark  |CK       |clarktaylo@gmail.com|

---

<!-- TASK LISTS -->
* [x] Task 1
* [ ] Task 2
* [ ] Task 3
