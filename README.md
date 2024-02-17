# variables.py-
# Define una variable de cada tipo de primitivo
presentacion = "Hola mi nombre es andres"
edad = 22
estatura = 1.78
masculino  = True

# Concatena la cadena con las otras variables
resultado_concatenacion = presentacion + str(edad) + str(estatura) + str(masculino)

# Límite de enteros en Python
# Los enteros en Python pueden ser tan grandes como la memoria de tu máquina lo permita.
# No hay límite específico para el tamaño de un entero en Python.

# Límite de flotantes en Python
# El límite está determinado por la representación en punto flotante de la máquina.
# El módulo sys puede proporcionar información sobre la precisión de los flotantes en tu sistema.

import sys

# Imprimir la precisión de los flotantes en tu sistema
print("Precisión de flotantes en tu sistema:", sys.float_info)

# Aplicar la fórmula de la suma de los primeros n números pares
# Fórmula: suma = n * (n + 1)
n = 5  # Puedes cambiar este valor según tus necesidades
suma_pares = n * (n + 1)

# Imprimir los resultados
print("Resultado de la concatenación:", resultado_concatenacion)
print("Resultado de la suma de los primeros", n, "números pares:", suma_pares)
