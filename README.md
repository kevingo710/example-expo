# Mi App · Taller de Expo para NASA Space Apps Challenge 2025

App base en **Expo + React Native** que usé para entrenar a los equipos de estudiantes de la PUCE Sede Esmeraldas (PUCESE) antes del **NASA International Space Apps Challenge 2025**. El objetivo del taller: pasar de cero a una app móvil instalable en una tarde, para que en el hackathon el tiempo se dedique al reto y a los datos de la NASA, no a configurar el proyecto.

🎥 [Sesión de entrenamiento](https://youtu.be/JQhSS41FXxk) · 📦 [Descargar el APK](https://github.com/kevingo710/example-expo/releases/latest) · 🌐 Taller web: [example-pucese-one](https://github.com/kevingo710/example-pucese-one)

## Qué se ve en el taller

- Crear el proyecto con `create-expo-app` y entender la estructura de **Expo Router** (rutas por archivos en `app/`)
- Navegación por pestañas (`app/(tabs)`) y una pantalla modal
- Componentes con tema claro/oscuro (`components/themed-*`) y scroll con parallax
- Probar en el móvil con **Expo Go** y generar un **APK con EAS Build** para la demo final

## Ejecutarlo

```bash
npm install
npx expo start
```

Escanea el QR con Expo Go (Android/iOS) o abre un emulador. Para generar el APK:

```bash
npx eas build -p android --profile preview
```

## Stack

Expo SDK 54 · React Native (New Architecture) · Expo Router 6 · TypeScript · EAS Build

---

Preparado por [Kevin Gracia Orejuela](https://github.com/kevingo710), mentor de NASA Space Apps Challenge.
