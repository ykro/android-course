# Crea tu app Android con Kotlin y Compose asistida por IA

Curso en línea de tres unidades. En cada una construyes una app Android con Kotlin y Jetpack Compose, con tests desde el primer paso, y trabajas con un agente de código sin perder el control de lo que entra a tu proyecto: le pides el código, revisas el diff y lo compruebas con los tests.

Este repositorio es el índice del curso. El código de cada unidad está en su propia plantilla de GitHub, con el proyecto base, los tests y la integración continua listos.

[English version](README.en.md)

## Las unidades

| Unidad | Plantilla | Qué construyes |
| :--- | :--- | :--- |
| 1 | [`android-course-u1-rpg-quest`](https://github.com/ykro/android-course-u1-rpg-quest) | **RPG Quest & Dice Tracker**, un tablero de misiones con arena de dados: Kotlin moderno, Compose con Material 3, State Hoisting, MVVM con `StateFlow`, corrutinas, navegación type-safe y Koin. |
| 2 | [`android-course-u2-gallery-vault`](https://github.com/ykro/android-course-u2-gallery-vault) | **Gallery Vault**, una galería de pinturas de dominio público que funciona sin red: offline-first con Retrofit, Room como fuente única de verdad, paginación, errores tipados y Turbine. |
| 3 | [`android-course-u3-cloudboard-sync`](https://github.com/ykro/android-course-u3-cloudboard-sync) | **CloudBoard Sync**, un tablero colaborativo: capas Domain, UseCases y Data, Firebase Auth y Firestore con `callbackFlow`, Security Rules y reintentos resilientes. |

Cada unidad termina con un reto: un contrato escrito, sin código guiado, que verificas con los tests públicos de tu repositorio.

## Cómo empezar

1. Abre la plantilla de la unidad y elige **Use this template > Create a new repository**.
2. Ponle tu propio nombre (no el de la plantilla) y elige visibilidad **Private**: así tu solución del reto no queda a la vista de cualquiera.
3. Clona tu repositorio, abre su raíz en Android Studio (File > Open) y, en la terminal del IDE:

   ```bash
   ./gradlew testDebugUnitTest   # al inicio: la demo en verde; el taller y el reto en rojo
   ```

El `README.md` de cada plantilla explica cómo instalar y correr el proyecto. El contrato del reto, qué archivos puedes modificar y la lista para revisar tu trabajo están en la guía del reto de cada unidad, en el material del curso.

## Requisitos

- Una computadora con 8 GB de memoria como mínimo (16 GB recomendado) y 20 GB libres.
- Android Studio estable (trae el JDK 21) y el SDK de Android.
- Git y una cuenta gratuita de GitHub, y un agente de código.
- Opcional: un emulador o un teléfono con Android 8.0 o superior para ver las apps (los tests no lo necesitan) y, en la Unidad 3, un proyecto propio de Firebase (el curso funciona completo en modo demo).
- Haber programado con clases y colecciones en Java, C#, TypeScript o un lenguaje similar. No necesitas experiencia previa con Android.
