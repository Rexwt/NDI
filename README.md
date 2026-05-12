# NDI Monitor Android App

Una aplicación Android para recibir y monitorear señales NDI (Network Device Interface) en tiempo real.

## Características

- 📡 Recepción de señales NDI desde la red
- 👁️ Monitoreo en vivo de múltiples fuentes NDI
- 🎯 Selección de fuentes NDI disponibles
- 🌐 Soporte para diferentes redes
- ⚙️ Interfaz simple e intuitiva

## Requisitos

- Android 8.0 (API 26) o superior
- Conexión a red local
- Librería NDI SDK

## Estructura del Proyecto

```
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── kotlin/
│   │   │   │   └── com/example/ndimonitor/
│   │   │   │       ├── MainActivity.kt
│   │   │   │       ├── ui/
│   │   │   │       ├── viewmodel/
│   │   │   │       └── ndi/
│   │   │   └── res/
│   │   └── test/
│   └── build.gradle.kts
├── gradle/
└── build.gradle.kts
```

## Instalación

1. Clona el repositorio
2. Abre el proyecto en Android Studio
3. Sincroniza las dependencias de Gradle
4. Ejecuta la aplicación

## Uso

1. Abre la aplicación
2. La app detectará automáticamente las fuentes NDI disponibles en la red
3. Selecciona la fuente que deseas monitorear
4. Visualiza la transmisión NDI en tiempo real

## Tecnologías Utilizadas

- Kotlin
- Jetpack Compose / Material Design
- NDI SDK
- Coroutines
- LiveData

## Licencia

MIT
