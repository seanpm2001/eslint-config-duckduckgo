# DuckDuckGo JavaScript Style Guide

To lint all our JavaScript we make use of [ESLint](http://eslint.org). This repository contains our default linting configuration.

What follows is a high-level summary of how we've applied ESLint's [rules](http://eslint.org/docs/rules/):

### [Best Practices](http://eslint.org/docs/rules/#best-practices)
* [complexity](https://eslint.org/docs/rules/complexity)
* [consistent-return](https://eslint.org/docs/rules/consistent-return)
* [eqeqeq](https://eslint.org/docs/rules/eqeqeq)
* [curly](https://eslint.org/docs/rules/curly)
* [dot-location](https://eslint.org/docs/rules/dot-location)
* [dot-notation](https://eslint.org/docs/rules/dot-notation)
* [no-case-declarations](https://eslint.org/docs/rules/no-case-declarations)
* [no-else-return](https://eslint.org/docs/rules/no-else-return)
* [no-empty-function](https://eslint.org/docs/rules/no-empty-function)
* [no-empty-pattern](https://eslint.org/docs/rules/no-empty-pattern)
* [no-eq-null](https://eslint.org/docs/rules/no-eq-null)
* [no-eval](https://eslint.org/docs/rules/no-eval)
* [no-extend-native](https://eslint.org/docs/rules/no-extend-native)
* [no-extra-bind](https://eslint.org/docs/rules/no-extra-bind)
* [no-fallthrough](https://eslint.org/docs/rules/no-fallthrough)
* [no-floating-decimal](https://eslint.org/docs/rules/no-floating-decimal)
* [no-global-assign](https://eslint.org/docs/rules/no-global-assign)
* [no-invalid-this](https://eslint.org/docs/rules/no-invalid-this)
* [no-lone-blocks](https://eslint.org/docs/rules/no-lone-blocks)
* [no-loop-func](https://eslint.org/docs/rules/no-loop-func)
* [no-octal](https://eslint.org/docs/rules/no-octal)
* [no-proto](https://eslint.org/docs/rules/no-proto)
* [no-redeclare](https://eslint.org/docs/rules/no-redeclare)
* [no-return-assign](https://eslint.org/docs/rules/no-return-assign)
* [no-script-url](https://eslint.org/docs/rules/no-script-url)
* [no-self-assign](https://eslint.org/docs/rules/no-self-assign)
* [no-self-compare](https://eslint.org/docs/rules/no-self-compare)
* [no-sequences](https://eslint.org/docs/rules/no-sequences)
* [no-useless-return](https://eslint.org/docs/rules/no-useless-return)
* [no-with](https://eslint.org/docs/rules/no-with)
* [radix](https://eslint.org/docs/rules/radix)
* [yoda](https://eslint.org/docs/rules/yoda)
* [no-unmodified-loop-condition](https://eslint.org/docs/rules/no-unmodified-loop-condition)
* [no-multi-spaces](https://eslint.org/docs/rules/no-multi-spaces)
* [no-multi-str](https://eslint.org/docs/rules/no-multi-str)
* [no-implied-eval](https://eslint.org/docs/rules/no-implied-eval)
* [no-useless-escape](https://eslint.org/docs/rules/no-useless-escape)
* [no-iterator](https://eslint.org/docs/rules/no-iterator)

### [Possible Errors](http://eslint.org/docs/rules/#possible-errors)
* [no-cond-assign](https://eslint.org/docs/rules/no-cond-assign)
* [no-constant-condition](https://eslint.org/docs/rules/no-constant-condition)
* [no-control-regex](https://eslint.org/docs/rules/no-control-regex)
* [no-debugger](https://eslint.org/docs/rules/no-debugger)
* [no-dupe-args](https://eslint.org/docs/rules/no-dupe-args)
* [no-dupe-keys](https://eslint.org/docs/rules/no-dupe-keys)
* [no-duplicate-case](https://eslint.org/docs/rules/no-duplicate-case)
* [no-empty-character-class](https://eslint.org/docs/rules/no-empty-character-class)
* [no-empty](https://eslint.org/docs/rules/no-empty)
* [no-ex-assign](https://eslint.org/docs/rules/no-ex-assign)
* [no-extra-boolean-cast](https://eslint.org/docs/rules/no-extra-boolean-cast)
* [no-extra-parens](https://eslint.org/docs/rules/no-extra-parens)
* [no-extra-semi](https://eslint.org/docs/rules/no-extra-semi)
* [no-func-assign](https://eslint.org/docs/rules/no-func-assign)
* [no-inner-declarations](https://eslint.org/docs/rules/no-inner-declarations)
* [no-invalid-regexp](https://eslint.org/docs/rules/no-invalid-regexp)
* [no-irregular-whitespace](https://eslint.org/docs/rules/no-irregular-whitespace)
* [no-obj-calls](https://eslint.org/docs/rules/no-obj-calls)
* [no-prototype-builtins](https://eslint.org/docs/rules/no-prototype-builtins)
* [no-regex-spaces](https://eslint.org/docs/rules/no-regex-spaces)
* [no-sparse-arrays](https://eslint.org/docs/rules/no-sparse-arrays)
* [no-unexpected-multiline](https://eslint.org/docs/rules/no-unexpected-multiline)
* [no-unreachable](https://eslint.org/docs/rules/no-unreachable)
* [no-unsafe-finally](https://eslint.org/docs/rules/no-unsafe-finally)
* [no-unsafe-negation](https://eslint.org/docs/rules/no-unsafe-negation)
* [use-isnan](https://eslint.org/docs/rules/use-isnan)
* [valid-typeof](https://eslint.org/docs/rules/valid-typeof)
* [no-compare-neg-zero](https://eslint.org/docs/rules/no-compare-neg-zero)

### [Stylistic Issues](http://eslint.org/docs/rules/#stylistic-issues)
* [array-bracket-spacing](https://eslint.org/docs/rules/array-bracket-spacing)
* [block-spacing](https://eslint.org/docs/rules/block-spacing)
* [brace-style](https://eslint.org/docs/rules/brace-style)
* [camelcase](https://eslint.org/docs/rules/camelcase)
* [comma-dangle](https://eslint.org/docs/rules/comma-dangle)
* [comma-style](https://eslint.org/docs/rules/comma-style)
* [semi](https://eslint.org/docs/rules/semi)
* [comma-spacing](https://eslint.org/docs/rules/comma-spacing)
* [computed-property-spacing](https://eslint.org/docs/rules/computed-property-spacing)
* [consistent-this](https://eslint.org/docs/rules/consistent-this)
* [eol-last](https://eslint.org/docs/rules/eol-last)
* [func-call-spacing](https://eslint.org/docs/rules/func-call-spacing)
* [new-parens](https://eslint.org/docs/rules/new-parens)
* [newline-per-chained-call](https://eslint.org/docs/rules/newline-per-chained-call)
* [no-array-constructor](https://eslint.org/docs/rules/no-array-constructor)
* [no-bitwise](https://eslint.org/docs/rules/no-bitwise)
* [no-lonely-if](https://eslint.org/docs/rules/no-lonely-if)
* [spaced-comment](https://eslint.org/docs/rules/spaced-comment)
* [space-unary-ops](https://eslint.org/docs/rules/space-unary-ops)
* [linebreak-style](https://eslint.org/docs/rules/linebreak-style)
* [no-mixed-spaces-and-tabs](https://eslint.org/docs/rules/no-mixed-spaces-and-tabs)
* [space-before-function-paren](https://eslint.org/docs/rules/space-before-function-paren)
* [space-in-parens](https://eslint.org/docs/rules/space-in-parens)
* [space-infix-ops](https://eslint.org/docs/rules/space-infix-ops)
* [semi-spacing](https://eslint.org/docs/rules/semi-spacing)
* [no-multiple-empty-lines](https://eslint.org/docs/rules/no-multiple-empty-lines)
* [no-new-object](https://eslint.org/docs/rules/no-new-object)
* [no-tabs](https://eslint.org/docs/rules/no-tabs)
* [no-trailing-spaces](https://eslint.org/docs/rules/no-trailing-spaces)
* [no-spaced-func](https://eslint.org/docs/rules/no-spaced-func)
* [operator-assignment](https://eslint.org/docs/rules/operator-assignment)
* [one-var-declaration-per-line](https://eslint.org/docs/rules/one-var-declaration-per-line)
* [no-whitespace-before-property](https://eslint.org/docs/rules/no-whitespace-before-property)
* [no-unneeded-ternary](https://eslint.org/docs/rules/no-unneeded-ternary)
* [object-curly-spacing](https://eslint.org/docs/rules/object-curly-spacing)
* [object-property-newline](https://eslint.org/docs/rules/object-property-newline)
* [no-continue](https://eslint.org/docs/rules/no-continue)
* [key-spacing](https://eslint.org/docs/rules/key-spacing)
* [space-before-blocks](https://eslint.org/docs/rules/space-before-blocks)
* [keyword-spacing](https://eslint.org/docs/rules/keyword-spacing)
* [max-len](https://eslint.org/docs/rules/max-len)
* [new-cap](https://eslint.org/docs/rules/new-cap)
* [no-restricted-syntax](https://eslint.org/docs/rules/no-restricted-syntax)
* [no-plusplus](https://eslint.org/docs/rules/no-plusplus)
* [no-nested-ternary](https://eslint.org/docs/rules/no-nested-ternary)
* [padded-blocks](https://eslint.org/docs/rules/padded-blocks)
* [no-mixed-operators](https://eslint.org/docs/rules/no-mixed-operators)
* [quote-props](https://eslint.org/docs/rules/quote-props)
* [max-depth](https://eslint.org/docs/rules/max-depth)
* [max-params](https://eslint.org/docs/rules/max-params)
* [padding-line-between-statements](https://eslint.org/docs/rules/padding-line-between-statements)
* [quotes](https://eslint.org/docs/rules/quotes)
* [unicode-bom](https://eslint.org/docs/rules/unicode-bom)

### [Variables](http://eslint.org/docs/rules/#variables)
* [no-delete-var](https://eslint.org/docs/rules/no-delete-var)
* [no-label-var](https://eslint.org/docs/rules/no-label-var)
* [no-shadow-restricted-names](https://eslint.org/docs/rules/no-shadow-restricted-names)
* [no-undef-init](https://eslint.org/docs/rules/no-undef-init)
* [no-undef](https://eslint.org/docs/rules/no-undef)
* [no-undefined](https://eslint.org/docs/rules/no-undefined)
* [no-unused-vars](https://eslint.org/docs/rules/no-unused-vars)
* [no-use-before-define](https://eslint.org/docs/rules/no-use-before-define)
