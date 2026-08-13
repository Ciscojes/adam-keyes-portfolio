# Adam Keyes Portfolio

Portfolio de un desarrollador front-end, construido con Vite y Sass.

## Enlaces

- Repositorio: https://github.com/Ciscojes/adam-keyes-portfolio
- Demo: https://ciscojes.github.io/adam-keyes-portfolio/

## Tecnologías

- HTML5 semántico
- CSS Flexbox
- Sass
- Vite

## Diseño

Portfolio personal de Adam Keyes reproducido a partir del diseño de Figma
proporcionado en el curso. El proyecto incluye los recursos gráficos originales
y, en su estado actual, el header con el logotipo y los enlaces sociales.

## Desarrollo

```bash
npm install
npm run dev
```

Vite carga `main.js`, que importa `sass/style.scss`. Los cambios de SCSS se
compilan en memoria y se reflejan automáticamente en el navegador. No es
necesario ejecutar Sass por separado.

## Compilación

```bash
npm run build
```

La compilación recrea `dist/` y genera los archivos optimizados para producción.

No edites `dist` manualmente: modifica las fuentes y vuelve a compilar.

Para revisar la compilación final localmente:

```bash
npm run preview
```
