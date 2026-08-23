WEBAR OPTIMIZADO - IMAGEN + VIDEO

La mejora principal:
- La versión anterior compilaba la imagen objetivo en el celular.
- Esta versión usa un archivo targets.mind precompilado.
- El celular solo carga el target y abre la cámara.

PASO ÚNICO DE PREPARACIÓN
1. Sube inicialmente estos archivos a GitHub:
   index.html
   target.html
   compiler.html
   target-persona.png
   video-ar-5s.mp4
   qr-webar.png

2. Cuando GitHub Pages esté activo, abre en la LAPTOP:
   https://diegoorbezoh.github.io/webar-demo/compiler.html

3. Pulsa "Generar targets.mind".
4. Se descargará targets.mind.
5. Sube targets.mind a la raíz del repositorio.
6. Espera a que GitHub Pages termine el deploy.

PRUEBA
Laptop:
https://diegoorbezoh.github.io/webar-demo/target.html

Celular:
Escanea el QR de target.html.

RESULTADO ESPERADO
- Cámara visible como fondo.
- Al detectar target-persona.png aparece el video superpuesto.
- El video dura 5 segundos.
- Al perder el target, el video se pausa y se oculta.
