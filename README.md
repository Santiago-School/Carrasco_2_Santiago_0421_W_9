# Carrasco_2_Santiago_0421_W_9

print(" ")

print("Santiago Carrasco 0421 3°W")

print(" ")

# solicitar un numero entero al usuario

try:

    numero = int(input("ingrese un numero entero: "))
    
    # comprobar si el numero es mayor a 40
    if numero > 40:
        # comprobar si el numero es divisible por 7
        if numero % 7 == 0:
            print("el numero es mayor a 40 y es divisible por 7")
        else:
            print("el numero es mayor a 40 pero no es divisible por 7")
    else:
        print("el numero no es mayor a 40")


except ValueError:

    print("por favor, ingrese un numero entero valido")

![image](https://github.com/user-attachments/assets/80a83936-48f5-4520-b67d-f5cf12a1f767)

