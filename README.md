# Mi Plan Nuttres — subir a GitHub Pages

Este paquete contiene tu app ya lista (`index.html`, con el diseño "Glassmorphism moderno").
Súbela a un repositorio de GitHub y activa GitHub Pages para tener una URL real
(`https://tu-usuario.github.io/nombre-repo/`) que funcione al 100% en el móvil,
con "Añadir a pantalla de inicio" y todo interactivo (pestañas, Barajar, etc.).

## Aviso de privacidad — lee esto antes de subirlo

Con una cuenta gratuita de GitHub, **GitHub Pages solo funciona con repositorios
públicos**. Eso significa que cualquiera que tenga el enlace podría ver tu plan
(no aparece en buscadores ni hay ningún enlace público hacia él, pero técnicamente
no está protegido con contraseña). Si prefieres que quede realmente privado,
necesitarías un plan de pago de GitHub (Pro, desde ~4 USD/mes), que sí permite
Pages en repos privados. Tú decides qué nivel de privacidad te vale.

## Pasos (repo público, gratis)

1. Ve a [github.com](https://github.com) y crea una cuenta si no tienes (gratis).
2. Arriba a la derecha, toca **+** → **New repository**.
3. Ponle un nombre, por ejemplo `mi-plan-nuttres`. Déjalo como **Public**. Crea el repo.
4. Dentro del repo, toca **Add file → Upload files**.
5. Arrastra el archivo `index.html` de este paquete. Confirma con **Commit changes**.
6. Ve a la pestaña **Settings** del repo → en el menú de la izquierda, **Pages**.
7. En "Build and deployment" → **Source**, elige **Deploy from a branch**.
8. En "Branch", elige `main` (o `master`) y carpeta `/ (root)`. Guarda.
9. Espera 1-2 minutos. GitHub te mostrará la URL, algo como:
   `https://tu-usuario.github.io/mi-plan-nuttres/`
10. Abre esa URL en Safari desde tu iPhone → icono de compartir →
    **"Añadir a pantalla de inicio"**. Listo: icono único, app completa e interactiva.

## Actualizar la app más adelante

Cuando quieras subir una versión nueva del archivo (por ejemplo si cambiamos
el diseño o el contenido), repite el paso 4-5: **Add file → Upload files**,
sube el `index.html` nuevo (sobrescribe el anterior) y confirma el commit.
GitHub Pages se actualiza solo, en un par de minutos.
