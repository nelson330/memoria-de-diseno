# Memoria de Diseño — Entrenador de Ojo Clínico

Juego web educativo interactivo estilo "Memoria + Duolingo" diseñado para aspirantes a la carrera de **Diseño Gráfico** y profesionales creativos. Pone a prueba la memoria visual, la agilidad y el "ojo clínico" sobre fundamentos de branding (colores hexadecimales, proporciones de degradados y reconocimiento de jerarquías tipográficas).

Desarrollado para el **Centro Tecnológico Ricardo Morales Avilés — Diriamba (INATEC Tecnológico Nacional)**.

👉 **[Jugar Ahora en GitHub Pages](https://nelson330.github.io/memoria-de-diseno/)**

---

## 🎮 Mecánica del Juego

1. **Fase de Memorización (5 segundos)**:
   - Se muestra una gran tarjeta central con una muestra visual de diseño y su fórmula técnica descriptiva.
   - Una barra superior realiza una cuenta regresiva de 5.0 segundos (puedes pulsar *"¡Ya lo memoricé!"* para avanzar antes).

2. **Fase de Construcción (10 segundos de límite)**:
   - Los datos técnicos desaparecen, manteniendo la muestra visual para contrastar.
   - Tienes **10.0 segundos** para colocar las 4 fichas correctas en las ranuras táctiles.
   - En los últimos 3 segundos se activa una alarma visual y sonora. Si el tiempo expira, pierdes 1 vida.

3. **Evaluación Competitiva Instantánea**:
   - **Sin botón de comprobación**: Al colocar la cuarta ficha, el juego evalúa la combinación de inmediato.
   - **Acierto**: Animación de celebración, confeti 3D, retroalimentación pedagógica y aumento de la racha de aciertos.
   - **Fallo o Tiempo Agotado**: Sacudida táctil, pérdida de 1 vida y regreso a la fase de memorización para recalibrar el ojo clínico.

4. **3 Vidas Compartidas para Todo el Juego**:
   - Cuentas con 3 vidas para todo el recorrido de los 10 niveles (no se recargan entre niveles).
   - Si pierdes las 3 vidas en cualquier momento, es **Game Over** y debes reiniciar desde el nivel 1.

---

## 🎨 Tipos de Desafíos (10 Niveles Progresivos)

- **Color Hexadecimal**: Identificación de valores `#RRGGBB` y sus canales cromáticos. Los últimos niveles incluyen trampas clínicas con variaciones de apenas 1 unidad hexadecimal.
- **Proporción de Degradados**: Estimación porcentual de transiciones armónicas entre dos tonos.
- **Jerarquía Tipográfica**: Reconocimiento de familias tipográficas (Display, Serif, Sans-Serif, Monospace) y escala de puntos (`pt`).

---

## 🛠️ Tecnologías

- **HTML5 / Vanilla JavaScript**: Todo empaquetado en un único archivo autónomo ([index.html](index.html)), sin dependencias de compilación ni backend.
- **Tailwind CSS (CDN)**: Diseño móvil *cozy*, paleta cálida crema/lino y microinteracciones táctiles.
- **Three.js**: Fondo 3D interactivo con formas geométricas flotantes tipo arcilla suave y efectos de partículas de confeti.
- **Web Audio API**: Sintetizador procedural integrado para sonidos orgánicos (marimba, campanas, advertencias de tiempo) sin necesidad de archivos de audio externos.

---

## 🏛️ Créditos

- **Institución**: INATEC — Tecnológico Nacional
- **Sede**: Centro Tecnológico Ricardo Morales Avilés, Diriamba, Carazo, Nicaragua.
- **Autor**: [@nelson330](https://github.com/nelson330)
