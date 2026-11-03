# Traza Minera — La ruta legal del mineral

App web instalable (PWA) de **Vibras Positivas HM** para llevar la trazabilidad del mineral del socavón a la venta. Está pensada para compraventas de oro, plantas de beneficio, asociaciones y titulares mineros del Bajo Cauca, el Nordeste y el sur de Córdoba.

**Contexto:** la ANM empezó la transición del Sistema de Trazabilidad de Minerales el 19 de mayo de 2026. Desde el **19 de noviembre de 2026** es obligatorio en todo el país (Decreto 2234 de 2023, Resolución ANM 759 de 2024 y Resolución 1549 de 2025).

## Qué hace
- **Proveedores:** titulares, solicitantes de formalización, ARE, subcontratistas, barequeros y chatarreros, con su título o registro y la fecha de vencimiento.
- **Lotes:** cada compra queda con un código único (TM-2026-0001). Guarda el peso bruto y la ley, calcula el peso fino y el valor, y registra el certificado de origen, el municipio, el GPS y una foto real del mineral o del certificado.
- **Ruta del lote:** extracción, compra, beneficio o fundición, transporte y venta o exportación, con RUCOM y documento soporte en cada paso. Cada lote trae su QR.
- **Alertas:** lote sin certificado, registro vencido o por vencer, RUCOM propio vencido, barequero por encima del tope mensual, más gramos vendidos que comprados, venta sin RUCOM del comprador y lote abierto hace más de 15 días.
- **Informes:** balance de masa del mes, compras por proveedor, origen por municipio, libro de control para imprimir, CSV para Excel, copia de seguridad y restauración.
- **Norma:** resumen práctico en español e inglés.
- Funciona sin señal: los datos quedan en el teléfono.
- Cumple Habeas Data (Ley 1581 de 2012): la cédula y el celular quedan ocultos y solo se ven con el PIN de administrador. Los formularios llevan aviso de privacidad.
- Viene en español e inglés.

> Es una herramienta de **control interno**. El reporte oficial ante la ANM se hace con un Operador Tecnológico de Trazabilidad de Minerales (OTTM) habilitado por la ANM. Esta app no reemplaza ese reporte ni el RUCOM.

## Foro Minero Bajo Cauca Caucasia 2026 (5 nov 2026, 8:00 a. m., Cámara de Comercio)
Pestaña **Foro** (enlace directo: `https://traza-minera.netlify.app/#foro`), con franja en la portada hasta el 5 de noviembre:
- **Cómo está:** paro minero de marzo de 2026, reclamos de los mineros, formalización, informalidad, Génesis y producción formal, cada dato con su fuente.
- **Hacia dónde va:** línea de tiempo (trazabilidad, nueva ministra, derogatoria de los 15 Distritos Mineros Especiales, el foro, 19 de noviembre) y la ruta del minero para vender legal.
- **La voz minera:** formulario para dejar un problema o una propuesta, con consolidado por tema y municipio, impresión para entregar a la mesa, CSV, resumen por WhatsApp y envío al WhatsApp de Vibras Positivas HM. El celular queda oculto (PIN).
- Cuenta regresiva, botón para agregar al calendario, cómo llegar e invitación por WhatsApp.
- `qr-foro.png`: QR que abre la sección del foro. Botón **Imprimir afiche con QR** para pegarlo o proyectarlo en el evento.

## Fotos y video reales
Pon tus fotos en la carpeta `fotos/` con estos nombres (si falta alguna, la app usa fotos de Wikimedia Commons):

| Archivo | Dónde sale |
|---|---|
| `fotos/hero.mp4` | Video de fondo de la portada (opcional, corto y liviano) |
| `fotos/hero1.jpg`, `hero2.jpg`, `hero3.jpg` | Fotos de la portada, que van rotando |
| `fotos/extraccion.jpg` | Eslabón 1 |
| `fotos/compra.jpg` | Eslabón 2 |
| `fotos/beneficio.jpg` | Eslabón 3 |
| `fotos/transporte.jpg` | Eslabón 4 |
| `fotos/venta.jpg` | Eslabón 5 |
| `fotos/foro.jpg` | Fondo de la sección del Foro Minero (ideal: foto real del evento o de mineros de Caucasia) |

## Publicar
1. Crea el repo `haroldco45/traza-minera` y sube: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`, `og.png`, `README.md` y la carpeta `fotos/`.
2. Activa GitHub Pages (rama main, raíz).
3. En Netlify, conecta el repo como **traza-minera**. Queda en `https://traza-minera.netlify.app`, que es la URL de los flyers y de la imagen para compartir (og).

## Para mostrarla a un cliente
En **Informes**, toca **Cargar datos de ejemplo**. Así ves de una vez proveedores, lotes con ruta completa y alertas. Luego usa **Borrar todo** antes de entregarla.

---
Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados · Caucasia, Antioquia · vibraspositivashm.com
