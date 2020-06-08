
## Structuring webpages with CSS

> ***"The key to understanding how CSS works is to
imagine that there is an invisible box around
every HTML element." -Master Duckett.***

- Block-level elements
    - These are on their own lines. 

- Inline elements
    - These are within lines. 

## Think inside the box just this once.

- The space inside those boxes and surrounding the elements can be styled with CSS. Not just the text! So a border or highlighting or other styles could be added to both inline or block level elements. 

## CSS Rules

- These rules connect a style element with an html element. 

Example rule: 

        h1 {
            font-family: Times New Roman; 
            color: red;
        }

In this example `h1` is the *selector*, meaning it selects the html element to style.  Inside the curly braces is the style *declaration*, which consists of a *property* such as `color:` or `font-family:`, and a *value* such as `red;` or `Times New Roman;`. <b>Note the specific punctuation that must be used. </b>

| Selector | What it do | Example | 
| --- | --- | --- |
| Universal | Styles all elements in the file/page  | `* {}` |
| Type  | Styles specific types of elements | `h1. h2.{}` |
| Class  | Styles elements who whose class attribute matches the stuff after the period in the selector and element matches what comes first. Or there can be none and it applied to all elementy with such a class attribute.  | `p.xyz {}` <br><br> `.xyz`|
| ID  | Styles elements whose class attribute matches the stuff after the hashtag in the selector| `#abc {}`
| Child  | Styles only the elements that are children (come below/after) the parent element. Parent>child | `p>ul {}` |
| Descendant  | Descendants are children, grandchildren and so on. This styles any element nested inside a parent element.| `p a {}` |
| Ajacent Sibling  | Siblings are elements that are not nested inside one another. This selector refers to siblings that come consecutively.  | `h1+p {}` |
| General Sibling  | Same as above but siblings can be anywhere in the document | `h1~p {}`
 |

## Rules 

If two or more selectors are the same, the last one rules. 

The more specific selector rules the more general ones (in that case). Top down in table above from general to specific. 

`!important` 
- Add this after any rule, but inside the curly braces, to make it take precedence over rules that would take normally rule the selector element/class/ID. 

## Inherited properties

Certain properties like `color` or `font-family` are automatically inherited by child elements. `background-color` and `border` are not. To force inheritence, use `inherit` for the value of that particular property in the inheriting element.  
