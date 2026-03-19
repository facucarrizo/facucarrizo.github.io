# GitHub Pages y dominio corto

## Opcion 1: dominio corto gratis de GitHub

Este proyecto ya quedo preparado para publicar en:

`https://facucarrizo.github.io/`

tenes que publicar el portfolio desde un repositorio llamado exactamente:

`facucarrizo.github.io`

Pasos:

1. Crear un repo nuevo con el nombre `facucarrizo.github.io`.
2. Copiar el contenido de este proyecto a ese repo.
3. Publicarlo con GitHub Pages desde la rama principal.
4. Publicar el contenido en la raiz del repo.

## Opcion 2: dominio propio

GitHub Pages permite usar dominio propio aun en hosting gratis.

Pasos:

1. Comprar un dominio, por ejemplo `facucarrizo.dev` o `facu.dev`.
2. Configurarlo en la seccion `Settings > Pages` del repositorio.
3. Agregar un archivo `CNAME` con tu dominio.
4. Configurar los registros DNS del proveedor del dominio.

Documentacion oficial:

https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site

## Notas para este proyecto

- El sitio actual es estatico, no Angular.
- Se agrego `.nojekyll` para que GitHub Pages publique el contenido tal cual.
- Antes de mover el repo conviene revisar las URLs canonicas del SEO para que coincidan con el dominio final.
