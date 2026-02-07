# 💎 DR Premium Utilities | Ecosistema 2.0
> **Arquitectura Híbrida de Alta Gama:** Firebase + Supabase + Jetpack Compose.

Este ecosistema representa una solución digital de vanguardia diseñada para la gestión de inventarios y experiencias de usuario premium. Construido bajo una arquitectura robusta, combina la potencia de procesamiento de datos en tiempo real de Firebase con el almacenamiento eficiente de Supabase y una interfaz moderna en Jetpack Compose.

---

## 🏗️ Arquitectura y Stack Tecnológico

El proyecto se fundamenta en principios de diseño modernos y una ingeniería de software escalable:

* **Frontend:** Jetpack Compose (Estética Glassmorphism).
* **Backend & Auth:** Firebase (Authentication & Firestore).
* **Storage:** Supabase Storage (Gestión de activos multimedia).
* **Patrón de Diseño:** MVVM (Model-View-ViewModel) + Clean Architecture.
* **Librerías Clave:** Coil (Carga asíncrona), Type-safe Navigation, Snapshots en tiempo real.

---

## 🛡️ Seguridad y Control de Acceso

El sistema implementa una lógica de permisos jerárquica para garantizar la integridad de los datos:

### 1. Panel Administrativo (Master CRUD)
* **Validación:** Control mediante `UID` y dominios de correo jerárquicos.
* **Capacidades:** Gestión total de stock, control de usuarios y acceso a un panel de control flotante exclusivo.

### 2. Experiencia del Cliente
* **Gestión de Perfil:** Autenticación fluida y persistencia de datos.
* **Interacción:** Historial de compras personalizado y persistencia de carrito de compras sincronizado.

---

## 📦 Gestión de Inventario & E-commerce

El núcleo del ecosistema permite una administración granular del catálogo de productos:

| Funcionalidad | Descripción | Tec. Principal |
| :--- | :--- | :--- |
| **CRUD Maestro** | Alta, baja y edición de productos con validaciones estrictas. | Firestore |
| **Sincronización** | Actualización instantánea de stock en todos los clientes conectados. | Snapshots |
| **Multimedia** | Vinculación de imágenes de alta resolución mediante URLs dinámicas. | Supabase |
| **Cálculo Métrico** | Gestión de unidades automática (ml, gr, oz) para perfumería. | Kotlin Logic |

---

## 🚀 Highlights Técnicos (Informe de Rendimiento)

* **Estética Premium:** Interfaz basada en **Glassmorphism** con efectos de desenfoque y gradientes mesh.
* **Optimización de Datos:** Prevención de errores de tipo (Double/Long) en la persistencia de Firestore.
* **UX Fluida:** Implementación de *Skeleton Screens* y *Shimmer Effects* para una carga percibida ultra-rápida.
* **Reactividad:** Filtrado de productos por departamentos en tiempo real sin recarga de página.

---

## 🎥 Demos de Funcionamiento

### UX & Navegación Premium
Visualización del flujo de usuario, animaciones de categorías y diseño de tienda de alta gama.
[Aquí iría tu video de UX]

### Backend & Sincronización Real-Time
Demostración de la entrada de datos simultánea en Firebase y Supabase.
[Aquí iría tu video de Backend]

---

## 📩 Contacto y Colaboración

Para consultas técnicas, soporte especializado o propuestas de colaboración sobre este ecosistema:

* **Desarrollador:** Diego Ruperti
* **Email:** [diegoruperti1987@hotmail.com](mailto:diegoruperti1987@hotmail.com)
* **Web:** [Explorar Demo Live](https://diegofernandorupertigordon-glitch.github.io/Html-Utility-2.0/)

---
<p align="center">
  <b>© 2026 DR PREMIUM UTILITIES</b><br>
  Desarrollado con precisión técnica y enfoque en el diseño de lujo.
</p>
