# CodeApp `<codeApp\>`

Describe y escribe tus fragmentos de código. CodeApp te permite salvar en localStorage todos tus fragmentos de código y además resalta la sintaxis para que te sea mucho más sencillo detaller o recordar la funcionalidad de tu Snippet.

CodeApp está basada en el estandar WebComponent y usa polymer en su versión 1

## Instalar versión de Polymer (Recomendado)

`npm install -g polymer-cli@1.1.0`

Es importante que tenga instalado Polymer CLI y Bower

## Ver aplicación en local

```
$ polymer serve
```

## Generar carpeta de producción

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
