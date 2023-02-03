Man må hente ned de ulike npm pakkene for å kjøre prosjektet,
kommandoene under på kjøres i terminalen, pass på at du ikke gjør det inni en av mappene, men globalt i prosjektet 

1. npm init
2. npm install sass concat autoprefixer postcss-cli css-minify npm-run-all --save-dev
3. npm i bootstrap@5.3.0-alpha1
4. npm i bootstrap-icons

Kommandoen under kompilerer main.scss til main.css hver gang den kjøres

5. npm run css:build 

Kommandoen under kompilerer main.scss til main.css hver gang man LAGRER main.scss (må alltid kjøres en gang først når man åpner prosjektet)

6. npm run css:watch
