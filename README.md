# Alejandro Barroso — web personal

Web de presentación y CV interactivo de Alejandro Barroso, ingeniero informático.

**En vivo:** https://alebarzalcv.netlify.app

## Cómo está hecha

Un único archivo `index.html`, sin frameworks, plantillas ni librerías.

| Parte | Tecnología |
| --- | --- |
| Estructura | HTML5 semántico |
| Estilos | CSS: grid, flexbox, variables, `position: sticky`, `clamp()`, `clip-path`, `mix-blend-mode` |
| Interacción | JavaScript nativo: `IntersectionObserver`, `requestAnimationFrame`, API `Intl` |
| Gráficos | Canvas 2D (esfera de puntos en espiral de Fibonacci, tramas de semitonos) y SVG (dial y logo) |
| Despliegue | Netlify |

## Secciones

- Cargador y cabecera con reloj en vivo y barra de progreso de scroll
- Cifras con dial, fijadas al scroll
- Puntos fuertes sobre una esfera de puntos que gira con el scroll
- Trayectoria académica y formación complementaria
- Proyecto destacado: aplicación web en Angular para personas celíacas (TFG)
- Ficha técnica de la propia web

## Verla en local

Abre `index.html` en el navegador, o sírvela con cualquier servidor estático:

```bash
npx serve .
```

## Contacto

- LinkedIn: https://www.linkedin.com/in/alejandro-barroso-786584178/
- GitHub: https://github.com/alebarzal
