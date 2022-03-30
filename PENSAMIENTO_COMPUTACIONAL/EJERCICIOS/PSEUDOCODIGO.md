
Convierte los siguientes ejercicios realizado durante el taller a pseudocodigo.

1. Realizar un algoritmo y diagrama de flujo de un programa que solicite un número y lo multiplique por 9, mostrando su resultado.

        Algoritmo numero_por_nueve
	        Escribir 'Ingresa un número:'
	        Leer num
	        resultado <- num*9
	        Escribir 'El resultado de multiplicar ',num,' por 9 es: ',resultado
        FinAlgoritmo

  ![image](https://user-images.githubusercontent.com/75552884/160764021-78f78fd2-9ee9-4508-b5b2-9e142509c518.png)


2. Realiza un diagrama de flujo para obtener la suma de diez cantidades, que se soliciten al usuario, mediante la utilización de un ciclo “Mientras”.

	   Algoritmo suma_diez_numeros
		   Leer contador
		   contador <- 1
		   Leer resultado
		   resultado <- 0
		   Mientras contador<=10 Hacer
			   Escribir 'Ingresa un número:'
			   Leer num
			   resultado <- resultado+num
			   Escribir 'La suma de los valores es:',resultado
			   contador <- contador+1
		   FinMientras
	   FinAlgoritmo
	   
	![image](https://user-images.githubusercontent.com/75552884/160764671-23c17f7a-ba49-48ff-b9a1-4176097b1c9d.png)


3. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

		Algoritmo promedio_calf
			Escribir 'Ingresa la calificación del primer periodo'
			Leer calf1
			Escribir 'Ingresa la calificación del segundo periodo'
			Leer calf2
			Escribir 'Ingresa la calificación del tercer periodo'
			Leer calf3
			Escribir 'Ingresa la calificación del cuarto periodo'
			Leer calf4
			promedio <- (calf1+calf2+calf3+calf4)/4
			Si promedio>6 Entonces
				Escribir "Tu promedio es: ", promedio, ". ", '¡Felicidades, aprobaste!'
			SiNo
				Escribir "Tu promedio es:", promedio, ". ", "Reprobado'
			FinSi
		FinAlgoritmo


	![image](https://user-images.githubusercontent.com/75552884/160765643-d2fa6543-e45e-463e-b36b-05197e71fa37.png)

4. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.

		Algoritmo num_par_o_impar
			Escribir 'Ingresa un valor'
			Leer num
			Si num MOD 2=0 Entonces
				Escribir 'El valor ingresado (',num,'), es un número par'
			SiNo
				Escribir 'El valor ingresado (',num,'), es un número impar'
			FinSi
		FinAlgoritmo

	![image](https://user-images.githubusercontent.com/75552884/160765803-278a4e49-0810-4323-b6d7-2d7916e4a6ac.png)


5. Un programa que pida una letra y detecte si es una vocal.




7. Programa que pida 3 números y los muestre en pantalla de menor a mayor.
8. Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.
9. Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.
