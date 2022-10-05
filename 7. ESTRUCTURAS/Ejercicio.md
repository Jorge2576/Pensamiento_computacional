1. Realiza un algoritmo y diagrama de flujo de un programa que compare dos números e indique cual es mayor.
  
        1 inico
        2 num1
          num2
        3 Escrbe el primer numero a comparar
        4 num1
        5 Escrbe el segundo numero a comparar
        6 num2
        7 num1=num2
        8 num1 es igual a num2
        9 num1>num2
        10 num1 es mayor a num2
        11 num<num2
        12 num1 es menor a num2
        13 fin
        
           Algoritmo sin_titulo
	   num1<-0(int)
	   num2<-0(int)
	   Escribir "Escribe el primer numero a comparar"
	   Leer num1
	   Escribir "Escibe el segundo numero a comparar"
	   Leer num2
	   Si num1=num2 Entonces
		   escribir " el ",num1," es igual a ",num2
	   SiNo
		   Si num1>num2 Entonces
			   escribir num1," es mayor que ",num2
		   SiNo
			   escribir num1," es menor que ",num2
		   Fin Si
	   Fin Si
           FinAlgoritmo
	   
	   Algoritmo sin_titulo
	   	nombre<-" "
		peso<-0
		altura<-0
		imc<-0
		i<-1
		Escribir "Hola, ingresa tu nombre"
		Leer nombre
		Repetir
			Escribir nombre,", ingrese su peso (kg)"
			leer peso
		Hasta Que peso>=30 y peso<=250
		Repetir
			Escribir nombre,", ingrese su altura (mts)"
			leer altura
		Hasta Que altura>=0.50 y altura<=2.60
		imc=peso/(altura*altura)
		Escribir nombre," su IMC es de:",imc
		si (imc<18.5) Entonces
			Escribir "peso inferior al normal"
		SiNo
			si (imc>=18.5 y imc<=24.9) Entonces
				Escribir "Normal"
			SiNo
				si (imc>=25.0 y imc<=30) Entonces
					Escribir "Peso superior al normal"
				SiNo
					Escribir "sobrepeso"
				FinSi
			FinSi
			
		FinSi
           FinAlgoritmo

        
  ![Diagrama de compracion num](https://user-images.githubusercontent.com/113545541/191880082-ac194b06-36ec-42d9-b1e3-bc751523c044.png)

        
2. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

        1 inicio
           2 nombre(string)
	   cal1(float)
	   cal2(float)
	   cal3(float)
	   cal4(float)
	   promedio(float)
	
	   3 Hola, cual es tu nombre
	   4 nombre
	   5 nombre, coloca tu primera calificacion
	   6 cal1
	   7 si cal1>0 y cal1<10
	   8 nombre, coloca tu segunda calificacion
	   9 sino calificacion invalida
	   10 nombre, coloca tu segunda calificacion
	   11 cal2
	   12 si cal2>0 y cal2<10
	   13 nombre, coloca tu tercera calificacion
	   14 sino calificacion invalida
	   15 nombre, coloca tu tercera calificacion
	   16 cal3
	   17 si cal3>0 y cal3<10
	   18 nombre, coloca tu cuarta calificacion
	   19 cal4
	   19 si cal4>0 y cal4<10
	   20 sino calificacion invalida
	   21 promedio=(cal1+cal2+cal3+cal4)/4
           22 si promedio>6
	   23 promedio,"Aprobado"
	   24 sino promedio,"Reprobado"
	   25 fin
	
	
	   Algoritmo sin_titulo
	   nombre<-" "
	   cal1<-0
	   cal2<-0
	   cal3<-0
	   cal4<-0
	   promedio<-0
	   Escribir "Hola, escribe tu nombre"
	   Leer nombre
	   Escribir nombre," coloca tu primera calificacion"
	   Leer cal1
	   Si cal1>0 y cal1<11 Entonces
		   escribir nombre," coloca tu segunda calificacion"
		   Leer cal2
		   Si cal2>0 y cal2<11 Entonces
			   escribir nombre," coloca tu tercera calificacion"
			   Leer cal3
			   Si cal3>0 y cal3<11 Entonces
				   escribir nombre," coloca tu cuarta calificacion"
				   Leer cal4
				   Si cal4>0 y cal4<11 Entonces
					   promedio<-(cal1+cal2+cal3+cal4)/4
					   Si promedio>6 Entonces
						   escribir nombre," tu promedio es ",promedio," Aprobado"
					   SiNo
						   escribir nombre," tu promedio es ",promedio," Reprobado"
					   Fin Si
				   SiNo
					   escribir "calificacion invalida"
				   Fin Si
			   SiNo
				    escribir "Calificacion invalida"
			   Fin Si
		   SiNo
			   escribir "Calificacion invalida"
		   Fin Si
	    SiNo
		   escribir "calificacion invalida"
	    Fin Si
            FinAlgoritmo

![Diagrama para calificacion](https://user-images.githubusercontent.com/113545541/191887224-8ec01949-b03e-4a7e-9475-70162ed90fee.png)



3. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.

           1 inicio
	   2 num
	   3 Coloca el numero que deseas conocer
	   4 num
	   5 si num es divisible entre dos y el residuo es cero
	   6 entonces el num es par
	   7 sino el num no es par 
	   8 fin
	   
	   Algoritmo sin_titulo
	   num<-0
	   Escribir "Coloca el numero que quieres conocer"
	   Leer num
	   Si num mod 2=0 Entonces
		   Escribir num, " es un numero par"
	   SiNo
		   Escribir num, " es un numero no  par"
	   Fin Si

           FinAlgoritmo
	
	![Diagrama de nuemro par e impar](https://user-images.githubusercontent.com/113545541/191891355-343272f2-8079-4d07-9281-e524198122e1.png)
	
	
	Programa que nos diga si la letra es vocal o no lo es
	
	   1 inicio
           2 declarar vocal "char"
	   3 mostrar "Escribe una letra para saber si es vocal"
	   4 asignar vocal
	   5 en caso de vocal hacer
	   6 en caso de "A" o "a"
	   7 mostrar "Es vocal"
	   10 en caso de "E" o "e"
	   11 mostrar "Es vocal"
	   13 en caso de "I" o "i"
	   14 mostrar "Es vocal"
	   18 en caso de "O" o "o"
	   19 mostrar "Es vocal"
	   20 en caso de "U" o "u"
	   21 mostrar "Es vocal"
	   22 sino
	   23   escribir "No es vocal"
	   24 fin
	   
	   Algoritmo sin_titulo
	   vocal<-" "
	   Escribir "Escribe una letra para saber si es vocal"
	   Leer vocal
	   Segun vocal Hacer
		    "A" o "a":
			    Escribir  vocal, " Es vocal"
		    "E" o "e":
			    Escribir  vocal, " Es vocal"
		    "I" o "i":
			    Escribir  vocal, " Es vocal"
		    "O" o "o":
			    Escribir  vocal, " Es vocal"
		    "U" o "u":
			    Escribir  vocal, " Es vocal"
			    
		De Otro Modo:
			Escribir vocal, " No es vocal"
	   Fin Segun
           FinAlgoritmo
![image](https://user-images.githubusercontent.com/113545541/192600036-0d3e907a-9203-45e6-bf17-bc7a5d72de8d.png)


    Calculadora de indice de peso corporal
    1 incio
    2 declarar nombre " " (char)
    4 peso 0 (float)
    5 altura 0 (float)
    7 imc 0 (float)
    6 mostrar "Hola, cual es tu nombre"
    7 asignar nombre 
    8 mostrar nombre, " Cual es tu peso?"
    9 asignar peso
    10 mostrar nombre, " Cual es tu altura"
    11 imc=peso/altura
    12 segun imc hacer
    13 imc<18.5 "Peso deficiente"
    14 imc=>18.5 o 29.9"Peso correcto"
    15 imc>29.9 " Sobrepeso"
    16 de otro modo
    17 Error de datos
    18 fin
    
    Algoritmo sin_titulo
	nombre<-" "
	peso<-0
	altura<-0
	imc<-0
	Escribir "Hola, ingresa tu nombre"
	Leer nombre
	Escribir nombre, " ingresa tu peso"
	Leer peso
	Escribir "ingresa tu altura"
	Leer altura
	imc<-peso/altura
	
	
	
	Segun imc Hacer
		imc<18.5:
			Escribir imc, " peso indeficiente"
		imc>=24.9 o 29.9: 
			Escribir imc, " peso correcto"
		imc>29.9 o 250:
			escribir imc, " sobrepeso"
		De Otro Modo:
			Escribir "Datos invalidsos"
	Fin Segun

	
     FinAlgoritmo
     
  ![image](https://user-images.githubusercontent.com/113545541/192607286-f0038be9-d3bc-4ac0-bc1f-2e67c595c1bb.png)
  
    
    ciclo (for)
   ![image](https://user-images.githubusercontent.com/113545541/192858153-612eecc0-63b9-4b78-9e99-5b5ff5f5a885.png)

    
    
    
    
    
    
    
    TABLA DE MULTIPLICAR 
  ![image](https://user-images.githubusercontent.com/113545541/192851847-14f45d49-e576-4eb1-88b1-c4a005ad536d.png)
           
    
    Algoritmo sin_titulo
	num<-0
	i<-0
	res<-0
	Escribir "Ingresa la tabla de multiplicar que quieres saber"
	Leer num
	Para i<-0 Hasta 10 Con Paso 1 paso Hacer
		res<-i*num
		Escribir num," x ",i," = ",res
	Fin Para
    FinAlgoritmo
    
    tablas de multiplicar de 1 al 10
    Algoritmo sin_titulo
	j<-0
	i<-0
	res<-0
	
	Para i<-1 Hasta 10 Con Paso 1 paso Hacer
		Para j<-1 Hasta 10 Con Paso 1 paso Hacer
			res<-i*j
			Escribir i," x ",j," = ",res
		Fin Para
	Fin Para
    FinAlgoritmo
    
   ![image](https://user-images.githubusercontent.com/113545541/192857717-2ce72769-a3dc-480d-ae0f-0f2996dd08d9.png)
   
    Programa para calcular la cailificacion de 10 alumnos
    Algoritmo sin_titulo
	nombre<-" "
	cal1<-0
	cal2<-0
	cal3<-0
	cal4<-0
	promedio<-0
	i<-0
	Para i<-1 Hasta 10 Con Paso 1 paso Hacer
	Escribir "Hola, escribe el nombre del alumno"
	Leer nombre
	Escribir "Coloca la primera calificacion del alumno ",nombre
	Leer cal1
	Si cal1>0 y cal1<11 Entonces
		escribir "Coloca la segunda calificacion del alumno ",nombre
		Leer cal2
		Si cal2>0 y cal2<11 Entonces
			escribir "Coloca la tercera calificacion del alumno ",nombre
			Leer cal3
			Si cal3>0 y cal3<11 Entonces
				escribir "Coloca la cuarta calificacion del alumno ",nombre
				Leer cal4
				Si cal4>0 y cal4<11 Entonces
					promedio<-(cal1+cal2+cal3+cal4)/4
					Si promedio>6 Entonces
						escribir" el promedio de ",nombre," es ",promedio," Aprobado"
					SiNo
						escribir" el promedio de ",nombre," es ",promedio," Reprobado"
					Fin Si
				SiNo
					escribir "calificacion invalida"
				Fin Si
			SiNo
				escribir "Calificacion invalida"
			Fin Si
		SiNo
			escribir "Calificacion invalida"
		Fin Si
	SiNo
		escribir "calificacion invalida"
	Fin Si
	Fin Para
    FinAlgoritmo
![Diagrama sin título drawio](https://user-images.githubusercontent.com/113545541/192930346-00e6e822-0815-44c5-b72f-1b5a183a165c.png)

   
   
   
    s
    Algoritmo sin_titulo
		nombre<-" "
		peso<-0
		altura<-0
		imc<-0
		i<-1
		Escribir "Hola, ingresa tu nombre"
		Leer nombre
		Repetir
			Escribir nombre,", ingrese su peso (kg)"
			leer peso
		Hasta Que peso>=30 y peso<=250
		Repetir
			Escribir nombre,", ingrese su altura (mts)"
			leer altura
		Hasta Que altura>=0.50 y altura<=2.60
		imc=peso/(altura*altura)
		Escribir nombre," su IMC es de:",imc
		si (imc<18.5) Entonces
			Escribir "peso inferior al normal"
		SiNo
			si (imc>=18.5 y imc<=24.9) Entonces
				Escribir "Normal"
			SiNo
				si (imc>=25.0 y imc<=30) Entonces
					Escribir "Peso superior al normal"
				SiNo
					Escribir "sobrepeso"
				FinSi
			FinSi		
		FinSi
     FinAlgoritmo

![diagrama para calculo de IMC](https://user-images.githubusercontent.com/113545541/193191855-8df58a90-73ca-4d76-93ee-1ffef58a09c9.png)


    Algoritmo sin_titulo
	num1<-0
	num2<-0
	num3<-0
	Escribir "Coloca el primer numero"
	Leer num1
	Escribir "coloca el segundo numero"
	leer num2 
	Mientras num1=num2 Hacer
		Escribir "Numero repetido"
		Escribir "coloca el segundo numero"
		leer num2
	Fin Mientras
	Escribir "coloca el tercer numero"
	leer num3
	Mientras num2=num3 o num3=num1 Hacer
		Escribir "numero repetido"
		Escribir  "coloca el tercer numero"
		leer num3
	Fin Mientras
	si num1<num2 y num1<num3 Entonces
		si num2<num3
			mostrar num1,num2,num3
		sino mostrar num1,num3,num2
		FinSi
	FinSi
	si num2<num1 y num2<num3 Entonces
		si num1<num3s Entonces
			mostrar num2,num1,num3
			sino mostrar num2,num3,num1
		FinSi
	FinSi
	si num3<num1 y num3<num2 Entonces
		si num1<num2
			Mostrar num3,num1,num2
			sino mostrar num3,num2,num1
		FinSi
	FinSi
    FinAlgoritmo
   ![Programa para detectar de menor a mayor](https://user-images.githubusercontent.com/113545541/193327360-7080d30b-d266-44e3-84af-63db1189cec6.png)


    1 incio 
    2 num1
    3 num2
    4 num3
    5 i
    6 mostrar "Ingresa el primer numero"
    7 asignar num1
    8 mostrar "Ingresa el segundo numero"
    9 asignar num2
    10 mientras num1=num2 entonces 
    11 mostrar "Numero repetidos
    12 mostrar "ingresa el segundo numero"
    13 asignar num2
    14 fin mientras 
    15 mostrar "Ingresa el terer numero"
    16 asignar num3
    17 mientras num3=num2 o num3=num1 entonces
    18 mostrar "Numero repetido"
    19 mostrar "Ingresa el tercer numero"
    20 asignar num3 
    21 mientras num1<num2 y num1<num3 hacer
    21    mostrar num1,num2,num3
    22    mientras num2<num3 hacer 
    23    mostrar num1,num3,num2
    24    fin mientras
    25    mientras num2<num1 y num2<num3 hacer
    26    mostrar num,2,num1,num3
    27    mientras num1<num3 hacer
    28    mostrar num2,num3,num1
    29    fin mientras 
    30    mientras num3<num1 y num3<num1 hacer
    31    mostrar num3,num1,num2
    32    mientras num1<num2 hacer
    33    mostrar num3,num2,num3
    34    fin mientras
    36    i=i+1
    37 fin mientras
    37 fin
    
    Algoritmo para adivina el numero
    
    1 inicio 
    2 num1=0(int)
    3 mum2=27(int)
    4 vidas=5
    5 mostrar "Bienvendo al juego adivina el numero secreto"
    6 Mientras>0 Hacer
    7 mostrar "ingresa el numero"
    8 asignar num1
    9 si num1=num2 entonces
    10 Mostrar "Felicidades, adivinaste el numero secreto"
    11 vidas=0
    12 sino
    13 vidas=vidas-1
    14 si vidas=0 Entonces
    15 mostrar "Has fallado los 5 intentos"
    16 mostrar "El numero secreto es ",num2
    17 sino
    18 mostrar "Has fallado te quedan ",vidas," vidas"
    19 fin si
    20 fin si
    21 fin mientras
    22 fin
    
    

     Algoritmo sin_titulo
	num1<-0
	num2<-27
	vidas=5
	escribir "Bienvenido al juego adivina el numero secreto"
	Mientras vidas>0 Hacer
		Escribir "Ingresa un numero"
		leer num1
		si num1=num2 Entonces
			Escribir "Felicidades, encontraste el numero ",num2
			vidas=0
		SiNo 
			vidas=vidas-1
			si vidas=0 Entonces
				Escribir "Has fallado los 5 intentos"
				Escribir "El numero secreto es ",num2
			SiNo 
				Escribir "Fallaste, te quedan ",vidas," vidas"
				
			FinSi
			
		FinSi
	FinMientras

     FinAlgoritmo
     
   ![diagrama juego Adivina el numero secreto](https://user-images.githubusercontent.com/113545541/193684758-31890451-8cb4-43b0-953f-9bf93c1d4593.png)
   
   
    ejercicio adivina el numero completo
    1 inicio
    2 declarar numsec azar(100)+1
    3 asignar (vidas=7 y numsec azar)
    4 mostrar "Adivina el nnumero secreto"
    5 asignar num
    6 mientras numsec=/num y vidas>0 hacer
    7  si numsec>num
    8    Mostarar "Tu numero es menor al numero secreto"
    9    vidas=vidas-1
    10   mostrar "Adivina el numero secreto ","te quedan ",vidas," vidas"
    11   asignar num}
    12 sino 
    13   mostrar "El numero ingresado es mayor al numero secreto"
    14   vidas=vidas-1
    15   mostrar "Adivina el numero secreto","te quedan ",vidas," vidas
    16 finsi
    17finmientras
    18 si numsec=num 
    19  mostrar "Felicidades el numero secreto es ",numsec
    20 sino
    21  mostrar "Se acabaron las vidas"
    22  mostrar "El numero sereo es ",vidas
    23 finsi
    24fin
    
    
    Seudocodigo
    Algoritmo sin_titulo
	numsec<-azar(100)+1	
	num<-0
	vidas<-7
	Escribir "Adivina el numero secreto"
	Leer num
	Mientras numsec<>num y vidas>0 Hacer 
		si numsec>num
			Escribir "Tu numero es menor al numero secreto"
			vidas=vidas-1
			Escribir "Adivina el numero secreto ","te quedan ",vidas," vidas"
			Leer num
		SiNo
			Escribir "El numero ingresado es mayor al numero secreto"
			vidas=vidas-1
			Escribir "Adivina el numero secreto ","te quedan ",vidas," vidas"
			Leer num
			
		FinSi
	FinMientras
	si numsec=num 
		Escribir "Felicidades, el numero secreto es ",numsec
	SiNo
		Escribir "Se acabaron las vidas"
		Escribir "El numero secreto es ",numsec
	FinSi
    FinAlgoritmo
    
    Diagrama
    
   ![diagrama completo adivina el numero](https://user-images.githubusercontent.com/113545541/193893687-d91d2d2e-b826-4d50-8440-5374c0143e5e.png)
   
   
  CALIFICACION FINAL
  
    Algoritmo sin_titulo
	edad1<-0
	edad2<-0
	edad3<-0
	edad4<-0
	edad5<-0
	prom<-0
	
	Escribir "Ingresa la edad del primier alumno"
	leer edad1
	Escribir "ingresa la edad del segundo alumno"
	leer edad2
	Escribir "Ingresa la edad del tercer alumno"
	leer edad3
	Escribir "Ingresa la edad del cuarto alumno"
	leer edad4
	Escribir "Ingresa la edad del quinto alumno"
	leer edad5
	prom=(edad1+edad2+edad3+edad4+edad5)/5
	
	Escribir "El promedio de edad de los alumnos es ",prom
	
	
    FinAlgoritmo



Funciones dentro de las variables
                     
    d
    Funcion prom<-Promedio(cal1,cal2,cal3)
	p<-(cal1+cal2+cal3)/3
	si p>=6 Entonces
		Escribir alum2," Aprobado"
		Escribir "Tu calificacion es ",p
	SiNo
		Escribir alum2," Reprobado,"
		Escribir "Tu calificacion es ",p
	FinSi
    Fin Funcion

    Algoritmo sin_titulo
	Escribir "ingresa la primera calificacion de codigo"
	leer cal1
	Escribir "ingresa la seguda calificacion de codigo"
	Leer cal2
	Escribir "ingresa la tercera calificacion de codigo"
	Leer cal3

	
	
	Escribir "ingresa la primera calificacion de codigo"
	leer cal4
	Escribir "ingresa la seguda calificacion de codigo"
	Leer cal5
	Escribir "ingresa la tercera calificacion de codigo"
	Leer cal6

	
	Escribir "Estudiante 1:",Promedio(cal1,cal2,cal3)
	Escribir "Estudiante 2:",Promedio(cal4,cal5,cal6)
	
	
     FinAlgoritmo
     
   Segundo ejemplo
     
     
     Funcion subrayar(texto) 
	Escribir Texto
	Para x<--1 Hasta Longitud(texto) Con Paso 1 paso Hacer
		Escribir Sin Saltar "_"
	Fin Para
	Escribir " "
	
     Fin Funcion

     Algoritmo sin_titulo
	
	subrayar("Primer ejemplo")
	
	subrayar("Segundo ejemplo")
	
	subrayar("Tercer Ejemplo  de funciones en psint")
     FinAlgoritmo



    


    
    

    

