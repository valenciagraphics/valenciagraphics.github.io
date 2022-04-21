# don't repeat yourself
to understand this concept, we are going to set up button variants. we will start with our primary button and create two secondary components. throughout the semester i will continuously refer to creating a BASE file. so we will start with base buttons and work our way up to designed buttons.
## reset links
## add your button classes
## output
## consolidation
1. mark what properties are the same
2. mark what properties are different
3. use the comma *combinator* to create one declaration
## what the scss looks like
## using scss extend/inheritance
- declaring variables to make styling and restyling easy
- `@extend` to share the styles of the parent `.button` classs
- `&` to use the prefix of the parent `.button` class
- nest declarations together to create one component