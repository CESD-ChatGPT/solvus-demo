# solvus-demo

Demo pública del ChatBot Stock de SOLVUS. Es un servicio aparte de la landing:
sin login, con datos ficticios y en modo solo lectura.

## Desarrollo

```
npm install
npm run dev
```

## Publicación

Cloudflare Pages compila cada cambio que se sube a la rama de producción:

- Comando de build: `npm run build`
- Carpeta de salida: `dist`

Los datos de la demo están en `src/pages/DemoVento.jsx`. No hay conexión con Vento
ni con las bases reales.
