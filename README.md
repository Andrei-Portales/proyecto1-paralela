# Proyecto 1 - Programación paralela con OpenMP
#Instrucciones para correrlo
###Instalar el compilador de C++:
```
sudo apt-get install g++
```
###Instalar la biblioteca SDL:
```
sudo apt-get install libsdl2-dev
```
### Como ejecutar el programa secuencial


    gcc main.cpp Circle.cpp Constants.cpp -o main


### Como ejecutar el programa paralelo


    gcc -fopenmp main_par.cpp Circle.cpp Constants.cpp -o main -lSDL2 -lSDL2_image 
## Integrantes
- Andrei Portales
- Randy Venegas
- Sebastián Maldonado
