The name of ESLint for VS Code is simply "ESLint" on extensions markeplace.

In VS Code, go to preferences and add the following to specify the ESLint file to be used:

{

    "eslint.options": {
    	"configFile": "path-to-eslintrc.json"
    }
}

