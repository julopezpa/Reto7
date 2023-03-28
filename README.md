# Reto7
# Imprimir un listado con los números del 1 al 100 cada uno con su respectivo cuadrado.

    x:int=1
    while x<=100:
        print(str(x)+ " y su cuadrado es " + str(x**2))
        x +=1
![image](https://user-images.githubusercontent.com/124606636/228108014-addd4120-f030-41c7-b332-74276c79bdfe.png)


# Imprimir un listado con los números impares desde 1 hasta 999 y seguidamente otro listado con los números pares desde 2 hasta 1000.

    x:int=1#definimos primera variable  que va a ser de numero impares
    y:int=0#definimos segunda variable que va a ser de numeros pares
    while x<=999:#el ciclo y se limita hasta que numero se va a evaluar
        print(str(x)+ " es impar")
        x +=2#se aumenta en 2 porque un numero impar mas dos siempre da el siguiente numero impar
    while y<=1000:
        print(str(y)+ " es par")
        y+=2#se aumenta en 2 porque un numero par mas dos siempre da el siguiente numero par
![image](https://user-images.githubusercontent.com/124606636/228108052-f6e845bf-2337-4b98-93fb-933f7127a2e4.png)

        
# Imprimir los números pares en forma descendente hasta 2 que son menores o iguales a un número natural n ≥ 2 dado

    n=int(input("ingrese un numero"))
    while n>=2: 
        z=n%2
        if z==0:
            print(str(n))
            n-=2
        if z!=0:
            n-=1

            
# En 2022 el país A tendrá una población de 25 millones de habitantes y el país B de 18:9 millones. Las tasas de crecimiento anual de la población serán de 2% y 3% respectivamente. Desarrollar un algoritmo para informar en que año la población del país B superará a la de A.

    A=int=25000000
    B=int=18900000
    Año=int=1
    while B<A:
        A*=1.02# esto ya que se le esta sumando deuna el 2% extra a la pobracion que se tenia anteriormente
        B*=1.03# esto ya que se le esta sumando deuna el 2% extra a la pobracion que se tenia anteriormente
        Año+=1
    print("para el año "+ str(Año)+" la pobracion de B("+str(B)+") sera mayor que la pobracion de A("+str(A)+")")
![image](https://user-images.githubusercontent.com/124606636/228108098-29449dd7-1f7e-42b9-a6d1-73a25ab2cd94.png)

    
# Imprimir el factorial de un número natural n dado.

    n=int(input("ingrese un numero al que le quiera sacar su factorial"))
    x=int=n
    while x>1:
        x-=1
        n*=x

    print (n)
# Implementar un algoritmo que permita adivinar un número dado de 1 a 100, preguntando en cada caso si el número es mayor, menor o igual.

    n=int(input("ingrese un numero del 1 al 100"))
    y=50
    while n!=y:
       if y<n:
          y +=1
       else:
          y-=1
    print("el numero que ingreso es "+str(y))
    
# Implementar un programa que ingrese un número de 2 a 50 y muestre sus divisores.

    n=int(input("ingrese un numero del 2 al 50"))
    x=1
    while x<=n:
        if n%x==0:
            print(str(x))
        x+=1
# Implementar el algoritmo que muestre los números primos del 1 al 100. nota: use funciones

    def numeros_primos(n : int,):
            i = int(2) 
            if n == 2 : 
                 print(n)
            while i < n :
                if n%i == 0: 
                    break 
                elif i == n-1: 
                    print(n) 
                i += 1 

    if __name__ == "__main__" :
        n = int(2) 
        Lim= 100 
        while n < Lim: 
            a = numeros_primos(n) 
            n += 1 
# MEME RANDOM
![image](https://user-images.githubusercontent.com/124606636/228107973-24c2e807-c4af-4b93-ab2c-b2959ce096a7.png)

    

