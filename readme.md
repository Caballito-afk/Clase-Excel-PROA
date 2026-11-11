# 📊 Laboratorio Interactivo de Excel: Sistema del Kiosco Escolar

Una plataforma web interactiva diseñada para guiar a los estudiantes en la construcción paso a paso de un sistema completo de gestión de inventario para un kiosco escolar en Microsoft Excel.

## 🎯 Objetivo Pedagógico

El objetivo de esta guía es afianzar el dominio de las funciones lógicas, matemáticas y de búsqueda en Excel. La ejercitación se realiza de forma **acumulativa sobre una única planilla de cálculo**, avanzando por etapas secuenciales con un sistema de candados dinámicos que garantizan la correcta ejecución de cada consigna antes de pasar a la siguiente.

---

## 🛠️ Estructura del Proyecto (5 Etapas Progresivas)

La planilla del kiosco se construye progresivamente a través de las siguientes etapas:

| Etapa | Tema / Función | Descripción |
| :--- | :--- | :--- |
| **Etapa 1** | **Estructura e Inventario** | Carga inicial de datos de productos (categoría, stock, precio costo y venta) y aplicación del formato numérico de moneda ($). |
| **Etapa 2** | **Operaciones Matemáticas y SUMA** | Incorporación de fórmulas directas para calcular el *Valor Total del Stock* (`Cantidad * Precio Venta`), la *Ganancia Unitaria* (`Precio Venta - Precio Costo`) y la inversión total con `=SUMA()`. |
| **Etapa 3** | **Lógica Condicional (SI)** | Creación de la columna *Estado Reposición* utilizando `=SI()` para identificar productos con stock crítico ($\le 10$ unidades) y aplicación de Formato Condicional. |
| **Etapa 4** | **Conteo Estadístico (CONTAR.SI)** | Construcción de un panel de indicadores para cuantificar automáticamente la cantidad de productos en estado "OK" y "REPONER URGENTE". |
| **Etapa 5** | **Búsqueda Dinámica (BUSCARV)** | Creación de una casilla de consulta rápida para atención al cliente utilizando `=BUSCARV()` para obtener el precio de venta de cualquier producto en tiempo real. |

---

## 🚀 Características de la Plataforma Web Interactiva

* **Sistema de Bloqueo por Etapas:** Pestañas correlativas que se desbloquean automáticamente al completar el 100% de las tareas de la fase actual.
* **Barra de Progreso Dinámica:** Cálculo en tiempo real del porcentaje global de avance de la guía.
* **Secciones Desplegables de Ayuda:** Pistas de sintaxis y recomendaciones prácticas ocultas debajo de cada actividad.
* **100% Autocontenido:** Desarrollado en un único archivo HTML (`.html`) listo para abrir en cualquier navegador web sin dependencias externas ni conexión a internet.

---

## 💻 Instrucciones de Uso

1. Descarga o abre el archivo `.html` en cualquier navegador web moderno (Chrome, Edge, Firefox).
2. Abre Microsoft Excel o Google Sheets en una ventana paralela.
3. Lee las consignas de la **Etapa 1**, completa las tareas en tu planilla y marca los casilleros de verificación (`checkboxes`) en la página web.
4. Una vez completadas las casillas de la etapa, haz clic en el botón de la siguiente etapa para desbloquear el nuevo desafío.

---

*Proyecto desarrollado para la escuela ProA.*