Algoritmo Problema_3_4

	acum<-0
	i<-0
	num<-0
	help<-0
	
	Para i<-100 Hasta 999 Con Paso 1
		help<-i
		acum<-0
		Para num<-1 Hasta 3 Con Paso 1
			acum<-acum+((help mod 10)^2)
			help<-trunc(help/10)
		FinPara
		Escribir "El numero ", i, " tiene ", acum, " VS ", trunc(i/3)
		Si acum==(trunc(i/3)) Entonces
			Escribir i, "IGUALES"
		FinSi
	FinPara
	
FinAlgoritmo
