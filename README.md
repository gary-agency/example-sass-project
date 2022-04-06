Ceci est un squelette de projet pour s'entrainer au SASS avec Bootstrap@5.X, ou pour créer des projets HTML. 
Pour une utilisation avec un framework javascript preférer une installation via webpack par exemple.


# Installation
#### Pré-requis
node JS (current) : https://nodejs.org/en/download/current/
puis lancer un update de NPM
```bash
npm install -g npm@latest
```
*note: pour windows voir ce lien : https://docs.npmjs.com/try-the-latest-stable-version-of-npm#upgrading-on-windows*
#### Telecharger les packages
Pour initier le projet lancer, cela installera tous les pkg necessaires :
```bash
npm i
```

# Usage
```bash
# pour compiler+prefixer+minifier une seule fois
npm run sass-once

# pour compiler+prefixer+minifier à chaque changement de fichier
npm run sass-watch
```