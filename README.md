# tp_git

2. Lancez ESLint :
npx eslint app.js : quand j'ai lancé cette commande, j'ai rien eu sur ma console 

3. 2. Ajoutez un hook pre-commit pour lancer ESLint :
npx husky add .husky/pre-commit "npx eslint ."
Vers cette étape j'ai eu l'erreur suivante : 
    husky - add command is DEPRECATED


3. 1. npx husky install
commande dépréciée : il faut remplacer cette ligne par :
    npx husky-init

3. 2. npx husky add .husky/pre-commit "npx eslint .": 
 la commande add aussi est dépréciée donc il faut ajouter npx eslint . directement sur le fichier pre-commit

 4. 1. : .eslintrc.json pas trouvé, il faut donc traduire le code donné par le prof en javascript. même traduit, ça ne marche pas . 
