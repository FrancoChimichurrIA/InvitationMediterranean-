# Formal Request Mediterráneo

Mini web de invitación estilo **Formal · Mediterranean · Request**.

## Qué incluye

- `index.html` único, con CSS y JS embebido.
- Estética Italia x Grecia.
- Botón “No” que escapa.
- Selección de horario: 21:00, 21:15, 21:30.
- Selección de comida.
- Dirección o ubicación actual.
- Resumen final y envío por WhatsApp.
- Música generada con Web Audio API, sin archivos externos.

## Configuración rápida

En `index.html`, buscar:

```js
const CONFIG={
  firma:'Franco',
  whatsapp:'5493416674074',
  dia:{label:'Sábado'},
  ...
};
```

Cambiar solo esos valores si hace falta.

## Deploy recomendado

Subir a Vercel como proyecto nuevo. No reutilizar el deploy del repo anterior.
