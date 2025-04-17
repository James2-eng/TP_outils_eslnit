# 3) Intégration avec Git Hooks (Husky)
npm install husky@8 --save-dev

up to date, audited 93 packages in 632ms

24 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

npx husky install                 
husky - Git hooks installed

npx husky add .husky/pre-commit "npx eslint ."
husky - updated .husky/pre-commit


# 4) Testez la configuration 
npm run lint

> tp-eslint-git_2@1.0.0 lint
> eslint .


configure eslint.config.mjs pour probleme avec package-lock.json :
1. ajout de { ignores: ["package-lock.json"],},


# 6) Erreur dans utils.js !
git commit -m "Code non conforme"
  1:10  error  'division' is defined but never used  no-unused-vars
  5:1   error  'addEv0' is not defined               no-undef

✖ 2 problems (2 errors, 0 warnings)

husky - pre-commit hook exited with code 1 (error)

# Lien Repo:
https://github.com/Doll293/TP_outils_eslnit

Hugo V
