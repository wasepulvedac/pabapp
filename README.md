# Descripcion
Crear una plataforma en línea que permita visualizar y agendar en tiempo real las salas de pabellón disponibles de la  [“Clínica Buena Salud”](https://www.behance.net/gallery/135986279/Propab-para-Clinica-Buena-Salud).
Problema: El proceso de agendamiento de salas de pabellón necesita un upgrade y pasar a formato digital. En este momento se hace de forma manual y es gestionado solo por una persona (enfermera supervisora de pabellón) y esto crea trabas en el proceso ya que no se actualiza a tiempo y no es posible visualizar las cancelaciones en tiempo real.

Solución: Crear una plataforma en línea que permita visualizar y agendar en tiempo real las salas de pabellón disponibles de la “Clínica Buena Salud”. El software permitirá al equipo de cirugía inscribir de forma integral al equipo (cirujano(a) a cargo, el nombre del anestesista a cargo, enfermera(o), personal de apoyo asignado: arsernalero/a, pabellonero/a y técnico/a de anestesia). También en la plataforma cada equipo podrá ingresar los datos del paciente (Cabe destacar que las políticas de procesamiento de información personal y confidencial estarán alineadas con el protocolo interno de protección de datos de los usuarios del sistema de salud en Chile) y detallar el tipo de cirugía junto a los datos de contacto del paciente. La plataforma permitirá además cancelar y generar notificaciones a quienes estén en lista de espera para usar las salas de pabellón susceptibles de liberación. La aplicación tendrá una interfaz simple e intuitiva donde los equipos de cirugía podrán agendar de forma simple y ordenada las salas de pabellón para asegurar un óptimo uso de los recursos humanos y monetarios de la clínica.

## Tecnologías a ocupar

- Frontend: React, Bootstrap, Jquery para web /React native para app móvil
- Backend: Spring Boot / Mysql /Expo para notificaciones push
- Hosting: OVH Cloud
- CI/CD:Github

La aplicación debe ser responsive y estar disponible para web y como aplicación móvil, debe ser capaz de funcionar sin conexión y notificar a los usuarios en caso de cambios imprevistos
