# Desarrollo de Aplicaciones Móviles (MOV)

**Repositorio:** [262mov/pagatu-mov](https://github.com/262mov/pagatu-mov)

## Implementación vigente

Por ahora **S1-S2** están publicadas; **S3-S16** se muestran abajo únicamente como referencia de los temas del sílabo vigente (2026-2).

## Producto del curso

**Aplicación móvil multiplataforma (Android e iOS) desarrollada con Kotlin Multiplatform y Compose Multiplatform, con arquitectura Clean + MVVM, CRUD sobre servicios REST, autenticación JWT, persistencia offline-first, builds firmados y sustentación en ambas plataformas.**

## Unidad 1: Fundamentos de Kotlin Multiplatform y UI con Compose Multiplatform

**Producto:** Aplicación KMP ejecutándose en Android e iOS con navegación completa, theming Material 3 y arquitectura Clean + MVVM con datos simulados.

| Sesión | Tema | Producto de sesión |
|---|---|---|
| [S1](sesiones/S01_Fundamentos_KMP_Compose.md) | Visión general del desarrollo móvil multiplataforma, arquitectura de KMP, configuración del entorno, creación del proyecto y Git. | Entorno configurado y proyecto KMP base ejecutable, versionado en Git. |
| [S2](sesiones/S02_Kotlin_Esencial_Dominio_CommonMain.md) | Kotlin esencial: null-safety, data classes, sealed classes, colecciones, corrutinas, Flow y modelado del dominio en commonMain. | Modelos y estados del dominio en `commonMain`. |
| S3 | Compose Multiplatform: composables, estado, modifiers, layouts, controles básicos y formularios. | Pantallas y formularios construidos con Compose. |
| S4 | Navegación multiplataforma, Scaffold, drawer, tabs, recursos multiplataforma, theming Material 3, modo claro/oscuro y diseño responsivo. | Navegación, layout base y tema Material 3. |
| S5 | Arquitectura Clean + MVVM, ViewModel multiplataforma, StateFlow, UiState, casos de uso, repositorios e inyección de dependencias con Koin. | Capas organizadas, ViewModel, UiState y repositorio simulado. |
| S6 | Evaluación 1: Aplicación KMP inicial con UI, navegación, theming y arquitectura Clean + MVVM. | **Producto U1** sustentado, funcionando en Android e iOS. |

## Unidad 2: Conectividad, CRUD REST y Persistencia Multiplataforma

**Producto:** Aplicación KMP con CRUD REST completo con Ktor, autenticación JWT y persistencia local offline-first.

| Sesión | Tema | Producto de sesión |
|---|---|---|
| S7 | Fundamentos HTTP/REST, Ktor Client, motores por plataforma, kotlinx.serialization y DTO. | Cliente Ktor configurado, consumo GET inicial. |
| S8 | CRUD REST completo: GET, POST, PUT, DELETE, estados de UI y manejo de errores con sealed classes. | CRUD completo con estados loading/success/error. |
| S9 | Mecanismo expect/actual, capacidades nativas por plataforma e interoperabilidad Kotlin-Swift. | Capacidad nativa implementada con `expect`/`actual`. |
| S10 | Autenticación JWT, plugins de Ktor, logging y almacenamiento seguro de tokens. | Login, token JWT y solicitudes protegidas. |
| S11 | Persistencia local con SQLDelight, estrategia offline-first, sincronización con API, conectividad y pruebas unitarias en commonTest. | Almacenamiento local y sincronización básica, con pruebas unitarias. |
| S12 | Evaluación 2: CRUD REST, autenticación y persistencia offline-first. | **Producto U2** sustentado, flujo conectado y persistente. |

## Unidad 3: Proyecto de Fin de Curso

**Producto:** Aplicación móvil multiplataforma completa, con arquitectura Clean + MVVM, CRUD REST, autenticación JWT, offline-first, builds firmados y sustentación en ambas plataformas.

| Sesión | Tema | Producto de sesión |
|---|---|---|
| S13 | Desarrollo del proyecto integrador, refinamiento offline-first, Firebase Kotlin SDK y manejo de permisos. | Mejoras finales y permisos nativos integrados. |
| S14 | Mejoras finales, pruebas en dispositivos reales, firma y generación de builds AAB e IPA, nociones de publicación. | Builds generados y validados en dispositivos reales. |
| S15 | Sustentación del proyecto de fin de curso. | Aplicación defendida funcionando en Android e iOS. |
| S16 | Evaluación final. | **Producto final:** entrega y cierre técnico del producto. |

## Enlaces

- [Sílabo 2026-2](silabo_mov_2026_2.md)
