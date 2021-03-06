# BibTeX apalike bibliography style: Spanish and Catalan versions

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/donate?business=VFQSX28Z9SW84&currency_code=EUR)

This project is the translation and adaptation of the apalike BibTeX style to Spanish and Catalan. Translations follow the rules of Real Academia Española (RAE) for the Spanish version and Institut d'Estudis Catalans (IEC) for the Catalan version.

The apalike (APA like) BibTeX style belongs to the extended set of standard BibTeX styles. It's called APA like since it does not implement the full APA citation rules. That's because some fields like translator do not belong to the standard fields that are supported in BibTeX (https://www.bibtex.com/s/bibliography-style-base-apalike).

### Usage

Use it in the same way than the original apalike style but:

For the Spanish version, replace the `apalike.bst` file with the `apalike-es.bst` file and add this line to the main file of the document:

```
\bibliographystyle{apalike-es}
```

For the Catalan version, replace the `apalike.bst` file with the `apalike-ca.bst` file and add this line to the main file of the document:

```
\bibliographystyle{apalike-ca}
```

### Author

Apalike original English file translated and adapted by Santi Planet.

## Estilo bibliográfico apalike en español

Esta es la versión en español del estilo bibliográfico apalike de BibTeX.

### Instrucciones de uso

Igual que el estilo original apalike pero reemplazando el archivo `apalike.bst` por el archivo `apalike-es.bst` y añadiendo la siguiente línea en el archivo principal del documento:

```
\bibliographystyle{apalike-es}
```

### Detalles de la traducción a español

* pages --> pp.
* page --> p.
* et~al. --> \textit{et al.} (la RAE marca que et al. equivale a un extanjerismo y debe ir en cursiva)
* volume --> volumen
* number --> número
* chapter --> capítulo
* In --> En
* and --> y (Pero si el apellido comienza por "I" la "y" pasa a ser "e")
* editors --> editores
* PhD Thesis --> Tesis doctoral
* Mater's thesis --> Tesis de máster
* edition --> edición

### Donativo

Si te ha resultado útil, ¡puedes invitarme a un café!

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/donate?business=VFQSX28Z9SW84&currency_code=EUR)

## Estil bibliogràfic apalike en català

Aquesta és la versió en català de l'estil bibliogràfic aplike de BibTeX.

### Instruccions d'ús

Feu-ho servir de la mateixa manera que l'estil original apalike però substituint l'arxiu `apalike.bst` per l'arxiu `apalike-ca.bst` i afegint la següent línia a l'arxiu principal del document: 

```
\bibliographystyle{apalike-ca}
```

### Detalls de la traducció a català

* pages --> p. (http://www.uoc.edu/serveilinguistic/criteris/convencions/abreviacions.html)
* page --> p.
* et~al. --> \textit{et al.}
* volume --> volum
* number --> número
* chapter --> capítol
* In --> En
* and --> i
* editors --> editors (sense variació)
* PhD Thesis --> Tesi doctoral
* Master's thesis --> Tesi de màster
* edition --> edició

### Donatiu

Si aquest projecte t'ha resultat d'utilitat, pots convidar-me a un cafè!

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/donate?business=VFQSX28Z9SW84&currency_code=EUR)
