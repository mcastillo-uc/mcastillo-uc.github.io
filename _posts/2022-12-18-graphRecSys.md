---
layout: post
title: Graph bases Resys - Redes Neuronales de Grafos para Sistemas de recomendación
---


Utilizando, la potencialidad de las redes neuronales, podemos interpretar la complejidad de redes de grafos,
manteniendo ciertas propiedades interesantes, que nos permiten mejorar y contextualizar las recomendaciones  generadas.


A diferencia de las redes neuronales, estas funcionan directamente sobre grafos, permitiendoles aprender a partir de información
más compleja, tomando en cuenta los items que tienen cercanos.

La ventaja de usar grafos para representar es que esto, es que son una forma de organizar la información como algún dato más sus relaciones. Este punto nos permite ejecutar redes neuronales complejas que podrían utilizar la información considerando en como esta influye en los otros nodos.

Su propuesta es reciente (2008) y pretende utilizar el poder de representación de las redes neuronales a su favor. para esto, mediante tecnicas como encoder se procesa la información sin perder las propiedades de los grafos, así como la representación de cercanía y lejanía con otros nodos según como estén vinculadas.

Existen distintas formas de entrenarlas, donde el aprendizaje Inductivo resalta dado que despues de su entrenamiento, puede ser utilizada para predecir la inclusión de nodos nuevos. Esta es la cualidad y principal diferencai del metodo Transductivo, el cual requiere re-entrenamiento en caso de agregar un nodo nuevo.

Dependiendo de lo que se desee hacer se pueden optar por varias opciones.

Mediante la introducción de Neuronas tipo GRU, podemos aprender represntacioens de nodo absorivendo iterativamente la influencia de otros nodos.

Tambien podríamos usar la Atención, para fijar un concepto de relevancia que tienen algunos usuarios/items sobre otros.