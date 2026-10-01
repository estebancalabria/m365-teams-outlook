# Microsoft 365: Ecosistema de Colaboración e Integraciones

Este repositorio documenta cómo se relacionan los principales servicios de colaboración de Microsoft 365 y cómo se integran entre sí.

## Objetivos

- Comprender la función principal de cada servicio.
- Identificar sus diferencias.
- Entender cómo se integran.
- Reconocer dónde se almacena el contenido.
- Comprender cómo Microsoft 365 Copilot utiliza la información según los permisos del usuario.

> **Idea clave:** Microsoft 365 no es un conjunto de aplicaciones aisladas. Outlook, Teams, SharePoint, OneDrive y Copilot forman parte de un ecosistema conectado mediante identidad, permisos, membresías y almacenamiento.

---

## Visión general del ecosistema

### Microsoft 365 Groups

Proporciona membresías compartidas y recursos conectados para otros servicios. No es una aplicación, sino una capa de organización y acceso.

### Outlook

- Correo electrónico.
- Calendarios.

### Microsoft Teams

- Canales.
- Publicaciones.
- Chats.
- Reuniones.

### SharePoint

- Sitios y páginas.
- Bibliotecas compartidas.

### OneDrive

- Archivos personales.
- Propiedad individual del contenido.

### Microsoft 365 Copilot

Actúa como una capa de inteligencia que trabaja sobre la información a la que el usuario ya tiene acceso autorizado.

---

## Microsoft 365 Groups

Microsoft 365 Groups es un contenedor compartido de membresías y recursos, no una aplicación independiente.

- Una misma lista de miembros puede reutilizarse en Outlook, Teams, SharePoint y Planner.
- Cada grupo incluye un buzón de grupo, un calendario compartido y un sitio de equipo de SharePoint.
- Los grupos pueden ser públicos o privados.
- Un grupo puede existir sin tener asociado un equipo de Teams.

**Distinción clave:** el grupo es el contenedor de membresía y recursos; las aplicaciones proporcionan las experiencias que se construyen sobre él.

**Acceso:** [Abrir Microsoft 365 Groups](https://outlook.cloud.microsoft/groups/home)

---

## Outlook

Outlook es la experiencia de correo electrónico y calendario para la comunicación personal y de grupo.

- El buzón personal y el calendario personal pertenecen al usuario.
- El buzón y el calendario del grupo pertenecen al Microsoft 365 Group.
- **Mis grupos** muestra los grupos a los que pertenece el usuario.
- **Descubrir grupos** muestra grupos públicos disponibles para unirse.

**Distinción clave:** los recursos personales pertenecen al usuario, mientras que los recursos del grupo pertenecen al Microsoft 365 Group.

**Acceso:** [Abrir Outlook](https://outlook.cloud.microsoft/)

---

## Microsoft Teams

Microsoft Teams es el espacio de trabajo para conversaciones, reuniones y colaboración diaria.

- Reúne canales, publicaciones, chats y reuniones online.
- Todo equipo estándar está respaldado por un Microsoft 365 Group.
- Los archivos de los canales se almacenan en el sitio de SharePoint conectado.

**Distinción clave:** Teams proporciona la interfaz para conversaciones y reuniones; la membresía y los archivos compartidos se apoyan en Microsoft 365 Groups y SharePoint.

**Acceso:** [Abrir Microsoft Teams](https://teams.cloud.microsoft/)

---

## SharePoint

SharePoint es la plataforma que almacena y publica contenido organizativo compartido.

- Incluye sitios de equipo, sitios de comunicación, bibliotecas de documentos, páginas y listas.
- Cada Microsoft 365 Group tiene un sitio de equipo de SharePoint conectado.
- Solo los sitios conectados a un grupo heredan la membresía del Microsoft 365 Group.

**Distinción clave:** tanto los sitios conectados a grupos como los sitios independientes son sitios de SharePoint, pero solo los primeros heredan la membresía del grupo.

**Acceso:** [Abrir SharePoint](https://www.microsoft365.com/launch/sharepoint)

---

## OneDrive

OneDrive es el almacenamiento personal para los archivos de trabajo de cada usuario.

- Los archivos pertenecen al usuario y se comparten mediante invitación explícita.
- Está construido sobre tecnología SharePoint, pero no es una ubicación compartida de equipo.
- El contenido destinado a todo el grupo debe almacenarse en SharePoint.

> **OneDrive:** mis archivos.  
> **SharePoint:** nuestros archivos.

**Acceso:** [Abrir OneDrive](https://www.microsoft365.com/launch/onedrive)

---

## Microsoft 365 Copilot

Microsoft 365 Copilot funciona sobre la información que el usuario ya tiene permiso para abrir.

### Contexto autorizado que puede utilizar

- Outlook.
- Teams.
- SharePoint.
- OneDrive.
- Calendarios.
- Reuniones.

### Qué hace Copilot

- Resume, redacta y compara contenido autorizado.
- Trabaja con información procedente de varios servicios en una misma solicitud.
- Identifica acciones, decisiones y seguimientos.

### Qué no hace Copilot

- No concede acceso a información que el usuario no puede abrir.
- No reemplaza Outlook, Teams, SharePoint ni OneDrive.
- No crea una copia independiente del contenido organizativo.

**Distinción clave:** la ubicación, la organización y los permisos del contenido determinan el contexto disponible para Copilot.

**Acceso:** [Abrir Microsoft 365 Copilot](https://m365.cloud.microsoft/chat)

---

## Otros productos de Microsoft 365

- **Microsoft Planner:** gestión de tareas mediante planes, depósitos y asignaciones, compartidos con Groups y Teams.
- **Microsoft Forms:** encuestas, cuestionarios y formularios compartidos mediante Teams, Outlook y SharePoint.
- **Microsoft OneNote:** blocs de notas compartidos para notas colaborativas en Teams y SharePoint.
- **Microsoft Loop:** espacios de trabajo colaborativos con componentes sincronizados entre Teams y Outlook.
- **Microsoft Stream:** vídeo en Microsoft 365, almacenado en SharePoint o OneDrive según la propiedad.
- **Microsoft Viva Engage:** comunidades y conversaciones para toda la organización que complementan Outlook y Teams.

---

# Integraciones entre servicios

## Microsoft 365 Groups y Outlook

- Microsoft 365 Groups proporciona una identidad compartida para un equipo o una comunidad.
- Cada Microsoft 365 Group incluye una dirección de correo electrónico y un buzón compartido.
- Los correos enviados a la dirección del grupo pueden distribuirse a sus miembros.
- Los miembros pueden leer y participar en las conversaciones del grupo desde Outlook.
- Los grupos pueden ser públicos o privados.
- Los grupos públicos pueden descubrirse dentro de la organización.
- Los usuarios pueden unirse a grupos públicos.

## Microsoft 365 Groups y Calendar

- Cada Microsoft 365 Group incluye un calendario compartido.
- Los miembros pueden ver los eventos del calendario del grupo.
- Los miembros pueden crear y administrar eventos en el calendario del grupo.
- Los eventos del calendario del grupo son visibles para sus miembros.
- Al invitar a un grupo a un evento, este se añade a los calendarios de sus miembros.
- Los calendarios de grupo ayudan a coordinar actividades compartidas.

## Microsoft 365 Groups y Teams

- Cada equipo de Teams está asociado a un Microsoft 365 Group.
- La membresía del equipo se basa en la membresía del grupo.
- Agregar un miembro al equipo también lo agrega al grupo asociado.
- Eliminar un miembro del equipo también lo elimina del grupo asociado.
- Los propietarios del equipo también son propietarios del grupo.
- Microsoft 365 Groups proporciona la base de membresía para Teams.
- Los cambios en la membresía del grupo se reflejan en el equipo.

## Microsoft 365 Groups y SharePoint

- Cada Microsoft 365 Group incluye un sitio de equipo de SharePoint.
- Los miembros del grupo reciben acceso al sitio de SharePoint asociado.
- Los permisos del sitio se basan en la membresía del grupo.
- Agregar o quitar miembros actualiza el acceso al sitio.
- Los documentos y el contenido del sitio se comparten con los miembros del grupo.
- SharePoint proporciona el espacio colaborativo de contenido para el grupo.

## Outlook y Teams

- Outlook y Teams comparten el mismo calendario de Microsoft 365.
- Las reuniones de Teams pueden programarse desde Outlook.
- Las reuniones de Teams creadas en Outlook aparecen en Teams.
- Las invitaciones y actualizaciones de las reuniones se distribuyen mediante Outlook.
- Los usuarios pueden unirse a reuniones de Teams directamente desde Outlook.
- Outlook y Teams proporcionan una experiencia unificada de reuniones y programación.

## Outlook, SharePoint y OneDrive

- Los correos pueden incluir vínculos a archivos almacenados en SharePoint y OneDrive.
- Los usuarios pueden compartir archivos de SharePoint y OneDrive directamente desde Outlook.
- Los permisos pueden administrarse al compartir vínculos desde Outlook.
- Los destinatarios pueden colaborar en documentos compartidos sin intercambiar archivos adjuntos.
- Las actualizaciones se reflejan automáticamente porque el contenido permanece en SharePoint o OneDrive.
- Outlook facilita la distribución y la colaboración sobre contenido almacenado en Microsoft 365.

## Teams, SharePoint y OneDrive

- Los archivos compartidos en canales de Teams se almacenan en SharePoint.
- Los archivos compartidos en chats de Teams se almacenan en OneDrive.
- Los usuarios pueden colaborar en documentos directamente desde Teams.
- Los cambios quedan disponibles en tiempo real para los usuarios autorizados.
- Teams proporciona una interfaz para acceder al contenido almacenado en SharePoint y OneDrive.
- Los permisos se administran mediante el almacenamiento subyacente de SharePoint y OneDrive.

## Copilot y el ecosistema

- Copilot trabaja con el contenido y las conversaciones que el usuario ya puede abrir.
- En Outlook, resume hilos de correo y redacta respuestas a partir del contenido del buzón.
- En Teams, resume reuniones y conversaciones de chat.
- En SharePoint y OneDrive, analiza documentos a los que el usuario tiene acceso.
- La membresía de los grupos y los permisos de los sitios determinan qué contenido puede utilizar.
- Copilot añade una capa de inteligencia sin crear nuevas copias del contenido.

---

# Matriz resumida de integraciones

| Servicio | Integración |
|---|---|
| Microsoft 365 Groups + Outlook | Correo y buzón de grupo |
| Microsoft 365 Groups + Teams | Membresía compartida |
| Microsoft 365 Groups + SharePoint | Sitio de equipo conectado |
| Microsoft 365 Groups + OneDrive | Sin relación directa |
| Microsoft 365 Groups + Calendar | Calendario compartido del grupo |
| Outlook + Teams | Reuniones y comunicación |
| Outlook + SharePoint | Vínculos a documentos |
| Outlook + OneDrive | Archivos adjuntos en la nube |
| Teams + SharePoint | Almacenamiento de archivos de canales |
| Teams + OneDrive | Almacenamiento de archivos de chats |
| SharePoint + OneDrive | Tecnología de almacenamiento compartida |

---

# Reglas clave para recordar

## Estructura

- Todo equipo estándar de Teams tiene un Microsoft 365 Group.
- Todo equipo estándar de Teams tiene uno o más sitios de SharePoint conectados.
- Todo Microsoft 365 Group tiene un sitio de equipo de SharePoint conectado.
- No todo Microsoft 365 Group tiene un equipo de Teams.
- No todo sitio de SharePoint tiene un Microsoft 365 Group.

## Almacenamiento

- OneDrive se utiliza principalmente para archivos personales.
- SharePoint se utiliza principalmente para archivos organizativos compartidos.
- Los archivos de chats y canales de Teams utilizan modelos de almacenamiento diferentes.
- El correo del grupo y el correo de un canal son conceptos diferentes.

## Calendarios y Copilot

- El calendario personal y el calendario del grupo son diferentes.
- Habilitar una reunión de Teams no invita automáticamente a todos los miembros del grupo.
- Copilot solo utiliza información a la que el usuario está autorizado a acceder.
- Otros productos de Microsoft 365 amplían el ecosistema de colaboración.

---

# Modelo mental

1. **Microsoft 365 Groups** organiza las membresías y los recursos compartidos.
2. **Outlook** proporciona correo electrónico y calendarios.
3. **Teams** proporciona conversaciones, chats y reuniones.
4. **SharePoint** almacena contenido organizativo compartido.
5. **OneDrive** almacena archivos personales de trabajo.
6. **Copilot** utiliza el contexto disponible según los permisos existentes.

## Resumen

- Groups organiza la membresía.
- Las aplicaciones proporcionan las experiencias.
- SharePoint y OneDrive almacenan el contenido.
- Copilot trabaja sobre el contexto autorizado.
- Los permisos definen qué puede abrir cada usuario y qué información puede utilizar Copilot.
