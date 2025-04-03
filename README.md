# PuntoVentaCloud_Movil

Aplicación móvil desarrollada en **Kotlin** con **Android Studio**, diseñada para usuarios administradores del sistema PuntoVentaCloud. Permite consultar informes clave del sistema en tiempo real mediante integración con la API RESTful.

## 📱 Descripción General

La aplicación está enfocada en la consulta de datos relevantes del negocio de manera rápida, segura y eficiente. Brinda acceso a:

- Reportes de ventas
- Cierres de caja
- Accesos de usuarios

Accede a esta información filtrando por rangos de fechas y obteniendo los resultados directamente desde la API, todo dentro de una interfaz moderna construida con Jetpack Compose.

## 🔐 Seguridad

- Autenticación segura mediante **JWT (JSON Web Tokens)**
- Gestión de sesión mediante un **TokenManager**
- Comunicación HTTP autenticada para proteger el acceso a los endpoints

## 🧩 Arquitectura

La aplicación sigue el patrón **MVVM (Model-View-ViewModel)** para lograr una separación clara de responsabilidades:

- **Screens**: Gestionan la presentación de la interfaz de usuario.
- **ViewModels**: Controlan la lógica de negocio y el estado de cada pantalla.
- **ApiService**: Cliente HTTP que maneja las solicitudes y respuestas a la API usando **Retrofit**.

## 🎨 UI y Experiencia de Usuario

- Construida con **Jetpack Compose**, utilizando un **Theme personalizado**
- Estructura de navegación basada en **AppScaffold** y **Compose Navigation**
- Manejo de listas extensas con **LazyColumn** (Lazy Loading)

## 🔧 Herramientas y Tecnologías

| Herramienta         | Uso principal                            |
|---------------------|-------------------------------------------|
| Kotlin              | Lenguaje de desarrollo                   |
| Android Studio      | Entorno de desarrollo                    |
| Retrofit            | Cliente HTTP para consumo de API        |
| OkHttp              | Interceptor y registro de peticiones     |
| Jetpack Compose     | Interfaz de usuario moderna y declarativa|
| JWT                 | Autenticación segura                     |


## 📈 Funcionalidades

- **Autenticación de usuario**
- **Informe de Ventas**: Detalles por fecha y hora
- **Informe de Cierres de Caja**: Totales por turno
- **Informe de Accesos de Usuario**: Tiempo activo por usuario
- **Navegación fluida** entre reportes y menús
- **Persistencia de sesión** mediante token

## ✅ Ventajas

- Modular y mantenible
- Experiencia fluida con grandes volúmenes de datos
- Seguridad reforzada
- Diseño moderno e intuitivo
- Preparada para escalabilidad futura

## 🚀 Instalación

1. Clona este repositorio
2. Abre el proyecto en Android Studio
3. Ejecuta en un emulador o dispositivo físico
4. Para distribuir, genera el `.apk` desde `Build > Build Bundle(s) / APK(s)`

![imagen](https://github.com/user-attachments/assets/47713e11-502b-482b-bd44-6ee5e0a8704c)

![imagen](https://github.com/user-attachments/assets/9e5655dd-6244-460d-ac05-c1fecec87482)





