# CV de Francisco Javier Cervantes Mendieta

Currículum general y cinco páginas enfocadas, cada una con su propio PDF de una columna.

- [CV web completo](index.html): trayectoria, habilidades y proyectos de UTEL.
- [CV para datos](cv-datos.html): Python, ETL, reportes e indicadores.
- [CV para automatización](cv-automatizacion.html): Python, Playwright e integraciones.
- [Data Engineer Jr.](cv-data-engineer-jr.html): ETL, integración y calidad de datos.
- [Python / Django Jr.](cv-python-django-jr.html): dashboards, aplicaciones e integraciones.
- [QA Tester Jr.](cv-qa-tester-jr.html): validación de APIs, diagnóstico y seguimiento de incidencias.

Cada página enfocada conserva el diseño principal, no enlaza a otras variantes y permite descargar únicamente su PDF. Cada PDF tiene un enlace a su página bajo https://elavat9000.github.io/CV/. Las páginas incrustan foto y estilos para no depender de archivos locales ignorados.

Las versiones ATS son HTML autónomos sin fuentes remotas, iconos, menú ni JavaScript. Se pueden imprimir o guardar como PDF desde el navegador. No garantizan compatibilidad con todos los sistemas de selección.

## Actualizar

La fuente de contenido es index.html. Después de editarla, ejecutar con Node.js:

```sh
node build-resumes.mjs
```

Las cinco variantes conservan las fechas y los seis empleos. El puesto objetivo aparece en el encabezado; el cargo en UTEL permanece como Analista de Datos. Priorizan actividades distintas y resumen la experiencia anterior. SQL se respalda con la formación documentada, sin añadir un proyecto laboral no confirmado. La variante QA presenta una transición y no atribuye experiencia profesional en regresión, suites automatizadas o diseño de casos de prueba que todavía no está documentada.

## Formación e idiomas

Las credenciales se conservan en certificaciones.json y en la web con emisor, fecha e ID; los PDF muestran título, emisor y fecha. Los cursos son formación, sin convertirlos en experiencia laboral ni certificaciones profesionales de AWS. El curso duplicado de Agentes de IA se registra una sola vez. Los idiomas se conservan en la web sin asignar niveles no confirmados y se omiten de las variantes de envío hasta precisar su uso. El campo de teléfono queda reservado para completarlo. No se inventan métricas ni credenciales.

## Contacto

- Teléfono: 5630150637
- [elavat.9000@gmail.com](mailto:elavat.9000@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/francisco-javier-cervantes-mendieta-327575213/)
- [GitHub](https://github.com/Elavat9000)
- [Portfolio Web](https://portal-web-sandy.vercel.app/)

## Diseño

HTML, CSS y JavaScript sin compilación para la web. Tipografía de sistema cercana al tema Minima y presentación inspirada en la claridad del [CV de Reuben Smit](https://github.com/Reubix29/Reubix29.github.io/blob/main/cv.md). La implementación y el contenido corresponden a este CV.

Las herramientas de auditoría y sus informes permanecen locales, excluidos en .gitignore.
