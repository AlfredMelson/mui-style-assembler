
# Automatic Class Sorting for MUI

Automates the organization of CSS within components that utilise MUI >=v5 styling. Automatically sorting according to the cascade and specificity, and how inheritance works in CSS.

## How classes are sorted
At it’s core, all this plugin does is organize your components classes. The actual ordering puts impactful classes that affect the layout at the beginning and decorative classes at the end, while also trying to keep related utilities together.

Utilities themselves are sorted in the same order by placing overriding classes later. Modifiers like hover: and focus: are grouped together and sorted after common utilities.

Responsive modifiers like md and lg are grouped together at the end in the same order they’re configured in MUI default theme — which is smallest to largest by default.# mui-style-assembler
