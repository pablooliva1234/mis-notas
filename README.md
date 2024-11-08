# mis-notas
hola ramon
# -OP:Significa computer o ordenador:Máquina electrónica capaz de realizar un tratamiento automático de la información y de resolver con gran rapidez problemas matemáticos y lógicos mediante programas informáticos cuyo funciónamiento es procesado mediante la CPU:Unidad central de procesamiento, esta procesa las señales y hace posible la computación. Actúa como el cerebro de cualquier dispositivo de computación. Obtiene instrucciones de la memoria, realiza las tareas necesarias y envía la salida a la memoria.
# -Computar es operar con un ordenador,está relacciónado con el manejo de símbolos,cuando hay un símbolo existe una asociación mental:Material:significante-Mental:significado
## 0:# Computación simbólica
## 0.1:##
## 0.2:se trata de una representación de síbolos en una manera más convencional.
## 0.2.1:###  
![1730797271066](https://github.com/user-attachments/assets/7913651d-9d20-412c-b8cc-5fb4ae03b4a3)

![1730797271071](https://github.com/user-attachments/assets/c01d529e-0fbb-47b1-8069-c0aad67b664a)

# ¿Como es la memoria? El modelo de memoria plana o modelo de memoria lineal se refiere a un paradigma de direccionamiento de memoria en el que "la memoria aparece ante el programa como un único espacio de direcciones contiguo ". La CPU puede direccionar directamente (y linealmente) todas las ubicaciones de memoria disponibles.La memoria suele dividirse en un almacenamiento primario de alta velocidad y uno secundario de menor velocidad. La gestión de memoria del sistema operativo se ocupa de trasladar la información entre estos dos niveles de memoria.
# ¿Que se puede hacer con la CPU?# :La CPU es el componente principal que procesa las señales y hace posible la computación. Actúa como el cerebro de cualquier dispositivo de computación. Obtiene instrucciones de la memoria, realiza las tareas necesarias y envía la salida a la memoria, ejecuta una secuencia de instrucciones y procesa los datos de las mismas. Estas secuencias de instrucciones son las que realizan los programas que tienes instalados en el ordenador.
# Los estímulos entran por NUM 1 Y NUM 2 a el operador que las transforma en una salida que recibe el nombre de RES.

# Py![1730797271059](https://github.com/user-attachments/assets/e4f3527c-ca09-4fad-98f9-487c5b3ce897)
thon es un lenguaje de programación ampliamente utilizado en las aplicaciones web, el desarrollo de software, la ciencia de datos y el machine learning (ML). Los desarrolladores utilizan Python porque es eficiente y fácil de aprender, además de que se puede ejecutar en muchas plataformas diferentes.
# Ejemplo de programa realizado en  phyton,consiste en una suma y una multlipicación sencilla.



 # Online Python - IDE, Editor, Compiler, Interpreter

def sum(a, b):           # define funcion sum
    return (a + b)  
    
def mul(a, b):           # define funcion mul
    return (a * b)
    
a = int(input('Enter 1st number: '))
b = int(input('Enter 2nd number: '))

print(f'Sum of {a} and {b} is {sum(a, b)}')
print(f'Mul of {a} and {b} is {mul(a, b)}')

print(f'Sum of {a} and {b} is {sum(a, b)} and the product is {mul(a, b)}') 

# Tipos de datos-Datos particulares
Clases-Objetos particulares
Perro-Pompa
Cada dato tiene un tipo distinto:entero(int) etc.
Los datos de un mismo tipo se pueden sumar,por ejemplo 3(tipo entero +3(tipo entero)= 6
![1730797271076](https://github.com/user-attachments/assets/a2227906-fb8f-487b-8d82-6cfb2e23b2bf)

# aquí un ejemplo de programa utrilizando las clases y datos
class gato:
    def_init_(self):
        print(``hola mundo, meow!``)
#        
        
class perro:
    def _init_(self):
        print(``hola mundo, wolf!``)
#

gato0 = gato()
perro0 = perro()

![1730797271055](https://github.com/user-attachments/assets/77816cf1-e6e1-435f-9181-f171aa3a8fda)

# Cliente,master  - Primario
# Servicio,slave - Secundario
# El cliente comeinza el programa pidiendole al servicio que trabaje utilizando el dato 22 y 33,el servicio nos comunica el dato que ha recibido y da el OK que controla la operación.
OK = True


def surv(f"dato, control=OK):
    PRINT("srv", recibido: {dato}" }
        return  OK
   
    
def cli():
    print("cli: begin")
    srv(22)
    srv(33)
    print(cli: end")
 main --------------------------------

cli()

# ÁNALISIS DE UNIVERSO
universo.nombre=”concesionario” universo.discurso.comienzo

El universo es un concesionario de automóviles.

de los clientes se conoces los datos habituales,tambien los coches ,de los vendedores y de las ventas.

un coche puede ser recomprado a un cliente.

universo.discursivo.fin

cliente
automovil
vendedor
venta
concesionario
dato
------------------------------------------------------------
# v2 universo.discurso.comienzo

concesionario de automóviles.

cliente:se conoces los datos habituales
coche:se conoces los datos habituales
vendedor:se conoces los datos habituales
venta:se conoces los datos habituales
un coche puede ser recomprado a un cliente.

universo.discursivo.fin

------------------------------------------------------------
# v3 universo.discurso.comienzo

concesionario de automoviles(de automoviles)
clientes(,,)
coche(,,)
vendedor(,,)
venta(,,)
recompra(de coche)(por cliente)
universo.discursivo.fin

------------------------------------------------------------
# v4 (con diseño)

concesionario de automoviles(de automoviles)(cochecitospuntos.com)
clientes(dni,nombre,apellido,tf,direccion...)
coche(numBastidor,matricula,año,marca,modelo,color...)
vendedor(numVendedor,dni,nombre,ape,tf)
venta(coche,cliente,vendedorimporte,fecha...)
recompra(de coche)(por cliente)

