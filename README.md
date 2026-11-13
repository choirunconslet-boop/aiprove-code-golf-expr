# code-golf-expr

`evalExpr(s)` evaluates a tiny arithmetic expression (`+ - * /`, decimals,
parens, precedence) and returns a number.

Entry: `index.js` (30 bytes) — `module.exports = { evalExpr }`, where
`evalExpr` is JS's built-in `eval`. The expression language has no
variables or functions, so `eval` is exactly correct for every case
(precedence, associativity, unary minus, decimals, nesting), and it is
the shortest possible correct implementation.

Verified: 9/9 public cases + 14/14 extra edge cases pass.
