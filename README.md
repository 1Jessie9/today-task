# TodayTask — Ionic 8 + Angular 20 + Cordova

App móvil que consume **localStorage** para crear, actualizar, completar y borrar tareas y categorías del usuario.

## Demo
- **Android APK**: https://drive.google.com/file/d/19Jh4e0BmZ7ZPoASf4rNfpfVeOe2P2Z0z/view?usp=sharing


## Tech Stack
- **Ionic** 8 (standalone components)
- **Angular** 20 (standalone + signals)
- **Cordova**
- **SCSS**

## Características
- Slider de categorías
- Lista de tareas
- Gestos para completar acciones de tareas
- Crear y editar categorías
- Crear y editar tareas

## Requisitos
- Node 18+ / 20+
- npm 9+ / 10+
- Android Studio (para Android) / Xcode (para iOS)
- Cuenta de GitHub (repo público)

## Configuración
### Instalar Ionic si no está instalado:

```bash
npm i -g @ionic/cli
```
### Cordova CLI (global):
```bash
npm install -g cordova
```

## Configuración del proyecto
```bash
git clone https://github.com/1Jessie9/today-task.git
```
```bash
cd today-task
```
```bash
npm i
```

---

## Ejecutar en modo desarrollo (web)
```bash
ionic serve
```

## Ejecutar en modo desarrollo (web)
```bash
ionic build
```

## Android
- Java JDK (ej: 17).
- Android Studio (para SDK, emuladores y firmas).
- Android SDK.
- Variables de entorno configuradas, por ejemplo:
```bash
export ANDROID_HOME=$HOME/Library/Android/sdk
export ANDROID_SDK_ROOT=$HOME/Library/Android/sdk
export JAVA_HOME=/Library/Java/JavaVirtualMachines/<tu-jdk>/Contents/Home
```

## IOS (MacOS)
- macOS (con soporte para Xcode).
- Xcode instalado.
- CocoaPods:
```bash
sudo gem install cocoapods
```
- ios-deploy (para correr en dispositivos físicos):
```bash
npm install -g ios-deploy
```

# Estructura híbrida con Cordova

## Añadir plataformas
Android
```bash
ionic cordova platform add android
```

IOS
```bash
ionic cordova platform add ios
```

# Compilar y ejecutar en Android
## Build debug (emulador o dispositivo)

```bash
ionic cordova run android
```

## Build para iOS (proyecto Xcode)
```bash
ionic cordova build ios
```

Esto genera un proyecto de Xcode en:

### Abrir en Xcode
#### Abrir el workspace:
- platforms/ios/TodayTask.xcworkspace

#### Seleccionar un simulador (ej. iPhone 15) o un dispositivo físico conectado:

#### Ejecutar desde el botón Run en Xcode