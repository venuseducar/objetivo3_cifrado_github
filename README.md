# objetivo3_cifrado_github
ESTE CODIGO CONTIENE LO SIGUIENTE
Un conjunto de funciones necesarias para implementar la interfaz que utilizará el usuario y que cumple con los requerimientos descritos a continuación.
# Al iniciar el programa se pide al usuario que seleccione si desea cifrar o descifrar un mensaje:
# Que desea hacer:
# 1) cifrar mensaje
# 2) Descifrar mensaje

# Opción: 1) Cifrar mensaje
# Se solicita al usuario que introduzca el mensaje a cifrar
# Ingrese el mensaje que desea cifrar: Hola mundo
# Acto seguido, se solicita al usuario que seleccione un cifrador.
# Que cifrador desea usar:
# 1) Cesar
# 2) Atbash
# Para el caso del cifrado César, se requiere una dave secreta (un número) que se solicitará al usuario
# Que clave desea utilizar para el cifrado Cesar: 7
# En caso de usar cifrado Atbash no requiere una clave secreta, por lo tanto directamente se procede a mostrar el mensaje cifrado.
# Finalmente el programa emite el mensaje en código:
# Su mensaje cifrado es: Ovsh tbukv
# Como puede ver, ni los mejores cientificos podrán jamás saber qué es lo que se esconde detrás de ese mensaje.
# En este punto debes utilizar las funciones desarrolladas en los objetivos 1 y 2.

# Opción: 2) Descifrar mensaje
# Implementar una interfaz de usuario similar a la anterior pero que guíe al usuario para introducir un mensaje ya cifrado y seleccionando el método y clave requerida, emita el mensaje original. 
# Reutilizar las funciones de cifrado que se implementaron en la parte anterior.
# 1. Se solicita al usuario que introduzca el mensaje a descifrar
# Ingrese el mensaje que desea descifrar: Ovsh thaky
# 2. Se solicita el cifrador que se desea para descifrar
# Que cifrador deses usar:
# 1)Cesar
# 2) Atbash
# 3. En caso de seleccionar el cifrado Cesar se solicita la clave
# Que clave desea utilizar para el cifrado Cesar: 7
# Finalmente el programa emite el mensaje descifrado:
# Su mensaje descifrado es: Fola and
# Finalmente enviale un mensaje secreto a otro grupo (indicando la clave y el método usado) y esperá su respuesta (también cifrada)
# Algunas ayudas para programar menos!
# • Un mensaje cifrado con César con clave N se puede descifrar aplicando el mismo método pero con clave -N (es decir, puede utilizar la misma función para cifrar y para descifrar)
# • Un mensaje cifrado con Atbash se puede descifrar aplicando nuevamente Atbash sobre el mensaje codificado.   
