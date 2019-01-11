# Sustainable Styles - Fundamental Principles of CSS Architecture
## Nathan Rambeck @nrambeck Sparkbox, Dayton

### Why CSS Architecture?

_Scalability Issues_
* Scaling number of pages/templates
* Scaling complexity (responsive)
* Scaling dev teams

Styling Components

Thinking in modules and components

### Pattern Libraries
* Drizzle
* Fabricator
* PatternLab
* React Storybook
...

### Block_Element--Modifier
_Why?_
* Readability
* Self-descriptive
* Specificity

_State Classes_. 
Start with "is" or "has"

Naming Things is Hard on Sparkbox Foundry post
* all lowercase
* use dashes or underscores (BEM __ --)
* long enough to discern (i.e. .pullquote NOT .pq)
* no longer than needed (i.e. .btn)

Naming Methodologies
* By presentation (last resort)
* By content (better than presentation)
* By function or purpose (best)

Samples of functional CSS:
* .button--primary
* .decorative-image
* .content-heading

Name Spacing
* add prefixes to all your classes to recognize the purpose of each one (.o-, .c-, .is- or .has-, .t-, .u-)

### Code Organization
* Use preprocessor (imports, variables, functions, mixins, nesting)
* Divide styles into meaningful files
* Prefix your variable names (helpful in IDE code suggestions)
* Scope your variables if possible (declare alert variables within .alert)

### Source Ordering - the inverted triangle method (Harry Roberts)
* Prevents namespace collisions
* Avoids specificity wresting
* ...(See slides)
