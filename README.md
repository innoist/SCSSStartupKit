# SCSSStartupKit
Startup kit for sass and scss with best practices
Preprocessor:
Step before CSS
Language on top of CSS
Powerful Capabilities:
1. variables
2. Nesting
3. Mixings:
4. Auto Vendor Prefixing

SASS: Syntatctivall Awesome Style-sheets, shorter syntax
SCSS: SASSY CSS, Newer Syntax, 

https://code.visualstudio.com/docs/languages/css#_transpiling-sass-and-less-into-css
https://rubyinstaller.org/    make sure to check 'Add Rubyexecutables to your PATH'
gem install sass


PARTIALS: always include with '_'

$shadows... passing multiple args as params

@import url()//used for e.g importing fonts, but variables cannot be used to import css/scss file

lighten the color Darken function

CTRL+SHIFT+O go to symbol v.important like go to a tag, go to button

mixins
functions

inheritence extend does not work inside media query
there are extend only selectors, which will not generate code. it generates code in the child classes
OPTIONAL FLAG TO LET IT GO AHEAD

extends generate less code, but we can do the same with mixins. more rules are generated

in mixins less rules are generating but more duplicate code

files size will increase in mixins

but extends have limitation to media query, and multiple inheritance

but but but.... wow... mixins after gzip is small size and performance is excellent

WE COULD CHOOSE MIXINS ONLY AND NOT EXTENDS