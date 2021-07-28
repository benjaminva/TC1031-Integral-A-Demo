# Calculadora de dosis por gramaje para medicamentos sin prescipción médica
Este proyecto se basa en la siguiente página web [calculadora](https://www.fisterra.com/ayuda-en-consulta/calculos/calculos-dosis-medicamento-mg-dosis/) 
donde para usarse se sigue el siguiente comporamiento:

>Ejemplo 1: Augmentine "125" suspensión, (125/31,25 mg/5 ml)
> 
>Paso 1: Introducir el peso del paciente. Por ejemplo: 8 kg.
>Paso 2: Introducir la posología deseada. Por ejemplo: 40 mg/kg/día.
>Paso 3: Introducir la presentación. Suspensión.
> 
>Con estos datos se obtiene la dosis al día: 320 mg/día.
>
>Paso 4: Elegir el número de dosis al día: 3 dosis = cada 8 horas.
>Paso 5: Introducir los mg que contiene la unidad (en este caso el ml).
>            Si la concentración es de 125 mg/5 ml. Los mg/ml = 125/5 = 25 mg/ml.
>            Para resolver este cálculo tenemos a la derecha otra calculadora.
>
>Obtenemos: 106,67 mg/dosis = 4,28 ml cada 8 horas.

Adicionalmente incluyo las funciones para registrar nuevo medicamentos y ver los medicamentos registrados 
por orden alfabético o por cantidad  de gramaje 

## SICT0302B: Toma decisiones 

### Selecciona y usa una estructura lineal adecuada al problema

Uso una lista doblemente encadenada para regristrar las medicinas porque quiero acceder rápidamente a la registrada más recientemente (head), 
pero también necesito consultar cuál fue la primera que se agrego (tail), cada medicina es un objeto que contiene (...   ) 
los elementos se pueden insertar y eliminar usando la lista como se muestra en el código en las funciones 
agrega medicina, elimina medicina, y obten gramaje, que se encuentran en el archivo medicinas.h en las lienas 37, 65 y 74 respectivamente. 


### Selecciona un algoritmo de ordenamiento adecuado al problema

### Usa un árbol adecuado para resolver un problema

## SICT0301B: Evalúa los componentes

### Presenta Casos de Prueba correctos y completos para todas las funciones y procedimientos del programa.,

### Hace un análisis de complejidad correcto y completo para todo el programa y sus compenetes.,


## SICT0303B: Implementa acciones científicas 

### Implementa mecanismos para consultar información de las estructuras correctos y útiles dentro de un programa.,


### Implementa mecanismos de lectura de archivos correctos y útiles dentro de un programa. Usar de manera


### Implementa mecanismos de escritura de archivos correctos y útiles dentro de un programa. Usar de manera

