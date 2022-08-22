# Terminal et IDE dans Mkdocs

## Introduction

`Pyodide-Mkdocs` est une solution technique permettant de créer un cours interactif à partir d'un site généré par Mkdocs. 

Il permet d'intégrer, dans le navigateur, côté client :

- une console Python ;
- un éditeur de code ;
- un juge en ligne associé à des corrigés.

Garantie :

- [x] sans cookie
- [x] sans inscription
- [x] créé par un enseignant pour les enseignants

??? info "Solution"
    La technologie permettant ce tour de force s'appelle [Pyodide](https://pyodide.org/en/stable/ "Pyodide, Python with the scientific stack, compiled to WebAssembly").
    
    Pyodide utilise WebAssembly pour faire le lien entre Python et Javascript et proposer un environnement permettant de manipuler le DOM avec Python, ou de manipuler Python avec Javascript.

## Aperçu

{{terminal()}}
