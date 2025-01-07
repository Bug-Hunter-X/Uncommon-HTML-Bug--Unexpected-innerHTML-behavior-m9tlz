# Uncommon HTML Bug: Unexpected innerHTML Behavior

This repository demonstrates an uncommon bug related to the use of `innerHTML` in HTML.  The bug arises from an incorrect concatenation of a string and a JavaScript expression within the `innerHTML` assignment. This leads to unexpected behavior where only part of the intended HTML is rendered.

The bug is demonstrated in `bug.html`. The solution showing the correct implementation is in `bugSolution.html`. The correct way of implementing the intended behaviour is shown in the `bugSolution.html` file. 

## Bug Description
The unexpected behavior stems from the way the `innerHTML` property is used. When you directly append an HTML element inside the `innerHTML` string, it must be concatenated properly as string to avoid misinterpretation by the browser.