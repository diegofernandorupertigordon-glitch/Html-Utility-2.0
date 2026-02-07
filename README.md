💎 DR Premium Utilities & Perfumery Ecosystem










DR Premium Utilities es un ecosistema móvil de alto rendimiento y estética premium, diseñado para combinar herramientas profesionales con un sistema de e-commerce exclusivo para perfumería de lujo.

El proyecto prioriza experiencia visual, seguridad, escalabilidad y sincronización en tiempo real, integrando múltiples servicios cloud bajo una arquitectura limpia y moderna.

🌌 Experiencia de Usuario (UX/UI)

La aplicación adopta un lenguaje visual High-End, enfocado en elegancia, claridad y fluidez:

Neon Cyan Aesthetics
Acentos en #00E5FF que refuerzan jerarquía visual y navegación intuitiva.

Glassmorphism & Depth
Contenedores translúcidos, bordes suaves y sombras dinámicas (spotColor) para sensación de profundidad premium.

Micro-interacciones
Animaciones sutiles de entrada (Alpha / Scale) y transiciones de estado con HorizontalPager.

Skeleton Loading
Pantallas de carga elegantes que reducen la percepción de espera y mejoran la experiencia continua.

🚀 Características Principales
🔐 Seguridad y Autenticación

Multi-Auth: Email/Password y Google Sign-In.

RBAC (Role-Based Access Control):
Acceso administrativo validado por UID + Email en tiempo real.

Sesión Persistente:
Manejo seguro de tokens y control de revocación de accesos.

🧴 E-Commerce de Perfumería Premium

Catálogo Inteligente:
Organización por departamentos (Perfumería, Maquillaje, Accesorios).

Búsqueda Reactiva:
Filtrado dinámico en tiempo real mediante StateFlow.

Fichas de Producto Avanzadas:
Manejo de unidades (ml, gr, oz) con sincronización directa al stock en Firestore.

Carrito Persistente:
Estado de compra conservado por sesión de usuario.

🛠️ Herramientas Utility

Módulo integrado de utilidades profesionales.

Arquitectura desacoplada y escalable.

Preparado para expansión futura del ecosistema.

🧠 Arquitectura del Sistema

Patrón: MVVM + Clean Architecture

Gestión de Estado: StateFlow

Sincronización: Real-time updates con Firestore Snapshots

Separación de Capas: UI / Domain / Data

Diseñada para mantenibilidad, testabilidad y crecimiento sostenido.

🛠️ Stack Tecnológico

Lenguaje:
Kotlin
 — Moderno, seguro y expresivo.

UI:
Jetpack Compose
 — UI declarativa con Material 3.

Backend:
Firebase

Authentication: Gestión global de usuarios.

Firestore: Base de datos NoSQL en tiempo real.

Storage:
Supabase Storage
 — Gestión de activos multimedia (imágenes de productos).

Carga de Imágenes:
Coil
 — Caché optimizada y crossfade.

Navegación:
Type-safe Navigation Graph.

📦 Instalación y Configuración

Clonar el repositorio

git clone https://github.com/diegofernandorupertigordon-glitch/DR.git


Configurar Firebase

Crear un proyecto en Firebase Console.

Añadir google-services.json en app/.

Habilitar Authentication (Email & Google).

Configurar Firestore Database.

Ejecutar el proyecto

Abrir en Android Studio (Ladybug o superior).

Sincronizar Gradle.

Ejecutar en dispositivo físico o emulador.

👤 Developer & Admin

El acceso administrativo está preconfigurado para el ecosistema del desarrollador principal:

Lead Developer: Diego Ruperti

Admin Email: diegoruperti1987@hotmail.com

🌐 Demo Web

🔗 https://diegofernandorupertigordon-glitch.github.io/Html-Utility-2.0/

📜 Licencia

Este proyecto es propiedad intelectual de Diego Ruperti.
Uso, modificación o distribución sin autorización expresa no permitidos.

Diseñado con precisión, estética y visión de producto premium. ✨
