# cordova-plugin-qrscanner-secore

Versión personalizada del plugin [`cordova-plugin-qrscanner`](https://github.com/bitpay/cordova-plugin-qrscanner), adaptada por [@luissecore](https://github.com/luissecore) para ser compatible con **Cordova Android 13+** y **Gradle 7+**.

---

## ✅ ¿Qué corrige esta versión?

- Reemplaza el uso obsoleto de `compile` por `implementation` en el archivo `.gradle`, necesario para builds con Gradle moderno.
- Mantiene compatibilidad con:
  - ✅ Android
  - ✅ iOS
  - ✅ Navegador (modo stub sin escaneo real)
  - ⚠️ Windows (no probado)
- Mantiene la **API original** para evitar cambios en el código de tu app.

---

## 📦 Instalación

Desde GitHub:

```bash
cordova plugin add https://github.com/LJSancibrian/cordova-plugin-qrscanner-secore.git
