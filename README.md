# CSS-CHEAT-SHEET-9000

CSS Cheatsheet
===============

Selectors
---------
element {
  property: value;
}
#id {
  property: value;
}
.class {
  property: value;
}

Properties
----------
color: red;
background-color: blue;
font-size: 16px;
padding: 10px;
margin: 10px;
border: 1px solid black;
text-align: center;
font-family: Arial, sans-serif;
font-weight: bold;
text-decoration: underline;
display: block;
width: 100%;
height: 100%;
position: absolute;
top: 0;
left: 0;
z-index: 1;
opacity: 0.5;

Pseudo-Classes
--------------
:hover {
  property: value;
}
:active {
  property: value;
}
:focus {
  property: value;
}
:visited {
  property: value;
}
:first-child {
  property: value;
}
:last-child {
  property: value;
}

Box Model
---------
content-box: width/height only affects content area
border-box: width/height includes content, padding, and border

Units
-----
px: pixels
em: relative to font-size of parent
rem: relative to font-size of root element
vh: viewport height
vw: viewport width
%: percentage of parent

Flexbox
-------
display: flex;
flex-direction: row/column;
justify-content: center;
align-items: center;
flex-wrap: wrap;
flex: 1;
order: 1;

Grid
----
display: grid;
grid-template-rows: 1fr 1fr;
grid-template-columns: 1fr 1fr;
grid-gap: 10px;
grid-row: 1/3;
grid-column: 1/3;

Media Queries
-------------
@media (max-width: 768px) {
  property: value;
}
@media (min-width: 768px) and (max-width: 1024px) {
  property: value;
}

Animations
----------
@keyframes my-animation {
  from { property: value; }
  to { property: value; }
}
animation-name: my-animation;
animation-duration: 1s;
animation-timing-function: ease-in-out;
animation-delay: 0.5s;
animation-iteration-count: infinite;
animation-direction: alternate;
animation-fill-mode: forwards;

Transitions
-----------
transition: property duration timing-function delay;
transition-property: property;
transition-duration: duration;
transition-timing-function: timing-function;
transition-delay: delay;

Text Styling
------------
Font Family
font-family: Arial, sans-serif;
Font Size
font-size: 16px;
Font Weight
font-weight: bold;
Font Style
font-style: italic;
