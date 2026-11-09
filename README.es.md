[Português](README.md) · [Español](README.es.md)

# DR 360° — Dodge Recian

## Descripción general

Aplicación web para visualizar vídeos en 360 grados, con una propuesta de experiencia inmersiva, múltiples perspectivas y controles multimedia.

Este repositorio es una implementación separada del proyecto [dr-360](https://github.com/WalyRobert/dr-360). Ambos proyectos tienen objetivos similares, pero estructuras y dependencias diferentes. Consulta sus respectivos códigos antes de considerarlos versiones equivalentes.

**Estado:** implementación independiente; la compatibilidad y las funcionalidades deben validarse en la versión publicada.

## Funcionalidades descritas por el proyecto

- Visualización panorámica 360°/180°/120°.
- Controles de reproducción, volumen, velocidad y progreso.
- Soporte anunciado para modo VR y seguimiento de cabeza.
- Interfaz adaptable para escritorio y dispositivos móviles.
- Reproducción de vídeos MP4, WebM y Ogg, según la descripción del proyecto.

> Las funcionalidades anteriores reflejan la documentación del proyecto. El soporte efectivo para visores, sensores y dispositivos específicos todavía debe validarse mediante pruebas.

## Tecnologías declaradas

- React 18
- TypeScript
- Three.js
- Lucide React
- Vite

## Instalación

**Requisitos:** Node.js y npm.

```bash
git clone https://github.com/WalyRobert/dr360-app.git
cd dr360-app
npm install
npm run dev
```

Para generar la compilación:

```bash
npm run build
npm run preview
```

El script `deploy` utiliza la CLI de Vercel, que debe estar instalada y configurada en el entorno:

```bash
npm run deploy
```

## Próximas tareas

- [ ] Documentar la arquitectura y los componentes principales.
- [ ] Confirmar la implementación del seguimiento de cabeza en el código.
- [ ] Probar el modo VR en los dispositivos declarados como compatibles.
- [ ] Añadir pruebas automatizadas y evidencias de compilación.
- [ ] Registrar capturas de pantalla y un vídeo de demostración.
- [ ] Explicar la relación y las diferencias con el repositorio `dr-360`.

## Demostración

Proyecto asociado a la dirección indicada en la documentación original: https://dr360graus.com.br

La disponibilidad y el funcionamiento de la dirección deben verificarse periódicamente.

## Autor / marca del proyecto

Dodge Recian

Repositorio mantenido en la cuenta GitHub WalyRobert.
