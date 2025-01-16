# Uncommon CSS Bugs

This repository demonstrates some uncommon but potentially tricky CSS bugs, focusing on specificity issues, typos, and problems with floating elements.  The lack of detailed error reporting in CSS makes debugging these types of issues challenging.  The `bug.css` file contains the problematic code, while `bugSolution.css` provides the corrected version and explanations.

## Bug Scenarios

1. **Specificity Conflicts:**  Multiple CSS selectors might target the same element, but the browser chooses the one with higher specificity, potentially overriding your intended style.
2. **Typos:** Simple typos in class names or selectors can create subtle and hard-to-find errors.  This can result in styles not applying at all.
3. **Floating Element Issues:** Floating elements without proper clearing methods may lead to unexpected layout overlaps or misalignments.