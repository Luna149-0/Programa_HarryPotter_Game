# Harry Potter Game
Harry Potter es un juego de escritorio inspirado en el universo de Harry Potter, donde los jugadores compiten en emocionantes carreras de escobas voladoras contra un oponente controlado por la computadora.

Durante la carrera, los participantes pueden encontrar premios que aumentan su velocidad u obstáculos que dificultan su avance. El movimiento de los competidores se realiza de forma automática mediante hilos (threads), permitiendo una simulación dinámica y en tiempo real dentro de una interfaz gráfica.

Este proyecto fue desarrollado aplicando conceptos de Programación Orientada a Objetos (POO), estructuras de datos, ciclos e hilos.

Objetivo del Juego

Seleccionar o crear un personaje y competir contra un oponente en una carrera de escobas voladoras hasta llegar a la meta antes que el rival.

Características Principales
Menú Principal

El sistema cuenta con una pantalla inicial que permite:

Iniciar una partida.
Crear un nuevo personaje.
Consultar el Top de Puntajes.
Salir de la aplicación.
Gestión de Personajes

Los jugadores pueden registrar nuevos personajes proporcionando:

Código
Nombre
Casa
Modelo de Escoba

También es posible seleccionar personajes previamente guardados.

 Modelos de Escobas
Escoba	Velocidad	Tiempo de espera
Nimbus 2000	Media	3 segundos
Nimbus 2001	Alta	2 segundos
Saeta de Fuego	Muy Alta	1 segundo

Cada escoba afecta directamente el rendimiento del personaje durante la carrera.

Sistema de Carreras
El jugador compite contra un personaje seleccionado aleatoriamente por la computadora.
Ambos corredores avanzan automáticamente mediante hilos independientes.
La carrera se muestra gráficamente en tiempo real.
Durante el recorrido pueden aparecer eventos especiales:
 Premios
 Obstáculos

Estos eventos modifican el avance de los competidores.

 Top de Puntajes

El sistema almacena los mejores resultados obtenidos por los jugadores para mostrar una clasificación de los mejores corredores.

 Tecnologías Utilizadas
Java
Programación Orientada a Objetos (POO)
Estructuras de Datos
Hilos (Threads)
Interfaz Gráfica (GUI)
 Estructura General del Proyecto
src/
│
├── personajes/
│   ├── Personaje.java
│   └── Escoba.java
│
├── carrera/
│   ├── Carrera.java
│   ├── Competidor.java
│   └── Evento.java
│
├── gui/
│   ├── MenuPrincipal.java
│   ├── CrearPersonaje.java
│   └── VentanaCarrera.java
│
└── Main.java
 Cómo Ejecutar
Clonar el repositorio:
git clone https://github.com/usuario/harry-potter-broom-racing.git
Abrir el proyecto en NetBeans o IntelliJ IDEA.
Compilar el proyecto.
Ejecutar la clase principal:
Main.java
 Conceptos Aplicados
Encapsulamiento
Herencia
Polimorfismo
Manejo de archivos
Colecciones
Programación concurrente con hilos
Interfaces gráficas
- Autor

Proyecto académico desarrollado por Ixchel Panjoj para aplicar conceptos fundamentales de programación en la creación de un videojuego de escritorio inspirado en el mundo de Harry Potter.
