


# [Bootcamp Web Developer Full Stack](https://www.thebridge.tech/bootcamps/bootcamp-fullstack-developer/)


## Workshop - Taller de Web Scraping

## Cómo ejecutar la App

### PARTE 1: Jugar con puppeteer para hacer scraping del e-commerce 
1. Instalar las dependencias del proyecto node: `npm install`
2. Completar el script `scraper.js` con lo explicado durante el taller. ***Este es fichero más importante para el taller, pues contendrá la lógica necesaria para hacer scraping con puppeteer***.


### PARTE 2 (extra): Probar el sistema completo dentro de una API
3. Comprobar que el script funciona correctamente: Ejecutar `node scraper.js` en la consola
4. Haz las modificaciones especificadas en `controller/products.js` para integrar el script anterior con la API ya proporcionada.
5. Lanzar el servidor: `npm start`. Puedes pararlo con `Ctrl+c` o `Ctrl+z`
6. Introduce en el navegador `http://localhost:3000`. Deberías visualizar: `{"mensaje":"La prueba funciona"}`
7. Introduce en el navegador `http://localhost:3000/products`. **Esta es la ruta que hará scraping internamente a nuestro e-commerce elegido**. Deberías visualizar los productos scrapeados: `[{producto1},{producto2},...,{productoN}]`

