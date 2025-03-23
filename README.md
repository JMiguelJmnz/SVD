# SVD

Analisis de descomposicion de valores singulares para generar conclusiones de agrupaciones de acuerdo a diversas categorias

Cargamos las librerías esenciales y los datos a utilizar para comenzar
<br>![image](https://github.com/user-attachments/assets/4f7cc0de-0dfe-4924-bcbc-c87916fd3dfa)

<br>![image](https://github.com/user-attachments/assets/697da4ca-6781-4f35-85b1-620513b7833a)
<br>![image](https://github.com/user-attachments/assets/e574b061-ae79-4ed2-b59f-227c5aa804b3)

Creamos series de pandas con información útil para el momento de graficacion
<br>![image](https://github.com/user-attachments/assets/f2877597-b33f-4cb0-a4ec-48d309b07f00)

Obtenemos las matrices y reconstruimos la matriz original para comprobar datos
<br>![image](https://github.com/user-attachments/assets/39f9cd57-ab73-4c60-b027-cb03863851e4)
<br>![image](https://github.com/user-attachments/assets/a118584b-54bd-4f8c-95dd-194926bf8f2c)

Realizamos la reducción a 2 Dimensiones
<br>![image](https://github.com/user-attachments/assets/9748e452-2406-44c3-99a4-54376624c72d)
![image](https://github.com/user-attachments/assets/84f4e0bb-7bcb-4fc7-b218-801151c3988a)

Con estas matrices, obtenemos la matriz transformada de dos dimensiones para poder realizar la graficación
<br>![image](https://github.com/user-attachments/assets/4ebfca85-8d69-48b7-9514-05404398e62c)
![image](https://github.com/user-attachments/assets/b3eb5a5f-a3a2-4a22-abda-d1d2ae20d514)

Esta gráfica resulta muy parecida a la obtenida con el método PCA pero un poco menos clara
<br>Ahora realizamos la reducción a 3 dimensiones y obtenemos la matriz T de 3 dimensiones
<br>![image](https://github.com/user-attachments/assets/22ee55aa-78d5-4df4-8e15-5cc9e9c29509)
![image](https://github.com/user-attachments/assets/1b1d638d-77d7-45fe-9574-25868c05feea)

Cargamos librerías para graficación en 3D y procesamos un poco los datos para la visualización
<br>![image](https://github.com/user-attachments/assets/bda302b1-a52f-475c-96aa-62dde028b563)

Realizamos la graficación
<br>![image](https://github.com/user-attachments/assets/a3218284-0da1-4a79-beb4-5797787e6466)
<br>![image](https://github.com/user-attachments/assets/d0731b1f-ab8c-48ce-8712-334b405b1ac8)

Esta nueva perspectiva nos permite ver cómo ciertos valores que parecían más cercanos resultan estar en grupos diferentes.

Por último graficamos y calculamos los errores
<br>![image](https://github.com/user-attachments/assets/3ccd4c2b-cde6-420d-be8d-82f8bd54b990)
<br>![image](https://github.com/user-attachments/assets/5992ef15-b333-4525-ac97-f859da281210)
<br>![image](https://github.com/user-attachments/assets/7a08a60a-5eb9-4a22-9122-a13d5eb1782a)
<br>![image](https://github.com/user-attachments/assets/f55e7d2b-fd7c-4a9f-85c4-d90782badde0)
<br>![image](https://github.com/user-attachments/assets/78063d38-aad0-416b-ab86-a3e385638ef5)
<br>![image](https://github.com/user-attachments/assets/49378201-e2c5-416c-8871-490c9a04c4b0)

Podemos ver que ciertos valores tiene mayor precisión en 2D y otros en 3D pero de forma general, los valores en 3 dimensiones parecen ser más confiables aunque podríamos utilizar ambas interpretaciones para determinar información valiosa.
