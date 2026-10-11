Invitación web Another World — Plantilla Team Building ("Operación Equipo") para empleados
=======================================================================================
Edita el bloque CONFIG en index.html o usa parámetros de URL:
  empresa      Nombre de la empresa (opcional; se muestra "{empresa} te invita a")
  formato      play4fun | escape (default) | bandera | torneo  → cambia agenda, descripción y misiones
  evento       Team Building (default) · Integración · Fin de año · Onboarding…
  fecha        AAAA-MM-DD     hora=HH:MM-HH:MM (o inicio= / fin=)     tz=-07:00 (default auto Cd. Juárez)
  sede         arena (default: Another World VR Arena, Av. Ejército Nacional 5230, Local 9) | empresa
  lugar, dir   Para sede=empresa (default lugar "En nuestras instalaciones"; sin dir se oculta "Cómo llegar")
  organizador  Nombre de quien recibe confirmaciones (opcional)
  wa           WhatsApp del organizador (solo dígitos). Default PLACEHOLDER 5216560000000
  msg          Mensaje de WhatsApp; admite {empresa} {evento} {fecha} {hora} {organizador} {formato}
Ejemplo: ?empresa=Grupo%20Alsa&formato=escape&fecha=2026-11-12&hora=09:00-13:00&wa=5216561674480
Sin precios. Imágenes: solo arte/capturas de juegos (sin personas reales) + logotipo oficial.
La agenda calcula horas reales desde la hora de inicio (horarios orientativos).
  grupo        Área/equipo invitado (opcional): "Valeo · CoDir te invita a"
  logo         Logo del cliente: clave de archivo en clientes/ (logo=valeo → clientes/valeo.svg, luego .png/.webp).
               Se muestra en placa blanca junto al símbolo Another World (sin modificar). Si no existe, se oculta.
               Para un cliente nuevo: sube su logo oficial a clientes/<clave>.svg|png (fondo transparente).
