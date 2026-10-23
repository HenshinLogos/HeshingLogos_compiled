# 📖 Guía de Usuario — HenshinLogos

**HenshinLogos** es una aplicación de escritorio para el estudio bíblico avanzado: leer la Biblia en múltiples versiones, consultar comentarios y diccionarios, buscar con precisión, crear y proyectar presentaciones, y organizar tu trabajo de estudio.

> **Nota sobre el idioma de las citas:** para navegar, el programa reconoce los nombres de los libros en **español o inglés** (`Génesis 1:1`, `Genesis 1:1`, `gen 1:1`, `Gn 1:1`). El texto bíblico que leas puede estar en cualquier idioma, según el módulo que tengas instalado.

---

## 📑 Índice

1. [Instalación y primer arranque](#-1-instalación-y-primer-arranque)
2. [La ventana principal](#-2-la-ventana-principal)
3. [Leer la Biblia](#-3-leer-la-biblia)
4. [El launcher: todas las herramientas](#-4-el-launcher-todas-las-herramientas)
5. [Buscador avanzado](#-5-buscador-avanzado)
6. [Panel de comentarios](#-6-panel-de-comentarios)
7. [Panel de diccionarios](#-7-panel-de-diccionarios)
8. [Comparar y cotejar](#-8-comparar-y-cotejar)
9. [Marcadores e historial](#-9-marcadores-e-historial)
10. [Anotaciones y diario](#-10-anotaciones-y-diario)
11. [Presentaciones y visores](#-11-presentaciones-y-visores)
12. [Recursos de estudio](#-12-recursos-de-estudio)
13. [Apariencia y configuración](#-13-apariencia-y-configuración)
14. [Idioma de la interfaz](#-14-idioma-de-la-interfaz)
15. [Crear módulos con LogosBuilder](#-15-crear-módulos-con-logosbuilder)
16. [Versículo del Día](#-16-versículo-del-día)
17. [Solución de problemas](#-17-solución-de-problemas)

---

## 📥 1. Instalación y primer arranque

1. Ejecuta `HenshinLogos.exe`.
2. En el primer arranque la aplicación crea automáticamente la carpeta `assets/`:

| Carpeta | Contenido | Extensión |
|---------|-----------|-----------|
| `assets/bibles/` | Módulos bíblicos | `.bbl.mybible` |
| `assets/commentaries/` | Comentarios | `.cmt.mybible` |
| `assets/dictionaries/` | Diccionarios | `.dct.mybible` |
| `assets/presentations/` | Presentaciones del Expositor | `.pptx`, `.pdf` |
| `assets/mydata/` | Módulos personalizados y notas | `.mybible` |

Las bases de datos usan el formato **MySword**, compatible con otras herramientas del ecosistema.

---

## 🖥️ 2. La ventana principal

| Panel | Posición | Función |
|-------|----------|---------|
| **Biblia** | Izquierda | Lectura de la Escritura, con navegación por libro, capítulo y versículo. |
| **Comentarios** | Centro | Comentarios exegéticos vinculados al pasaje actual. |
| **Diccionarios** | Derecha | Definiciones de palabras hebreas, griegas y términos teológicos. |

### Barra de título
- **← →** — avanzar y retroceder entre las citas visitadas.
- La ventana **no tiene bordes de sistema**: se arrastra desde la barra de título.

### Distribución de paneles (☰⁝ → Distribución de Paneles)
- **📖 Solo Biblia** — ocupa toda la pantalla.
- **📖📝 Biblia + Comentarios** — pantalla dividida en dos.
- **📖📝📚 Los 3 paneles** — vista completa (opción por defecto).

> Cada panel tiene un botón de **📌 expandir/contraer** en su esquina superior derecha. Al cambiar de versículo, los paneles vuelven a la vista normal automáticamente.

---

## 📜 3. Leer la Biblia

### Escribir una cita directamente
En el cuadro de búsqueda del panel bíblico, escribe la referencia y pulsa **Enter**:

```
Juan 3:16
1 Corintios 13:1-5
Salmos 23
Apocalipsis 1
```

**Formatos válidos:**

| Tipo | Ejemplo |
|------|---------|
| Nombre completo | `Génesis 1:1` · `Genesis 1:1` |
| Abreviatura | `gen 1:1` · `Gn 1:1` · `1Co 13:4` |
| En inglés | `John 3:16` · `1Cor 13:4` |
| Rango de versículos | `Romanos 8:1-10` |
| Solo capítulo | `Salmos 23` → versículo 1 |

### Navegación
- **◀** y **▶** cambian de capítulo.
- El **combo de versiones** cambia entre las biblias instaladas.

### Funciones dentro del texto bíblico
- **Números Strong** — si el módulo los incluye, son enlaces clicables que abren la definición léxica.
- **Morfología** — análisis gramatical de palabras en griego o hebreo, también clicable.
- **Notas al pie (RF)** — aparecen como `refx` en verde; haz clic para leerlas.
- **Referencias cruzadas** — el icono indica cuántas hay; se activa o desactiva desde Configuración.
- **Promesas bíblicas** — si las activas, los versículos de cumplimiento se resaltan.
- **Texto interlineal** — los módulos con formato interlineal (palabra, análisis, traducción) se muestran maquetados en tabla, con las palabras alineadas por campo y legibles incluso en columna estrecha.
- **Marcar versículo** — haz clic en el icono de la cinta para guardarlo en marcadores.

---

## 🧭 4. El launcher: todas las herramientas

El botón **:::** de la barra de título abre el launcher con **17 herramientas**, ordenadas alfabéticamente por su nombre traducido.

| Herramienta | Para qué sirve |
|-------------|----------------|
| **⌕ Buscador** | Búsqueda avanzada con fuzzy (sección 5). |
| **≡ Cotejar versículos** | Un mismo pasaje encolumnado en todas tus versiones (sección 8). |
| **▣▣ Vista paralela** | Igual que cotejar, con navegación por secciones cuando hay muchas versiones. |
| **▤ Anotaciones** | Editor de notas personales vinculadas a versículos. |
| **▸ Expositor** | Importa y proyecta presentaciones `.pptx` / `.pdf` (sección 11). |
| **✞︎ Historias Bíblicas** | Visor de PDFs con historias bíblicas infantiles. |
| **〽 Línea de Tiempo** | Eventos bíblicos en orden cronológico; clic para ir a la referencia. |
| **✎ Marcadores** | Panel deslizante con tus versículos guardados, por secciones. |
| **𓆛 Tipología Bíblica** | Tipos y antitipos (p. ej. el cordero pascual como tipo de Cristo). |
| **♡ Promesas** | Visualizador de promesas bíblicas y su cumplimiento. |
| **+ Agregar archivos** | Importa biblias, comentarios, diccionarios y devocionales. |
| **☰⁝ Configuración** | Paneles, fuente, espaciado, diccionarios, modo dislexia (sección 13). |
| **❃ Temas** | Cambia el aspecto de toda la aplicación (sección 13). |
| **𓀘 LogosBuilder** | Crea y exporta tus propios módulos (sección 15). |
| **ⓘ Información** | Abre **esta misma guía** en el idioma activo, e información del módulo activo. |
| **𝄜 Inicio automático** | Configura el Versículo del Día para arrancar con Windows. |
| **文 Idioma** | Cambia o añade idiomas de la interfaz (sección 14). |

> Las ventanas abiertas que quedan ocultas tras la principal **parpadean** en su botón, para recordarte que siguen abiertas.

---

## 🔍 5. Buscador avanzado

Abre el buscador con **⌕** en el launcher.

### Opciones
- **Módulos** — en qué biblias buscar.
- **Rango** — toda la Biblia, Antiguo o Nuevo Testamento, o secciones específicas (Torá, Evangelios…).
- **Tipo de búsqueda**:
  - **Normal** — coincidencia exacta.
  - **Fuzzy (aproximada)** — encuentra resultados similares aunque haya errores ortográficos.
- **Filtro dinámico** — escribe arriba para filtrar los módulos disponibles.

Los resultados aparecen resaltados; haz clic en cualquiera para navegar a esa referencia.

---

## 📝 6. Panel de comentarios

1. Selecciona un módulo en el combo superior del panel central.
2. El comentario se actualiza **automáticamente** al cambiar de capítulo en la Biblia.
3. Usa la barra de búsqueda del panel para buscar sobre una referencia concreta.

### Opciones del panel
- **📊 Comparar** — dos módulos de comentarios lado a lado.
- **ℹ Información del módulo** — autor, idioma, descripción.
- **Lupa** — ver los comentarios en ventana independiente.

---

## 📚 7. Panel de diccionarios

1. Selecciona uno o varios diccionarios en el combo del panel derecho.
2. Escribe una palabra y pulsa **Enter**. Las referencias bíblicas dentro de las definiciones son clicables.
3. **Modo de búsqueda**:
   - **Actual** — solo en los diccionarios seleccionados.
   - **Global** — en todos los diccionarios disponibles.

---

## ⚖️ 8. Comparar y cotejar

Dos herramientas distintas y complementarias:

| | **≡ Cotejar** | **▣▣ Vista paralela** |
|---|---|---|
| Ideal para | Ver muchas versiones a la vez | Muchas versiones con navegación |
| Presentación | El pasaje en columnas, todos los módulos | Por secciones, con índice |
| Ampliable | Sí | Sí |

Ambas admiten **Strong, morfología, notas RF y texto interlineal**. Los módulos interlineales se maquetan en tabla para que las palabras queden alineadas y legibles incluso en columna estrecha.

---

## 🔖 9. Marcadores e historial

### Marcadores (✎)
1. Navega al versículo.
2. Haz clic en el icono de la cinta junto al versículo.
3. Queda guardado en la sección seleccionada del panel.

Crea secciones temáticas ("Predicaciones", "Estudio personal", "Favoritos"). Se guardan en `bookmarks.json`.

### Historial
Los botones **← →** de la barra de título recorren las citas visitadas en la sesión.

---

## ✍️ 10. Anotaciones y diario

**Anotaciones (▤)**: editor de notas personales con formato enriquecido (negrita, cursiva, listas, color), vinculadas a un versículo concreto.

**Diario (`.bok.mybible`)**: los libros devocionales se abren en el panel de diccionarios. Puedes **editar el título y el contenido** de cada entrada, y al añadir una entrada nueva se rellenan automáticamente la referencia y la fecha siguientes.

---

## 🎬 11. Presentaciones y visores

**Expositor (▸)** importa archivos `.pptx` y `.pdf`, y los proyecta con transiciones automáticas y atajos de teclado, con integración bíblica: puedes saltar a una referencia desde la propia presentación.

**Historias Bíblicas (✞︎)** es un visor de PDFs con historias bíblicas infantiles, con navegación por páginas.

---

## ⏳🕊️📚 12. Recursos de estudio

| Recurso | Qué ofrece |
|---------|-------------|
| **Línea de Tiempo (〽)** | Eventos bíblicos ordenados cronológicamente. Clic en un evento para ir a su referencia. |
| **Tipología Bíblica (𓆛)** | Tipos y antitipos: conexiones entre figuras y eventos del Antiguo y el Nuevo Testamento. |
| **Promesas (♡)** | Panel deslizante con las promesas bíblicas y su cumplimiento. |

---

## 🎨 13. Apariencia y configuración

### Temas (❃)
🌑 **Dark** (por defecto) · ☀️ **Light** · 🔵 **Word** · 🌌 **Futuristic** · 💜 **Neon** · 🔷 **Future**

El tema se guarda y se aplica a toda la interfaz, incluidas las ventanas secundarias.

### Configuración (☰⁝)

| Sección | Opciones |
|---------|----------|
| **📐 Distribución de Paneles** | Solo Biblia · Biblia + Comentarios · Los 3 paneles |
| **🔤 Tamaño de Fuente** | De 8 px a 24 px, se aplica en todos los paneles |
| **📏 Espaciado entre versículos** | De 4 px a 30 px |
| **📖 Diccionario Strong** | Por defecto · Strong personalizado |
| **📚 Diccionario Morfológico** | Por defecto · Morfológico personalizado |
| **🔗 Referencias Cruzadas** | Activadas · Desactivadas |
| **✨ Promesas bíblicas** | Activadas · Desactivadas |
| **🔤 Modo Dislexia** | Activado · Desactivado (fuente **OpenDyslexic**) |

Todos los cambios se aplican **en tiempo real**, sin reiniciar.

### El archivo `settings.json`
Guarda tu configuración y se puede editar a mano. Las claves más útiles:

```json
{
  "theme": "Dark",
  "language": "Es_es",
  "paneles": 3,
  "font_size": 14,
  "verse_spacing": 8,
  "dyslexia_mode": false,
  "cross_refs_enabled": false,
  "promises_enabled": false,
  "strong_db_path": null,
  "morph_db_path": null,
  "ultima_cita": "Juan 3:16",
  "bible_version": "RV1960+",
  "modulos_seleccionados": []
}
```

`paneles` admite `1`, `2` o `3`. Un `null` en las rutas de diccionarios significa "usar el de por defecto".

---

## 🌐 14. Idioma de la interfaz

Botón **文** en el launcher.

- 🇪🇸 **Español** · 🇬🇧 **English** · y cualquier idioma personalizado que hayas importado.

> Cambiar el idioma traduce la **interfaz**, pero **no** los nombres de los libros bíblicos para navegar: estos siguen aceptándose en español e inglés sea cual sea el idioma de la interfaz.

### Añadir un idioma nuevo
1. Pulsa **📤 Exportar plantilla** — genera un JSON con **todas** las claves de la interfaz y sus valores en español.
2. Traduce los **valores** (no las claves). Puedes usar DeepL, Google Translate, una IA, o hacerlo a mano con el Bloc de notas.
3. Escribe el nombre visible del idioma en la clave `_language_name` (por ejemplo `"Français"`).
4. Guarda el fichero con el nombre del código (`Fr_fr.json`, `De_de.json`…).
5. Vuelve a **文** → **📥 Importar traducción** y selecciona el fichero.

El idioma queda disponible de inmediato y persiste entre sesiones. Las claves que no traduzcas caen automáticamente al español.

> La plantilla incluye también las claves de **contenido** (historias bíblicas, línea de tiempo, tipologías), no solo las de la interfaz.

---

## 🛠️ 15. Crear módulos con LogosBuilder

Botón **𓀘** en el launcher.

### Qué puedes hacer
- Crear biblias personalizadas (`.bbl`), comentarios (`.cmt`), diccionarios (`.dct`) y libros devocionales (`.book`).
- Editar registros existentes en módulos `.hlgx`.
- **Exportar** cualquier módulo al formato **MySword** estándar para compartirlo.

### Flujo de trabajo
1. **➕ Nuevo Módulo** → elige el tipo (Biblia, Comentario, Diccionario o Libro).
2. Escribe el nombre y crea el archivo.
3. Usa el editor para añadir contenido versículo por versículo.
4. **Exporta a MySword** cuando termines. Durante la exportación verás una **barra de progreso**, y las referencias se convierten automáticamente al formato de destino.

---

## 🔔 16. Versículo del Día

Widget independiente que muestra versículos en la esquina de la pantalla.

- Ábrelo con el botón **𝄜** del launcher, o configúralo para que arranque con Windows.
- Elige entre distintos **planes de lectura** (por ejemplo, un recorrido de un año) y ajusta el **intervalo** de rotación.
- El progreso se guarda automáticamente.

---

## ❓ 17. Solución de problemas

| Problema | Solución |
|----------|----------|
| No aparecen biblias en el combo | Comprueba que hay archivos `.bbl.mybible` en `assets/bibles/`. |
| Los comentarios no cargan | Verifica que los `.cmt.mybible` estén en `assets/commentaries/`. |
| Error al buscar un libro | Usa nombres en español o inglés: `gen 1`, `john 3`, `1co 13`. |
| Un versículo interlineal sale vacío o con `()` | Es un módulo con etiquetas en formato inesperado; prueba con otra vista o repórtalo. |
| La ventana no responde | Espera un momento: indexar diccionarios puede tardar. |
| Las ventanas secundarias "desaparecen" | Haz clic en su botón en el launcher; parpadeará si está minimizada. |
| No se guardan los ajustes | Revisa que `settings.json` no sea de solo lectura. |

---

## 📄 Licencia

HenshinLogos es software **privativo**. Puede usarlo libremente en sus dispositivos personales, ministeriales o académicos, pero **no puede modificarlo, parchearlo ni distribuir versiones derivadas** sin autorización escrita del autor.

La licencia completa está en el archivo `LICENSE`. Se rige por las leyes de la República de Honduras.

---

*Guía de usuario de HenshinLogos v5.1*
