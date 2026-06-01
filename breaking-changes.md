# Breaking Changes in `physics` Package

## Change in Source Package (No Change in Use)

- `\abs`, `\norm`
- `\tr`, `\rank`
- `\arccot`, `\arcsec`, `\arccsc`, `\sech`, `\csch`
- `\grad`, `\div`, `\curl`, `\laplacian`

## Change in Implementation (No Change in USe)

- `\Conditional`, `\set`
- `\identityM`, `\zeroM`
- `\unitv`

## Rename in Macro

- `\dd` -> `\diracdelta`
- `\unitvb` -> `\unitv*`

## Removal of Macros

- `\vargrad`, `\vardiv`, `\varcurl`, `\varlaplacian`
- `\Partial`, `\PartialN`

### Replaced with `physics` Package

- `\para` -> `\pqty`; `\brac` -> `\bqty`; `\brce` -> `\Bqty`
- `\vm` -> `\vb`; `\vmb` -> `\vb*`
- `\re` -> `\Re`; `\im` -> `\Im`
- `\Diff`, `\DiffN` -> `\dd`
- `\DiffFrac`, `\DiffOp`, `\DiffNFrac`, `\DiffNOp` -> `\dv`
- `\PartialFrac`, `\PartialOp`, `\PartialNFrac`, `\PartialNOp` -> `\pdv`

## Other Packages

- `\qty` -> `\SI`: package `siunitx`

## Change in Typesetting Habits

- Use `\qq` or `\qqTEXT` wherever possible
- Use `\vdot`, `\cross` for vector dot/cross products
- When using `\dd` (differentiation), use built-in functionalities for powers and spacing
- Use `\dv*` and `\pdv*` for flat derivatives
- No use of `\partial` or `\dd` (unless in integral or manipulating infinitesimals)
- Use `\flatfrac` for flat quotients
- Use `\PV` for Cauchy Principle Value
- Matrices should be produced using `physics`
