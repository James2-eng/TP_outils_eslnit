# configure eslint.config.mjs pour probleme avec package-lock.json :
## 1. ajout de { ignores: ["package-lock.json"],},

# Erreur dans utils.js !
  1:10  error  'division' is defined but never used  no-unused-vars
  5:1   error  'addEv0' is not defined               no-undef

✖ 2 problems (2 errors, 0 warnings)

husky - pre-commit hook exited with code 1 (error)