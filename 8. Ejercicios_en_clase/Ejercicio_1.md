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

![image](https://user-images.githubusercontent.com/119714900/213831672-faa2ed88-2fbd-450e-9ce0-0e5b95ee0d57.png)
![image](https://user-images.githubusercontent.com/119714900/213831691-9deb6c67-eb87-435e-9f69-b5c8f1058cc5.png)

#  Números pares

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

# flujo
![image](https://user-images.githubusercontent.com/119714900/213836899-737da725-0618-4d70-9880-43b9edf9f3b5.png)
![image](https://user-images.githubusercontent.com/119714900/213836985-99de799f-9813-42e0-9a33-ef5524fa7b94.png)


# Lápices

Algoritmo Lapices
	Definir x Como Entero
	Definir total Como Real
	Escribir 'Ingresa la cantidad de lápices a comprar'
	Leer n
	Si n >= 1000 Entonces
		total = n * 0.85
	SiNo
		total = n * 0.90
	FinSi
	Escribir "La cantidad a pagar por ", n, " lápices es de: $ ",total, " Pesos "
FinAlgoritmo


# Flujo 

![image](https://user-images.githubusercontent.com/119714900/213837228-52ce4da8-0552-4870-9976-9f3af470948d.png)

![image](https://user-images.githubusercontent.com/119714900/213837315-df909911-d85d-4e02-ab14-f2ac69772d69.png)


# Edad promedio

Algoritmo edad_promedio
	Definir total,edad,suma Como Entero
	Definir promedio Como Real
	Escribir "Ingrese el total de alumnos"
	Leer total
	x=1
	suma=0
	Mientras x <= total Hacer
		Escribir "Ingrese su edad"
		Leer edad
		suma=suma+edad
		x=x+1
		
	FinMientras
	Escribir "El promedio de edades del grupo es de " , suma / total , " años"
	
FinAlgoritmo

# Flujo

![image](https://user-images.githubusercontent.com/119714900/213840212-49ecd89e-10af-48cf-ac1d-e22f2ff6e136.png)

![image](https://user-images.githubusercontent.com/119714900/213840223-62f52b81-1f59-47e5-9928-a9e128e3ce00.png)

# promedios de calificaciones

Algoritmo Calificaciones
	Definir total,calificacion,suma Como Entero
	Definir promedio Como Real
	Escribir 'Ingrese el número total de calificaciones a capturar'
	Leer total
	x <- 1
	suma <- 0
	Mientras x<=total Hacer
		Escribir 'Ingrese la calificacion'
		Leer calificacion
		suma <- suma+calificacion
		x <- x+1
	FinMientras
	
	Si suma/total>=4.0 Entonces
		Escribir "El promedio de alumno es de ", suma/total, " se encuentra aprobado"
	SiNo
		Escribir "El promedio de alumno es de ", suma/total, " se encuentra reprobado"
	FinSi
FinAlgoritmo

# Flujo

![image](https://user-images.githubusercontent.com/119714900/213841541-50014410-af15-46ed-a257-477ffc0e4415.png)
![image](https://user-images.githubusercontent.com/119714900/213841545-4cf82ab7-7a7d-45fe-9880-b7b6bae082ff.png)


# ciclo while 
Algoritmo Recomendaciones_cine_libros_comida_lugares_salir
	recomendacion<-0
	
	Escribir "Ingrese la recomendación que deseas recibir: 1.- Cine 2.- Libros 3.- Comida 4.- Lugares 5.- Salir"
	Leer recomendacion
	Mientras recomendacion <> 5 Hacer
		Segun recomendacion Hacer
			1:
				Escribir "====CINE====="
				Escribir "AVATAR , GATO_CON_BOTAS"
			2:
				Escribir "====LIBROS====="
				Escribir "uN MUNDO FELIZ ,  DON QUIJOTE"
			3:
				Escribir "====COMIDA====="
				Escribir "ENSALADAS Y PIZZA"
			4:
				Escribir "====LUGARES====="
				Escribir "MUSEO DE ANTROPOLOGÍA Y CHAPULTEPEC"
			De Otro Modo:
				Escribir "OPCION INVALIDA"
		Fin Segun
		Escribir "Ingrese la recomendación que deseas recibir: 1.- Cine 2.- Libros 3.- Comida 4.- Lugares 5.- Salir"
		Leer recomendacion
	Fin Mientras
	
	Escribir "HASTA LUEGO"
	
FinAlgoritmo

# FLUJO
![image](https://user-images.githubusercontent.com/119714900/213881313-6d10bd6f-4eb6-425f-88d5-ff93b8f2b98c.png)

![image](https://user-images.githubusercontent.com/119714900/213881325-54cd3b00-6398-4237-b7e8-1564a7f7cd65.png)

# Ciclo FOR
Algoritmo multiplicar
	num<-0
	res<-0
	Escribir "De que número requieres la tabla de multiplicar"
	leer num

	Para i<-1 Hasta 10 Con Paso 1 Hacer
		res<-num*i
		Escribir num," * ",i," = ",res
	Fin Para
FinAlgoritmo
 
# flujo

![image](https://user-images.githubusercontent.com/119714900/213882360-0a9cdec6-66ce-4a29-8b46-7d2f5122bcc3.png)

![image](https://user-images.githubusercontent.com/119714900/213882368-ed25e0cf-93c3-4337-808c-85364d34bcd0.png)

# Para 2 tablas

Algoritmo multiplicar
	num<-0
	res<-0
	Escribir "De que número requieres la tabla de multiplicar"
	leer num

	Para i<-1 Hasta 10 Con Paso 1 Hacer
		res<-num*i
		Escribir num," * ",i," = ",res
	Fin Para
	
	Escribir "De que número requieres la tabla de multiplicar"
	leer num
	
	Para i<-1 Hasta 10 Con Paso 1 Hacer
		res<-num*i
		Escribir num," * ",i," = ",res
	Fin Para
FinAlgoritmo


# Flujo
![image](https://user-images.githubusercontent.com/119714900/213882591-8f8d7cc2-cfb8-486c-86de-713fee91f2df.png)
![image](https://user-images.githubusercontent.com/119714900/213882627-487cd88b-c5c6-495c-8a10-fa4023f6ec53.png)


