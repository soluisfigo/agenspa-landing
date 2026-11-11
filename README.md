# Landing AgenSpa IA (agenspa.mx)

Sitio estático, mismo esquema que la landing de Agendent (GitHub + Cloudflare Pages).

## Publicar

1. **GitHub** → github.com → botón verde **New** (arriba a la izquierda) → Repository name: `agenspa-landing` → Public → **Create repository**.
2. En la página del repo nuevo → link **uploading an existing file** → arrastra TODO el contenido de esta carpeta (`index.html`, `contacto.html`, `404.html`, `favicon.svg`, `agenspa-logo-icon.png`, `og-image.png`, `robots.txt`, `sitemap.xml` y la carpeta `pago-recibido`) → **Commit changes**.
3. **Cloudflare** → dash.cloudflare.com → menú izquierdo **Workers & Pages** → **Create** → pestaña **Pages** → **Connect to Git** → elige `agenspa-landing` → Framework preset: **None** · Build command: vacío · Build output directory: `/` → **Save and Deploy**.
4. Dentro del proyecto de Pages → pestaña **Custom domains** → **Set up a custom domain** → `agenspa.mx` → Continue → Activate. Repite con `www.agenspa.mx`.

## Pendientes conocidos

- Términos y Aviso de privacidad apuntan a agendent.mx (mismo operador). Revisar con el abogado.
- Límites de conversaciones (80 / 200 / 300 / 400) pendientes de revisión.
- Sin complemento de voz (el prompt de Vapi todavía es dental).
- `pago-recibido/` queda lista, pero el `success_url` del anticipo sigue apuntando a agendent.mx/pago-recibido.
