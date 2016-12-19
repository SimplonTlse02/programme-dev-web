# babel-cli
[Doc Babel CLI](http://babeljs.io/docs/usage/cli/)

```
npm install --save-dev babel-cli babel-preset-env
./node_modules/.bin/babel --version
# 6.18.0 (babel-core 6.21.0)

# Créer le fichier .babelrc

# Transpilation dans la sortie standard du terminal
./node_modules/.bin/babel begin.es6.js

# Transpilation dans un fichier de destination
./node_modules/.bin/babel begin.es6.js -o begin.js

# Transpilation et watch
./node_modules/.bin/babel begin.es6.js -w -o begin.js
```

## Mémo babel
```
babel begin.es6.js --out-dir public
babel begin.es6.js -d public

babel begin.es6.js --out-file begin.js
babel begin.es6.js -o begin.js

babel begin.es6.js --watch -o begin.js
babel begin.es6.js -w -o begin.js
```