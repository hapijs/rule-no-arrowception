<a href="http://hapijs.com"><img src="https://raw.githubusercontent.com/hapijs/assets/master/images/family.png" width="180px" align="right" /></a>

# rule-no-arrowception

[![Build Status](https://travis-ci.org/hapijs/rule-no-arrowception.svg?branch=master)](https://travis-ci.org/hapijs/rule-no-arrowception)

ESLint rule preventing arrow functions that implicitly return arrow functions. Functions can still be returned by arrow functions whose bodies use curly braces and an explicit return. This rule prevents the pattern `() => () => () => ...;`. This rule does not accept any configuration options.
