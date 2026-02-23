# Sistema de Diseño: Pelos Match 🐾

Este documento establece los diseños visuales y de estilo para el proyecto.

## 1. Paleta de Colores (Colección Astral)
Basado en la escala cromática de azules profesionales para transmitir confianza y tranquilidad en el proceso de adopción.

* Primario (Acción): #3486AC (Astral 500) - Utilizar en botones principales de "Match", enlaces activos y elementos de marca.
* Secundario (Soporte): #87C2D9 (Astral 300) - Utilizar para bordes de tarjetas, iconos secundarios y estados de desactivado.
* Fondo General: #F0F8FB (Astral 50) - Color base para la aplicación para mantener una estética limpia y amigable.
* Texto Principal: #152737 (Astral 950) - Para máxima legibilidad en títulos y descripciones de las mascotas.
* Acento de Interacción: #2A5774 (Astral 700) - Usar en estados de hover y encabezados destacados.

## 2. Tipografía "Animalista" y Amigable

* Fuente Principal: 'Quicksand' o 'Fredoka'. 
* Encabezados (H1, H2): Bold, color Astral 950. 
* Cuerpo: Regular, tamaño 16px para asegurar legibilidad en dispositivos móviles.

## 3. Componentes de Interfaz 

* **Tarjetas de Mascotas (Cards):**
    * Fondo blanco puro (`bg-white`).
    * Bordes muy redondeados (`rounded-3xl` / `20px`).
    * Sombra suave para profundidad (`shadow-lg`).
* **Botones de Acción (Swipe):**
    * Forma circular o de píldora (`rounded-full`).
    * Padding amplio para facilitar el toque en móviles.
    * Efecto de escala al presionar para feedback táctil.

## 4. Layout y Espaciado
* **Enfoque:** Mobile-First (Diseño priorizado para pantallas táctiles).
* **Sistema de Grilla:** Basado en múltiplos de 8px (utilizando `gap-4`, `m-8`, etc., de Tailwind).