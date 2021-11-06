# Jest very slow with barrel files

Run tests using `yarn test`.

Test in `src/barrel-files.test.tsx` is v slow due to `import * as Icons from "@mui/icons-material";`.
Test in `src/no-barrel-files.test.tsx` is fast due to individual icon being imported instead.

Is there a way to avoid this slowness while still using barrel files?
