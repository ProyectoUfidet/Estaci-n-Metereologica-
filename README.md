# Estación meteorológica UFIDET

Página de presentación en español, adaptable a celulares y computadoras. Incluye la propuesta, componentes, imágenes de referencia y enlaces a documentos y piezas STL del repositorio. No muestra mediciones en vivo.

## Ver la página

Abre `index.html` en tu navegador, o desde esta carpeta ejecuta:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

No requiere instalar dependencias ni compilar. Para detener el servidor, pulsa Ctrl+C.

## Publicar en GitHub Pages

Después de subir los archivos de la página a GitHub, abre Settings → Pages → Build and deployment. Selecciona Deploy from a branch, rama `main`, carpeta `/ (root)` y guarda. GitHub mostrará la dirección pública cuando termine la publicación.

## Editar

- `index.html`: textos, imágenes, enlaces y secciones.
- `styles.css`: colores, diseño y adaptación a pantallas pequeñas.

Las imágenes son material aportado al repositorio; se presentan como referencias y diseños, sin atribuirles pruebas de funcionamiento. Antes de una publicación pública, confirma que tienes permiso para utilizarlas. La velocidad del viento requiere calibración del anemómetro. El sensor elegido es KY-003; no se sustituye por DRV5023.
