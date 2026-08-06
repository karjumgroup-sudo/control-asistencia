# 📍 Sistema de Control de Asistencia Geolocalizado & Vinculación de Dispositivo

Un sistema de registro de asistencia web ligero, seguro y responsivo diseñado para validar el marcaje de ingreso/salida de empleados mediante **geocercas (GPS)** e **identificación única de dispositivo (UUID)**, integrado directamente con **Google Sheets** como base de datos a través de **Google Apps Script**.

---

## 🚀 Características Principales

- 📱 **Interfaz Web Responsiva:** Diseñada tipo PWA/Mobile-First para un uso intuitivo desde teléfonos celulares.
- 📌 **Validación Geofencing (GPS):** Utiliza la API de Geolocalización del navegador para calcular la distancia en metros entre el usuario y la ubicación de la empresa mediante la fórmula de Haversine.
- 🔒 **Vinculación de Dispositivo Único (Device ID):** Asigna un identificador único (UUID) almacenado localmente para amarrar la cédula del colaborador a un solo teléfono.
- ⚡ **Backend Serverless con Apps Script:** Procesa peticiones HTTP `POST` sin necesidad de servidores ni costos de infraestructura extra.
- 🌐 **Manejo Seguro de CORS:** Configurado con `Content-Type: text/plain` para garantizar compatibilidad con política de origen cruzado en navegadores móviles.
- 📊 **Base de Datos en Google Sheets:** Registro automático con fecha, hora, tipo de evento, coordenadas GPS, distancia calculada y estado de validación.


