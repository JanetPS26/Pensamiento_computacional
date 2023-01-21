Ejercicio que calcula cuánto tiempo se tarda en leer los nombres de determinado número de población.
# Algoritmo 

Algoritmo sin_titulo
	poblacion=0
	tiempo=2
	segundoss=0
	minutos=0
	horas=0
	dias=0
	meses=0
	años=0
	Escribir "Ingresa el número de la población que deseas validar"
	Leer poblacion
	segundoss=poblacion*tiempo
	minutos=segundoss/60
	horas=minutos/60
	dias=horas/24
	años=dias/365
	Escribir "segundos ="," ",segundoss," ","minutos ="," ",minutos," ","horas = ", horas," ","dias = "," ",dias," ","años = "," ",años;
 # Diagrama de flujo poblacion
 ![image](https://user-images.githubusercontent.com/119714900/208263949-2a125d90-9dc7-4bf9-8fff-f0dce8c1d244.png)

 ![image](https://user-images.githubusercontent.com/119714900/208263933-ea86cd26-794a-41af-915c-cf7b5373c5d6.png)
 # pseudocódigo
 ![image](https://user-images.githubusercontent.com/119714900/208264009-adb9ff49-2222-4bf0-b31e-e368611ea186.png)
 
 # Algoritmo edad
 
 Algoritmo Calculo_de_edad
	edad <- 0
	Escribir 'Ingresa tu edad'
	Leer edad 
	Si edad>0 y edad<120 Entonces
		Si edad>=18 Entonces
			Escribir 'Eres mayor de edad'
		SiNo
			Escribir "Eres menor de edad"
		FinSi
		
	SiNo
		Escribir"Ingresa edad correcta"
	Fin Si
	
FinAlgoritmo

 # Diagrama de flujo edad
 ![image](https://user-images.githubusercontent.com/119714900/211166030-8b044b61-d9d7-45b5-a2e5-cc90c29b1be2.png)
 ![image](https://user-images.githubusercontent.com/119714900/211166189-7a9b6500-1e7d-434b-ba6a-4b48c742a4eb.png)
 ![image](https://user-images.githubusercontent.com/119714900/211166048-572ad822-59cf-40ff-a9d1-69aa80878731.png)

# Algoritmo número par

Algoritmo numeros_par
	num<-0
	Escribir "Ingresa el número"
	Leer num
	Si num MOD 2 == 0 Entonces
		Escribir "Es un número par"
	SiNo
		Escribir "Es un número impar"
	Fin Si

FinAlgoritmo


 # Diagrama de flujo numero par
 
![image](https://user-images.githubusercontent.com/119714900/211169278-7373c60e-919d-4641-b929-df3ae0287b09.png)

# Pseudocodigo que imprima los números pares que se encuentran entre 0 y 100.

 Algoritmo numeros_pares
	Definir x Como Entero	
	x=0
	Mientras x <= 100 Hacer
		si x mod 2 == 0 Entonces
			Escribir x
			
		FinSi
		x=x+1
	FinMientras
FinAlgoritmo

# Diagrama de flujo

![image](https://user-images.githubusercontent.com/119714900/213831636-6dd7747f-6b79-48b1-9997-2a2cc60daf74.png)

