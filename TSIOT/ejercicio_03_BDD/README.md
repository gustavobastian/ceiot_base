# BDD 

## Creación del entorno de trabajo

```
git init bdd
cd bdd

```
## Configuración del archivo .gitignore

```
node_modules
coverage
.nyc_output
.vscode 

```
## Creación del proyecto npm
```
    npm init  
```
## Instalación de los paquetes de pruebas
```
    npm install --save @cucumber/cucumber chai nyc
```
###    Ajustes en el package.json
```
    "scripts": {

        "test": "cucumber-js --publish-quiet",

        "coverage": "nyc --reporter=html cucumber-js --publish-quiet"

      },

      "nyc": {

        "exclude": "features/**" 

      }
```

# Solución Bastian(en otro repositorio)
```
git clone https://github.com/gustavobastian/TestingIoTTP3
```
