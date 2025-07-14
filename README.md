# Repositorio de Conexión al Servidor de Minecraft 1.20.1

Este repositorio contiene todo lo necesario para conectarse correctamente al servidor de Minecraft **1.20.1 con Forge**, incluyendo los mods obligatorios y contenido visual opcional para quienes tengan una PC potente.

Con seguir las instrucciones de este README (y las de los README de las carpetas interiores en caso de ser utilizadas) se va a poder entrar al servidor con Minecraft configurado.

---

## Pasos para la Instalación (‼️)

### 1. Requisitos Previos

- Tener **Java 17** instalado.
  - [Descargar Java 17](https://www.java.com/en/download/manual.jsp) (64 bits).
- Tener **WinRAR** instalado para descomprimir archivos.
  - [Descargar WinRAR](https://www.win-rar.com/start.html?&L=6) (no lo paguen, no es necesario)
- Descargarse este mismo _repositorio_ ([wiki](https://es.wikipedia.org/wiki/Repositorio_(contenido_digital))):
  - Le dan click al botón verde que dice "Code".
  - Le dan click a "Download ZIP"/"Descargar ZIP".
  - Al archivo descargado lo "Extraen".

A partir de este punto, para leer las instrucciones recomiendo usar esta misma página para ir navegando en las carpetas, pero todo lo que es manejo de archivos se va a realizar desde el Explorador de Archivos de Windows.

### 2. Instalar Forge

- Ejecutar el archivo `forge-1.20.1-47.4.0-installer.jar` ubicado en la raiz de la carpeta extraida y elegí la opción **Install client**.

### 3. Instalar los Mods

- Entrar a su carpeta de `.minecraft`. ([mini explicacion](https://youtu.be/XYNdWGJI0Vg?si=e3KWQYHHYuu7C6lL\&t=43) utilizando el launcher de Minecraft para encontrarla)
- **Backup**: si ya tienen una carpeta llamada `mods`, guardarla en otro lugar para no perderlos, que cuando se quiera volver a usarlos se van a tener que volver a poner ahí.
- Copiar el contenido de la carpeta `Mods 1.20.1/` y pegarlo en `.minecraft/mods/`.

### 4. Iniciar Minecraft

- Abrir el launcher de Minecraft.
- Seleccionar la versión `forge-1.20.1-47.4.0`. (\*)
- En la pestaña "Instalaciones" hay que editar el perfil y cambiar los argumentos de JVM para asignarle _al menos_ **4GB de RAM** (gente con 24+GB recomiendo dedicarle 10GB, al resto recomiendo **6GB**): (\*)
  - Ejemplo: `-Xmx6G`
  - [Mini explicación](https://www.youtube.com/clip/UgkxccZbczh97olrcoOc_uja0_PHN1YS4sQX)
- Darle a "Jugar".

(\*) Estos puntos sólo hay que hacerlos la primera vez, ya que quedan guardados.

### 5. Configurar gráficos

Al cargar el juego, recomendamos presetear ciertas configuraciones antes de entrar a cualquier mundo, ya que las mismas pueden tardar mucho estando adentro de uno.
Esto es **principalmente** si su PC no puede correr juegos con los gráficos al tope, sino ni lean esto.

1. Entran a _Opciones_ → _Gráficos_.
2. _Renderizado_ y _Simulación_: Precisan estar en 12 chunks.
3. _Suavizado de mipmap_: **NO** (literalmente, hay que bajarlo a NO).
4. Aceptar.

Puede que haya otras configuraciones a ajustar, pero estas son las que conviene hacer antes de entrar al mundo (en especial la del _mipmap_).

### 6. Conectar al Servidor

- Entrar a "Multijugador" y agregar un nuevo servidor con los siguientes datos:
  - **Nombre:** _Montoto_ (poner un nombre a gusto)
  - Dirección/IP: (revisar el discord)
  - Aceptar.
- Darle doble click a _Montoto_ (el nuevo servidor).

> 🚨 Si el servidor está apagado, no se va a poder conectar, pero ya queda guardado para cuando lo esté.

### 7. Reconfigurar Teclas

Al tener tantos mods hay muchas teclas que se chocan, y configurarlas una por una es un garrón, por lo que armé un archivo de configuración para que no pase y se pueda tener todo ya pre-configurado.

Para hacer esto:
- Primero hay que cerrar el juego si estaba abierto.
- Hacer un backup (por las dudas) de su archivo `.minecraft/options.txt`, ya sea guardarlo en otro lado o renombrarlo a `options_old.txt`.
- Copiar el archivo `options.txt` (de esta carpeta) y pegarlo en su `.minecraft/`, reemplazando el archivo original.
- Si el juego estaba abierto hay que reiniciarlo.

_DISCLAIMER_: Recomiendo hacer esto aunque sea **una vez**, para poder configurar el Chat de Voz (de la siguiente sección), ya que el control original (la tecla `V`) se choca con otros mods.

### 8. Configuración del Chat de Voz (Simple Voice Chat)

Al entrar al mundo hay que configurar el Chat de Voz (una sola vez):
1. Presionar `SHIFT + V` para abrir el menú de configuración del Chat de Voz.
2. Seguir los pasos:
   - Elegir **micrófono** de entrada.
   - Elegir **auriculares o parlantes** de salida.
   - Configurar el modo como **"Activación por voz"**.
   - Ajustar la sensibilidad a gusto.
3. Finalizar.

_DISCLAIMER_: Todas estas configuraciones se pueden actualizar posteriormente al presionar las mismas teclas (`SHIFT + V`).

---

## Extras Visuales (Opcionales)

Para usuarios con PCs potentes, se pueden instalar mejoras visuales. Todo lo necesario está en la carpeta `Extras visuales (Opcionales)`.

---

## Soporte

Cualquier problema, duda o error:

- Preguntale a Alex (experto tech y host del server).
- Preguntale a Martu (experta visual).
- Contactá por el grupo o por mensaje privado.

---

> ✨ Con esto deberían tar ready pa la acción.

