---
name: "🐞 Bug Report"
about: "Reportar un error encontrado en la aplicación"
title: "[BUG] "
labels: bug
assignees: ""
---

## 🐛 Título
Error al iniciar sesión con credenciales válidas

## 📋 Descripción
El sistema no permite iniciar sesión aunque se ingresen credenciales correctas.

## 🔁 Pasos para reproducir
1. Abrir la aplicación web.
2. Ir a la pantalla de Login.
3. Ingresar usuario: `usuario@test.com`
4. Ingresar contraseña: `123456`
5. Presionar el botón **Iniciar Sesión**.

## ❌ Resultado actual
Se muestra el mensaje: **"Credenciales inválidas"**.

## ✅ Resultado esperado
El usuario debería poder iniciar sesión correctamente y ser redirigido al **Dashboard**.

## ⚠️ Severidad
Alta (bloquea a todos los usuarios).

## 💻 Entorno
- Navegador: Google Chrome 127.0  
- SO: Windows 11  
- Versión de la app: v1.2.0
