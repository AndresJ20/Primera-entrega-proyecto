# Primera-entrega-proyecto
Avance del proyecto
# 1.) ¿Qué es Python?
Como sabemos Python es un lenguaje de programación interpretado, utilizamos códigos, es muy fácil de aprender, es elegante y nos ayuda en la práctica del aprendizaje.
# 2.) ¿Qué es una variable?
Aprendimos que una variable es una "caja" ya que existen elemento almacenando el valor en ella, la variable puede cambiar de valor a nuestro gusto.
## 2.1.) Nombrando una variable
Nombrar una variable significa el nombre que le daremos a la "caja" 
## 2.2.) Asignando valores a una variable
A la asignación se le agrega un valor para identificarlo, el operador de una variable es "=" de derecha a izquierda.
Ejemplo:
```x = 20```
# 3.) Operadores básicos
En python podemos realizar operaciones básicas matemáticas sin ningún problema. Operaciones como:
```Suma = +
   Resta = -
   Multiplicación = *
   División = /
   Módulo = %
   Potenciación = **
```
## 3.1.) Suma
Podemos realizar la suma de tres diversas formas:
### 3.1.1.) Asignanción de variables:
    a = 8
    b = 2
    print(a+b) #Al realizar este proceso, obtendremos nuestra suma
### 3.1.2.) Operadores de asignación
    a = 8
    a += 2
    print(a) #Obtendremos nuestra suma ya que asignamos que nuestra variable "a" que vale 8 se sume +2```
### 3.1.3.) Pidiendo al usuario valores:
    num1 = int(input("Dígite un valor: "))
    num2 = int(input("Dígite un valor: "))
    operación = num1 + num2
    print(operación) #Pedimos valores al usuario y obtendremos nuestra suma
## 3.2.) Resta
Podemos realizar la resta de tres diversas formas:
### 3.2.1.) Asignanción de variables:
    a = 8
    b = 2
    print(a-b) #Al realizar este proceso, obtendremos nuestra resta:
### 3.2.2.) Operadores de asignación
    a = 8
    a -= 2
    print(a) #Obtendremos nuestra resta ya que asignamos que nuestra variable "a" que vale 8 se reste -2
### 3.2.3.) Pidiendo al usuario valores:
    num1 = int(input("Dígite un valor: "))
    num2 = int(input("Dígite un valor: "))
    operación = num1 - num2
    print(operación) #Pedimos valores al usuario y obtendremos nuestra resta
## 3.3.) Multiplicación
Podemos realizar la multiplicación de tres diversas formas:
### 3.3.1.) Asignanción de variables:
    a = 8
    b = 2
    print(a*b) #Al realizar este proceso, obtendremos nuestra multiplicación
### 3.3.2.) Operadores de asignación
    a = 8
    a *= 2
    print(a) #Obtendremos nuestra multiplica ya que asignamos que nuestra variable "a" que vale 8 se multiplique *2
### 3.3.3.) Pidiendo al usuario valores:
    num1 = int(input("Dígite un valor: "))
    num2 = int(input("Dígite un valor: "))
    operación = num1 * num2
    print(operación) #Pedimos valores al usuario y obtendremos nuestra multiplicación
## 3.4.) División
Podemos realizar la división de tres diversas formas:
### 3.4.1.) Asignanción de variables:
    a = 25
    b = 5
    print(a/b) #Al realizar este proceso, obtendremos nuestra división
### 3.4.2.) Operadores de asignación
    a = 25
    a /= 5
    print(a) #Obtendremos nuestra divisón ya que asignamos que nuestra variable "a" que vale 25 se divida /5
### 3.4.3.) Pidiendo al usuario valores:
    num1 = int(input("Dígite un valor: "))
    num2 = int(input("Dígite un valor: "))
    operación = num1 / num2
    print(operación) #Pedimos valores al usuario y obtendremos nuestra división
## 3.5.) Módulo
Podemos realizar el módulo de tres diversas formas:
### 3.5.1.) Asignanción de variables:   
    a = 11
    b = 8
    print(a%b) #Al realizar este proceso, obtendremos el resto de la división que en esta operación sería "1"
### 3.5.2.) Operadores de asignación
    a = 11
    a %= 8
    print(a) #Obtendremos nuestro módulo ya que asignamos que nuestra variable "a" que vale 11 su resto al ser %8
### 3.5.3.) Pidiendo al usuario valores:
    num1 = int(input("Dígite un valor: "))
    num2 = int(input("Dígite un valor: "))
    operación = num1 % num2
    print(operación) #Pedimos valores al usuario y obtendremos nuestro módulo
# 4.) Tipos de datos en Python
Los tipos de datos son aquellos que nos ayudarán a registrar datos de manera entera, decimal, cadena de caracteres, etc. Ayudan al momento de realizar cualquier operación
## 4.1.) Integer
También conocida cómo "Int" o "Entero", al realizar este tipo de dato númerico, nuestro resultado será de forma entera sin ningún decimal. La podemos realizar de dos maneras:
### 4.1.1.) Pidiendo valores al usuario
    num1 = int(input("Dígite un valor: "))
    print("Su numero es: ", num1) #El usuario sólo aceptará números enteros
### 4.1.2) Asignando valores
    a = 8.456
    print(int(a)) #La variable "a" está de forma decimal, al imprimir el texto por pantalla, se convertirá en entero
## 4.2.) Float
Es lo contrario a la función "Int", los números en esta sección serán "flotantes", es decir, serán decimales. La podemos realizar de dos maneras:
### 4.2.1.) Pidiendo valores al usuario
    num1 = float(input("Dígite un valor: "))
    print("Su numero es: ", num1) #El usuario sólo aceptará números decimales
### 4.2.2) Asignando valores
    a = 8.456
    print(float(a)) #La variable "a" está de forma decimal, al imprimir el texto por pantalla, seguirá decimal o a su vez, se redondea.
## 4.3) String
Comprendí que este tipo de datos nos permitirá unir las variables tanto como numéricas o escritas, formando varias asignaciones para tener una sola. Ejemplo:
```
nombre = "Soy Andrés Jaramillo, tengo" 
numero= 19 edad= "años" 
variable= nombre + "" + str(numero) + "" + edad 
print(variable) #Obtendremos nuestra frase
```
## 5.) Casting en Python
Los tipos de casting nos ayudarán a convertir un tipo de dato a otro.
```
sueldo = 780.50
print(int(sueldo)) # El valor decimal será transformado a entero
salario = 790.455
print(float(salario)) #El valor con muchos decimales, se convertirá a un solo decimal
```
## 5.1.) List
Las listas, son estructuras de datos más flexibles. Las listas están conformadas por [] almacenando cualquier tipo de valor (númerico, cadenas, etc).
## 5.2.) Tuple
Las tuplas, son tipos de condiciones además, son listas inmutables, ya que no se pueden modificar en ello. Las tuplas están conformadas por ().
## 5.3.) Dictionary
Los diccionarios son tipos de colección, tienen dos elementos por posición (clave y valor). Los diccionarios están conformadas por {}.
# 6.) Tomando decisiones
Encontramos una gran variedad en ella, nos ayudan a ejecutar bucles o ciclos de manera rápida. Estructura muy importante en la programación.
## 6.1.) Sentencia if
El condicional if nos sirven para realizar una condición "Sí" deberá repetirse aquella condición. Si se cumple, se repite el ciclo, si no se cumple, sale del ciclo. Existe también otras condicionales como "elif" y "else", elif nos ayudará a verificar varias condiciones y else realiza la condición "No" y sale del ciclo
```
numero = int(input("Digite un numero: "))
if numero > 0:
   print("El numero es positivo)
elif numero == 0:
   print("El numero es 0")
else:
   print("El numero es negativo")
#Al realizar este ejercicio, el usuario pide un valor, al registrarlo, el "if" servirá para identificar si es positivo saldrá del ciclo, como sabemos "0" no es positivo ni negativo, es decir, el elif nos servirá para identificarlo, o a su vez, si el usuario digita un número negativo, omitirá el "if" y "elif" e irá directamente al "else" 
```
## 6.2.) Ciclo For
El bucle se repetirá el número de veces que le indiquemos ya sea una tupla, lista, variables, etc.
```
n = 5
cubo_cuarta = 0
for i in range(n):
    numero = int(input("Ingrese un numero: " + str(i+1) + ": "))
    print("Cubo y cuarta de",numero,"son",numero**3,"y",numero**4)
# El "n" nos ayuda a repetir el ciclo el número de veces que queremos, en este caso, se repetirá 5 veces, lo que estamos pidiendo es ingresar un número al usuario, donde obtendremos el cubo y la cuarta de ese número
```
## 6.3.) Ciclo While
Al contrario del ciclo for, este bucle se repetirá indeterminadas o determinadas veces.
```
numero = -1
while numero < 0:
    numero = int(input("Ingresar numeros positivos: "))
if numero>=1 and numero <= 10:
    print("1-10")
#El ciclo while, especifica que se repetira muchas veces, aceptará cualquier número, tanto negativo como positivo, a excepción que se digite 1 o 10, donde se saldrá del bucle.
```
## 6.4.) Break
En términos comunes se podría decir que esta condición "sale o se rompe del ciclo" cuando ejecute el programa.
```
j = 0
for i in range(10):
    j+=2
    print("i:",i,"j:", j)
    if j == 10:
        break 
#En este ejercicio, estamos registrando números, donde "i" aumentará en 1 y "j" aumentará en +2, es decir, cuando "j" sea igual a 10, la función "break" romperá y saldrá del ciclo.
```
## 6.5.) Continue
A diferencia del ciclo break, este condicional nos ayuda a continuar a terminar el ciclo o "salta" el ciclo for a pesar que le indiquemos.
```
j = 0
for i in range(10):
    j+=2
    print("i:",i,"j:", j)
    if j >= 2 and j <=6:
        continue #Salta del ciclo for
    print("El valor de j:", j)
```
