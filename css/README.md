# CSS

## Selectors

```css
.class1.class2
```
Selects all elements if both classes class1 and class2 exists in its class attribute.
<br>
<br>

```css
.class1 .class2
```
Selects all elements with class2 that is a descendant of an element with class1.
<br>
<br>

```css
.class1, .class2
```
Selects all elements of class1 and class2.
<br>
<br>

### Direct child
```css
div > p
```
Selects all \<p> elements where the parent is a \<div> element.
<br>
<br>

```css
[target=_blank]
```
Selects all elements with target="_blank"
<br>
<br>

### Begins With
```css
a[href^="https"]
```
Selects every \<a> element whose href attribute value begins with "https".
<br>
<br>

### Ends With
```css
a[href$=".pdf"]
```
Selects every \<a> element whose href attribute value ends with ".pdf"
<br>
<br>

### Contains
```css
img[src*="thumbnails"]
```
Select only those images containing “thumbnails” anywhere in the src attribute’s value.
<br>
<br>



### :first-child
```css
p:first-child{
      background-color: yellow;
}
```
Selects every \<p> element that is the first child of its parent.
<br>
<br>

### :last-child
### ::before 
### ::after
### :nth-child(n)