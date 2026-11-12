# Simulador EGEL Mecatrónica 2026

Cuestionario interactivo de práctica para estudiantes de **Ingeniería Mecatrónica**, basado en un documento de simulación EGEL-CENEVAL proporcionado para este proyecto.

> [!IMPORTANT]
> **Proyecto no oficial.** Este simulador es una herramienta de estudio independiente; no está desarrollado, aprobado ni avalado por CENEVAL. La puntuación obtenida aquí **no equivale** al resultado oficial del EGEL Plus.

## Características

- **60 reactivos** con respuestas de opción múltiple **A, B y C**.
- **6 áreas temáticas** de mecatrónica.
- Navegación entre preguntas y posibilidad de modificar respuestas antes de calificar.
- Barra de progreso y contador de reactivos respondidos.
- **Calificación automática** al finalizar, con aciertos y porcentaje.
- Desglose de resultados por área y revisión de cada respuesta.
- Guardado local del avance en el mismo navegador, cuando está disponible.
- **Diseño adaptable a celulares**, tabletas y computadoras.
- Sin instalación, cuentas, servidor ni librerías externas.

## Áreas del cuestionario

| Área | Reactivos |
| --- | ---: |
| Diseño mecánico y manufactura | 1–10 |
| Electrónica y sistemas digitales | 11–20 |
| Automatización y control | 21–27 |
| Robótica y sistemas mecatrónicos | 28–40 |
| Modelado, simulación y sistemas embebidos | 41–54 |
| Integración y mantenimiento mecatrónico | 55–60 |

> Estas son las áreas del **documento de práctica** y no deben confundirse con la estructura oficial vigente del EGEL Plus IMECATRO.

## Cómo utilizarlo

1. Abre la página del simulador en tu navegador.
2. Lee cada reactivo y selecciona una respuesta.
3. Usa **Anterior**, **Siguiente** o los números para navegar.
4. Presiona **Calificar examen** al terminar.
5. Revisa tu resultado, el desglose por área y las respuestas correctas.
6. Selecciona **Volver a intentarlo** para iniciar un nuevo intento.

**Nota:** si quedan preguntas sin contestar, el simulador te pedirá confirmar si deseas calificar de todos modos.

## Publicación gratuita con GitHub Pages

La versión diseñada para celular se distribuye como un único archivo HTML: `Simulador_EGEL_Mecatronica_2026_Movil.html`.

1. Crea un repositorio **público** en GitHub, por ejemplo `simulador-egel-mecatronica`.
2. Sube el archivo HTML y **renómbralo a `index.html`** en la raíz del repositorio.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/(root)`; guarda los cambios.
6. Cuando GitHub Pages termine de publicar el sitio, abre el enlace indicado en la sección Pages.

La dirección normalmente tendrá esta forma:

```text
https://TU-USUARIO.github.io/simulador-egel-mecatronica/
```

Reemplaza `TU-USUARIO` por tu usuario de GitHub. Si el nombre del repositorio cambia, cambia también la última parte de la URL.

### Uso desde Android o iPhone

Comparte el enlace de GitHub Pages por WhatsApp, correo o mensaje. Los usuarios pueden abrirlo directamente en **Chrome, Safari u otro navegador moderno**, sin instalar una aplicación. El diseño se adapta al tamaño de la pantalla.

## Archivos

```text
simulador-egel-mecatronica/
├── index.html      # Copia renombrada de la versión móvil del simulador
└── README.md       # Documentación del proyecto
```

## Progreso, privacidad y limitaciones

- El progreso se almacena, cuando el navegador lo permite, mediante `localStorage` **en el dispositivo y navegador del usuario**. No se sincroniza entre teléfonos o computadoras.
- El simulador no incluye cuentas, una base de datos ni un panel para consultar resultados de otras personas.
- Borrar los datos del sitio o utilizar otro navegador puede hacer que se pierda el avance.
- Las respuestas correctas se muestran en la interfaz al calificar. Como el proyecto funciona íntegramente en el navegador, una persona con conocimientos técnicos también puede inspeccionar el código y encontrar la clave de respuestas antes de finalizar.
- El porcentaje de aciertos es orientativo y **no se convierte directamente al índice CENEVAL**.

## Referencia de estudio

Para consultar el temario, la estructura y los criterios **oficiales y actualizados** del examen, visita las [guías del CENEVAL](https://guias-egel.ceneval.edu.mx/).

## Uso y atribución

Las preguntas provienen del documento de práctica **«SIMULADOR EGEL MECATROINICA 2026»** proporcionado para la elaboración de esta versión. Antes de redistribuir públicamente el contenido, verifica que tienes permiso para compartirlo. Este repositorio no afirma titularidad sobre materiales de terceros y no implica afiliación con CENEVAL.
