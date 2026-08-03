# Sistema de Gestión de Personal · Notificación — Descargas

> **Software propietario.** © 2026 **codezxmax** — todos los derechos
> reservados. **El código fuente es privado** y no está publicado en ningún
> repositorio. Este repositorio existe con un único fin: distribuir los
> **instaladores oficiales** para que los equipos autorizados se actualicen
> automáticamente.

Programa de escritorio para Windows que notifica licencias médicas a las
jefaturas de área. Obra de **codezxmax**, protegida por la Ley N° 17.336
sobre Propiedad Intelectual de Chile y los tratados internacionales.

---

## Instalar o actualizar

1. Ir a **[Releases](../../releases/latest)** y descargar
   `SGP-Notificacion-Setup.exe`.
2. Doble clic y seguir el asistente (instala por usuario, sin pedir
   administrador).

Los equipos que ya lo tienen instalado **se actualizan solos**: el programa
comprueba este repositorio al arrancar, descarga la versión nueva, **verifica
su firma SHA-256** contra la publicada y la instala sin pasos manuales. Si la
firma no coincide, no instala nada.

### Si Windows dice «Windows protegió su PC»

Pasa en la primera instalación y **es esperable**: el instalador no lleva
firma digital de código (un certificado comercial que hoy no está comprado),
así que SmartScreen avisa por no reconocer al editor. No significa que el
archivo tenga algo raro.

Para seguir: **Más información** → **Ejecutar de todas formas**.

Antes de hacerlo, si querés estar seguro de que el archivo es el publicado
acá y no otro, comprobá su firma con el comando de la sección siguiente.

## Verificar la descarga (opcional)

Cada versión se publica junto a su firma `SHA256SUMS.txt`:

```powershell
Get-FileHash .\SGP-Notificacion-Setup.exe -Algorithm SHA256
```

El resultado tiene que coincidir con el hash publicado.

---

## Licencia — leer antes de usar

Que el instalador pueda descargarse desde acá **no convierte al programa en
gratuito ni en software libre**. La licencia de uso (ver
[`LICENCIA.txt`](LICENCIA.txt), se muestra y debe aceptarse al instalar) es
**interna, personal e intransferible**, limitada a la organización que
recibió el programa del autor. En particular queda **prohibido** sin
autorización escrita del autor:

- copiar, redistribuir, vender o poner el programa a disposición de terceros;
- descompilar, desensamblar o aplicarle ingeniería inversa;
- modificarlo o crear obras derivadas;
- quitar o eludir sus medidas de protección (PIN, sello de integridad,
  cifrado) — infracción autónoma según el art. 85 N de la Ley N° 17.336;
- reutilizar su código, interfaz o textos en otro programa.

**Autor y contacto**: codezxmax. Cualquier autorización o consulta sobre la
licencia, por escrito al autor.
