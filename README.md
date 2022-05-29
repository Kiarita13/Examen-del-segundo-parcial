# Programas en C++ de Barrera Garcia Kiara Domenica
## Información del autor 
- Apellidos y Nombres: Barrera Garcia Kiara Domenica
- Correo de contacto:  kiara.barrera.garcia@utelvt.edu.ec
- Video explicativo acerca de la introducción de la programación:
https://www.youtube.com/watch?v=dAXir7tXT1U

## Programas

### Comparar 2 números 
Con este programa podremos comparar 2 números, y saber cuál número es mayor o si son similares entre sí.

#### Funcionalidad 

1. Nos van a pedir escribir el primer número.

		cout<<"Escriba el primer numero: "<<endl;
		cin>>kg_num1;

2. Despues pide escribir el segundo número.

		cout<<"Escriba el segundo numero: "<<endl;
		cin>>kg_num2;

3. Se compara si los 2 números son iguales.

		if (kg_num1==kg_num2){

4. Se compara si el primer número es mayor que el segundo número.

		else if (kg_num1>kg_num2){

#### Salida

1. Si son iguales nos presenta el siguiente resultado:

		cout<<"Las dos cantidades son iguales"<<endl;
		}

2. En caso de que la comparación sea verdadero nos va a presentar el resultado:

		cout<<kg_num1<<" es mayor que "<<kg_num2<<endl;
		}

3. Caso contrario, presenta el resultado:  

		else{
		cout<<kg_num2<<" es mayor "<<kg_num1<<endl;
		} 

#### Diagrama de Flujo

![BarreraKiara-Compara](https://user-images.githubusercontent.com/101472253/170847271-dc9838e3-8f78-4dd2-a361-948e1fe7bb17.jpg)


================================================
### Suma de varios números
Con el siguiente programa se puede sumar distintas cantidades y obtener un resultado final.

#### Funcionalidad 

1. Nos pide la cantidad de números que queremos sumar.

		cout<<"Escriba la cantidad de numeros que quiere sumar: "<<endl;
		cin>>kg_v;

2. Despues digitamos los numeros respectivo. 

		cout<<"Digite el numero: "<<endl;
		cin>>kg_p;

3. Se suman todos los números.

		kg_k=kg_k+1; 
		kg_j=kg_j+kg_p;

4. Se verifica que la condición sea la correcta.

		while (kg_k<kg_v);

#### Salida

1. Al final, nos presenta: 

		cout<<"Usted ingreso "<<kg_v<<" numeros"<<endl;
		cout<<"Suma total: "<<kg_j<<endl;

#### Diagrama de Flujo

![BarreraKiara-SumaN](https://user-images.githubusercontent.com/101472253/170847751-e9b2d3bc-6d4f-4861-b973-2c8194e19ca5.jpg)


================================================
### Punto de Venta

Con el siguiente programa se puede calcular el valor y total a pagar de varios productos ingresados.

#### Funcionalidad 

1. Escribir la cantidad de productos a ingresar.

		cout<<"Escriba la cantidad de productos que va a ingresar"<<endl;
		cin>>kg_p;

2. Ingresar el monto de compra de los productos.

		cout<<"Ingrese el monto de la compra: "<<kg_j+1<<endl;
		cin>>kg_k;

3. Se realiza la suma de los productos.

		kg_j=kg_j+1;
		kg_b=kg_b+kg_k;

4.  Se comprueba que la condición sea la correcta.

		while (kg_j<kg_p);

5. Escribimos el porcentaje de descuento.

		cout<<"Escriba el descuento deseado: "<<endl;
		cin>>kg_c;

6. Calcular el valor bruto, IVA, descuento y el valor total.

		kg_t=(kg_b*kg_c)/100;
		kg_t1=kg_b-kg_t;
		kg_y=kg_t1*0.12;
		kg_l=(kg_b-kg_t)+kg_y;

#### Salida

1. 	Se presentan los resultados: 

			cout<<"Valor bruto: "<<kg_b<<endl;
			cout<<"Descuento: "<<kg_t<<endl;
			cout<<"IVA: "<<kg_y<<endl;
			cout<<"Valor TOTAL: "<<kg_l<<endl;

#### Diagrama de Flujo

![BarreraKiara-PuntoVenta](https://user-images.githubusercontent.com/101472253/170848201-8edfa3a3-bf89-45ef-b71a-cbe14359e16f.jpg)


================================================
### Calcular Edad

Con este programa se puede calcular la edad de una persona, en días, meses y años.

#### Funcionalidad 

1. Pedimos ingresar la fecha actual en el formato, día, mes y año.

		cout<<"Escriba la fecha actual (día/mes/año): "<<endl;
		cin>>kg_kk>>kg_jj>>kg_yy;

2. Pedimos ingresar la fecha de nacimiento en el formato, día, mes y año..

		cout<<"Escriba su fecha de nacimiento (día/mes/año): "<<endl;
		cin>>kg_cc1>>kg_pp1>>kg_yy1;

3. Sí el día actual es menor que el día de nacimiento, se realiza el siguiente procedimiento; 

		if (kg_kk<kg_cc1){
		kg_kk=kg_kk+30;
		kg_jj=kg_jj-1;
		kg_da=kg_kk-kg_cc1;
		}

4. Caso contrario se resta normalmente:

		else {
		kg_da=kg_kk-kg_cc1;
		}

5. Sí el mes actual es menor que el mes de nacimiento, se realiza el siguiente procedimiento; 

		if (kg_jj<kg_pp1){
		kg_jj=kg_jj+12;
		kg_yy=kg_yy-1;
		kg_la=kg_jj-kg_pp1;
		}

6. Caso contrario se resta normalmente:

		else {
		kg_la=kg_jj-kg_pp1;
		}

7. Se calcula el año.

		kg_ca=kg_yy-kg_yy1;

#### Salida

1. Se presenta com resultado:

		cout<<"Tienes"<<kg_ca<<" años, "<<kg_la<<" meses "<<"y "<<kg_da<<" días."<<endl;

#### Diagrama de Flujo

![BarreraKiara-laedad](https://user-images.githubusercontent.com/101472253/170848744-24dd925b-9f67-4397-8b39-a3b351b339e2.jpg)


================================================
### Cuenta Moneda

En este programa se va a realizar la clasificación de las monedas de 10ctv, 25ctv y 50ctv; asi como el valor total de las monedas ingresadas.

#### Funcionalidad 

1. Ingresar la cantidad de monedas.

		cout<<"Escriba la cantidad de monedas que desea ingresar: "<<endl;
			cin>>kg_n;

2. Escribir el valor de la moneda.

		int num [kg_n];
		cout<<"Escriba el valor de la moneda: "<<endl;

3. Se escribe la funcion del ciclo "for". 

		for (int kg_i=0; kg_i<kg_n; kg_i++)

4.  Se lee la variable y se realiza la suma general.

		cin>>num [kg_i];
		kg_sum=kg_sum+num [kg_i];

5. Se realiza un proceso donde se clasifican las monedas respectivamente. 

		if (num [kg_i]==10){
			kg_sum1=kg_sum1+(num[kg_i]==10);
		}
		else if (num [kg_i]==25){
			kg_sum25=kg_sum25+(num[kg_i]==25);
		}
		else {
			kg_sum50=kg_sum50+(num[kg_i]==50);
		}

#### Salida

1. Para finalizar se imprimen los siguientes resultados:

		cout<<"La cantidad de monedas de 50 ctvs que ingresó fueron: "<<kg_sum50<<endl;
		cout<<"La cantidad de monedas de 25 ctvs que ingresó fueron: "<<kg_sum25<<endl;
		cout<<"La cantidad de monedad de 10 ctvs que ingresó fueron: "<<kg_sum1<<endl;
		cout<<"El total de dinero es: "<<kg_sum<<endl;

#### Diagrama de Flujo

![BarreraKiara-CuentaMoneda](https://user-images.githubusercontent.com/101472253/170849317-5426bd8f-2ccc-413e-bec0-e7ab2324e69d.jpg)


## Indicaciones para descargar y ejecutar los programas:

1. Luego de abrir el Termux , se escribe:

		git clone https://github.com/Kiarita13/Examen-del-segundo-parcial.git

2. Revisamos que se haya descargado correctamente el repositorio, con el comando:

		ls 

3. Para ingresar a un directorio se hace uso del comando:

		 cd Examen-del-segundo-parcial

4. Para revisar la estructura de un programa, se utiliza el comando:

		vim BarreraKiara-Compara.cpp

5. Para salir y guardar, se presiona el "Esc", luego ":wq" y finalmente en "enter":

![image](https://user-images.githubusercontent.com/101405632/170844868-6509dfb6-bca1-4347-a687-f07f8667d0a0.png)

6. Para volverlo ejecutable usamos el comando: 

![image](https://user-images.githubusercontent.com/101472253/170849536-08d5d4dc-1e91-4ac9-9f15-6cf497da3ecf.png)


7.  Para ejecutar un programa se utiliza el comando:

		 ./BarreraKiara-Compara
