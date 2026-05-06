# Enfermería Escolar — Liceo Bicentenario Industrial

Demo público: https://pedro-fernandez-m.github.io/enfermeria-lbi/

## Resumen del proyecto

Esta aplicación web es un sistema de gestión de atenciones de enfermería escolar diseñado para el Liceo Bicentenario Industrial. Permite registrar y consultar atenciones médicas y dentales de estudiantes, además de administrar antecedentes de salud (fichas médicas) y actualizar la nómina de alumnos mediante carga de Excel.

## Características principales

- Registro de atenciones de enfermería con datos de alumno, motivo, tratamiento y situación final.
- Registro de atenciones dentales separado del historial general.
- Historial filtrable por curso, fecha y situación.
- Exportación de historial a CSV.
- Fichas médicas por alumno con alergias, diagnósticos, medicamentos y observaciones.
- Carga de matrícula desde archivo Excel para actualizar la lista de alumnos.
- Conexión a Supabase para sincronización de datos en la nube.
- Interfaz elegante y responsiva en HTML, CSS y JavaScript puro.

## Tecnología usada

- HTML5
- CSS3
- JavaScript (vanilla)
- Supabase REST API
- Librería `xlsx` para procesar archivos Excel

## Cómo usar la demo

1. Visita la URL pública:
   - https://pedro-fernandez-m.github.io/enfermeria-lbi/
2. Ingresa con las credenciales de ejemplo:
   - Usuario: `liceo`
   - Clave: `2026`

## Estructura del proyecto

- `index.html` — aplicación completa con interfaz y lógica.

## Detalles técnicos clave

- La aplicación guarda y carga datos desde Supabase a través del endpoint REST.
- Usa `localStorage` para persistencia local inmediata y sincroniza con la nube.
- El proyecto funciona como una SPA ligera sin frameworks externos.
- El código está preparado para usarse como demostración de desarrollo front-end con integración de backend moderno.

## Por qué usarlo en un portafolio

Este proyecto demuestra habilidades en:

- Desarrollo front-end con HTML, CSS y JavaScript puro.
- Integración con bases de datos y servicios en la nube.
- Diseño de interfaces accesibles y responsivas.
- Gestión de datos en tiempo real y persistencia local.
- Resolución de casos reales en entornos educativos.

---

Si quieres, puedo ayudarte a mejorar el README con secciones adicionales como pruebas, despliegue o mejoras futuras.