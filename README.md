	# Rstudio
debemos crear y manipular objetos

comandos:
-ctrl + l = limpiar la consola.
-sqrt(9) = raiz de 9.
-pi = numero pi.
-vector <-c(1,2,3,4,5) = para crear un vector.
-vector = para llamar a los valores del "vector".
-caracteres <-c("pepito","juanito","panchito") = para crear un vector no numerico.
-caracteres = para llamar a los nombres. 
-imc <-peso/altura^2 = operaciones entre vectores.
-sum("nombre vector x") = sumatoria Xi.
-length(peso) = tamaño de la muestra del vector peso.
-xbar <-sum(peso)/length(peso) = peso promedio.
-varianza <-sum((peso-xbar)^2)/(length(peso)-1) = varianza de la variable peso.
-desv.std <-sqrt(varianza) = desviacion estadar
----------------------------------------------------------------------------------
clase 14 sep:

Rstuio = A & a son distintos (por la mayuscula)

-x <-2 = darle un valor a la x.
-print (x) = me de el valor de x.
-se pueden comparar las cajas( x e y). x < y      creo una variable k para almacenar estos valores. 
                                       x >= y       
                                       x > t
                                       x <= y
                                       x == y

-se asigana variable "j" <- x > y &&TRUE y luego print(k).
-control + z = reversa.
- not,and,or
-a%%b = resto de una división
-a + b
-a - b
-a*b
-a/b  

condicionantes: funciones que acruan bajo condiciones(true/false)
-if(condicion1) = si la condicion es verdader se hace algo y si es falsa no hace nada. if(x>y||w>m){print("holamundo")} 
en el caso que sea falso, existe el if-else: se encarga de tomar todo lo que ocupo en la condicion del if.(los vlores que no cumplen la condición).

-else=  if(condicion1){print(resultado)
        }else{
        (condicion2)
        }

-elevar al cuadrado= 2*x**2 || 2*x^2

reseta de diseño: desripcion de que queremos hacer, por ejm tenemos una funcion que entrega el doble de x si x>0 (son los gatos: funcion,como se lee y ejm).
SIEMPRE SE HACE PARA IR EXPLICANDO QUE VAMOS HACIENDO.

-#comentario en R 

tipos de datos: 
-enteros(int): negtivos, cero y positivos.
-reales(double): decimales tmbn.
-booleans(boolean): true o false.
-carácter(char): a,b,c....etc.
-texto(string): "hola mundo". 



