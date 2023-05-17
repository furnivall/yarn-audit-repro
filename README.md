# yarn-audit-repro
Reproduction of a bug in yarn npm audit

# Instructions
- Run `yarn install`
- Run `yarn npm audit --environment production -R`
- Will give a 400 bad request.
