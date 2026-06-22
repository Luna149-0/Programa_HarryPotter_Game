# Harry Potter Game

# Harry Potter Broom Racing

## Descripción

Harry Potter Broom Racing es un juego de escritorio inspirado en el universo de Harry Potter, donde los jugadores participan en carreras de escobas voladoras contra un oponente controlado por la computadora.

Durante la carrera, los competidores pueden encontrar premios y obstáculos que afectan su rendimiento. El movimiento de los corredores se realiza mediante hilos independientes, permitiendo una simulación dinámica en tiempo real dentro de una interfaz gráfica.

Este proyecto fue desarrollado aplicando conceptos de Programación Orientada a Objetos (POO), estructuras de datos, ciclos y programación concurrente.

---

## Objetivo

Permitir al jugador seleccionar o crear un personaje y competir en una carrera de escobas voladoras contra un oponente generado aleatoriamente, llegando a la meta antes que su rival.

---

## Funcionalidades

### Menú Principal

La aplicación cuenta con una pantalla principal que permite:

* Iniciar una partida.
* Crear un nuevo personaje.
* Consultar el top de puntajes.
* Salir de la aplicación.

### Gestión de Personajes

Los usuarios pueden registrar nuevos personajes proporcionando:

* Código
* Nombre
* Casa
* Modelo de escoba

También es posible seleccionar personajes previamente registrados.

### Modelos de Escobas

| Modelo         | Velocidad | Tiempo de espera |
| -------------- | --------- | ---------------- |
| Nimbus 2000    | Media     | 3 segundos       |
| Nimbus 2001    | Alta      | 2 segundos       |
| Saeta de Fuego | Muy alta  | 1 segundo        |

Cada modelo influye directamente en la velocidad de avance durante la carrera.

### Sistema de Carreras

* El jugador compite contra un personaje seleccionado aleatoriamente por la computadora.
* Cada competidor se ejecuta mediante un hilo independiente.
* La carrera se visualiza en una interfaz gráfica en tiempo real.
* Durante el recorrido pueden aparecer premios y obstáculos que modifican el avance de los participantes.

### Top de Puntajes

El sistema almacena los mejores resultados obtenidos por los jugadores para generar una clasificación de los competidores con mejor desempeño.

---

## Tecnologías Utilizadas

* Java
* Programación Orientada a Objetos
* Hilos (Threads)
* Estructuras de Datos
* Interfaz Gráfica de Usuario (GUI)
* Manejo de Archivos

---

## Estructura General

```text
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
```

---

## Cómo Ejecutar

1. Clonar el repositorio:

```bash
git clone https://github.com/usuario/harry-potter-broom-racing.git
```

2. Abrir el proyecto en NetBeans, IntelliJ IDEA o el entorno de desarrollo de su preferencia.

3. Compilar el proyecto.

4. Ejecutar la clase principal `Main.java`.

---

## Conceptos Aplicados

* Encapsulamiento
* Herencia
* Polimorfismo
* Colecciones
* Manejo de archivos
* Programación concurrente
* Interfaces gráficas

---

## Autor
Ixchel Panjoj

Proyecto académico desarrollado como parte de mi formación en Ingeniería en Ciencias y Sistemas, aplicando conceptos fundamentales de programación para la construcción de un videojuego de escritorio inspirado en el universo de Harry Potter.

