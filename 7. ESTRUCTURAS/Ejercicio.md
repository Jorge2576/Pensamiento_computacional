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


