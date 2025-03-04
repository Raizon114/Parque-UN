# Parques UN🎲

**Una adaptación digital del clásico juego de mesa "Parques o Parchis", desarrollado en Python con gráficos interactivos en Pygame.**

---

## Descripción

"Parques UN" es una versión digital del  juego de mesa "Parques o parchis". **Este juego permite jugar entre 1 y 4 jugadores**, con mecánicas clásicas como:

- Salida de fichas con un **5** en los dados.
- Captura de fichas enemigas.
- Zonas seguras.
- Recorrido interno antes de la meta.
- Movimiento mediante clics y selección de dados.
- Lanzamiento de dados con BARRA ESPACIADORA

Actualmente, **los bots aún no están implementados al 100%**, por lo que al iniciar el juego, cuando en la consola se pregunte si un equipo jugará automáticamente, **se debe responder "n"**.

---

## Instalación

### **Descarga y extracción del juego**

Para instalar el juego, \*\*se debe extraer el archivo \*\*\`\` en la siguiente dirección:

📂 `C:\Users\HP\Documents`      o      en DOCUMENTOS 📂 (la cual se ubica en Biblioteca).

Es importante respetar esta ruta, ya que el juego busca recursos (imágenes) dentro de esta ubicación.

### **Instalación de paquetes necesarios**

Para ejecutar el juego, necesitas tener **Python** instalado y la librería `pygame`. Si no tienes **Pygame** instalado, puedes hacerlo ejecutando el siguiente comando en la terminal o consola:

```sh
pip install pygame
```

---

## ¿Cómo jugar?

### **Ejecutar el juego**

Para iniciar la partida, ejecuta el archivo \`\` con Python:

```sh
python juego.py
```

Aparecerá un mensaje en la consola pidiendo el número de jugadores.

&#x20;**IMPORTANTE**: Cuando se pregunte si un equipo jugará automáticamente, **se debe responder "n"**, ya que los bots aún no están completamente implementados.

### Jugabilidad

- **Lanzar los dados:** Presiona la **barra espaciadora** para lanzar los dados.
- **Mover fichas:**
  - **Haz clic** en la ficha que deseas mover.
  - **Haz clic** en el dado que tenga el número de movimientos que deseas usar.
- **Condiciones del juego:**
  - Si obtienes un **5**, puedes sacar una ficha de la cárcel.
  - Si tu ficha cae en una casilla ocupada por un enemigo, lo capturas y lo envías a la cárcel.
  - No puedes moverte a una casilla ocupada por **dos fichas del mismo color** (bloqueo).
  - El juego termina cuando un equipo logra llevar **todas sus fichas a la meta**.

&#x20;**Nota:** Aún no hay una interfaz de menú, por lo que el juego se maneja directamente desde la ventana de Pygame y la consola.

---

Hecho por:

- **Olga Escobar Celis**
- **Robinson Bustos Sepulveda**
- **Jeferson Steven Arango Aguilar** 

---
