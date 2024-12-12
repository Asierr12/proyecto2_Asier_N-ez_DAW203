# proyecto2_Asier_N-ez_DAW203

## Descripción del Proyecto
Este proyecto es un juego interactivo basado en un tablero de 10x10, donde el jugador controla a un héroe con el objetivo de llegar a un tesoro. El jugador puede ingresar su nombre, lanzarse un dado para determinar cuántas casillas mover, y luego hacer clic en las celdas resaltadas para mover al héroe. El juego también incluye un sistema de récords que guarda el mejor número de tiradas (movimientos) realizados para alcanzar el tesoro.

## Funcionalidades
1. **Ingreso de nombre:**
   - El jugador debe ingresar un nombre válido (al menos 4 caracteres sin números) antes de comenzar a jugar.
   - Si el nombre no es válido, se muestra un mensaje de error.

2. **Inicio del juego:**
   - Una vez validado el nombre, el jugador puede hacer clic en el botón "Jugar" para comenzar la partida.
   - Se genera un tablero de 10x10 donde el héroe comienza en la esquina superior izquierda y el tesoro está en la esquina inferior derecha.

3. **Lanzamiento del dado:**
   - Al hacer clic en "Tirar dado", el jugador obtiene un valor aleatorio entre 1 y 6, que indica cuántas casillas puede mover al héroe en una dirección.
   - Las celdas en las direcciones posibles (arriba, abajo, izquierda, derecha) se resaltan, y el jugador puede hacer clic en una celda resaltada para mover al héroe.

4. **Final del juego:**
   - Si el héroe llega a la celda del tesoro, el juego muestra un mensaje de victoria y desactiva el botón de lanzamiento del dado.

5. **Sistema de récords:**
   - El juego guarda el récord de tiradas en el almacenamiento local del navegador. Si el jugador logra alcanzar el tesoro en menos tiradas que el récord guardado, se establece un nuevo récord.

## Requisitos para Ejecutar el Proyecto
Este proyecto utiliza tecnologías web estándar como HTML, CSS y JavaScript. No requiere ninguna instalación adicional o servidor para funcionar, ya que se ejecuta completamente en el navegador.

## Pasos para Ejecutar el Proyecto
1. **Descargar o Clonar el Proyecto:**
   - Puedes clonar el proyecto desde un repositorio de GitHub o simplemente descargar los archivos del proyecto.

   ```bash
   git clone <URL del repositorio>
