
Algoritmo sin_titulo
	Definir a Como Entero
	Leer a
	Si a MOD 2 = 0 Entonces
		Escribir "es par"
	SiNo
		Escribir "es impar"
	Fin Si
FinAlgoritmo

Sandra Valderrama
Algoritmo areavol_cilindro_promedioponderado
	
	Escribir "Escribe la altura del cilindro en variable h"
	leer variableh
	
	Escribir "Escribe el radio del cilindro en la variable r"
	leer variabler
	
	areacirculo=variabler*variabler*3.1416
	volumencilindro=areacirculo*variableh
	perimetrocirc=2*3.1416*variabler
	areasuperficiecil=variableh*perimetrocirc
	areacilindro=(areacirculo*2)+(areasuperficiecil)
	
	escribir "el volumen del cilindro es:", volumencilindro
	escribir "el area del cilindro es:", areacilindro
