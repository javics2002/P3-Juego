# <p align="center">**VROOM VROOM!**</p>
<div align="center">
    <img src="readme_assets/game_logo.png" alt="game_logo" width="969" height="300">
</div>

## <p align="center">**MOTOR ENGINE**</p>
<div align="center">
    <img src="readme_assets/engine_logo.png" alt="engine_logo" width="827" height="400">
</div>

* Javier Cano Salcedo, jacano01@ucm.es 
* José Miguel Villacañas, josemv03@ucm.es 
* Pablo Arredondo Nowak, pablarre@ucm.es
* Rodrigo Cabello Hernández, rodricab@ucm.es
* Alfonso Rodulfo Guío, arodulfo@ucm.es
* Diego Rol Sánchez, drol@ucm.es 
* Pedro Pablo Cubells Talavera, pablocub@ucm.es 
* Liyuan Li, liyli@ucm.es

## <p align="center">**LINKS DE INTERÉS**</p>

<div align="center">
  <a href="https://www.pivotaltracker.com/n/projects/2630589">
    <img src="readme_assets/pivotal_logo.png" alt="Logo_pivotal" width="214" height="80">
  </a>
</div>

## <p align="center">**INFORMACIÓN GENERAL**</p>
Juego de carreras desenfadado para retar a tu amigo.


|**Especificaciones**||
| ------ | ----------- |
| Género: | Carreras, Competitivo |
| Plataforma: | Windows |
| Público objetivo:   | Niños entre 7 y 14 años |
| Modos: | Competitivo local entre 2 jugadores y contrarreloj de 1 jugador |
| Cantidades: | 2 coches, 1 circuito, 3 power-ups. |

|**Hitos**| |
| ------ | ----------- |
| 0. Propuesta del concepto: 13 de febrero de 2023  | 1. Arquitectura base: 6 de marzo de 2023  |
|2. Ciclo de juego: 27 de marzo de 2023 | 3. Release: 5 de mayo de 2023 |

## <p align="center">**PARTIDA TÍPICA**</p>

Los jugadores conectan sus mandos al ordenador o se colocan en posición para usar el teclado a la vez. Pulsan el botón de RACE 2P.\
Una pantalla de carga aparecerá mientras se carga el circuito. Cuando termine la carga aparecerán 2 pantallas, una para jugador en la línea de salida y comienza la cuenta atrás.\
Comienza la partida y compiten entre ellos para ver quién acaba primero 7 vueltas, haciendo uso de objetos para ir más rápido o molestar al oponente.\
Cuando los 2 jugadores llegan a la meta, aparecen los resultados en una tabla que indica quién ha llegado primero su tiempo total y su vuelta más rápida. Al pulsar un botón, vuelven al menú principal.

## <p align="center">**CONTROLES**</p>
El juego soporta teclado y mando.

|**Acción**|**Teclado(J1)**|**Teclado(J2)**|**Mando Xbox**|**DualShock 4**|
| ------ | ------ | ------ | ------ | ------ |
| Acelerar | W | Flecha arriba | A | X |
| Girar a la izquierda | A | Flecha izquierda | Joystick/Dpad | Joystick/Dpad |
| Girar a la derecha | D | Flecha derecha | Joystick/Dpad | Joystick/Dpad |
| Frenar/Marcha atrás | S | Flecha abajo | B | O |
| Derrape | Shift | O |  RB/RT | R1/R2 |
| Usar objeto | Space | P | LB/LT | L1/L2 |
| Pausa | ESC | ESC | Start | Options |

<div align="center">
    <img src="readme_assets/xbox_layout.png" alt="xbox_layout" width="691" height="334">
</div>

## <p align="center">**MECÁNICAS**</p>

### **Circuito**

El circuito es el escenario que recorren los vehículos. Cuentan con una serie de checkpoints para asegurar la correcta vuelta de los jugadores. Hay cajas de objetos repartidas por el escenario, que contienen un power-up, especificados más abajo.

### **Jugadores**

Cada uno de los jugadores manejará un vehículo, con la misma aceleración y una velocidad máxima. El vehiculo del jugador 1 será de color rojo, y de color azul para el coche del jugador 2.\
La cámara se situará en la parte de atrás de cada jugador y le seguirá en todo momento.

### **Power-Ups**

Los power-ups serán bolas rojas que los jugadores podrán recoger durante la carrera. Al ser recogidas, dotan al jugador de un objeto aleatorio, elegido con una ruleta en la interfaz.\
Los jugadores solo podrán llevar un power up a la vez de forma que si coge otro se queda el que tiene actualmente y desaparece el power up del circuito.\
Los jugadores con power-up podrán usarlo en cualquier momento al pulsar el botón de objeto, siempre y cuando no se le haya quitado el control de su vehículo al jugador por la colisión con otro power-up.\
Las bolas desaparecen al ser recogidas y una nueva bola aparece en su misma posición pasados 3 segundos.\


### **Mecánicas de escenario**

Solo habrá un elemento del escenario a tener en cuenta
  * Vallas: rodean el circuito para no salirte de forma que si chocas con ella rebotarás un poco hacia atrás y tendrás que redirigir el coche.
  
  
## <p align="center">**Dinámica**</p>

El tiempo de una carrera será de aproximadamente 2,25 minutos, siendo el tiempo por vuelta de aproximadamente 20 segundos, siempre dependiendo de la actuación de cada jugador.\
En el modo un jugador, el objetivo es superar el último récord establecido, tratando de completar el circuito en el menor tiempo posible, que se guardará entre partidas. \
El juego busca la competición y el inconformismo con uno mismo, de manera que siempre se trate de superarse a uno mismo como su máximo rival.\
En el modo dos jugadores, el objetivo del juego es ganar al rival en la carrera. Como se ha explicado anteriormente, se deben aprovechar los Power Ups y conocimientos del circuito para ser más rápido que el rival. Al final de la partida aparecerá el tiempo por vuelta de cada uno de los jugadores y el ganador.\
El juego busca que los jugadores compitan entre ellos y disfruten de la sensación de velocidad y la competición entre ellos. Dada la estructura del juego, es apto para jugadores competitivos o para “casuals” que solo quieran pasar un buen rato.\

## <p align="center">**Estética**</p>

La estética general del juego está basada en un arte cartoon vectorizada, con una gama de colores saturada y animada. En definitiva, una estética poco agresiva que promueve el aspecto para todos los públicos del juego.\
Habrá dos personajes en sus respectivos coches, iguales en geometría pero con una textura diferenciadora.\
El diseño de sonido consta de una gama de sonidos cartoon, que representan cada una de las acciones realizadas por el jugador, como derrapar, acelerar y usar un objeto. A excepción del motor y las ruedas, que serán los sonidos más realistas.\

## <p align="center">**Contenido**</p>

**2 X Personajes:**
  * **Kart**
  * **Karterine**
  
**2 X Coches**

**1 X Circuito:**

  * **Baby Park:**
    Este circuito tiene forma de 0, tiene amplitud de 8 coches y se completa al darle 7 vueltas. El espacio reducido y la sencillez de este circuito nos proporcionará una gran sensación de frenetismo centrándonos más en coger los power ups para molestar o beneficiarnos.
    
*3 X Power Ups:*
  * **Thunder:**
    Da un impulso a la velocidad del jugador en el momento en el que se activa el power up.
  * **Nerf:**
    Lanza un proyectil hacia delante que hace saltar por los aires al jugador y le quita el control de su movimiento. El proyectil avanza en la dirección del jugador que lo lanza y rebotará 3 veces como máximo luego se destruirá.
  * **Oil:**
    Deja una mancha de radio igual al ancho de 1 coche que, al colisionar con un corredor, lo ralentiza y hace deslizar durante un breve periodo de tiempo, quitando a la vez el control sobre su movimiento. La botella de aceite será lanzada al circuito detrás del coche y se quedará tirada en el suelo hasta que alguien colisione con ella.
    
<div align="center">
    <img src="readme_assets/power_ups.png" alt="power_ups" width="666" height="500">
</div>
    
    
## <p align="center">*UI*</p>

En la parte superior derecha podremos ver el tiempo que tardamos en dar cada vuelta, que se mostrará una vez hayamos cruzado la meta en cada vuelta, además podremos ver el número de vuelta en el que nos encontramos y el número de vueltas totales del nivel. Tendremos en la parte inferior izquierda la posición en la que vamos. En la parte superior izquierda podremos ver el power up que tenemos en nuestro arsenal en caso de que hayamos recogido alguno. 

<div align="center">
    <img src="readme_assets/game_layout.png" alt="layout" width="666" height="500">
</div>

## <p align="center">*Menús*</p>

**Menú principal :**  En el menú principal podremos encontrar distintos botones
 * **1J/2J :**  Al pulsar alguno de estos botones dará comienzo al juego, ya sea al modo “Contrarreloj / Un Jugador” **(1J)** como al modo “Dos jugadores” **(2J)**.
 * **Settings :** Al ser pulsado nos llevará al menú de settings.
 * **Quit :** Este botón cerrará el juego directamente.
 * **Controller info :** Un par de imágenes pequeñas en la esquina inferior derecha muestran el controlador usado por cada jugador. Si hay mandos conectados, se asigna automáticamente al mando. Si solo hay uno, se le da al jugador 1. A falta de mandos, jugarán con teclado.

**Menú de settings :** En este menú encontraremos todas las opciones relacionadas con los ajustes del juego, volumen de la música y sonidos, pantalla completa, etc.

**Menú de pausa :** 
 En este menú encontraremos los siguientes tres botones :
  * **Resume :** En este botón nos devolverá a la partida, en el punto en el que la habíamos dejado.
  * **Settings :** Al igual que el botón del menú principal, este nos llevará al menú de opciones.
  * **Menú principal :** Este botón nos llevará directamente al menú principal, terminando la partida que estábamos jugando.

**Pantalla de carga :** Escena que se usará cuando comienza una partida para cargar todos los recursos del juego, con indicaciones visuales para que el jugador sepa que el juego sigue funcionando correctamente.

**Menú resultados :** En este menú se nos dará toda la información acerca de nuestra partidas, el número de vueltas y el tiempo que hayamos hecho en la vuelta más rápida. Además encontraremos un botón que nos permitirá regresar al menú principal.

<div align="center">
    <img src="readme_assets/title_window.png" alt="title" width="666" height="500">
</div>

El flujo de juego que encontraremos entre los distintos menús y escenas del juego es el descrito a continuación.

```mermaid
stateDiagram
    [*] --> Main_Menu
    Main_Menu -->  Settings
    Settings --> Main_Menu
    Main_Menu --> Game
    Game --> Results
    Results-->Main_Menu
    Game-->Pause
    Pause-->Game
    
    Pause_Settings-->Pause
    Pause-->Pause_Settings
    Pause-->Main_Menu
    Main_Menu-->Exit
  
```

## <p align="center">*UML*</p>

## <p align="center">*QA*</p>

## <p align="center">*Referencias y contexto cultural*</p>
 * Saga Mario Kart
 <div align="center">
    <img src="readme_assets/mariokart.jpg" alt="mario" width="666" height="500">
</div>
 * ModNation Racers
 <div align="center">
    <img src="readme_assets/modnation.jpg" alt="modnation" width="666" height="500">
</div>
 
