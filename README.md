Hola, este es mi primer proyecto en base a lo que estoy aprendiendo en mi carrera

# 🍎 Sistema de Gestión - Verdulería

¡Bienvenido al sistema de gestión de inventario para una verdulería! Este proyecto nació como un desafío académico para implementar y dominar las estructuras lógicas fundamentales de la programación y el desarrollo Full Stack. 

La aplicación permite administrar el stock de productos (nombre, precio por kg y cantidad disponible) a través de una interfaz limpia, interactiva y funcional desplegada en la web.

---

## 🚀 Demo En Vivo
Puedes ver y probar la aplicación web funcionando directamente en el navegador a través de GitHub Pages:
👉 **https://stevenjajw-lang.github.io/gestion-verduleria/**

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructuración de las secciones, formularios y maquetación de la interfaz de usuario.
* **CSS3:** Estilos personalizados, paleta de colores temática (Verdulía), diseño de tarjetas (`box-shadow`) y adaptabilidad.
* **JavaScript (Vanilla):** El "cerebro" de la aplicación. Manejo del DOM, control de eventos y toda la lógica algorítmica.

---

## 🧠 Conceptos de Programación Aplicados

Este proyecto traduce la lógica dura aprendida en Pseudocódigo/PSeInt a un entorno web real, implementando:

* **Vectores / Arrays en Paralelo:** Uso de tres arreglos independientes (`v_nombres`, `v_precios`, `v_stock`) sincronizados mediante el mismo índice para mantener la integridad de los datos de cada producto.
* **Ciclos Iterativos (`for`):** Implementados para recorrer los vectores fila por fila al momento de listar los productos o buscar elementos específicos.
* **Estructuras Condicionales (`if / else`):** Validación de datos de entrada (que no queden campos vacíos) y control del estado de las búsquedas (si el producto existe o no).
* **Acumuladores:** Lógica matemática integrada para multiplicar dinámicamente el `precio * stock` de cada producto y acumular el valor monetario total de toda la mercadería disponible.
* **Algoritmo de Eliminación:** Desplazamiento y reordenamiento de los índices de los vectores al dar de baja un producto para evitar "huecos" vacíos en la memoria.

---

## 📋 Características del Menú

1.  **Agregar Producto:** Permite ingresar un nuevo artículo con su precio y stock correspondiente.
2.  **Mostrar Productos:** Renderiza el inventario completo en pantalla y calcula automáticamente el valor total de la mercadería en stock.
3.  **Buscar Producto:** Encuentra y muestra en tiempo real los detalles de un producto específico ingresando su nombre.
4.  **Modificar Precio:** Permite actualizar de forma directa el precio de cualquier artículo existente en el sistema.
5.  **Eliminar Producto:** Da de baja un artículo y reorganiza el inventario automáticamente.

---

## 🧑‍💻 Autor

* **Steven Alconada** - *Estudiante de Programación Full Stack* - [Tu GitHub](https://github.com/stevenjajw-lang)
