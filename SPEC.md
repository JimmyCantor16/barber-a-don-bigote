# Especificación y plan

## Qué se construye
Landing page premium para la Barbería Don Bigote con información de servicios, paquetes, galería, horario y reserva vía WhatsApp

## Pantallas que verás
- Home
- Servicios
- Paquetes
- Galería
- Horario
- Contacto

## Datos del sistema
- Servicio
- Paquete
- ImagenGaleria
- Testimonio
- Horario
- Contacto

## API del backend
- GET /api/servicios
- GET /api/paquetes
- GET /api/galeria
- GET /api/testimonios
- GET /api/horario
- POST /api/contacto

## Para considerarlo funcional, debes VER
- Home muestra hero con foto de alta calidad, tagline, botón flotante WhatsApp, horario resumido y tarjetas de servicios destacados
- Servicios muestra una cuadrícula de tarjetas con nombre, descripción breve, precio y micro‑interacción hover
- Paquetes muestra tarjetas con nombre, descripción, precio, lista de beneficios y botón reservar que abre WhatsApp
- Galería muestra una galería responsive de imágenes con efecto lightbox
- Horario muestra una tabla clara de días (lunes‑sábado) y rango 9:00‑20:00 con estado vacío si el día está cerrado
- Contacto muestra botón WhatsApp y formulario de contacto con validación visual y mensaje de éxito/error simulado
- Todas las vistas se adaptan a móvil y desktop, incluyen estados vacíos (sin datos) y mensajes de error amigables, y micro‑interacciones sutiles en botones y tarjetas

## Stack
Frontend React con Vite y Tailwind CSS; Backend Node.js + Express (TypeScript) para servir los endpoints; despliegue estático en Netlify o Vercel
