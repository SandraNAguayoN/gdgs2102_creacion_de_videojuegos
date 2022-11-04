# Creacion de Videojuegos
<p align="center">
    <img src="https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/blob/main/img/wallpaper.webp" alt="Logo" width=800 height=auto>
      <p align="center">
    Contenido sobre la Creación de Videojuegos y proyecto de Videojuego 3D.
    <br>
    <a href="https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/issues/new?template=bug.md">Report bug</a>
    ·
    <a href="https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/issues/new?template=feature.md&labels=feature">Request feature</a>
  </p>
</p>

### GDGS2102-E

## Contenido
- [Introducción](#introducción)
- [Código Fuente](#código-fuente)
- [Planificación](#planificación)
- [Autores](#autores)
- [Copyright](#copyright)


## Introducción
- Nombre del proyecto: Ali-en casa
- Objetivo. Lograr escapar de la tierra y del espacio exterior esquivando a todos los enemigos que ataquen, recolectando los puntos requeridos para que Ali pueda llegar a su hogar en el planeta Marte.
- Plataforma, Género, Clasificación, Personajes, Escenario.
    - Plataforma: Desktop.
    - Género: Aventura, Space shooter.
    - Clasificación: Clasificación “B”: Contenido para adolescente a partir de 12 años.
    - Personajes: 
        - Jugador principal "Ali" (un alienigena).
        - Humanos (enemigos nivel 1).
        - Naves espaciales (enemigos nivel 2).
    - Escenario: 
        - Bosque (nivel 1).
        - Espacio exterior (nivel 2).
        - Obstaculos Nivel 1 humanos.
        - Obstaculos Nivel 2 naves espaciales y meteoritos.
        - Sonidos al colisionar con algún obstaculo, perder el juego, recolectar un powerup, al disparar, al recolectar puntos, en general durante el juego activo hará musica de fondo con un estilo futurista.
        - Efecto de explosión al colisionar con un obstaculo, efecto de chispa al obtener powerup.
        - El jugador podrá introducir su nombre para poder guardar sus puntuaciones.
        - Guardará la puntuación del jugador y en "My scores" mostrará el historial de las puntuaciones del jugador.
        - Al terminar el juego (Game Over) mostrará que puntaje obtuvo y cual es el mejor puntaje (Best score) que ha tenido de todas las partidas que ha jugado.
- Historia: Un alinigena llamado Ali se encuentra atrapado en la tierra, deberá cruzar el largo del bosque para encontrar su nave mientras sus enemigos los humanos lo persiguen para hacer pruebas cientificas con su cuerpo, una vez que recupere su nave podrá volver al espacio, pero incluso en el espacio sus enemigos acechan, deberá escapar de estos para poder volver a casa que se encuentra en otra lejana galaxia.
- Personajes:
    - Jugador principal "Ali" (un alienigena).
    - Humanos (enemigos nivel 1).
    - Naves espaciales (enemigos nivel 2).
- Reglas de Juego.
    - Nivel 1
        - Terminar el recorrido del nivel sin haber muerto.
        - Recolectar los puntos objetivo antes de que termine el tiempo.
        - Recolectar cierta cantidad de puntos objetivo para pasar al siguiente nivel.
        - Esquivar a los enemigos para no perder vidas.
        - Los puntos se obtienen al recolectar objetos en el escenario.
        - Al chocar con el enemigo, se reduce 1 vida.
        - Al perder las 3 vidas el jugador muere (pierde).
    - Nivel 2
        - Recolectar los puntos objetivo sin haber muerto.
        - Recolectar los puntos objetivo antes de que termine el tiempo.
        - Esquivar disparos de los enemigos para no perder vidas.
        - Al ser disparado por un enemigo se reduce 1 vida.
        - Vencer a los enemigos para obtener puntos.
        - Al perder las 3 vidas el jugador muere (pierde).
        - Al recolectar espera P se activará el powerup de Poder que hará los disparos más grandes y rápidos.
        - Al recolectar espera I se activará el powerup de Inmunidad por 5 segundos ante los ataques de los enemigos.
     - Modos de dificultad
        - Fácil: Rango de generación de enemigos y obstaculos. 3 vidas. 
        - Medio: Rango de generación de enemigos y obstaculos en un valor duplicado del modo fácil. Sólo 2 vidas.
        - Difícil: Rango de generación de enemigos y obstaculos en un valor duplicado del modo medio. Sólo 1 vida.
        - Aún no se define el tiempo contrarreloj pero será estándar para los 3 modos de dificultad.
- Pantallas de Juego.
    - Start game window
        - ![start-game](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/blob/main/img/StartGameWindow.png)
    - Scene level 1
        - ![scene-level-1](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/blob/main/img/SceneLevel1.png)
    - Scene level 2
        - ![scene-level-2](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/blob/main/img/SceneLevel2.png)
    - Choose level
        - ![choose-level](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/blob/main/img/ChooseLevelWindow.png)
    - Choose level difficulty
        - ![choose-difficulty](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/blob/main/img/LevelDifficultyWindow.png)
    - Game over
        - ![game-over](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/blob/main/img/GameOverWindow_v1.png)
    - My Scores (historial de puntuaciones)
        - ![my-scores](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/blob/main/img/MyScoresWindow.png)
        
- Plan de creación de VideoJuego.
    - Tablero Trello: https://trello.com/b/uW79WxxZ/proyecto-juego-ali-en-casa 

## Código Fuente
* Lección 1:
  * > [Unit 1 - Player Control](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Leccion1_U1)
  * > [Challenge 1 - Plane Programming](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Challenge1_Leccion1_U1)
  * > [VIDEO Challenge 1 - Plane Programming Minuto: 00:00-11:53](https://drive.google.com/drive/folders/1vH5zMZLEHAH34E31FUxOEu76fYDgh8ln)
  * > [Lab 1 - Project Design Document](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Lab1_Leccion1_U1)
  * > [Quiz 1](https://drive.google.com/file/d/1bf2LuYpJ2OGdyrws7RVGbuC6HUcVplQK/view?usp=sharing)
  * > [Quiz 1 Perfil](https://drive.google.com/file/d/13oha8Tp3ukM1_UbFSHt7zdCwQUoaeG8X/view?usp=sharing)
* Lección 2:
  * > [Unit 2 - Basic Gameplay](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Leccion2_U1)
  * > [Challenge 2 - Play Fetch](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Challenge2_Leccion2_U1)
  * > [VIDEO Challenge 2 - Play Fetch Minuto: 11:54-32:16](https://drive.google.com/drive/folders/1vH5zMZLEHAH34E31FUxOEu76fYDgh8ln)
  * > [Lab 2 - New Project with Primitives](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Lab2_Leccion2_U1)
  * > [Quiz 2](https://drive.google.com/file/d/1X9mNvEfzjECPtt96ahI5FsAzSuFJZsaw/view?usp=sharing)
  * > [Quiz 2 Perfil](https://drive.google.com/file/d/18ogAU1HoecqzTsOamhDsYP9qt9sa7-69/view?usp=sharing)
* Lección 3:
  * > [Unit 3 - Sound and Effects](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Leccion3_U2)
  * > [Challenge 3 - Balloons, Bombs, & Booleans](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Challenge3_Leccion3_U2)
  * > [VIDEO Challenge 3 - Balloons, Bombs, & Booleans](https://drive.google.com/file/d/1gxvOwceXA2R01EIqMUl0zqqIQs1Ual4u/view?usp=sharing)
  * > [Lab 3 - Player Control](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Lab3_Leccion3_U2)
  * > [Quiz 3](https://drive.google.com/file/d/1zI7WP-7qsBF8djkG1qKnJXP27vwDkxsT/view?usp=sharing)
  * > [Quiz 3 Perfil](https://drive.google.com/file/d/1lGrEyJnUJARG4N7bVVZB7QlQjlF1L-Lg/view?usp=sharing)
* Lección 4:
  * > [Unit 4 - Gameplay Mechanics](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Leccion4_U2)
  * > [Challenge 4 - Soccer Scripting](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Challenge4_Leccion4_U2)
  * > [VIDEO Challenge 4 - Soccer Scripting](https://drive.google.com/file/d/1ArhXwDDNB0KO5NpJ5NTPkZyz__yYtPay/view?usp=share_link)
  * > [Lab 4 - Basic Gameplay](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Lab4_Leccion4_U2)
  * > [Quiz 4](https://drive.google.com/file/d/1zx7u1PZVBFZhCfwNHYLBYT46CC7L-_Aa/view?usp=share_link)
  * > [Quiz 4 Perfil](https://drive.google.com/file/d/1W3eJEySZOPHP9v9oNsC1ILn58cSQIhcY/view?usp=share_link)
* Lección 5:
  * > [Unit 5 - User Interface](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Leccion5_U2)
  * > [Challenge 5 - Whack-a-Food](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Challenge5_Leccion5_U2)
  * > [VIDEO Challenge 5 - Whack-a-Food](https://drive.google.com/file/d/1PDiTUTLEI91MZTCCn83S1HrLza7mY6q_/view?usp=sharing)
  * > [Lab 5 - Swap out your Assets](https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/tree/main/Lab5_Leccion5_U2)
  * > [Quiz 5](https://drive.google.com/file/d/11yLi6w3UlNj7Rba8lWksLoMbeZGCPITY/view?usp=sharing)
  * > [Quiz 5 Perfil](https://drive.google.com/file/d/1I_O_m8cHudlaijhOWEDF6c8Dsezv1ns6/view?usp=sharing)


## VideoJuego
  * Nivel 1
  * > <a href="https://github.com/SandraNAguayoN/gdgs2102_creacion_de_videojuegos/blob/main/Proyecto%20Ali-en-Casa/Nivel1.unitypackage"> Avance 1 </a>
    - Se agrego la escena con el ground (suelo) y el background (fondo), el fondo se va generando y moviendo hacia la izquiera, también se agregó el player (jugador) a la escena y se configuro la forma de salto que tendrá la cual se limitará a un salto cuando se presione la barra espaciadora.
  * Nivel 2
  * > <a href="https://drive.google.com/file/d/1yzeY_UNSh12e3HD_x6Ix9LkvUy3M6oCF/view?usp=share_link"> Avance 1 </a>
    - Se agrego una nave la cual se puede mover usando las flechas del teclado y una imagen de fondo del espacio, también se limito el movimiento de la nave para que no salga del espacio de juego.

## Autores
Aguayo Nuñez Sandra Nohelia & Godínez Torres Juan Ramiro

## Copyright
Derechos Reservados 2022



