# 🏦 Aplicación Bancaria - JavaScript

[![HTML](https://img.shields.io/badge/HTML-100%25-orange)](https://github.com/claudio-hcn/actividad-L5-M2)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.x-purple)](https://getbootstrap.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)](https://www.javascript.com/)
[![GitHub Pages](https://img.shields.io/badge/demo-online-success)](https://claudio-hcn.github.io/actividad-L5-M2/)

> Aplicación web bancaria desarrollada con HTML, Bootstrap y JavaScript - Lección 5, Módulo 2

## 🌐 Demo en Vivo

Prueba la aplicación aquí: **[https://claudio-hcn.github.io/actividad-L5-M2/](https://claudio-hcn.github.io/actividad-L5-M2/)**


## 🔐 Credenciales de Acceso

Para iniciar sesión en la aplicación, utiliza las siguientes credenciales:

**Usuario:** `admin@email.com`  
**Contraseña:** `admin123`

> ⚠️ **Nota**: Estas son credenciales de demostración. En un entorno de producción real, nunca debes usar credenciales tan simples ni compartirlas públicamente.

## 📝 Descripción

Este proyecto es una aplicación web bancaria completa que simula las operaciones básicas de un sistema bancario. Desarrollada como parte de un ejercicio educativo, permite a los usuarios realizar depósitos, transferencias y consultar el historial de transacciones mediante una interfaz intuitiva y responsiva.

**Los datos se almacenan localmente en el navegador mediante LocalStorage**, lo que permite que la información persista incluso después de cerrar la página o el navegador, manteniendo el historial de transacciones y el saldo actualizado entre sesiones.

## ✨ Características Principales

- 🏠 **Página de Inicio**: Portal de bienvenida con acceso directo a todas las funcionalidades
- 📋 **Menú de Navegación**: Sistema de navegación claro e intuitivo
- 💰 **Gestión de Depósitos**: Realiza depósitos en tu cuenta de forma sencilla
- 💸 **Transferencias**: Envía dinero a otras cuentas con validación de datos
- 📊 **Historial de Transacciones**: Visualiza todas tus operaciones realizadas
- 📱 **Diseño Responsivo**: Adaptado perfectamente a dispositivos móviles, tablets y escritorio
- ⚡ **Interfaz Dinámica**: Interacciones fluidas gracias a JavaScript
- 💾 **Persistencia de Datos**: Almacenamiento local que mantiene los datos incluso después de cerrar el navegador

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica de la aplicación
- **CSS3**: Estilos personalizados y diseño visual
- **Bootstrap**: Framework CSS para diseño responsivo y componentes UI
- **JavaScript**: Lógica de negocio y manipulación del DOM
- **LocalStorage API**: Almacenamiento persistente de datos en el navegador
- **GitHub Pages**: Hosting y despliegue de la aplicación

## 📂 Estructura del Proyecto

```
actividad-L5-M2/
│
├── .vscode/                  # Configuración del editor VS Code
│   └── settings.json         # Preferencias del workspace
│
├── index.html                # Página principal/home
├── menu.html                 # Menú principal de operaciones
├── deposit.html              # Módulo de depósitos
├── sendmoney.html            # Módulo de transferencias
├── transactions.html         # Historial de movimientos
├── .gitignore               # Archivos ignorados por Git
└── readme.md                # Documentación del proyecto
```

## 🚀 Instalación y Ejecución

### Prerrequisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet (para cargar Bootstrap desde CDN)

### Pasos para ejecutar

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/claudio-hcn/actividad-L5-M2.git
   ```

2. **Navegar al directorio del proyecto**
   ```bash
   cd actividad-L5-M2
   ```

3. **Abrir en el navegador**
   - Opción 1: Doble clic en `index.html`
   - Opción 2: Usar Live Server en VS Code
   - Opción 3: Servir con un servidor local
     ```bash
     # Con Python 3
     python -m http.server 8000
     
     # Con Node.js (usando http-server)
     npx http-server
     ```

4. **Acceder a la aplicación**
   - Abre tu navegador en `http://localhost:8000` (si usas servidor local)
   - O simplemente abre el archivo `index.html` directamente
   - O visita la demo en línea: [https://claudio-hcn.github.io/actividad-L5-M2/](https://claudio-hcn.github.io/actividad-L5-M2/)

## 🎯 Funcionalidades

### 1. Página de Inicio (`index.html`)
Punto de entrada de la aplicación con presentación del sistema bancario.

### 2. Menú Principal (`menu.html`)
Dashboard con acceso rápido a todas las operaciones bancarias disponibles.

### 3. Depósitos (`deposit.html`)
- Formulario para ingresar monto de depósito
- Validación de datos en tiempo real
- Confirmación de operación exitosa

### 4. Envío de Dinero (`sendmoney.html`)
- Selección de cuenta destino
- Ingreso de monto a transferir
- Validación de fondos suficientes
- Confirmación de transferencia

### 5. Historial de Transacciones (`transactions.html`)
- Listado completo de operaciones realizadas
- Filtrado por tipo de transacción
- Información detallada de cada movimiento
- **Datos almacenados en LocalStorage**: Todas las transacciones se guardan localmente y persisten entre sesiones

## 💾 Almacenamiento de Datos

La aplicación utiliza **LocalStorage** para guardar la información del usuario:

- ✅ **Saldo de cuenta**: Se mantiene actualizado después de cada operación
- ✅ **Historial de transacciones**: Todas las operaciones quedan registradas
- ✅ **Sesión de usuario**: Los datos persisten al cerrar y reabrir el navegador
- ✅ **Datos locales**: No se envía información a ningún servidor externo

Para **limpiar los datos almacenados**, puedes:
- Usar las herramientas de desarrollador del navegador (F12 → Application → Local Storage)
- Borrar el historial y datos del navegador
- Usar la funcionalidad de "Limpiar datos" dentro de la aplicación (si está implementada)

## 💡 Conceptos Aplicados

Este proyecto implementa conceptos clave de desarrollo web:

- **DOM Manipulation**: Modificación dinámica del contenido HTML
- **Event Handling**: Gestión de eventos del usuario
- **Form Validation**: Validación de formularios con JavaScript
- **Local Storage**: Almacenamiento de datos en el navegador
- **Bootstrap Components**: Uso de componentes prediseñados (cards, forms, navbars)
- **Responsive Design**: Diseño adaptable con sistema de grid
- **Navigation**: Navegación multi-página con estado persistente

## 🎓 Aprendizajes

Este proyecto está diseñado para practicar:

- ✅ Manipulación del DOM con JavaScript
- ✅ Integración de Bootstrap en proyectos web
- ✅ Validación de formularios
- ✅ Gestión de estado de la aplicación
- ✅ Diseño responsivo mobile-first
- ✅ Estructura modular de aplicaciones web
- ✅ Buenas prácticas de código limpio

## 📸 Capturas de Pantalla

> *Agrega aquí capturas de pantalla de tu aplicación*

## 🔮 Futuras Mejoras

- [ ] Implementar backend con Node.js/Express
- [ ] Agregar autenticación de usuarios
- [ ] Conectar con base de datos (MongoDB/PostgreSQL)
- [ ] Implementar API REST para operaciones
- [ ] Agregar gráficos de análisis financiero
- [ ] Implementar notificaciones en tiempo real
- [ ] Agregar exportación de transacciones a PDF/Excel

## 👨‍💻 Autor

**Claudio HCN**

- GitHub: [@claudio-hcn](https://github.com/claudio-hcn)
- Proyecto: [actividad-L5-M2](https://github.com/claudio-hcn/actividad-L5-M2)

## 📄 Licencia

Este proyecto es de código abierto y está disponible para fines educativos.

## 🤝 Contribuciones

Este es un proyecto de aprendizaje, pero las sugerencias y mejoras son bienvenidas:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/mejora`)
3. Commit tus cambios (`git commit -m 'Agrega nueva característica'`)
4. Push a la rama (`git push origin feature/mejora`)
5. Abre un Pull Request

## ⚠️ Nota Importante

Este es un proyecto educativo con fines de demostración. **No incluye funcionalidad de backend real** ni procesamiento de transacciones bancarias reales. 

- **Datos locales**: Toda la información se almacena únicamente en el navegador del usuario mediante LocalStorage
- **Sin servidor**: No hay comunicación con servidores externos ni bases de datos
- **Solo demostración**: No utilices esta aplicación para gestionar dinero real
- **Seguridad limitada**: Las credenciales son solo para propósitos de demostración

## 🚀 Despliegue en GitHub Pages

Este proyecto está desplegado en GitHub Pages. Si quieres hacer tu propio despliegue:

1. Ve a la configuración del repositorio en GitHub
2. Navega a **Settings** → **Pages**
3. En **Source**, selecciona la rama `main` o `master`
4. Guarda los cambios
5. Tu sitio estará disponible en: `https://tu-usuario.github.io/actividad-L5-M2/`

## 📞 Soporte

Si tienes preguntas o sugerencias, no dudes en:
- Abrir un [Issue](https://github.com/claudio-hcn/actividad-L5-M2/issues)
- Contactar al autor a través de GitHub

---

⭐ Si este proyecto te fue útil, considera darle una estrella en GitHub

**Desarrollado con ❤️ como parte del Módulo 2 - Lección 5**