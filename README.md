# The Magical Tea Party · Ensayo interactivo

Minijuego para que las niñas ensayen la obra paso a paso: los personajes caminan por el escenario, aparecen los globos de diálogo y suena música de 8 bits.

## Cómo jugar
- Abrir `index.html` en el navegador (doble clic). No necesita instalar nada.
- Avanzar: clic, espacio o →. Retroceder: ←.
- F: pantalla completa. M: música. Teclas 1 a 5: saltar a una escena.
- Modo ensayo: en la pantalla inicial se toca un personaje. Sus líneas aparecen ocultas; la niña la dice en voz alta y al avanzar se muestra para comprobar.

## Publicar en GitHub Pages
1. Crear un repositorio nuevo (por ejemplo `magical-tea-party`) y subir esta carpeta.
2. En el repositorio: Settings > Pages > Source: "Deploy from a branch", rama `main`, carpeta `/ (root)`.
3. El juego queda en `https://<usuario>.github.io/magical-tea-party/`.

## Ajustar el escenario
Al inicio del código (objeto `P`) están las posiciones de la casa de hongo, la mesita, el plato de tiza y los árboles 1 a 4. El libreto completo está en el arreglo `STEPS`: cada elemento es una pulsación de "avanzar", con la acotación (`cap`), el diálogo (`say`) y la pizarra de restas (`math`).
