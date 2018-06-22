# CEP-CLI [![npm](http://img.shields.io/npm/v/node-cep-cli.svg)](https://www.npmjs.com/package/node-cep-cli) ![Downloads](https://img.shields.io/npm/dm/node-cep-cli.svg) [![Build Status](https://secure.travis-ci.org/leonardothibes/node-cep-cli.png)](http://travis-ci.org/leonardothibes/node-cep-cli) [![Package Quality](http://npm.packagequality.com/shield/node-cep-cli.svg)](http://packagequality.com/#?package=node-cep-cli) [![License](https://img.shields.io/npm/l/node-cep-cli.svg)](LICENSE)

Consulta de CEP via linha de comando.

Installation
------------

```bash
npm install node-cep-cli --save
```

Examples
--------

* [Consultando](#consultando)
* [Help](#help)
* [Version](#version)

Consultando
-----------

```js
cep 01315-010
```

Help
----

Exibe a mensagem de help.

```bash
cpf -h
```
```bash
cpf --help
```

```bash
cpf help
```

A saída do comando será:

```bash
Gerador e validador de CPF via linha de comando (node-cep-cli - 1.0.0)
Uso: cpf [CPF para validar]|<command> [options]

  -m               Inclui máscara na geração de CEPs
  -q               Define a quantidade de CEPs a serem gerados
  -v|--version     Exibe o número da versão
  -h|--help        Exibe esta mensagem de help

Para maiores informações: https://www.npmjs.com/package/node-cep-cli

Test and development
--------------------

* Install external dependencies: **``npm install``**
* Run the test suite without coverage: **``npm test``**
* Run the test suite with coverage: **``npm run testdox``**

How to Contribute
-----------------

* Open a pull request or an issue about what you want to implement / change. We're glad for any help!
* Please be aware that we'll only accept fully tested code.

Contributors
------------

 * **Leonardo Thibes <leonardothibes@gmail.com>**

LICENSE
=======

Copyright (c) 2018 Leonardo Thibes

The MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
