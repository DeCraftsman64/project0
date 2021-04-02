# project0
Front-end for Google Search


02/04/21

Define structure
Start with HTML index

Get handy on Git and GitHub

About styling
Chrome code inspector, how to get the best out of it
No bootstrap...
Scss
Where to use variables?
$color: red;

ul {
    font-size: 14px;
        color: $color;
 }
ol {
    font-size: 18px;
        color: $color;
 }
        
How to use nesting
div {
    font-size: 18px;
    p {
            color: blue;
                }
    ul {
            color: green;
                }
    }
                
When to use inheritance
% message {
font-family: sans-serif;
font-size: 18px;
font-weight: bold;

. success {
@extend %message;
 background-color: green;
