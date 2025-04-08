# False positive for eslint-plugin-import(namespace) with TypeScript enum

```bash
$ npm test
> oxlint-repro@1.0.0 test
> oxlint


  × eslint-plugin-import(namespace): "Foo" not found in imported namespace "./lib".
   ╭─[test.ts:3:24]
 2 │ 
 3 │ export const bar = lib.Foo.BAR;
   ·                        ───
 4 │ 
   ╰────

Found 0 warnings and 1 error.
Finished in 2ms on 2 files using 10 threads.
```
