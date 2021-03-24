[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=4420251&assignment_repo_type=AssignmentRepo)


Defina la clase Coordenada que tenga dos atributos del tipo float con los valores de x e y
representando un punto del plano cartesiano.
Define una clase Linea con dos atributos: puntoA y puntoB ambos del tipo Coordenada. Son dos
puntos por los que pasa la línea en un espacio de dos dimensiones. La clase dispondrá de los
siguientes métodos:
Linea() Constructor predeterminado que crea una línea con sus dos puntos como (0,0) y (0,0).
Linea(Coordenada, Coordenada) Constructor que recibe como parámetros dos objetos de la clase Punto, que son
utilizados para inicializar los atributos.
mueveDerecha(double) Desplaza la línea a la derecha la distancia que se indique.
mueveIzquierda(double) Desplaza la línea a la izquierda la distancia que se indique.
mueveArriba(double) Desplaza la línea hacia arriba la distancia que se indique.
mueveAbajo(double) Desplaza la línea hacia abajo la distancia que se indique.
Getters y Setters.
toString : que nos permita mostrar la información de la línea de la siguiente forma:
[puntoA,puntoB]. Por ejemplo: [(0.0,0.0),(1.0,1.0)].