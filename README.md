# Trabajo Práctico N° 4: Producción de Contenidos con IA
**Estudiante:** GUILLERMO FABIAN DAVILA  
**Marca / Proyecto:** El Sabor de la Masa  

---

## 📄 1. Descripción del Proyecto y Storytelling
Este proyecto integra herramientas avanzadas de IA generativa para crear un contenido de marca automatizado, manteniendo una identidad humana, cálida y profesional.

* **Storytelling narrado (Máx. 45s):**  
  *"Hace más de once años comenzamos un camino inspirado en las recetas de nuestras madres y abuelas. Creemos que el sabor del hogar sigue teniendo un lugar importante en la vida de las personas. Por eso preparamos platos caseros con ingredientes frescos y el mismo cuidado de siempre."*
* **Valores de Marca transmitidos:** Tradición, calidez, sabor artesanal, cercanía y calidad familiar.

---

## 🛠️ 2. Desarrollo Técnico y Herramientas

### 🎙️ Generación de Voz (ElevenLabs)
* **Archivo de origen:** `assets/audio marian.mp4` (o tu archivo `.mp3`)
* **Herramienta:** ElevenLabs.
* **Proceso:** Se realizó la clonación de una voz autorizada. Se ajustaron manualmente los parámetros de *Stability* (Estabilidad) y *Clarity/Exaggeration* (Claridad/Exageración) en la plataforma para asegurar que la entonación refleje la carga emocional del storytelling, logrando un tono cercano y afectuoso.

### 🎵 Generación de Música (Suno v4 / Udio 1.5)
* **Archivo de origen:** `assets/Caserito en la Maza (1).mp3`
* **Herramienta:** Suno v4 / Udio 1.5.
* **Prompt utilizado:** `Ambient acoustic folk, warm acoustic guitar, soft piano, inspiring, corporate background music, no vocals, emotional, 85 BPM` *(Nota: Si usaste otro prompt, cámbialo por el tuyo)*.
* **Justificación:** Se generó una pieza puramente instrumental que evoca la nostalgia y el calor del hogar, alineándose perfectamente con una marca gastronómica tradicional y sirviendo como fondo ideal.

### 🤖 Producción de Avatar y Validación Final (HeyGen)
* **Archivo Final:** `output/[nombre_de_tu_video].mp4`
* **Herramienta:** HeyGen (Talking Heads).
* **Proceso:** Se importó el personaje principal diseñado previamente en el Módulo 3. Se subió el audio con la voz clonada para generar la animación del avatar.
* **Validación de Entrega:** Se realizó un control de calidad técnico para verificar la perfecta sincronización labial (*lip-sync*). Además, se nivelaron los volúmenes del audio para garantizar que la música instrumental de fondo funcione como acompañamiento y no eclipse la voz principal en ningún momento.

---

## 📁 3. Estructura del Repositorio
* 📁 **`assets/`**: Contiene los archivos fuente y recursos utilizados (el audio de la voz clonada y la pista de música instrumental).
* 📁 **`output/`**: Contiene el archivo de video final renderizado con el avatar animado, la voz y la música integradas.
