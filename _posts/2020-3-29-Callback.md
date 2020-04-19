---
layout: post
title: Callbacks en JavaScript
---

<b>¿Qué es un Callback?</b>

<b>De forma sencilla:</b> Un Callback (llamada de vuelta) es una función que se ejecutará después de que otra función haya terminado de ejecutarse, de aquí el nombre de Callback.

<b>De forma más compleja:</b> En JavaScript, las funciones son objetos. Por ello, las función admiten funciones como argumentos y pueden ser devueltas por otras funciones. Las funciones que hacen esto se denominan funciones de orden alto (high-order). Cualquier función que se pase como argumento se denomina función Callback.

Pero esto sólo es mucha palabrería… Veamos algunos ejemplos para detallar estas definiciones.

<b>¿Por qué necesitamos Callbacks?</b>

Por una razón muy importante, JavaScript es un lenguaje orientado a eventos. Esto significa que en lugar de esperar a una respuesta para avanzar, JavaScript seguirá ejecutándose mientras escucha otros eventos. 