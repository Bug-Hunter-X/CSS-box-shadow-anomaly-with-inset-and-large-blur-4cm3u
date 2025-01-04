# CSS box-shadow anomaly with inset and large blur radius

This repository demonstrates an unexpected behavior in the CSS `box-shadow` property when using `inset` with a significant blur radius.  The shadow unexpectedly extends far beyond the element's boundaries. This issue can be particularly challenging to debug due to the counter-intuitive results.

The `bug.css` file contains the problematic CSS code.  The `bugSolution.css` file offers a potential workaround, although it may not be a perfect solution in all cases.

## Potential Causes and Workarounds
The precise cause of this behavior is not yet fully understood and might relate to browser rendering quirks or an edge case in the CSS specification's handling of `inset` box-shadows with large blur radii.  The workaround provided focuses on potentially limiting the spread of the shadow, even though it may impact visual style slightly.