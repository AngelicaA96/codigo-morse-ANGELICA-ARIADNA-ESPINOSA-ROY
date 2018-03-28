# codigo-morse-ANGELICA-ARIADNA-ESPINOSA-ROY
EJEMPLO: digitas: 1 este te manda al proceso que se encuentra en el case 1. 
Conversión de código Español a Morse" 
En la línea 12 de código muestra las de conversión que permite este programa que son "Español a Morse" y "Morse a Español".
En la línea 14 digita el tipo de conversión que eligiste ya sea "Español a Morse" o viceversa.
Dependiendo de la opción elegida el switch te llevara directo al proceso correspondiente para hacer la conversión.
EJEMPLO: digitas: 1 este te manda al proceso que está en el case 1. 
"Conversión de Español a Morse"
En la línea 18 se Ingrese el texto que se desea convertir a Morse se guarda en la variable cadena de tipo String. 
En la línea 20 se declara una variable tipo char c.
En la línea 21 se declara otra variable tipo String que permite concatenar cada carácter de codigo Morse en una sola cadena.
En la línea 22 se declaró un ciclo for para recorrer cada elemento de la cadena "Ingresada por el usuario" por medio de lenght() .
En la línea 23 se le asigna a la variable c  el carácter situado en la posición 'índex' de la cadena esta va cambiando al estar haber una iteración nueva.
(recorre la cadena carácter por carácter).
De la línea 24 a 134 cada carácter se compara con otro esto se hace con el fin de estar traduciendo letra por letra a codigo Morse.
Ejemplo: ingresas "aa" la cadena al entrar al ciclo tendrá 2 iteraciones y entraran a la condición de la linea de codigo 24.
Entra al ciclo y como el carácter es 'a' entonces en cad se concatenara 2 veces ".-.-"; esto se hace para que en una solo renglón salga.
la traducción correspondiente del código Morse. Cada vez que se cumpla una condición se acumulara en cad un código específico.
Al terminar de recorrer la cadena se sale del ciclo y se imprime en consola (cadena)=(cad) en otras palabras el valor ingresado por el teclado y su equivalente en código Morse.  

EJEMPLO: digitas: 2 este te manda al proceso que se encuentra en el case 2. 
"Conversión de Morse a Español"
En la línea 141 Ingrese el texto que se desea convertir de Morse a Español se guarda en la variable cadena de tipo String  cadena1.
En la línea 142 se declara una variable tipo String llamada letra que almacena de la letra "a-z" y del "0-9".
En la línea 143 se declara una variable tipo String llamada espacio que almacena un espacio en blanco entre palabras.
En la línea 144 se declara un vector tipo.
En la línea 145 se declara una variable tipo String llamada morse que almacena un espacio en blanco para al momento de imprimir la cadena te separe "palabras o frases".
De la línea 146 a 182 se especifica en cada posición del vector el valor asignado en código morse.
En la línea 183 se declara un vector tipo String oración servirá para guardar los fragmentos del código morse  en cada posición del vector.
En la línea 184 se declara una variable tipo int max que se usara para sacar la longitud de la oracion[] .
Se declara un ciclo for que se usara para recorrer el vector el tope es su tamaño.
Se declara un ciclo for que se usara para recorrer el tamaño máximo de caracteres puede tener la oración.
En la línea 187 se declara un if donde se comparara si es igual algún elemento que se ingresó del teclado con c/a posición del vector declarado.
En la línea 188 se concatenara a la variable morse cada letra que cumpla la condicion anterior.
charAt para separar lo que almacena la cadena letra por caracteres la tetra que cumpla la condición anterior se acumulara en la variable tipo morse.
En la línea 189 se declaró break para dejar de comparar cuando en la cadena ya no haya más elementos y se salga de los ciclos.
En la línea 190 se cierra el if de la línea 187.
En la línea 192 se cierra el for de la línea 185.
En la línea 194 se imprime en consola la converSión de MORSE-ESPAÑOL.


