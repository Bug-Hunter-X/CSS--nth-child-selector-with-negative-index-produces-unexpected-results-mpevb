# CSS :nth-child Selector with Negative Index

This repository demonstrates a subtle bug related to using the `:nth-child` pseudo-class selector in CSS with a formula that produces a negative index.  The unexpected behavior can vary across browsers.

## Bug Description

The issue arises when attempting to style elements using a formula like `-n + 3` within `:nth-child`. While the intention is typically to select the first few elements, the result is often inconsistent or incorrect.

## How to reproduce

1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe the styling of the list items.  The unexpected behavior highlights the inconsistency in how different browsers handle negative indices within the `:nth-child` selector.

## Solution

The `bugSolution.css` file provides a more robust approach that avoids the use of negative indices in the `:nth-child` selector, ensuring consistent results across browsers.  This solution uses a positive index approach. 

## Contributing

Contributions are welcome!  If you find any other edge cases or improvements for this solution, please feel free to open a pull request.