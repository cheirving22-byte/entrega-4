# Trabajo Práctico N° 4: Producción de Contenidos con IA

**Estudiante:** GUILLERMO FABIAN DAVILA  
**Marca / Proyecto:** El Sabor de la Masa  

---

## 1. Descripción del Proyecto y Storytelling

Este proyecto integra herramientas avanzadas de IA generativa para crear un contenido de marca automatizado, manteniendo una identidad humana, cálida y profesional que representa la esencia de la cocina tradicional, de mamá y de la nona.

### Storytelling narrado:
"Hace más de 11 años comenzamos un camino inspirado en las recetas de nuestras madres y abuelas. Creemos que el sabor del hogar sigue teniendo un lugar importante en la vida de las personas. Por eso preparamos platos caseros con ingredientes frescos y el mismo cuidado de siempre."

* **Valores de Marca transmitidos:** Tradición, calidez, sabor artesanal, cercanía y calidad familiar.

---

## 2. Desarrollo Técnico y Decisiones

### Generación de Voz (ElevenLabs)
* **Archivo de origen:** `assets/Voz-Joven-Caserito...mp3`
* **Herramienta:** ElevenLabs.
* **Decisión técnica:** Se realizó la clonación de la voz de mi esposa. Elegimos esta opción porque queríamos lograr una identidad única y familiar. El resultado fue excelente, muy natural, amable y cálida, al punto de que varias personas que la escucharon no notaron diferencias con su voz real.

### Generación de Música (Suno v4 / Udio 1.5)
* **Archivo de origen:** `assets/Caserito en la Maza.mp3`
* **Herramienta:** Suno.
* **Prompt utilizado:** Ambient acoustic folk, warm acoustic guitar, soft piano, inspiring, corporate background music, no vocals, emotional, 85 BPM.
* **Justificación:** Se generó una pista instrumental alegre y muy pegadiza que evoca la nostalgia y el calor del hogar, alineándose con una marca gastronómica tradicional.

### Producción de Avatar y Validación Final (HeyGen)
* **Archivo Final:** `output/202606251902 (3).mp4`
* **Herramienta:** HeyGen.
* **Selección del Avatar:** Elegí el avatar de una chef mujer con delantal. Me pareció la mejor forma de representar visualmente los lineamientos del negocio. Además, representa la edad aproximada de mi esposa, quien es la que dirige el emprendimiento.

---

## 3. Desafíos Técnicos y Soluciones

El proceso presentó varios retos debido a la falta de experiencia previa con estas herramientas de IA, lo que hizo el camino muy desafiante paso a paso:
1. **Sincronización en CapCut:** Al unir las piezas en el editor de video, la pista musical de Suno era significativamente más larga que el video del avatar. Con asistencia técnica, aprendí a utilizar la herramienta de división (`Ctrl + B`) y corte preciso sobre la línea de tiempo para lograr que el audio y el video finalizaran exactamente en el mismo segundo.
2. **Curva de aprendizaje:** El traspaso de archivos entre ElevenLabs, Suno y HeyGen requirió paciencia para entender los formatos, pero se resolvió con éxito logrando una entrega completamente fluida.

---

## 4. Estructura del Repositorio

* `/assets`: Contiene los archivos fuente utilizados (el audio de la voz clonada, la pista de música instrumental y la imagen del personaje `foto entrega 4.jpeg`).
* `/output`: Contiene el archivo de video final renderizado con el avatar animado, la voz y la música integradas.
