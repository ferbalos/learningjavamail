# learningjavamail
Proyecto para aprender a usar la interfaz de programación de aplicaciones
[JavaMail](https://javaee.github.io).

## Creación del proyecto en Elcipse

## Instalación de la API (Application Programming Interface) JavaMail

## Ejecución del programa _"mailshow"_ en Eclipse

## Ejecución del programa _"mailshow"_ en la terminal
Este programa de ejemplo muestra un listado de los emails de una cuenta de
Gmail.

```bash
# Cambiar al directorio del proyecto
cd samples/mailshow/

# Compilar el programa `javac -cp <ruta librerias> <ruta clase principal>`
javac -cp './lib/*' src/mailshow/Main.java

# Ejecutar el programa `java -cp <ruta librerias>:<ruta clases java> <clase principal> <argumentos clase principal>`
java -cp ./src/:'./lib/*' mailshow/Main -D -T imaps -H imap.gmail.com -U usuario@gmail.com -P contraseña
```