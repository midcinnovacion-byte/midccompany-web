# MIDC Company — Rediseño web octubre 2026

Sitio web estático listo para Vercel. Mantiene los colores de MIDC, una línea visual más cálida y minimalista, logo sin recuadro blanco y nombre corporativo correcto **GROUPE UNI**.

## Publicación (repositorio actual)
1. Descomprime este ZIP en la computadora.
2. Abre https://github.com/marianapino2/midccompany .
3. En la rama `main`, elige **Add file → Upload files**.
4. Arrastra `index.html`, `README.md` y la carpeta `assets` completa al área de carga. Confirma la sustitución de `index.html` y el README existentes. Los recursos anteriores pueden permanecer sin causar errores.
5. Selecciona **Commit changes**. Vercel desplegará automáticamente si sigue conectado con ese repositorio.
6. Comprueba el sitio de prueba antes de cambiar el dominio.

## Recursos / consideraciones
- `assets/logo-midc-transparente.png`: versión con transparencia creada a partir del logo compartido anteriormente.
- `assets/favicon.png`: icono extraído del logotipo.
- `assets/memorial-enterprise-group.png`: imagen institucional previamente compartida.
- Las dos fotografías humanas son servidas por Unsplash; requieren Internet y pueden sustituirse después por imágenes propias con permisos.
- El formulario **no envía correos desde el servidor**: abre la aplicación de correo del visitante usando `mailto:`. Para recepción web automática se requiere conectar un servicio de formularios.
- Verificar la representación oficial, permisos de imagen y mensajes institucionales antes de la publicación definitiva.

## Dominio Namecheap → Vercel
En Vercel: Project → Settings → Domains → agregar `midccompany.com` y `www.midccompany.com`. Copiar **exactamente** los registros DNS indicados por Vercel en Namecheap → Domain List → Manage → Advanced DNS. No reemplazar registros MX, SPF, DKIM o DMARC del correo. Ajustar primero cualquier DNS web anterior conflictivo. La validación y emisión SSL pueden tardar.
