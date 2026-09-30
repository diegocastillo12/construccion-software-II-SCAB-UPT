# SCAB-UPT — Construcción de Software II

**Sistema de Control de Acceso Biométrico para Reducir la Suplantación de Identidad en los Procesos de Admisión de la Universidad Privada de Tacna, 2026**

| Dato | Detalle |
|---|---|
| Universidad | Universidad Privada de Tacna (UPT) |
| Curso | Construcción de Software II |
| Semestre | 2026-II |
| Docente | *(completar)* |
| Proyecto | SCAB-UPT |

## Integrantes

| Integrante | Rol |
|---|---|
| Sergio Alberto Colque Ponce | Líder del equipo |
| Diego Fernando Castillo Mamani | Integrante |

## Descripción del proyecto

SCAB-UPT es un sistema de control de acceso biométrico orientado a los procesos de admisión de la UPT. Permite registrar y enrolar postulantes, gestionar sedes y aulas, verificar la identidad mediante huella dactilar con matching local a través del Agente SCAB, registrar los accesos y mostrar los resultados en tiempo real en una pantalla Kiosk, con el fin de reducir el riesgo de suplantación de identidad durante el examen de admisión.

**Flujo principal:** postulante → enrolamiento (mínimo 3 huellas) → habilitación → Agente SCAB → lector biométrico → matching local 1:N → validación → registro de acceso → Kiosk.

**Componentes:**

- **Panel web SCAB-UPT:** gestión de usuarios, postulantes, admisión, sedes, puertas, control de acceso, historial, alertas y auditoría.
- **SCAB Agent:** aplicación de escritorio para emparejar la puerta, capturar huellas y realizar el reconocimiento local con el lector biométrico.
- **Kiosk:** pantalla asociada a cada puerta/aula que muestra el resultado del acceso en tiempo real.

## Estado actual

| Aspecto | Estado |
|---|---|
| Desarrollo | Desarrollado y funcional en el entorno del proyecto |
| Catálogo de pruebas | 85 casos definidos (17 funcionalidades × 5 tipos de prueba) |
| Ejecución de pruebas y evidencias | En proceso |
| Documentación por iteraciones | En proceso de consolidación |
| Implementación institucional | No realizada |

## Organización del repositorio

```
construccion-software-II-SCAB-UPT/
├── README.md
├── UNIDAD_01/
│   ├── 01_Revision_de_Codigo/
│   ├── 02_Especificaciones_Funcionales/
│   ├── 03_Casos_de_Prueba/
│   ├── 04_Plan_de_Iteracion/
│   ├── 05_Laboratorios_y_Evidencias/
│   └── 06_Codigo_Fuente/
├── UNIDAD_02/
└── UNIDAD_03/
```

### UNIDAD_01 — Revisión y planificación del software

| Carpeta | Contenido |
|---|---|
| `01_Revision_de_Codigo` | Laboratorio de revisión de código |
| `02_Especificaciones_Funcionales` | Laboratorio de especificaciones funcionales |
| `03_Casos_de_Prueba` | Casos de prueba y catálogo de pruebas |
| `04_Plan_de_Iteracion` | Planes de iteración |
| `05_Laboratorios_y_Evidencias` | Laboratorios desarrollados, informe ejecutivo, presentación y evidencias de ejecución |
| `06_Codigo_Fuente` | Código fuente del sistema |

### UNIDAD_02 — Desarrollo progresivo

Espacio reservado para los entregables, laboratorios y evidencias que se definan durante el desarrollo de la segunda unidad.

### UNIDAD_03 — Desarrollo progresivo

Espacio reservado para los entregables, laboratorios, pruebas y evidencias que correspondan a la tercera unidad.

## Flujo de trabajo

- Los avances que impliquen cambios en el código se registran mediante **commits**, **ramas** y **Pull Requests**.
- Cada laboratorio incluye su documentación y evidencias. Cuando hay código, se enlazan los archivos, commits o Pull Requests que permiten verificarlo.
- Las carpetas vacías contienen un archivo `.gitkeep` para que Git las registre; se pueden eliminar cuando la carpeta tenga contenido.
