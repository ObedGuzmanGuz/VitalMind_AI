# Diagrama de Gantt - VitalMind AI

Las fechas representan **planificación académica** dentro del periodo mayo-agosto de 2026. Una barra en el cronograma no prueba por sí sola que la actividad haya sido ejecutada.

```mermaid
gantt
    title VitalMind AI - planificación mayo-agosto 2026
    dateFormat YYYY-MM-DD
    axisFormat %d/%m
    Planeación del proyecto :t01, 2026-05-20, 10d
    Investigación y contexto :t02, 2026-05-25, 12d
    Definición de requerimientos :t03, 2026-06-01, 12d
    Diseño de la aplicación :t04, 2026-06-08, 12d
    Diseño de interfaz para smartwatch :t05, 2026-06-15, 12d
    Modelo de datos :t06, 2026-06-22, 12d
    Servicios backend :t07, 2026-06-29, 19d
    Sincronización con smartwatch :t08, 2026-07-06, 19d
    Visualización de mediciones :t09, 2026-07-13, 19d
    Registro digital de medicamentos :t10, 2026-07-13, 12d
    Recordatorios y confirmación manual :t11, 2026-07-20, 12d
    Módulos de análisis e IA :t12, 2026-07-27, 12d
    Seguridad y privacidad :t13, 2026-08-03, 8d
    Preparación y pruebas planificadas :t14, 2026-08-05, 8d
    Documentación continua :t15, 2026-05-20, 86d
    Integración final :t16, 2026-08-10, 4d
    Entrega académica :milestone, t17, 2026-08-13, 0d
```

## Responsables y dependencias

| ID | Actividad | Responsable | Dependencia | Estado |
|---|---|---|---|---|
| T01 | Planeación del proyecto | Yazmin Gutierrez Hernandez | Inicio | Planificación académica |
| T02 | Investigación y contexto | Obed Guzmán Flores | Planeación | Planificación académica |
| T03 | Definición de requerimientos | Obed Guzmán Flores | Investigación | Planificación académica |
| T04 | Diseño de la aplicación | Yazmin Gutierrez Hernandez | Requerimientos | Planificación académica |
| T05 | Diseño de interfaz para smartwatch | Yazmin Gutierrez Hernandez | Diseño aplicación | Planificación académica |
| T06 | Modelo de datos | Michelle Castro Otero | Requerimientos | Planificación académica |
| T07 | Servicios backend | Carlos Daniel Garcia Pluma / Jennifer Bautista Barrios | Modelo de datos | Planificación académica |
| T08 | Sincronización con smartwatch | Carlos Daniel Garcia Pluma / Jennifer Bautista Barrios | Backend / selección wearable | Planificación académica |
| T09 | Visualización de mediciones | Yazmin Gutierrez Hernandez | Datos / diseño | Planificación académica |
| T10 | Registro digital de medicamentos | Jennifer Bautista Barrios | Backend | Planificación académica |
| T11 | Recordatorios y confirmación manual | Carlos Daniel Garcia Pluma | Registro medicamentos | Planificación académica |
| T12 | Módulos de análisis e IA | Michelle Castro Otero | Datos disponibles | Planificación académica |
| T13 | Seguridad y privacidad | Carlos Daniel Garcia Pluma | Backend | Planificación académica |
| T14 | Preparación y pruebas planificadas | Citlalli Perez Dionicio | Módulos integrables | Planificación académica |
| T15 | Documentación continua | Obed Guzmán Flores | Inicio | En elaboración académica |
| T16 | Integración final | Equipo completo | Módulos priorizados | Planificación académica |
| T17 | Entrega académica | Equipo completo | Integración y documentos | Hito programado |