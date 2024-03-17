#Repositorio #4

<p>
El siguiente repositorio contiene los ejercicios correspondientes al reto número 4 (ayuda no puedo ma)
</p>


<b>1. Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.</b>

    # Algoritmo que dado un numero entero, determinar si ese numero corresponde al codigo ASCII de una vocal minuscula.
    
    num_entero: int
    num_entero = input("Ingrese un numero entero: ")
        
    match num_entero:
        case "97":
            print("El numero 97 corresponde a la vocal minuscula a")
        case "101":
            print("El numero 101 corresponde a la vocal minuscula e")
        case "105":
            print("El numero 105 corresponde a la vocal minuscula i")
        case "111":
            print("El numero 111 corresponde a la vocal minuscula o")
        case "117":
            print("El numero 117 corresponde a la vocal minuscula u")
        case _:
          print("El numero ingresado no corresponde a ninguna vocal minuscula.")


<b>2. Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.

</b>

    #Dada una cadena de longitud 1, determine si el código ASCII de la primera letra de la cadena es par o no.
    
    texto = input("Ingrese un texto: ")
    primera_letra = ord(texto[0])
    
    if primera_letra % 2 == 0:
        print("El codigo ASCII de la primera letra de la cadena es par.")
    else:
        print("El codigo ASCII de la primera letra de la cadena es impar.")
		
		
		
		
<b>3. Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

</b>

    # Dado un caracter, construya un programa en Python para determinar si el caracter es un digito o no.
    
    caracter: str
    caracter = input("Ingresa un caracter:")
    
    match caracter:
        case "0":
            print("El caracter" ,caracter, "es un digito")
        case "1":
            print("El caracter" ,caracter, "es un digito")
        case "2":
            print("El caracter" ,caracter, "es un digito")
        case "3":
            print("El caracter" ,caracter, "es un digito")
        case "4":
            print("El caracter" ,caracter, "es un digito")
        case "5":
            print("El caracter" ,caracter, "es un digito")
        case "6":
            print("El caracter" ,caracter, "es un digito")
        case "7":
            print("El caracter" ,caracter, "es un digito")
        case "8":
            print("El caracter" ,caracter, "es un digito")
        case "9":
            print("El caracter" ,caracter, "es un digito")
        case _:
            print("El caracter" ,caracter, "no es un digito")
			
			
<b>4. Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

Positivo: "El número x es positivo"
Negativo: "El número x es negativo"
Cero (0): "El número x es el neutro para la suma"</b>

    #Dado un numero real x, construya un programa que permita determinar si el numero es positivo, negativo o cero.
    
    num_real: int
    num_real = int(input("Ingrese un numero real: "))
    
    if num_real > 0:
        print("El numero " + str(num_real) + " es positivo")
    elif num_real < 0:
        print("El numero " + str(num_real) + " es negativo")
    else:
        if num_real == 0: 
            print("El numero " + str(num_real) + " es el neutro para la suma")
			
			
<b>5. Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.

</b>

    #Dado el centro y el radio de un circulo, determinar si un punto de R2 pertenece o no al interior del círculo.
    
    radio = float(input("Ingresa el radio del circulo: "))
    centro_en_x = float(input("Ingresa la ubicacion del centro del circulo en x: "))
    centro_en_y = float(input("Ingresa la ubicacion del centro del circulo en y: "))
    punto_en_x = float(input("Ingresa el punto x: "))
    punto_en_y = float(input("Ingresa el punto en y: "))
    
    distancia = ((punto_en_x - centro_en_x)**(2) + (punto_en_y - centro_en_y)**(2))**(1/2)
    
    if distancia <= (radio):
        print("El punto ( " +str(punto_en_x)+" , "+str(punto_en_y)+" ) esta ubicado dentro del circulo con radio " + str(radio) + " y centro en ( " + str(centro_en_x)+" , "+ str(centro_en_y)+" ).")
    else:
        if distancia > (radio):
            print("El punto ( " +str(punto_en_x)+" , "+str(punto_en_y)+" ) no esta ubicado dentro del circulo.")


<b>6. Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.

</b>

    #Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
    
    lado_1 = float(input("Ingresa un valor para el lado 1: "))
    lado_2 = float(input("Ingresa un valor para el lado 2: "))
    lado_3 = float(input("Ingresa un valor para el lado 3: "))
    
    if (lado_1 + lado_2) > lado_3:
        if (lado_2 + lado_3) > lado_1:
            if(lado_1 + lado_3) > lado_2:
                print("Los lados ingresados permiten crear un triangulo.")
            else:
                print("Los lados ingresados no permiten crear un triangulo.")
				
				
<b> 
by: Said Ibrahim</b>
