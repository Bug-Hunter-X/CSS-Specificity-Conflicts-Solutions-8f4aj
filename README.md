# CSS Specificity Conflicts

This repository demonstrates a common yet subtle bug in CSS: unexpected styling issues arising from specificity conflicts.  Two CSS rules targeting the same element with equal specificity can lead to unpredictable results, making debugging challenging.  The solution shows how to resolve such conflicts using techniques like better selector construction and the `!important` flag (used cautiously).

## Bug

The `bug.css` file contains conflicting CSS rules that cause unexpected visual outcomes based on loading order.