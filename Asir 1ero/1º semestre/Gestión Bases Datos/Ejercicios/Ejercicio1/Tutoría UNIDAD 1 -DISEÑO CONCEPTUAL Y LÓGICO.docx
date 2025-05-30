-11/03


Ejercicios:


Realizar el Diseño Lógico de una BD (partiendo de un Diseño Conceptual).

Pasos a seguir:

Recopilación de la Información.

Definición de Entidades y Atributos.

Establecimiento de Relaciones.

Implementación del Diseño Lógico.

Normalización.

Tarea por hacer 🡪 Visualización.

Entidades: Representadas por rectángulos.

Atributos: Listados dentro de las entidades.

Relaciones: Dibujadas con líneas que conectan las entidades.

Cardinalidades: Indicadas al lado de las líneas (1, N, etc.).


--> CASO 1:

1):

#Objetivo: Identificar los datos necesarios para gestionar una liga de fútbol.

#Datos necesarios:

  -Equipos: Nombre, ciudad, entrenador, etc.

  -Jugadores: Nombre, posición, edad, equipo al que pertenecen, etc.

  -Partidos: Fecha, equipos que juegan, resultado, lugar, etc.

  -Árbitros: Nombre, licencia, partidos dirigidos.

#Relaciones:

  -Un equipo juegan muchos jugadores.
  
  -Un jugador sólo pertenece equipo.

  -Un partido involucra a dos equipos.

  -Un equipo juega en cada jornada un partido.

  -Un equipo jugará muchos partidos.

  -El mismo árbitro puede haber dirigido muchos partidos.

  -Un partido sólo es dirigido por un árbitro.

--VER EJERCICIO 1: MOD._CONCEPTUAL

2)Definición de entidades y atributos:

·Equipo:

  -Atributos: ID_Equipo (PK), Nombre, Ciudad, Entrenador

·Jugador

  -Atributos: ID_Jugador (PK), Nombre, Posición, Edad, ID_Equipo (FK)

·Partido

  -Atributos: ID_Partido (PK), Fecha, ID_Equipo_Local (FK), ID_Equipo_Visitante (FK), Resultado

·Árbitro

  -Atributos: ID_Árbitro (PK), Nombre, Licencia

--VER EJERCICIO 1: EJEMPLO_2


3)Establecimiento de relaciones:

·Equipo y Jugador: Un equipo tiene muchos jugadores (uno a muchos).

  -Relación: Equipo (1) ----- (N) Jugador

·Partido y Equipo: Un partido involucra a dos equipos (muchos a muchos a través de la relación que se establece en la tabla de Partido).

 -Relación: Equipo (1) ----- (N) Partido (dos relaciones de equipo en la tabla de Partido).

·Árbitro y Partido: Un árbitro puede dirigir muchos partidos (uno a muchos).

 -Relación: Árbitro (1) ----- (N) Partido

--VER MOD. ENTIDAD-RELACION--


4)Normalización:

Aplicar la Primera Forma Normal (1NF): Asegurar que cada columna contenga datos atómicos y que cada fila
sea única.

En este caso, todas las entidades y atributos cumplen con estas formas normales, ya que cada atributo es
dependiente solo de la clave primaria de su entidad.

(M:N) => (1:N) y (1:N)

--VER MOD. LÓGICO (MOD.RELACIONAL 4 y 5)--