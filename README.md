# Caminata del Amor — Demo interactiva

Prototipo clickeable del wireframe de la app **Caminata del Amor**, hecho en HTML/CSS/JS (sin build ni dependencias) a partir del diseño trabajado en Pencil.

## Ver la demo

👉 **[Abrir la demo](https://REPLACE_WITH_PAGES_URL/)**

Es un mock de las 6 pantallas de la app con navegación real:

1. **Crear perfil** — formulario completo con preguntas condicionales (Condición, Bautismo/Espíritu Santo si sos Miembro, Terapia del Amor, relación anterior, Altar, disposición a conocer alguien).
2. **Mi Perfil** — resumen del perfil, switch para activar/desactivar "dispuesta a conocer a alguien", acceso a notificaciones.
3. **Caminata del Amor** — elegir ubicación del día, ver quién compartió sus datos con vos, buscar a alguien.
4. **Buscar persona** — resultados con distintos niveles de acceso (match completo, ubicación privada, solicitud pendiente, no disponible).
5. **Notificaciones** — aceptar o rechazar una solicitud de datos (afecta en vivo lo que se ve en Caminata del Amor).
6. **Datos compartidos** — perfil completo de alguien que aceptó compartir sus datos.

## Correr localmente

```bash
node server.js
```

Abre en `http://localhost:8935`.

No hay backend real: todo el estado vive en memoria del navegador (se resetea al recargar la página).

---
Meta Web — prototipo de referencia, no es el producto final.
