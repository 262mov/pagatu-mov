<!-- Versión 2026-2 construida desde docs/index.md usando la estructura y fechas de silabo_poo_2026_2.md -->

Universidad Peruana Unión
Carret. Central km. 19.5 Ñaña. Telf. 01-6186300 Casilla 3564 Lima 1, Perú

# Sílabo: Desarrollo de Aplicaciones Móviles

## I. Información General de Asignatura

| N. | Campo | Información | N. | Campo | Información |
|---|---|---|---|---|---|
| 01 | Facultad/EGP | Facultad de Ingeniería y Arquitectura | 09 | Año de plan de estudio | 2026-1 |
| 02 | Programa de estudio | EP Ingeniería de Sistemas | 10 | Ciclo de estudio | 8 |
| 03 | Tipo de estudio | Especialidad | 11 | Código de asignatura |  |
| 04 | Nombre de asignatura | Desarrollo de Aplicaciones Móviles | 12 | Número de créditos | 3 |
| 05 | Duración |  | 13 | Nota mínima probatoria | 13 |
| 06 | Horas de la asignatura | H. Te. Pract: 2 / H. Prc. Pres: 2 | 14 | Año y semestre académico | 2026-2 |
| 07 | Docente | [Nombre del docente] |  |  |  |
| 08 | Pre-requisito | Desarrollo de Aplicaciones Distribuidas |  |  |  |
## II. Sumilla

La asignatura de Desarrollo de Aplicaciones Móviles es de naturaleza teórico-práctica. Su propósito es que el estudiante diseñe, implemente y sustente aplicaciones móviles multiplataforma mediante Kotlin Multiplatform y Compose Multiplatform, integrando arquitectura Clean + MVVM, conectividad REST, autenticación, persistencia local, funcionamiento offline-first y generación de builds para Android e iOS.

## III. Competencia del perfil de egreso con relación a la asignatura

| Tipo | Competencia | Dimensiones |
|---|---|---|
| General | **Carácter y aprendizaje autónomo.** Cultiva un carácter íntegro y autónomo, guiado por principios bíblicos y adventistas, integrando un enfoque espiritual con la proactividad en el aprendizaje y el desarrollo personal. | N. 1.1 Firmeza de propósito, ejecución, dominio propio y mantener el esfuerzo. |
| Específica | **Ingeniería de Software.** Gestiona y desarrolla software de manera eficiente y efectiva, basándose en estándares internacionales de calidad a fin de lograr el control y aseguramiento de la calidad según el contexto de la organización. | N. 1.1 Programación y desarrollo de soluciones de software. |

## IV. Resultado de aprendizaje de la asignatura

| Resultado de aprendizaje | Producto Académico |
|---|---|
| Al finalizar el curso, el estudiante desarrolla y sustenta una aplicación móvil multiplataforma funcional para Android e iOS, integrando arquitectura Clean + MVVM, UI declarativa con Compose Multiplatform, conectividad REST, autenticación, persistencia local y funcionamiento offline-first. | **Nombre:** Aplicación móvil multiplataforma Android/iOS desarrollada con Kotlin Multiplatform y Compose Multiplatform. |
|  | **Descripción:** Aplicación móvil multiplataforma con arquitectura Clean + MVVM, CRUD sobre servicios REST, autenticación JWT, funcionamiento offline-first, builds para Android/iOS, repositorio Git, documentación y sustentación técnica. |

## V. Unidades de aprendizaje

## Unidad 1: Fundamentos de Kotlin Multiplatform y UI con Compose Multiplatform

| Resultado de aprendizaje | Producto |
|---|---|
| Construye una aplicación KMP inicial ejecutable en Android e iOS, aplicando fundamentos de Kotlin, Compose Multiplatform, navegación, theming y arquitectura Clean + MVVM con datos simulados. | **Nombre:** Aplicación KMP ejecutándose en Android e iOS con navegación completa, theming Material 3 y arquitectura Clean + MVVM con datos simulados. |

| Criterios de evaluación del producto | Descripción del producto |
|---|---|
| Configuración correcta del entorno multiplataforma. Modelado del dominio en commonMain. Interfaz Compose funcional. Navegación y tema Material 3. Organización inicial Clean + MVVM. | Aplicación móvil inicial multiplataforma que demuestra estructura de proyecto KMP, pantallas principales, navegación, UI declarativa y organización arquitectónica básica. |

### Sesiones de aprendizaje

| N. | Fecha | Contenido | HT | HP | Actividad práctica | Actividad autónoma |
|---|---|---|---:|---:|---|---|
| 1 | 10/08/2026  15/08/2026 | Visión general del desarrollo móvil multiplataforma, arquitectura de KMP, configuración del entorno, creación del proyecto y Git. | 2 | 2 | Configura Android Studio, Xcode y crea el proyecto KMP base. | Documenta el entorno, comandos de ejecución y estructura del proyecto. |
| 2 | 16/08/2026  22/08/2026 | Kotlin esencial: null-safety, data classes, sealed classes, colecciones, corrutinas, Flow y modelado del dominio en commonMain. | 2 | 2 | Modela entidades y estados del dominio en commonMain. | Completa modelos, casos simples y evidencias de ejecución. |
| 3 | 23/08/2026  29/08/2026 | Compose Multiplatform: composables, estado, modifiers, layouts, controles básicos y formularios. | 2 | 2 | Construye pantallas y formularios con Compose. | Refina estados de UI y valida formularios básicos. |
| 4 | 30/08/2026  05/09/2026 | Navegación multiplataforma, Scaffold, drawer, tabs, recursos multiplataforma, theming Material 3, modo claro/oscuro y diseño responsivo. | 2 | 2 | Implementa navegación, layout base y tema Material 3. | Ajusta diseño responsivo y evidencia Android/iOS. |
| 5 | 06/09/2026  12/09/2026 | Arquitectura Clean + MVVM, ViewModel multiplataforma, StateFlow, UiState, casos de uso, repositorios e inyección de dependencias con Koin. | 2 | 2 | Organiza capas, ViewModel, UiState y repositorio simulado. | Documenta responsabilidades por capa y pruebas de flujo. |
| 6 | 13/09/2026  19/09/2026 | Evaluación 1: Aplicación KMP inicial con UI, navegación, theming y arquitectura Clean + MVVM. | 2 | 2 | Sustenta el Producto U1 funcionando en Android e iOS. | Corrige observaciones y consolida evidencias de U1. |

## Unidad 2: Conectividad, CRUD REST y Persistencia Multiplataforma

| Resultado de aprendizaje | Producto |
|---|---|
| Integra conectividad REST, autenticación, manejo de errores y persistencia local offline-first en una aplicación KMP. | **Nombre:** Aplicación KMP con CRUD REST completo con Ktor, autenticación JWT y persistencia local offline-first. |

| Criterios de evaluación del producto | Descripción del producto |
|---|---|
| Consumo REST con Ktor. CRUD completo. Manejo de estados y errores. Autenticación JWT. Persistencia local y sincronización offline-first. | Aplicación móvil conectada a servicios web REST, con autenticación, almacenamiento seguro y persistencia local sincronizable. |

### Sesiones de aprendizaje

| N. | Fecha | Contenido | HT | HP | Actividad práctica | Actividad autónoma |
|---|---|---|---:|---:|---|---|
| 1 | 20/09/2026  26/09/2026 | Fundamentos HTTP/REST, Ktor Client, motores por plataforma, kotlinx.serialization y DTO. | 2 | 2 | Configura cliente Ktor y consumo GET inicial. | Documenta endpoints, DTO y pruebas de conexión. |
| 2 | 27/09/2026  03/10/2026 | CRUD REST completo: GET, POST, PUT, DELETE, estados de UI y manejo de errores con sealed classes. | 2 | 2 | Implementa CRUD completo con estados loading, success y error. | Registra pruebas de operaciones y errores controlados. |
| 3 | 04/10/2026  10/10/2026 | Mecanismo expect/actual, capacidades nativas por plataforma e interoperabilidad Kotlin-Swift. | 2 | 2 | Implementa una capacidad nativa usando expect/actual. | Documenta diferencias por plataforma y evidencia iOS/Android. |
| 4 | 11/10/2026  17/10/2026 | Autenticación JWT, plugins de Ktor, logging y almacenamiento seguro de tokens. | 2 | 2 | Integra login, token JWT y protección de solicitudes. | Valida expiración, almacenamiento y cierre de sesión. |
| 5 | 18/10/2026  24/10/2026 | Persistencia local con SQLDelight, estrategia offline-first, sincronización con API, conectividad y pruebas unitarias en commonTest. | 2 | 2 | Implementa almacenamiento local y sincronización básica. | Agrega pruebas unitarias y evidencia escenarios offline. |
| 6 | 25/10/2026  31/10/2026 | Evaluación 2: CRUD REST, autenticación y persistencia offline-first. | 2 | 2 | Sustenta el Producto U2 con flujo conectado y persistente. | Corrige observaciones y estabiliza documentación. |

## Unidad 3: Proyecto de Fin de Curso

| Resultado de aprendizaje | Producto |
|---|---|
| Integra, estabiliza y sustenta una aplicación móvil multiplataforma completa con funcionamiento Android/iOS, REST, autenticación, offline-first y builds publicables. | **Nombre:** Aplicación móvil multiplataforma completa, con arquitectura Clean + MVVM, CRUD REST, autenticación JWT, offline-first, builds firmados y sustentación en ambas plataformas. |

| Criterios de evaluación del producto | Descripción del producto |
|---|---|
| Integración funcional completa. Sincronización offline-first. Uso de capacidades nativas o Firebase. Pruebas en dispositivos reales. Builds firmados y sustentación técnica. | Producto final móvil multiplataforma ejecutable en Android e iOS, documentado, versionado y sustentado con evidencias técnicas. |

### Sesiones de aprendizaje

| N. | Fecha | Contenido | HT | HP | Actividad práctica | Actividad autónoma |
|---|---|---|---:|---:|---|---|
| 1 | 01/11/2026  07/11/2026 | Desarrollo del proyecto integrador, refinamiento offline-first, Firebase Kotlin SDK y manejo de permisos. | 2 | 2 | Integra mejoras finales y permisos nativos. | Documenta flujo completo y evidencias por plataforma. |
| 2 | 08/11/2026  14/11/2026 | Mejoras finales, pruebas en dispositivos reales, firma y generación de builds AAB e IPA, nociones de publicación. | 2 | 2 | Genera builds y valida el producto en dispositivos. | Prepara guía de instalación y checklist de entrega. |
| 3 | 15/11/2026  21/11/2026 | Sustentación del proyecto de fin de curso. | 2 | 2 | Presenta y defiende la aplicación funcionando en Android e iOS. | Atiende observaciones y registra aportes individuales. |
| 4 | 22/11/2026  28/11/2026 | Evaluación final. | 2 | 2 | Demuestra competencias pendientes y cierre técnico del producto. | Entrega final de evidencias, repositorio y documentación. |

## VI. Estrategias metodológicas

| N. | Estrategias de enseñanza y de aprendizaje que se aplicarán en la asignatura |
|---|---|
| 1.1 | Aprendizaje basado en proyectos: desarrolla progresivamente un producto funcional articulado a un problema real o simulado. |
| 1.2 | Aprendizaje cooperativo: promueve coordinación, comunicación técnica, responsabilidad individual y trabajo en equipo. |
| 1.3 | Laboratorio guiado: permite practicar herramientas, patrones, evidencias y entregables técnicos en cada sesión. |
| 1.4 | Sustentación técnica: fortalece la explicación de decisiones, evidencias, limitaciones y mejora continua del producto. |

## VII. Recursos, medios y materiales

| N. | Recursos medios y materiales |
|---|---|
| 1 | Guías y/o tutoriales del curso |
| 2 | PC o laptop con entorno de desarrollo configurado |
| 3 | Laboratorio de cómputo |
| 4 | Internet - Wifi |
| 5 | Proyector y/o TV Smart |
| 6 | Repositorio Git y documentación técnica del proyecto |

## VIII. Evaluación

La evaluación de los estudiantes se rige por el Reglamento de Estudios, disponible en: <https://upeu.edu.pe/reglamentos/evaluacion>. La estructura evaluativa comprende componentes formativos y/o de procesos, de producto y genéricos, reflejando un enfoque integral.

### Componentes de evaluación y ponderación

- **Evaluación de sesiones (ES):** promedio de actividades aplicadas durante las sesiones. Contribuye hasta el 20% de la nota final.
- **Evaluación de productos (EP):** promedio ponderado de los productos entregados en cada unidad. Representa como mínimo el 70% de la nota final.
- **Evaluación de competencias generales (ECG):** aporta hasta el 10% al cálculo de la nota final.

### Programación de evaluaciones

| Fecha | Unidad | Producto | Evaluación de proceso y de resultado | Pesos |
|---|---|---|---|---:|
| 18/09/2026 | Unidad 1: Fundamentos de Kotlin Multiplatform y UI con Compose Multiplatform | Aplicación KMP ejecutándose en Android e iOS con navegación completa, theming Material 3 y arquitectura Clean + MVVM con datos simulados. | Evaluación del producto | 20% |
|  |  |  | Evaluación de sesiones | 5% |
| 30/10/2026 | Unidad 2: Conectividad, CRUD REST y Persistencia Multiplataforma | Aplicación KMP con CRUD REST completo con Ktor, autenticación JWT y persistencia local offline-first. | Evaluación del producto | 20% |
|  |  |  | Evaluación de sesiones | 5% |
| 20/11/2026 | Unidad 3: Proyecto de Fin de Curso | Aplicación móvil multiplataforma completa, con arquitectura Clean + MVVM, CRUD REST, autenticación JWT, offline-first, builds firmados y sustentación en ambas plataformas. | Evaluación de sesiones | 10% |
|  |  |  | Evaluación del producto | 30% |
| 20/11/2026 | Competencia General | Carácter y aprendizaje autónomo. | Competencia General | 10% |

| Promedio ponderado de las evaluaciones | Pesos |
|---|---:|
| Evaluación de sesiones | 20% |
| Evaluación del producto | 70% |
| Evaluación de competencia genérica | 10% |
| Total | 100% |

## IX. Referencias

- Cash App. (2025). SQLDelight documentation. https://sqldelight.github.io/sqldelight/`r`n- Google. (2025). Jetpack Compose documentation. Android Developers. https://developer.android.com/jetpack/compose`r`n- JetBrains. (2025a). Compose Multiplatform. https://www.jetbrains.com/compose-multiplatform/`r`n- JetBrains. (2025b). Kotlin Multiplatform documentation. https://kotlinlang.org/docs/multiplatform.html`r`n- JetBrains. (2025c). Ktor documentation. https://ktor.io/docs/`r`n- Moskała, M. (2022). Kotlin coroutines: Deep dive. Kt. Academy.`r`n- Touchlab. (2025). Kotlin Multiplatform resources. https://touchlab.co/