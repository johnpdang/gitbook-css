# Flexbox

|                                                                                                                                                                                                                     |            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| [CSS Flex: What Every Developer Should Know](https://www.syncfusion.com/blogs/post/css-flex-every-developer-should-know.aspx?utm\_campaign=Frontend%2BWeekly\&utm\_medium=email\&utm\_source=Frontend\_Weekly\_355) | 4/25/23    |
| [CSS Flexbox vs Grid layout](https://blog.bitsrc.io/css-flexbox-vs-grid-layout-5ae41e28d1d2)                                                                                                                        | 9/19       |
| [Understanding flex-grow, flex-shrink, and flex-basis](https://css-tricks.com/understanding-flex-grow-flex-shrink-and-flex-basis/)                                                                                  | 11/16      |
| [Flexbox — The Animated Tutorial](https://medium.com/@js\_tut/flexbox-the-animated-tutorial-8075cbe4c1b2)                                                                                                           | 2/11       |
| [CSS Flexbox Fundamentals Visual Guide](https://medium.com/swlh/css-flexbox-fundamentals-visual-guide-1c467f480dac)                                                                                                 | 1/5/2020   |
| [How I create a Contact Us form using Flexbox](https://medium.com/swlh/how-i-create-a-contact-us-form-using-flexbox-b9f6660d4c96)                                                                                   | 12/24/2019 |

```css
.item {
    display:flex;
    flex-direction: row; //left-right direction
    flex-wrap: wrap; //drops to second column
    justify-content: flex-start; //left aligned
    align-items: flex-start; //top aligned
    align-content: flex-start; //lines packed to start of container
    .child {
        order:1; //order of element, default 0
        flex-grow: 1; // default 0
        flex-shrink: 1; //default 1
        flex-basis: auto; //remaining space distributed based on flex-grow
        flex: 0 1 auto; //grow shrink basis
        align-self:flex-start; //auto is default
    }
}
```
