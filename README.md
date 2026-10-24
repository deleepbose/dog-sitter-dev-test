# Dog Sitters Test HTML Website

Responsive banner and services sections built in HTML and plain CSS for the Black Sheep Creative dev test, based on designs provided in Figma.

Live Website: https://deleepbose.github.io/dog-sitter-dev-test/

## How to run it

Open `index.html` in a browser.

## Approaches used
- Used BEM class names like .block__element--modifier. If .card is block, .card__title is element and .card__button--disabled is modifier
- Used CSS custom variables for colours and type sizes to avoid redundancy
- Desktop styles as default, with max-width: 1199px for tablet devices and max-width: 599px for mobile devices
- Banner photo, gradient and wave layered as CSS backgrounds

## Notes
- I have fixed three typos in the design: "futher" (in first section), "piece of mind" (under "Our Services" title), "someones else" (in 2nd section)
- The brand orange (#DE6C17) with white doesn’t meet the WCAG accessibility contrast standard (3.35:1 currently instead of 4.5:1 for 18px text). I have kept it as designed. 
