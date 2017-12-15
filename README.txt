
Requisitos para correr el programa:
-Python version 3.5 en adelante
-Windows 8,10 64 bits
-Instalar tensorflow y scikit-learn
	pip install tensorflow
	pip install -U scikit-learn


Luego de tener los requisitos 
El programa hace uso de un corpus para funcionar es por ello que se debera agregar uno para hacer uso del programa.Para
ello simplemente agregamos el corpus que deseamos en corpus.txt. En este caso usamos 3 corpus que se encuentran en corpus1.txt,corpus2.txt,
corpus3.txt si desea usarlos borre el contenido de corpus.txt y copie el contenido del corpus que desee usar.
Si el corpus es muy grande modificar el archivo de codigo word2vec_tftut.py y disminuir el valor de la variable n_iters, esto es importante debido
a que sino demorara mucho en genarse el resultado.

El archivo corpus.txt siempre tiene que estar en la misma carpeta que el archivo word2vec_tftut.py

Para empezar ha ejecutar el programa escriba: python word2vec_tftut.py 
El resultado demorara en aparecer debido a la cantidad de procesos a ejecutar 
Al final saldra un grafico con los resultados
