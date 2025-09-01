# Amigo Secreto

![Captura de pantalla de la aplicación](assets/amigo-secreto.png)

Una aplicación web interactiva para realizar sorteos aleatorios y determinar quién es el "amigo secreto" entre un grupo de personas.

## 📋 Descripción

Esta aplicación permite a los usuarios crear una lista de nombres de amigos y realizar un sorteo aleatorio para seleccionar quién será el amigo secreto. 
## ✨ Características

- **Agregar nombres**: Campo de texto para ingresar nombres de amigos
- **Validación de entrada**: Previene nombres vacíos con alertas informativas
- **Lista visual**: Muestra todos los nombres agregados en tiempo real
- **Sorteo aleatorio**: Selecciona un amigo secreto usando algoritmos aleatorios
- **Limpiar lista**: Botón para resetear toda la lista y resultados
- **Interfaz responsiva**: Diseño adaptativo para diferentes dispositivos
- **Diseño moderno**: UI atractiva con colores y tipografías profesionales

## 🚀 Funcionalidades

### 1. Gestión de Lista
- Agregar nombres individuales
- Validar que el campo no esté vacío
- Mostrar lista actualizada en tiempo real
- Limpiar toda la lista con un clic

### 2. Sistema de Sorteo
- Algoritmo aleatorio usando `Math.random()`
- Validación de lista no vacía
- Resultado visual destacado

### 3. Interfaz de Usuario
- Diseño limpio y moderno
- Botones con efectos hover
- Colores contrastantes para mejor legibilidad

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica y accesible
- **CSS3**: Estilos modernos con variables CSS y Flexbox
- **JavaScript Vanilla**: Lógica de programación pura sin frameworks
- **Responsive Design**: Adaptable a diferentes tamaños de pantalla

## 📁 Estructura del Proyecto

```
challenge-amigo-secreto/
├── index.html          # Página principal
├── style.css           # Estilos y diseño
├── app.js              # Lógica de la aplicación
├── assets/             # Recursos multimedia
│   ├── amigo-secreto.png
│   └── play_circle_outline.png
└── README.md           # Este archivo
```


## 💻 Código JavaScript

### Funciones Principales

```javascript
// Array para almacenar nombres
let amigos = [];

// Agregar amigo a la lista
function agregarAmigo() {
    // Validación y lógica de agregado
}

// Actualizar lista visual
function actualizarListaAmigos() {
    // Renderizado de la lista
}

// Sorteo aleatorio
function sortearAmigo() {
    // Algoritmo de selección aleatoria
}

// Limpiar toda la lista
function limpiarLista() {
    // Reset de datos y UI
}
```
