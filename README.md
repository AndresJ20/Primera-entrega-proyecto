# Primera-entrega-proyecto
Avance del proyecto
# 1.) ¿Qué es Python?
Como sabemos Python es un lenguaje de programación interpretado, utilizamos códigos, es muy fácil de aprender, es elegante y nos ayuda en la práctica del aprendizaje.
# 2.) ¿Qué es una variable?
Aprendimos que una variable es una "caja" ya que existen elemento almacenando el valor en ella, la variable puede cambiar de valor a nuestro gusto.
## 2.1.) Nombrando una variable
Nombrar una variable significa el nombre que le daremos a la "caja" 
## 2.2.) Asignando valores a una variable
A la asignación se le agrega un valor para identificarlo, el operador de una variable es ´´=´´ de derecha a izquierda.
Ejemplo:
x = 20
# 3.) Operadores básicos
En python podemos realizar operaciones básicas matemáticas sin ningún problema.
## 3.1.) Suma
Podemos realizar la suma de tres diversas formas:
### 3.1.1.) Asignanción de variables:
a = 8
b = 2
print(a+b) #Al realizar este proceso, obtendremos nuestra suma
### 3.1.2.) Operadores de asignación
a = 8
a += 2
print(a) #Obtendremos nuestra suma ya que asignamos que nuestra variable "a" que vale 8 se sume +2
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
print(a-b) #Al realizar este proceso, obtendremos nuestra resta
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
nombre= "Soy Andrés Jaramillo, tengo"
numero= 19
edad= "años"
variable= nombre + "" + str(numero) + "" + edad
print(variable) #Obtendremos nuestra frase
## 5.) Casting en Python

## 5.1.) List

## 5.2.) Tuple

## 5.3.) Dictionary

# 6.) Tomando decisiones

## 6.1.) Sentencia if

## 6.2.) Ciclo For

## 6.3.) Ciclo While

## 6.4.) Break

## 6.5.) Continue
