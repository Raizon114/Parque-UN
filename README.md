# Parques UN

**Una adaptacion digital del clasico juego de mesa "Parques o Parchis", desarrollado en Python con graficos interactivos en Pygame.**

---

## Descripcion

"Parques UN" es una version digital del  juego de mesa "Parques o parchis". **Este juego permite jugar entre 1 y 4 jugadores**, con mecanicas clasicas como:

- Salida de fichas con un **5** en los dados.
- Captura de fichas enemigas.
- Zonas seguras.
- Recorrido interno antes de la meta.
- Movimiento mediante clics y seleccion de dados.
- Lanzamiento de dados con BARRA ESPACIADORA

Actualmente, **los bots aun no están implementados al 100%**, por lo que al iniciar el juego, cuando en la consola se pregunte si un equipo jugarq automqticamente, **se debe responder "n"**.

---

## Instalacion

### **Descarga y extraccion del juego**

Para instalar el juego, se debe extraer el archivo `parqueses.rar` en la siguiente direccion:

 `C:\Users\HP\Documents`      o   en   `DOCUMENTOS`  (la cual se ubica en Biblioteca).

Es importante respetar esta ruta, ya que el juego busca recursos (imagenes) dentro de esta ubicacion.

### **Instalacion de paquetes necesarios**

Para ejecutar el juego, necesitas tener **Python** instalado y la libreria `pygame`. Si no tienes **Pygame** instalado, puedes hacerlo ejecutando el siguiente comando en la terminal o consola:

```sh
pip install pygame
```

---

## ¿Como se juega?

### **Ejecutar el juego**

Para iniciar la partida, ejecuta el archivo \`\` con Python:

```sh
python juego.py
```

Aparecera un mensaje en la consola pidiendo el número de jugadores.

**IMPORTANTE**: Cuando se pregunte si un equipo jugara automaticamente, **se debe responder "n"**, ya que los bots aun no están completamente implementados.

### Jugabilidad

- **Lanzar los dados:** Presiona la **barra espaciadora** para lanzar los dados.
- **Mover fichas:**
  - **Haz clic** en la ficha que deseas mover.
  - **Haz clic** en el dado que tenga el numero de movimientos que deseas usar.
- **Condiciones del juego:**
  - Si obtienes un **5**, puedes sacar una ficha de la carcel.
  - Si tu ficha cae en una casilla ocupada por un enemigo, lo capturas y lo envias a la carcel.
  - No puedes moverte a una casilla ocupada por **dos fichas del mismo color** (bloqueo).
  - El juego termina cuando un equipo logra llevar **todas sus fichas a la meta**.

**Nota:** Aun no hay una interfaz de menu, por lo que el juego se maneja directamente desde la ventana de Pygame y la consola.

---

Hecho por:

- **Olga Escobar Celis**
- **Robinson Bustos Sepulveda**
- **Jeferson Steven Arango Aguilar** 

---
