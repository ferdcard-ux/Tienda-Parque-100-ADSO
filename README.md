# Tienda Virtual Parque 100 - Maquetación UI
**Evidencia:** GA5-220501095-AA1-EV04 - Maquetación de la interfaz gráfica en HTML.  
**Programa:** Análisis y Desarrollo de Software (ADSO).

## Descripción
Este proyecto presenta la maquetación de la interfaz de usuario para la **Tienda Virtual Parque 100**. Se ha desarrollado siguiendo un enfoque de **Single Page Application (SPA)** mediante manipulación dinámica del DOM con JavaScript, permitiendo una navegación fluida sin recargas de página.

La interfaz está diseñada bajo el concepto *Mobile-First*, garantizando una experiencia óptima tanto en dispositivos móviles como en escritorio, utilizando **Tailwind CSS** para un diseño moderno, limpio y profesional.

---

## Características Principales
*   **Navegación Dinámica:** Cambio de vistas (Inicio, Categorías, Carrito, Perfil, Login) sin recargar el navegador.
*   **Sistema de Carrito Funcional:** Permite añadir productos, modificar cantidades y eliminar ítems con cálculo de totales en tiempo real.
*   **Buscador en Tiempo Real:** Filtro reactivo de productos por nombre o categoría.
*   **Simulación de Roles:** Sistema que adapta la interfaz según el perfil seleccionado (Usuario, Vendedor, Administrador).
    *   *Administrador:* Acceso exclusivo al panel de gestión de inventario.
*   **Componentes UI Avanzados:** Modales de dirección de envío, selectores de roles y estados de carga.
*   **Diseño Responsivo:** Menú de navegación inferior para móviles y encabezado extendido para escritorio.

---

## Tecnologías Utilizadas
*   **HTML5:** Estructura semántica de la aplicación.
*   **Tailwind CSS:** Framework de utilidades para el diseño visual y respuesta adaptativa.
*   **JavaScript (Vanilla):** Lógica de negocio, gestión de estado local y renderizado dinámico de componentes.
*   **FontAwesome:** Iconografía técnica y descriptiva.
*   **Google Fonts:** Tipografía optimizada para lectura en pantalla.

---

## Estructura del Proyecto
El archivo principal contiene toda la lógica necesaria para el prototipo:
*   `index.html`: Contiene el esqueleto HTML, los estilos embebidos de Tailwind y la lógica de script.
*   **Secciones Dinámicas:**
    *   `view-home`: Catálogo de productos y búsqueda.
    *   `view-categories`: Clasificación visual del catálogo.
    *   `view-cart`: Resumen de compra y checkout.
    *   `view-profile`: Gestión de datos de usuario y panel administrativo.
    *   `view-login`: Formulario de acceso autenticado.

---

## Instrucciones de Uso
1.  Clona este repositorio o descarga el archivo `index.html`.
2.  Abre el archivo en cualquier navegador moderno (Chrome, Edge, Firefox).
3.  **Para probar los roles:**
    *   Ve a la sección **Perfil**.
    *   Haz clic en "Cambiar Rol".
    *   Selecciona "Administrador" para ver cómo aparece dinámicamente el panel de inventario.
4.  **Para el proceso de compra:**
    *   Agrega productos desde la pestaña "Inicio".
    *   Dirígete al "Carrito", verifica los precios y haz clic en "Continuar" para ver el modal de dirección.

---

## Vista Previa del Prototipo


---

## Autores
**Miguel Fernando Cárdenas Alvear, Brandon Vergara, David Pardo**  
*Aprendices SENA - ADSO*
*Ficha: 3235894  *
*Barranquilla, Colombia*

---

### Licencia
Este proyecto se distribuye bajo fines educativos para el programa de formación ADSO del SENA.
