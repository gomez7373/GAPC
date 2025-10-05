<p align="center">
  <img src="https://raw.githubusercontent.com/gomez7373/GAPC/main/GAPC.png" alt="GAPC Logo" width="600">
</p>



# ✝️ GAPC – Ganando Almas para Cristo

**GAPC (Ganando Almas para Cristo)** es una aplicación interactiva creada con el propósito de ayudar a las personas a **entender la Biblia en su contexto histórico, cultural y espiritual**, de manera clara, dinámica y visual.

Este proyecto busca **inspirar, educar y despertar entendimiento**, eliminando confusiones causadas por interpretaciones fuera de contexto. ** GAPC no reemplaza la Biblia **.

---

## 🌟 Visión Central
> **GAPC será una experiencia digital inspirada por Dios**, que combine historia, arqueología y fe viva, ayudando a las personas a redescubrir el poder y la belleza de la Palabra en su contexto original.

El objetivo es que **nadie más se aleje del Reino de Dios por falta de entendimiento**.

---

## 💡 Objetivos del Proyecto

- Enseñar el **contexto histórico y cultural** detrás de los pasajes bíblicos.  
- Unir **historia + arqueología + fe**, en una experiencia interactiva.  
- Romper mitos y errores de traducción que han causado confusión.  
- Transformar el estudio bíblico en algo **emocionante, visual y dinámico**.  
- Inspirar a todas las edades a acercarse a la Palabra con claridad y amor.

---

## 🧩 Concepto Interactivo

### 🌍 1. Mapa de la Biblia Viva
Un mapa 3D o pergamino interactivo donde cada **libro bíblico** aparece como una región.

- Al seleccionar “Mateo”, se despliega su **contexto histórico** (Roma, Palestina, personajes, idioma, cultura).  
- Incluye ilustraciones, artefactos y costumbres representadas visualmente.

---

### 📜 2. Versículo con Contexto
Cada versículo se presenta con tres niveles de profundidad:

1. **Texto original** (hebreo, griego o arameo con transliteración simple).  
2. **Explicación cultural e histórica** (costumbres, significados, geografía).  
3. **Mensaje espiritual actual:** cómo aplicar su sabiduría hoy.

El propósito es que el usuario comprenda la **intención y el contexto original** de cada palabra,  
reconociendo su significado más allá de la traducción literal.

---

### 🧠 3. Misiones de Entendimiento
Pequeños retos interactivos que promueven reflexión y curiosidad:
 
- “Aprende por qué Jesús usaba parábolas según la cultura de su tiempo.”

**Gamificación ligera**, centrada en el aprendizaje y la revelación, no en competir.

---

### 🎧 4. Guía Inspirada
Una voz suave o mentor narrativo guía al usuario mientras lee:
> “Aquí Jesús hablaba a pescadores que entendían el esfuerzo y la fe diaria…”

Modo accesible con **narración de texto y música instrumental cristiana suave** (lo-fi, ambient, etc.).

---

### 🕯️ 5. Modo Luz
Cada comprensión desbloquea “luz espiritual” — un reflejo del crecimiento interior.  
No es una puntuación, sino una **representación visual de la sabiduría adquirida.**

---

## 📘 Ejemplo de Módulo: “El Ojo de la Aguja”

**Versículo:** Mateo 19:24  
> “Es más fácil que un camello entre por el ojo de una aguja, que un rico entre en el reino de los cielos.”

**Experiencia Interactiva:**
- Animación muestra el camello arrodillándose para pasar por una pequeña puerta.  
- Texto explica la costumbre cultural, el simbolismo de la humildad y el poner a Dios primero.  
- Reflexión práctica: *“¿Qué significa arrodillar tu corazón y poner a Dios en orimer lugar?”*

---

## 🛠️ Desarrollo Técnico

**Motor:** Unity (versión 2022.3 LTS o superior)  
**Lenguaje:** C#  
**Plataformas:** Android, iOS, WebGL  
**Diseño:** Procreate / Blender (para arte visual)  
**Audio:** Audacity + Bensound / Free Music Archive  

**Fuentes de datos:**
- Biblias con traducciones de licencia abierta.  
- Fuentes académicas y arqueológicas sobre historia bíblica.  
- APIs opcionales para integración de texto o narración.

---

## 🧭 Estructura Base del Proyecto

```
GAPC/
│
├── Assets/
│   ├── Scenes/
│   │   ├── MainMenu.unity
│   │   ├── BibleMap.unity
│   │   └── VersesContext.unity
│   ├── Scripts/
│   │   ├── VerseManager.cs
│   │   ├── ContextInfo.cs
│   │   ├── AudioNarrator.cs
│   │   └── LightProgress.cs
│   ├── UI/
│   │   ├── Menus/
│   │   ├── Buttons/
│   │   └── TextBoxes/
│   └── Resources/
│       ├── HistoricalData/
│       ├── Audio/
│       └── Illustrations/
│
├── Documentation/
│   └── README.md
│
└── Builds/
    ├── Android/
    ├── iOS/
    └── WebGL/
```

---

## 🌍 Futuras Funciones

- 📜 **Modo Histórico-Contextual**
  
  *Explora la Biblia de manera histórica, comprendiendo cada evento dentro de su cultura, época y propósito divino.*

- 🕊️ **Tipos de Estudios Bíblicos Integrados en GAPC**

  **1. Estudio Bíblico Contextual:** <br>
       Busca comprender el mensaje de la Biblia dentro de su tiempo, cultura, idioma original y propósito histórico.

  **2. Exégesis Bíblica:** <br>
       Analiza en profundidad el texto para descubrir su significado original según el autor, el idioma y el contexto.

  **3. Hermenéutica Bíblica:** <br>
       Interpreta correctamente la Palabra para aplicarla con sabiduría y relevancia en la vida actual.

  **4. Estudio Histórico-Cultural:** <br>
       Explora las costumbres, leyes, lugares y tradiciones que dan vida y contexto al mensaje bíblico.

  **5. Teología Bíblica:** <br>
       Revela cómo Dios se manifiesta progresivamente a lo largo de toda la Biblia como una historia unificada de redención.

  **6. Estudio Devocional:** <br>
       Invita a una conexión personal con Dios, aplicando cada enseñanza para el crecimiento espiritual diario.

  **7. Estudio Temático:** <br>
       Reúne versículos y enseñanzas sobre un mismo tema para entender la visión completa de Dios sobre ese asunto.
        
- 🕊️ **Modo Comunidad:** compartir reflexiones, preguntas y descubrimientos.  
- 🔊 **Modo Voz:** narraciones dramatizadas de pasajes históricos.  
- 🎯 **Modo Infantil:** lenguaje simple con minijuegos educativos.

---

## 💎 Impacto Espiritual

- Ayudar a las personas a **amar la Palabra de Dios desde el entendimiento.**  
- Sanar malinterpretaciones que generaron miedo o confusión.  
- Conectar generaciones con el mensaje eterno del amor divino.  
- **Ganar almas no por obligación, sino por revelación del Dios vivo.**

 📖 **Marcos 16:15 (RVR1960)**

 - “Y les dijo: Id por todo el mundo y predicad el evangelio a toda criatura.”

---

## 🙏 Créditos y Agradecimientos

**Fundadora y Diseñadora del Proyecto:** Sheila Gómez Cubero (SGC)  
**Inspiración:** La Gracia de Dios 💫  
**Desarrollo Técnico:** Unity + C#  
**Arte y Diseño:** Procreate 
**Misión:** Enseñar, inspirar y ganar almas a través del conocimiento y la verdad.

---
## ✝️ “Para que todos sean uno — La oración de Jesús que inspira GAPC (Juan 17:20–23)”

> **20** Mas no ruego solamente por éstos, sino también por los que han de creer en mí por la palabra de ellos,  
> **21** para que todos sean uno; como tú, oh Padre, en mí, y yo en ti, que también ellos sean uno en nosotros; para que el mundo crea que tú me enviaste.  
> **22** La gloria que me diste, yo les he dado, para que sean uno, así como nosotros somos uno.  
> **23** Yo en ellos, y tú en mí, para que sean perfectos en unidad, para que el mundo conozca que tú me enviaste, y que los has amado a ellos como también a mí me has amado.  

---

## 💬 En Palabras Sencillas

Jesús está diciendo:

> “Padre, no oro solo por mis discípulos que están aquí conmigo,  
> sino también por todos los que creerán en mí por medio de su mensaje,  
> para que sean uno, así como tú y yo somos uno.”

---

## 🌟 Significado Espiritual

- Jesús oró **no solo por sus discípulos**, sino por **todas las generaciones futuras de creyentes** — tú, yo, y todos los que algún día creerían.  
- Su deseo fue una **unidad espiritual**, no uniformidad: una comunión basada en amor, verdad y propósito divino.  
- La **unidad de los creyentes** es el testimonio más poderoso para que el mundo crea que Jesús fue enviado por el Padre.  

---

> ✨ *“Que todos sean uno, así como Tú, Padre, en mí, y yo en Ti.”*  
> — *Juan 17:21*

---
## 🕊️ Versículo Inspirador

> “Mi pueblo fue destruido porque le faltó conocimiento.”  
> — Oseas 4:6

---

## 📖 Biblias incluidas en GAPC

Estas versiones están integradas directamente en este repositorio para uso educativo y espiritual,  
respetando las licencias de sus textos fuente.

### 🇪🇸 Versión Biblia Libre (Español)
📘 [Descargar Biblia Libre – Español (PDF)](https://github.com/gomez7373/GAPC/raw/main/spavbl_all.pdf)  
🔗 Fuente original: [https://ebible.org/pdf/spavbl/](https://ebible.org/pdf/spavbl/)  
📜 Licencia: © 2018–2020 Jonathan Gallagher y Shelly Barrios de Ávila — *Licencia Creative Commons (uso educativo permitido)*  


---

### 🇬🇧 World English Bible (Inglés)
📘 [Download World English Bible – English (PDF)](https://github.com/gomez7373/GAPC/raw/main/eng-web_all.pdf)  
🔗 Official source: [https://ebible.org/pdf/eng-web/](https://ebible.org/pdf/eng-web/)  
📜 License: *Public Domain* (may be freely copied and distributed)  

---

## 📬 Contacto Oficial

Para más información, colaboración o contacto con el equipo creativo de GAPC,  
puedes visitar el sitio oficial del proyecto:

🌐 **[https://brand.site/gapc/contact](https://brand.site/gapc/contact)**

---

##📜 Licencia

Este documento puede **compartirse y adaptarse únicamente con fines educativos y evangelísticos no comerciales**, bajo estas condiciones:

- **Atribución obligatoria:** menciona a *Sheila Gómez Cubero (SGC)* y enlaza a este repositorio.  
  Ej.: “Contenido adaptado de GAPC por Sheila Gómez Cubero (SGC) — [https://github.com/gomez7373/GAPC](https://github.com/gomez7373/GAPC)
- **Indicar cambios:** señala claramente si realizas modificaciones y **no** distorsiones el sentido del mensaje.
- **Mantener el propósito e integridad:** no utilices este contenido para fines contrarios a **“Ganar almas para Cristo a través del entendimiento.”**
- **Compartir igual (ShareAlike):** cualquier obra derivada debe distribuirse **bajo los mismos términos**.
- **Prohibido uso comercial:** no se permite vender, monetizar o integrar en productos comerciales sin autorización escrita.
- **Protección del arte y recursos visuales:** el logo, ilustraciones, diseños, audios y demás recursos gráficos son **propiedad de Sheila Gomez Cubero**; queda **prohibida** su copia o reutilización sin permiso por escrito.

Para permisos especiales (comerciales o distintos a los anteriores): **sgcartgal@gmail.com**  
© 2025 Sheila Gómez Cubero (SGC). *Todos los derechos reservados sobre arte y recursos visuales.*

