Este ejercicio tenía dos particularidades: 

* una de ellas es que usamos nuevas condiciones como `hay pasto` o `hay rocas`.  Te las dejamos en la categoría de “condiciones”, dentro de “Funciones primitivas”. 
* la más importante es que utilizamos un nuevo conector lógico: `o bien`. Al igual que `y también`, este conecta dos condiciones, pero de otra forma. 

Ahora **no** nos interesa que hayan rocas `y también` minerales en el suelo para poner una bandera; nos alcanza con que haya alguno de los dos. Por eso, nuestra condición para poner una bandera roja es que hayan rocas `o bien` que hayan minerales. 

Por otra parte, si confirmamos que hay rocas o minerales, pondremos la bandera :triangular_flag_on_post: solo `si no hay` una `bandera` puesta previamente `y si hay pasto` :seedling:. Por eso, es importante usar en este caso el `y también`.
