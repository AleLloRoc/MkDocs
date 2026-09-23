# Práctica 1: Git - Ramas y uniones

## 1. Objetivos de la práctica

El objetivo principal de esta práctica es aprender a trabajar con **ramas en Git** y comprender cómo se utilizan para desarrollar diferentes partes de un proyecto de forma independiente. También se aprende a realizar **uniones (*merge*)** entre ramas y a solucionar los conflictos que pueden aparecer durante este proceso.

Durante la práctica se trabaja con la creación, modificación y eliminación de ramas, así como con la sincronización de estas con un repositorio remoto de GitHub.

## 2. Concepto de rama

Una **rama (*branch*)** representa una línea independiente de desarrollo dentro de un repositorio. Permite realizar cambios sin modificar directamente la rama principal del proyecto.

La rama principal se denomina normalmente `main` y contiene el estado principal del proyecto. Para consultar las ramas existentes se utiliza:

```bash
git branch
