# Entrevistas de Seguridad – Equipo de Mantención

Formulario web para entrevistas individuales al equipo de mantención, con evaluación separada por entorno (Taller / Faena), seguimiento de entrevistados, gráficos de tendencias y criticidades, e informes descargables.

## Uso

Abra la página publicada (GitHub Pages) en el navegador del equipo donde se realizarán las entrevistas.

- **Entrevista:** datos del trabajador, evidencias fotográficas (AST, HCR, OTROS) y las 43 preguntas con respuesta escrita y calificación Taller / Faena.
- **Seguimiento:** listado de entrevistados, gráficos, hallazgos críticos, informe consolidado, informe individual y exportación a Excel (CSV).

## Dónde se guardan los datos

Las entrevistas **no se suben a ningún servidor ni a GitHub**. Se guardan solo en el navegador del equipo que las ingresa.

- Use siempre el mismo equipo y el mismo navegador.
- Use **Respaldar datos** con frecuencia y guarde el archivo `.json` en un lugar seguro.
- Si se borran los datos de navegación, las entrevistas se pierden; se recuperan con **Restaurar respaldo**.

## Publicar en GitHub Pages

1. Suba `index.html` (y este `README.md`) a la raíz del repositorio.
2. En el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`, **Save**.
3. Después de 1–2 minutos la página queda en `https://<usuario>.github.io/<repositorio>/`.
