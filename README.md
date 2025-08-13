    # Servicio de Banquetes FelEmma - Proyecto Next.js (lista para Vercel)

    **Qué contiene:** carpeta lista para subir a Vercel con el prototipo visual aprobado.

    **Dónde encontrar la carpeta:** descarga el archivo `banquetes-felemma.zip` desde el enlace que te doy (estará en `/mnt/data/banquetes-felemma.zip`). Al extraerlo verás la carpeta `banquetes-felemma/` con todo el proyecto.


    ## Probar localmente

    1. Extrae el zip y abre una terminal en la carpeta `banquetes-felemma`.

    2. Ejecuta:

```
npm install
npm run dev
```

3. Abre `http://localhost:3000` en tu navegador.

## Subir a Vercel — método recomendado (GitHub)

1. Crea un repositorio en GitHub.
2. En tu máquina local dentro de la carpeta del proyecto:

```
git init
git add .
git commit -m "Primer commit - FelEmma"
git branch -M main
git remote add origin <URL_DE_TU_REPOSITORIO>
git push -u origin main
```

3. En el panel de Vercel: `New Project` → `Import Git Repository` → selecciona tu repo → `Import` (Vercel detecta Next.js automáticamente y aplicará la configuración óptima).

(Referencia a la documentación oficial de Vercel incluida en la guía del asistente.)

## Subir a Vercel — alternativa (desde tu máquina con Vercel CLI)

1. Instala la CLI: `npm i -g vercel`
2. En la carpeta del proyecto ejecuta `vercel` y sigue las indicaciones (o `vercel --prod` para publicar en producción).

## Notas
- Si quieres usar Tailwind (recomendado), ya incluí la configuración básica. Si no lo vas a usar, quita las directivas de Tailwind en `styles/globals.css`.
- Reemplaza los archivos SVG en `/public` por tus fotos reales (nombres: `hero.svg`, `galeria.svg`, `pollo.svg`, `brocoli.svg`, `papas.svg`, `salsa.svg`).

Si quieres, puedo:
- Subir el mismo proyecto a un repositorio GitHub (si me das acceso a un repo vacío), o
- Guía paso a paso en pantalla para hacer el `git push` desde tu ordenador.
