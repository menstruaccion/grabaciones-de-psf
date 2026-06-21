# grabaciones-de-psf

Generador manual de correos para enviar grabaciones de Peruanos Sin Fronteras.

## Uso rápido

1. Abre `index.html`.
2. Escribe el nombre del participante.
3. Haz clic en `+ Añadir` en la grabación o grabaciones que quieres mandar.
4. Copia el asunto sugerido.
5. Haz clic en `Copiar correo`.
6. Pega en Gmail.

## Videos ya cargados

- Dr. Walter Curioso — https://youtu.be/XZts8Zb51-I
- Fernanda Pons — https://youtu.be/elv_WEn_GwA
- Alejandra Carrasco — https://youtu.be/98RXvd5bC14

## Cómo añadir más videos después

Abre `index.html`, busca el nombre de la charla y ubica esta línea:

```js
"video": "PEGAVIDEOAQUI"
```

Reemplaza `PEGAVIDEOAQUI` por el link de YouTube, por ejemplo:

```js
"video": "https://youtu.be/tu-video"
```

Ese es el único code word que necesitas buscar:

```txt
PEGAVIDEOAQUI
```

Cuando reemplaces ese texto por un link real que empiece con `https://`, el botón de esa charla se activará automáticamente en la página.

## Si tienes una charla nueva que no está en la lista

Busca en `index.html`:

```txt
PEGANUEVAGRABACIONAQUI
```

Debajo de ese marcador hay una plantilla para copiar y pegar una nueva grabación dentro de `GRABACIONES`.
