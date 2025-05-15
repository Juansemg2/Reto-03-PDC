Reto 3 PDC
Juan Sebastian Martinez Garcia

En el siguiente reto se mostrara el algoritmo para llegar a los numeros primos hasta un numero n determinado de 3 maneras: Lista de pasos, Pseudocodigo y Diagrama de flujo

Lista de pasos

1.Elegir un numero n
2.Revisa cada numero n iniciando desde 2 (i)
3.Revisa si un numero menor a i puede dividirlo exactamente
-si encuentras un numero que lo divida sin dejar residuo NO ES PRIMO
-si no encuentras un numero que lo divida sin dejar residuo ES PRIMO
4..sumale 1 al numero i 
-si es menor o igual a n vuelve al paso 2 y opera
-si es mayor a n FIN

Pseudocodigo

Inicio
    Leer n
    i ← 2
    Mientras i ≤ n hacer
        esPrimo ← Verdadero
        j ← 2
        Mientras j < i y esPrimo = Verdadero hacer
            Si i mod j = 0 Entonces
                esPrimo ← Falso
            FinSi
            j ← j + 1
        FinMientras
        Si esPrimo = Verdadero Entonces
            Imprimir i
        FinSi
        i ← i + 1
    FinMientras
Fin

Diagrama de flujo
Archivo Diagrama_De_Flujo_RETO3

