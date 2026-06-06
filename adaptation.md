# Adapting to `physics`

## Breaking Changes

1. Simple Replacement (No Issues Expected)
   - `\dd` -> `\diracdelta`
   - `\unitvb` -> `\unitv*`
   - `\para` -> `\pqty`; `\brac` -> `\bqty`; `\brce` -> `\Bqty`
   - `\vm` -> `\vb`; `\vmb` -> `\vb*`
   - `\re` -> `\Re`; `\im` -> `\Im`
   - `\qty` -> `\SI`
2. Differentiation Symbols (No Issues Expected)
   - `\Diff` -> `\dd`
   - `\DiffFrac`, `\DiffOp` -> `\dv`
   - `\PartialFrac`, `\PartialOp` -> `\pdv`
3. Differentiation Symbols (Manual Breaking Changes)
   - `\DiffN` -> `\dd`
   - `\DiffNFrac`, `\DiffNOp` -> `\dv`
   - `\PartialNFrac`, `\PartialNOp` -> `\pdv`
4. Differentiation Spacing `\dd`: use built-in functionalities for powers and spacing

## Non-Breaking Changes

1. No use of `\partial` or `\dd` (unless in integral or manipulating infinitesimals); use `\dv*` and `\pdv*` for flat derivatives
2. Use `\qq` or `\qTEXT` wherever possible
3. Use `\vdot`, `\cross` for vector dot/cross products
4. Use `\flatfrac` for flat quotients
5. Use `\PV` for Cauchy Principle Value
6. Matrices should be produced using `physics`
