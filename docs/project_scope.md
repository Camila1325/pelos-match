# Alcance del Proyecto: "Pelos Match" 🐾

## 1. Descripción General
"Pelos Match" es una aplicación web inspirada en la dinámica de "swipe" de aplicaciones de citas, pero enfocada exclusivamente en la adopción de animales. [cite_start]Su objetivo es conectar de manera lúdica y emocional a personas que buscan adoptar con mascotas que viven en hogares de paso o refugios.

## 2. Usuario Objetivo
* *Adoptantes:* Personas interesadas en encontrar una mascota que se adapte a su estilo de vida.
* *Hogares de Paso / Refugios:* Entidades o personas que necesitan dar visibilidad a los animales rescatados para encontrarles un hogar definitivo.

## 3. Funcionalidades Principales (Core Features)
Para cumplir con el enfoque incremental del proyecto, se definen las siguientes funcionalidades:

1. *Interfaz de Emparejamiento (Match):* Una vista principal donde se presentan tarjetas visuales con fotos de los animales, nombre, edad y temperamento.
2. *Sistema de Swipe:* Botones visuales (o gestos en el futuro) para indicar "Me interesa" (corazón) o "Siguiente" (equis).
3. *Detalle de la Mascota:* Al hacer clic en una tarjeta, se despliega información sobre la historia del animal, cuidados especiales y requisitos de adopción.
4. *Lista de Favoritos:* Una sección donde el usuario puede ver todos los perfiles a los que les dio "Match" para iniciar el contacto.

## 4. Reglas de Negocio e Implementación Técnica
* *Persistencia:* En la fase inicial, los datos de los animales y los favoritos se gestionarán mediante LocalStorage de JavaScript.
* *Enfoque Visual:* La interfaz debe ser "Mobile First", priorizando el uso de tarjetas (cards) y una navegación táctil sencilla.