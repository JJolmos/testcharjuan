# FrontEnd

## Ejercicio 1 

Se modificaron las propiedades de los radios y el hover para obtener la vista requerida.
(se agregaron los comentarios en codigo).

## Ejercicio 2

 NO COMPLETADO

## Ejercicio 3

Se creo un metodo para calcular de entre los arreglos de datos los limites de los ejes "Y" y se agrego a la propiedad(afterBuildTicks) para que lo pinte el canvas.
(se agregaron los comentarios en codigo).

# Backend

## Nivel 1

Lambda Function.

Se creó una funcion lambda en Node.js 14.x que ejecuta el metodo hasMutation se incluye el codigo descargado de AWS

Nota: comprendo que no es exactamente lo que se pidio y entiendo si no es tomado en cuenta como valido.

## Nivel 2
API-Gateway

se creo un stage y un metodo POST que ejecutan a su vez la lambda function descrita anteriormente y regresa el resultado del metodo:

url: https://yqf3w7euod.execute-api.us-east-1.amazonaws.com/develop/mutation

Ejemplo de request: {"dna":["ATGCGA","CAGTGC","TTATTT","AGACGG","GCGTCA","TCACTG"]}

Nota: Aunque el lambda puede recibir bastantes peticiones por segundo, tomar en cuenta que es una cuenta con capa gratuita y demasiadas peticiones podrian generarme un costo $ extra por tiempo de ejecucion y llamadas.
## Nivel 3

Mongo DB

se utilizo como base de datos Mongo DB y se alamacena la informacion requerida, al realizar la consulta GET sobre el mismo API- Gateway que ya se esta utilizando regresa la informacion requerida.

url: https://yqf3w7euod.execute-api.us-east-1.amazonaws.com/develop/stats

para tener acceso a la consola de Mongo favor de ccrar una cuenta o proporcionar Usuario para agregarlo
