# LATAM Launch Cockpit

MVP para gestionar lanzamientos de productos por mercado. Incluye cockpit regional, alta de productos y lanzamientos, hitos con plan original/estimación/fecha real, registro de riesgos y acciones, filtros y persistencia local.

## Requisitos

- Node.js 18 o superior
- npm

## Ejecución

```powershell
npm install
npm run dev
```

Vite mostrará la URL local disponible, normalmente `http://localhost:5173`.

## Datos y alcance

El modelo tipado y normalizado está en `src/model.ts`; la demostración inicial está en `src/seed.ts`. El blueprint de requisitos, roles, relaciones, pantallas y automatizaciones está en `docs/MVP-Blueprint.md`.

Este MVP guarda la información en `localStorage` del navegador y permite descargar una copia JSON. Los datos no se comparten entre usuarios o dispositivos. Para operación multiusuario, el siguiente incremento debe incorporar API, base de datos relacional, autenticación y autorización por rol; no hay integraciones automáticas con ERP ni sistemas externos.
