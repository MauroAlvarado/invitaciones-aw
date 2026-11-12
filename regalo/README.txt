Plantilla TARJETA DE REGALO · Another World VR Arena
Edita el bloque CONFIG en index.html o usa parámetros de URL:
  nombre, escuela (quien otorga), motivo, sesiones,
  vigencia=AAAA-MM-DD (válida hasta ese día inclusive, hora de Cd. Juárez), folio,
  wa (solo dígitos, opcional), msg (opcional; usa {nombre} {escuela} {motivo} {sesiones} {vigencia} {folio}), lugar, dir
  "monto" ya no se usa: si viene en el link se ignora. La tarjeta no muestra montos en pesos.
Ejemplo: ?nombre=Macrina%20D%C3%ADaz&escuela=Fluency%20Studio&sesiones=10&vigencia=2026-11-30&folio=AW-FS-HALLOWEEN-2026-001
Imágenes: solo arte de juegos y logotipo oficial (sin personas reales). Sin precios ni montos.
Estructura: index.html (CONFIG) + regalo.css + regalo.js (marcado y lógica compartidos) + img/ + fonts/.
Páginas cortas: crea regalo/<clave>/index.html copiando regalo/macrina/index.html (usa <base href="../">),
cambia CONFIG y las metas og:. Con fijo:true ignora parámetros de URL. Ej.: /regalo/macrina/
