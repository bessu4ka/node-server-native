scripts
--

"start": "node ./dist/main.js"
    
"dev": "nodemon"
    
"dev:inspect": "nodemon -e ts,json --exec node --inspect=localhost:9222 -r ts-node/register src/main.ts"
		
 "lint": "eslint ./src/**"
		
"lint:fix": "eslint ./src/** --fix"
		
"build": "tsc"
		
"test": "echo \"Error: no test specified\" && exit 1"
