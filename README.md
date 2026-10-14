# Brimahd — QAS

Ambiente de pruebas de la app Brimahd: https://isaacjorquera5823-dev.github.io/brimahd-qas/

- **Qué rama está publicada:** la que dice el archivo `RAMA`.
- **Cambiar de rama:** editar `RAMA` y guardar. Se vuelve a publicar solo en ~2 minutos.
- **Traer los últimos cambios de la misma rama:** pestaña *Actions* → *Publicar QAS* → *Run workflow*.

En QAS la app corre en **modo prueba**:
- Los informes se numeran `PRUEBA-XXXX` y no gastan números reales del contador.
- El borrador y la configuración se guardan aparte de PRD, así que probar aquí no toca un informe real a medio llenar.
- ⚠️ Usa la misma base de datos Firebase que PRD: las observaciones nuevas que se agreguen quedan como pendientes en la lista real. El botón "Enviar informe" envía correos y WhatsApp de verdad.

El código de la app vive en https://github.com/isaacjorquera5823-dev/Brimahd-inspeccion — este repo solo contiene la configuración para publicar QAS.
