# Portafolio de Camilo Ortiz Motta

Página web de fotografía y video, lista para publicar gratis en GitHub Pages.

## Qué hay en esta carpeta

- `index.html`: toda la página (textos, diseño y funciones).
- `img/`: las fotos. Cada foto tiene dos versiones:
  - `nombre.jpg`: la versión grande, la que se ve completa al tocar una foto.
  - `nombre-t.jpg`: la versión pequeña, la que se usa en las teclas, la tira y el carrusel 3D.
- `.nojekyll`: un archivo vacío que GitHub Pages necesita. No lo borres.

## Publicarla en GitHub Pages

1. Entra a github.com con tu cuenta y crea un repositorio nuevo, por ejemplo `portafolio`. Déjalo **público**.
2. En el repositorio, toca **Add file → Upload files**.
3. Arrastra **todo el contenido** de esta carpeta: `index.html`, `.nojekyll`, `LEEME.md` y la carpeta `img`. Arrastra el contenido, no la carpeta `portafolio` completa. Luego toca **Commit changes**.
4. Ve a **Settings → Pages**. En *Source* elige **Deploy from a branch**, rama **main**, carpeta **/ (root)**, y guarda.
5. En uno o dos minutos la página queda en `https://ivanortizx.github.io/portafolio/`.

## Conectar tu dominio

1. Compra el dominio, por ejemplo `fotografohuila.com`.
2. En GitHub ve a **Settings → Pages → Custom domain**, escribe el dominio y guarda.
3. En el panel de tu dominio crea estos registros DNS:
   - Cuatro registros **A** para `@`, apuntando a: `185.199.108.153`, `185.199.109.153`, `185.199.110.153` y `185.199.111.153`.
   - Un registro **CNAME** para `www`, apuntando a `ivanortizx.github.io`.
4. Cuando GitHub muestre el dominio como verificado, activa **Enforce HTTPS**.

Los cambios de DNS pueden tardar desde unos minutos hasta un día en verse.

## Editar la página

Puedes editarla siempre que quieras. Abre `index.html` en GitHub, toca el lápiz, cambia lo que necesites y guarda con **Commit changes**. La página se actualiza sola en uno o dos minutos.

- **Textos:** busca el texto que quieras cambiar con Ctrl+F (o Cmd+F) y reemplázalo.
- **Número de WhatsApp:** aparece como `573124502235` (para los enlaces) y como `+57 312 450 2235` (para el texto que se copia). Si lo cambias, cambia todas las veces que aparece.
- **Fotos de una galería:** sube las dos versiones de la foto nueva a `img/`, con el mismo nombre que la que reemplazas. Si agregas fotos nuevas, también hay que agregarlas a la lista `PHOTOS` dentro de `index.html`. Para no equivocarte, puedes pedirle a Claude que lo haga.
- **Planes:** los textos de los planes están en `PLANS` y `planList` dentro de `index.html`.
