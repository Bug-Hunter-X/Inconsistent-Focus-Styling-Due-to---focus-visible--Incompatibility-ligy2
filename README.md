# Inconsistent Focus Styling Due to `:focus-visible` Incompatibility

This repository demonstrates a common issue with the `:focus-visible` pseudo-class in CSS:  inconsistent focus styling across browsers due to lack of support in older versions.  The `bug.css` file shows the problem, while `bugSolution.css` offers a solution.

**Problem:** The `:focus-visible` pseudo-class provides a more user-friendly experience by only showing focus styles when the user is actively using a keyboard or assistive technology to navigate.  However, older browsers don't support it, leading to unexpected styling for all users.