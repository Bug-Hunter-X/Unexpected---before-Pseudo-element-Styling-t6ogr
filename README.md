# Unexpected ::before Pseudo-element Styling

This repository demonstrates a common CSS issue where a style rule targeting the `::before` pseudo-element unintentionally affects all elements on the page, creating unexpected visual results. 

The `bug.css` file showcases the problematic CSS code, while `bugSolution.css` provides a corrected version. This issue is particularly problematic when combined with absolute positioning and unintentionally affects all elements with a `::before` pseudo-element.