# Argument Parser

Argument Parser is C based program that lets you take arugments with preceded by hyphen **'-'** or **' -- "**.

### Why
In **The Art of Unix Programming** *Eric Steven Raymond* describes how this practice evolved:
 >In the original Unix tradition, command-line options are single letters preceded by a single hyphen... The original Unix style evolved on slow ASR-33 teletypes that made terseness a virtue; thus the single-letter options. Holding down the shift key required actual effort; thus the preference for lower case, and the use of ¡°-¡± (rather than the perhaps more logical ¡°+¡±) to enable options.

>The GNU style uses option keywords (rather than keyword letters) preceded by two hyphens. It evolved years later when some of the rather elaborate GNU utilities began to run out of single-letter option keys (this constituted a patch for the symptom, not a cure for the underlying disease). It remains popular because GNU options are easier to read than the alphabet soup of older styles. 

### Compile
```sh
$ cd arg_parser
$ make
```
