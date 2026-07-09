# Sílabo del Curso: Desarrollo de Aplicaciones Móviles (DAM)

Escuela Profesional de Ingeniería de Sistemas  
Facultad de Ingeniería  
Semestre Académico 2025-II  
Del 14 de agosto al 27 de noviembre de 2025  
Docente: [Nombre del docente]  
Créditos: [N.º de créditos] - Horas semanales: [N.º de horas]

## 1. Nombre del Curso

Desarrollo de Aplicaciones Móviles (DAM)

## Producto del Curso

Aplicación móvil multiplataforma (Android e iOS) desarrollada con Kotlin Multiplatform y Compose Multiplatform, con arquitectura Clean + MVVM, CRUD sobre servicios web REST, autenticación y funcionamiento offline-first, publicada en repositorio Git y sustentada en ambas plataformas.

## Unidad I: Fundamentos de Kotlin Multiplatform y UI con Compose Multiplatform

**Producto U1:** Aplicación KMP ejecutándose en Android e iOS con navegación completa, theming Material 3 y arquitectura Clean + MVVM con datos simulados.

**Tabla 1. Programación de la Unidad I (semanas 1 a 6)**

| Semana | Contenidos |
|---|---|
| s1 | Visión general del desarrollo móvil multiplataforma, arquitectura de KMP, configuración del entorno (Android Studio, Xcode), creación del proyecto (commonMain, androidMain, iosMain), Git |
| s2 | Kotlin esencial: null-safety, data classes, sealed classes, colecciones, corrutinas, Flow, modelado del dominio en commonMain |
| s3 | Compose Multiplatform: composables, estado, modifiers, layouts, controles básicos, formularios |
| s4 | Navegación multiplataforma, Scaffold, drawer, tabs, recursos multiplataforma, theming Material 3, modo claro/oscuro, diseño responsivo |
| s5 | Arquitectura Clean + MVVM, ViewModel multiplataforma, StateFlow, UiState, casos de uso, repositorios, inyección de dependencias con Koin |
| s6 | Evaluación 1 |

## Unidad II: Conectividad, CRUD REST y Persistencia Multiplataforma

**Producto U2:** Aplicación KMP con CRUD REST completo con Ktor, autenticación JWT y persistencia local offline-first.

**Tabla 2. Programación de la Unidad II (semanas 7 a 12)**

| Semana | Contenidos |
|---|---|
| s7 | Fundamentos HTTP/REST, Ktor Client, motores por plataforma (OkHttp, Darwin), kotlinx.serialization, DTO |
| s8 | CRUD REST completo: GET, POST, PUT, DELETE, estados de UI (loading, success, error), manejo de errores con sealed classes |
| s9 | Mecanismo expect/actual, capacidades nativas por plataforma, interoperabilidad Kotlin-Swift (SKIE) |
| s10 | Autenticación JWT, plugins de Ktor (Auth, Logging), almacenamiento seguro de tokens con multiplatform-settings |
| s11 | Persistencia local con SQLDelight, estrategia offline-first, sincronización con la API, detección de conectividad, pruebas unitarias en commonTest |
| s12 | Evaluación 2 |

## Unidad III: Proyecto de Fin de Curso

**Producto U3:** Aplicación móvil multiplataforma (Android e iOS) desarrollada con Kotlin Multiplatform y Compose Multiplatform, con arquitectura Clean + MVVM, CRUD sobre servicios web REST, autenticación JWT y funcionamiento offline-first con sincronización de datos, publicada en repositorio Git con builds firmados (AAB e IPA) y sustentada funcionando en ambas plataformas.

**Tabla 3. Programación de la Unidad III (semanas 13 a 16)**

| Semana | Contenidos |
|---|---|
| s13 | Desarrollo del proyecto integrador, refinamiento offline-first, Firebase Kotlin SDK, manejo de permisos |
| s14 | Mejoras finales, pruebas en dispositivos reales, firma y generación de builds (AAB, IPA), nociones de publicación en Play Store y App Store |
| s15 | Sustentación del proyecto de fin de curso |
| s16 | Evaluación final |

## Sistema de Evaluación

Evaluación 1 (semana 6): entrega del Producto U1. Evaluación 2 (semana 12): entrega del Producto U2. Sustentación del proyecto de fin de curso (semana 15) y Evaluación final (semana 16): entrega y defensa del producto del curso. Los avances semanales se versionan en Git y forman parte de la evaluación continua.

## Referencias

Cash App. (2025). SQLDelight documentation. https://sqldelight.github.io/sqldelight/

Google. (2025). Jetpack Compose documentation. Android Developers. https://developer.android.com/jetpack/compose

JetBrains. (2025a). Compose Multiplatform. https://www.jetbrains.com/compose-multiplatform/

JetBrains. (2025b). Kotlin Multiplatform documentation. https://kotlinlang.org/docs/multiplatform.html

JetBrains. (2025c). Ktor documentation. https://ktor.io/docs/

Moskała, M. (2022). Kotlin coroutines: Deep dive. Kt. Academy.

Touchlab. (2025). Kotlin Multiplatform resources. https://touchlab.co/