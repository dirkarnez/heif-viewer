heif-viewer
===========
Read heif file and render to html canvas

### Sample files
- [HEIC sample file gallery | Download HEIC images](https://heic.digital/samples/)

### Tutorials
- https://framebird.io/viewer/heif
  - https://framebird.io/_next/static/chunks/raw-converter-worker.a2ef306d23d70bfe.js
    - ```javascript
      createImageBitmap(new ImageData(1,10)).then(r => {
      const o = new OffscreenCanvas(r.width,r.height);
      const c = o.getContext("2d");
      c.drawImage(r, 0, 0);
      const i = c.getImageData(0, 0, o.width, o.height);
      debugger;
      })
      ```
  - https://framebird.io/_next/static/chunks/libheif-js.c10e1358ebb4dfdd.js
  - https://framebird.io/_next/static/media/libraw.851147f4.wasm
- [strukturag/libheif: libheif is an HEIF and AVIF file format decoder and encoder.](https://github.com/strukturag/libheif)

