## Resumen

<!-- Qué cambia y por qué. -->

## Rama destino

<!-- dev (integración) · main (producción) — borrar la que no aplique. -->

## Épica / HU relacionada

<!-- Ej: Epic 1 · HU-1.2 — o "N/A" si es infraestructura/tooling. -->

## Checklist

- [ ] Corrí `npm run audit`, `npm run format:check`, `npm run lint`, `npm run spell`, `npm run build` y `npm test` en local sin errores
- [ ] Si el cambio toca `src/prisma/contract.prisma`, corrí `npm run contract:emit` y commiteé los archivos generados
- [ ] Actualicé `AGENTS.md` si el cambio resuelve o agrega algo a la sección TODO
- [ ] No quedaron `console.log`, código comentado ni TODOs sueltos
