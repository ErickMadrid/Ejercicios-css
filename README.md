# Ejercicios de Introducción a CSS

Este repositorio contiene la resolución de la guía de ejercicios prácticos de CSS. 

## Nota para la Corrección 📑
Para facilitar la visualización y pruebas de cada ejercicio, **las reglas de estilo CSS han sido integradas directamente dentro de cada archivo HTML** utilizando la etiqueta `<style>` en el `<head>`. 

Se optó por esta estructura autocontenida por las siguientes razones:
1. **Demostración Práctica:** El CSS requiere un contexto estructural (etiquetas HTML) para poder aplicar sus efectos visuales.
2. **Independencia:** Cada ejercicio es un archivo autónomo y limpio, evitando mezclar estos conceptos nuevos con tareas de unidades anteriores.
3. **Facilidad de Revisión:** Permite abrir cualquier archivo `.html` directamente en el navegador para comprobar el funcionamiento inmediato de los estilos sin dependencias externas.

---

## Detalle de los Ejercicios Resolvidos 🛠️

### Ejercicio 1: Agrupación de Selectores
* **Archivo:** `ejercicio1.html`
* **Objetivo:** Aplicar una misma regla de diseño a múltiples elementos simultáneamente.
* **Concepto:** Uso de comas (`,`) para agrupar selectores (`p, h6`), demostrando cómo comparten propiedades base mientras mantienen sus propiedades nativas de navegador (como el peso de fuente por defecto).

### Ejercicio 2: Herencia de Propiedades
* **Archivo:** `ejercicio2.html`
* **Objetivo:** Comprender la transmisión de estilos desde elementos padres a hijos.
* **Concepto:** Definición de propiedades en el nodo `body` que son heredadas de forma automática por un párrafo (`p`), y cómo los encabezados (`h1`, `h2`, `h3`) redefinen selectivamente su propia tipografía.

### Ejercicio 3: Estilos en Función del Contexto
* **Archivo:** `ejercicio3.html`
* **Objetivo:** Aplicar estilos específicos basados en la ubicación jerárquica de un elemento.
* **Concepto:** Selectores descendientes (`h1 em`, `h2 em`, etc.) combinados con una escala de grises exacta mediante códigos hexadecimales de canales idénticos.

### Ejercicio 4: Estilos por Medio de Clases
* **Archivo:** `ejercicio4.html`
* **Objetivo:** Crear estilos modulares y reutilizables en cualquier parte del documento.
* **Concepto:** Declaración de clases en CSS mediante el punto (`.subrayado`, `.tachado`) y su implementación inline mediante la etiqueta genérica `<span>`.

### Ejercicio 5: Estilos por Medio de ID
* **Archivo:** `ejercicio5.html`
* **Objetivo:** Diseñar identificadores únicos para la maquetación estructural de bloques.
* **Concepto:** Declaración de selectores de identidad con el símbolo numeral (`#cabecera`, `#cuerpo`, `#pie`) aplicados de manera unívoca a contenedores estructurales `<div>`.
