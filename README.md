
# The Web Ahead
https://speakerdeck.com/jensimmons/revolutionize-your-page-40min-fall-2016

Most layouts' grids come from 960 grid system

Don't design based on available tools

Float is like a bunch of bars of soap in a bathtub, all of them trying to bubble up to the top

labs.jensimmons.com

CSS Initial letter, like the big beginning letter for a paragraph

feature query: @support conditional in your css directly

mozilla article: using-featre-queries-in-css

height vh: viewport height
- vmin
- vmax

Object Fit: crops image when space is filled
- cover

Shape Outside property

Mondrian came up after lots of victorian embellishments and symmetry. Was about uncentered clean structure.

# Motion Paths Beyond SVG
@dancwilson
https://danielcwilson.com/talks/2016/motionpath

SVG using simple lines, paths, keyframes, and transforms

CSS Motion Paths
- takes stuff from SVG and uses the DOM via css and JS
- motion-path, motion-offset, motion-rotation properties
    + just renamed those properites: offset-path, offset-distance, offset-rotation

# Applicable ES6
@wesbos

#### `let` and `const`
- block scoped
    + only available inside the block they're defined in
- const can't really be changed, but is not immutable!
    + prevents wiping or re-binding of variable

Template strings
- will start using backticks!
    + allow for real string interpolation
    + can do multiline strings automaticallys

#### If statements
- uses ternerary statements

#### Render functions
- can define functions seperately for returning html in string form

#### Default Function Args
- definable in the function definition (like ruby)

#### Arrow Functions
- use arrow instead of `function`
- can lose parens if only one argument
- implicit return
    + one liner with no `{}`

#### Enhanced Object Literals
- create objects from variables, listing the variables once instead of the property name and then the same variable name

#### Tooling
- Transpiling
    + Babel ES6 -> ES5 to let it run
- Polyfill
    + babel again

#### Destructuring
- create/assign vars in single line of code
    + `const {first, twitter, city} = person`
        * `person` being an object
- can rename while destructuring
- default variables in destructure statement
- works with arrays, too
- swap values

#### Sets
- a unique array with solid API for manipulation
- only can contain unique data
- `.has('this')`
- `for(const student of students) {}`

