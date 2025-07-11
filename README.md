# reto-login

# 🔒 Sistema de Autenticación Segura

![Login Demo](https://via.placeholder.com/600x400?text=Captura+del+Formulario+de+Login)

Un sistema de autenticación que utiliza hash SHA-256 para proteger las credenciales.

## ✨ Características Principales
- Validación de campos de usuario y contraseña
- Encriptación de contraseñas con SHA-256
- Botón para mostrar/ocultar contraseña
- Mensajes claros de error/éxito

## 🛠️ Tecnologías Utilizadas
- HTML5
- JavaScript (ES6)
- CryptoJS para generación de hashes

## 🚀 Cómo Usar
1. Clona este repositorio
2. Abre `index.html` en tu navegador
3. Ingresa las credenciales:
   - Usuario: admin
   - Contraseña: admin123*

## 📝 Notas de Implementación
- El hash almacenado es: `0208788aa...`
- La validación se realiza comparando hashes
- Código modularizado en diferentes archivos JS

```javascript
// Ejemplo de generación de hash
const hash = generateSHA256Hash('admin123*');
```

## 📜 Licencia
MIT 2025 </DevJuseth>
