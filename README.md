# COMO CREAR APPS EN IONIC

## 1. Instalar ionic (-g/global)

### Tienes que poner lo siguiente (tienes que tener npm) / -g es para que la instalación sea global

    npm install -g @ionic/cli

## 2. Crear proyecto de ionic

### Ejemplo solo

    ionic start

### Ejemplo personalizado

    ionic start "nombre_app" "nombre_del_template" --type=nombre_del_framework

### Templates disponibles

- blank | Un proyecto de inicio en blanco
- list | Un proyecto inicial con una lista
- my-first-app | Una plantilla para el tutorial "Tu primera aplicación ".
- sidemenu | Un proyecto inicial con un menú lateral con navegación en el área de contenido
- tabs | Un proyecto inicial con una simple interfaz con pestañas

### Lenguajes disponibles

- javascript
- typescript

### frameworks disponibles

- react
- angular
- vue

### Ejemplo con solo un nombre

    ionic start app_web

### Ejemplo usando un template y con el framework de react

    ionic start mi_app tutorial --type=react

## 3. Integrar capacitor

### Activar

    ionic integrations enable capacitor

### Desactivar

    ionic integrations disable capacitor

## 4. Integrar ios/android

### Ios

    ionic capacitor add ios

### Android

    ionic capacitor add android

## 5. Ponerlo en producción

### Poner en producción para web

    ionic build | npm build

### Copiar datos

    ionic cap copy

### Sincronizar datos

    ionic cap sym

### Abrir android estudio / X code para crear apk

    ionic cap open android
    ionic cap open ios

## Otros comandos importantes

### Si descargarte un proyecto de GitHub o de un zip

    npm i (para instalar las librerías de node)

### Iniciar servidor

React

    npm run start
