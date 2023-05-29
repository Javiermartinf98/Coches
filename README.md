# Coches

Este proyecto consta de una Clase Padre que es Vehiculo, la cual tiene los siguientes atributos:
* **Matricula**
* **Marca**
* **Modelo**
* **potencia**

> Constructor vacio y por defecto
> Getter y Setters
> ToString

A su vez crearemos una Interface a la que llamaremos Conducible, en esta interface
simplemente contendra los metodos que tendremos que desarrollar en las clases Hijas.
Estos metodos son los siguientes: 
* **public void conducir()**
* **public void arrancar()**
* **public int velocidad(int m, int t)**
* **public void avanzar(int avance)**
* **public void parar()**

A continuación creamos la Clase Coche, la cual sera hija, de la clase Padre, heredando los stributos del padre, y a su vez implementara la Interface, con sus metodos.
Los atributos de la Clase Hija unicamente sera:
* **Color**
* **Isarrancar** > Para cambiar el estado segun el coche este encendido o parado

Ya que hereda los atributos del padre.
