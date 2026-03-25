# Sass Import Fix TODO

1. Kill current dev server (Ctrl+C in terminal).
2. Edit src/index.scss: Prepend `@use './styles/variablesAndMixins.scss' as *;` at line 1.
3. Find and edit other affected .scss files.
4. Run `npm run dev`.
5. Verify.

