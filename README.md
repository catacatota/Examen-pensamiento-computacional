# Examen-pensamiento-computacional
Sistema visual interactivo avanzado en p5.js

[link](https://editor.p5js.org/Cataaa/sketches/mr_CHW91Z) editable de p5.js

[link](https://editor.p5js.org/Cataaa/full/mr_CHW91Z) solo para visualizar
nombre de la obra: Resonancia Orbital
___

# ¿Qué es?

- A partir de la base de la solemne 2, quise proponer una breve interacción con pantalla de inicio, interactividad y pantalla de menú. Para personalizarlo se agregó una tipografía (Rammetto One) y un gif. El propósito era buscar una forma de evolucionar la anterior propuesta y hacerlo más interactivo para el usuario, pero sin perder la propuesta inicial.

# Proceso

## - Primero comenzé agregando las variables let, con estado, espacio, fondoIntro y las variables para el fondo, el relleno de los círculos y los bordes de los círculos.

- estado: define las etapas de la pantalla (pantala de inicio, pantalla interactiva y pantalla menú).
- espacio: define los espacios para las columnas y las filas.
- fondoIntro: define el gif usado para la pantalla de inicio y de menú
- las siguientes son variables que definen los colores R, G, B del fondo, el relleno de los círculos y los bordes.

  <img width="1506" height="776" alt="image" src="https://github.com/user-attachments/assets/daaf17f1-c05d-442d-a277-ea65c1554527" />



## - Luego puse las funciones para el gif de la intro, el canvas y para definir el orden de los estados ( 0 = intro, 1 = juegoDeCirculos, 2 = final)
<img width="1154" height="962" alt="image" src="https://github.com/user-attachments/assets/c226e0bc-d7d7-4efd-8775-c6374c2c740e" />



# - Después hice una función para hacer la intro, juegoDeCirculos (base: la segunda solemne) y el final (menú)

<img width="1160" height="866" alt="image" src="https://github.com/user-attachments/assets/4ac50c68-f9bb-41a3-b3c0-3aa375efbb73" />
<img width="1366" height="882" alt="image" src="https://github.com/user-attachments/assets/b3e6216c-56fe-4369-9335-6a5cc06fbb70" />

# - Por último apliqué la función keyPressed. 
- Significa que se ejecuta algo cuando apretas un botón. Con esta función definí los cambios de estado, osea cuando estoy en el estado 1 (Intro) y necesito que cambie al siguiente estado, apreto la tecla enter. Lo mismo con las siguientes funciones. 
también utilicé esta función para poder cambiar los colores del fondo, el relleno de los círculos y los bordes dependiendo del botón.
<img width="1060" height="1090" alt="image" src="https://github.com/user-attachments/assets/fd201ed8-e6af-44ba-a367-c7c714c6505f" />
<img width="1288" height="1146" alt="image" src="https://github.com/user-attachments/assets/142b6d1f-d962-4fce-aba3-eb05c1fc1687" />


# - Sobre la tipografía: 
- Para poder poner una tipografía, se tiene que sacar el link de la tipografía (yo usé google fonts) y pegarla en index.html, al lado de head.
<img width="1122" height="410" alt="image" src="https://github.com/user-attachments/assets/41973070-4e08-443b-8f29-22f62f99277f" />

Devuelta al sketch, arriba del texto se pone "textFont()" y se escribe el título de la fuente.
<img width="940" height="180" alt="image" src="https://github.com/user-attachments/assets/778833aa-257b-4d89-aec2-5c2c9af4239e" />




## Inputs y Outputs
# Inputs
- Posición del mouse *(mouseX y mouseY)*
- Clic del mouse *(mouseIsPressed)*
- las teclas *(ENTER, F, C, S, Esc, r.)*

# Outputs
- El gif de fondo *(image)*
- Textos *(text)*
- El color de fondo *(background)*
- los círculos *(ellipse)*
- El color de los círculos *(fill)*
- El color del borde *(stroke)*
- El grosor del borde (que varía) *(strokeWeight)*


## Diagrama de lujo
[link](https://www.canva.com/design/DAHNp91l9B0/SzZktwPrTB5XcElRUJh6NQ/edit?ui=eyJFIjp7IkE_IjoiQSIsIkEiOiJGbG93Y2hhcnQifX0)
  <img width="1920" height="1080" alt="Flowchart Whiteboard in Bright Green Lime Green Pink Corporate Neon Style" src="https://github.com/user-attachments/assets/2aff2d99-4d71-4e5b-9840-d4b8ed175435" />

# Autora: Catalina San Martín
