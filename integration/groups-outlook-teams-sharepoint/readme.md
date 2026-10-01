# Microsoft 365 Groups, Outlook, Teams y SharePoint

## Concepto principal

El elemento central de la integración entre Outlook, Teams y SharePoint es el **Microsoft 365 Group**.

```text
Microsoft 365 Group
│
├─ Outlook
│   ├─ Mailbox del grupo
│   ├─ Conversations
│   └─ Calendario
│
├─ SharePoint
│   └─ Sitio de SharePoint
│
└─ Teams (opcional)
    ├─ Team
    └─ Channels
```

La mayor parte de la integración entre Outlook, Teams y SharePoint existe porque las tres plataformas utilizan el mismo Grupo Microsoft 365.

---

# Microsoft 365 Groups

Un Microsoft 365 Group puede existir con:

- Outlook
- SharePoint
- Team (opcional)

Por lo tanto:

```text
Grupo M365
├─ Outlook
├─ SharePoint
└─ (sin Team)
```

es una configuración válida.

También es válida:

```text
Grupo M365
├─ Outlook
├─ SharePoint
└─ Teams
```

---

# Relación entre Teams y Microsoft 365 Groups

## Team → Grupo M365

Un Team estándar de Microsoft Teams tiene un Grupo Microsoft 365 asociado.

```text
Team
│
├─ Grupo M365
├─ SharePoint
└─ Miembros
```

Por lo tanto:

- Todo Team estándar tiene un Grupo M365.
- Todo Team estándar tiene un sitio de SharePoint.
- Los miembros del Team y del Grupo son compartidos.

## Grupo M365 → Team

La relación inversa no es obligatoria.

Puede existir un Grupo M365 sin Team.

```text
Grupo M365
├─ Outlook
├─ SharePoint
└─ (sin Team)
```

---

# Relación entre SharePoint y los Grupos

## Cuando se crea un Grupo M365

Al crear un Microsoft 365 Group se crea automáticamente:

```text
Grupo M365
├─ Outlook
└─ Sitio de SharePoint
```

Por lo tanto:

✅ Todo Grupo M365 tiene un sitio de SharePoint asociado.

---

## Cuando se crea un sitio de SharePoint

La relación no siempre funciona al revés.

Existen sitios de SharePoint que:

```text
Sitio SharePoint
├─ Grupo M365
└─ Team (opcional)
```

pero también existen sitios que son independientes.

Por lo tanto:

✅ Todo Grupo M365 tiene SharePoint.

❌ No todo sitio de SharePoint implica la existencia de un Grupo M365.

---

# Grupos públicos y privados

Un grupo puede ser:

```text
Público
```

o

```text
Privado
```

Independientemente de si tiene Team o no.

Ejemplos válidos:

```text
Público + Team
Público + Sin Team
Privado + Team
Privado + Sin Team
```

---

# Outlook Groups

En Outlook Web aparece la sección:

```text
Groups
```

Allí normalmente se muestran los grupos de los que el usuario es miembro.

También puede aparecer:

```text
Discover Groups
```

donde se muestran grupos descubribles de la organización.

---

# Unirse a un grupo

Si el grupo tiene Team asociado:

```text
Join Group
↓
Miembro del Grupo
↓
Miembro del Team
```

porque la membresía es compartida.

---

# Correo electrónico de un Grupo M365

Un grupo puede tener una dirección como:

```text
ventas@empresa.com
proyectox@empresa.com
rrhh@empresa.com
```

Al enviar un correo:

```text
usuario
  ↓
grupo@empresa.com
```

el mensaje llega al buzón del grupo.

Se consulta desde:

```text
Outlook
└─ Groups
    └─ Conversations
```

---

# Dirección de correo de un canal de Teams

Un canal puede tener su propia dirección de correo.

Ejemplo:

```text
general.xxxxx@amer.teams.ms
```

No es la dirección del Grupo M365.

Es la dirección específica del canal.

Al enviar un correo a esa dirección:

```text
usuario
  ↓
email del canal
```

el contenido se publica en el canal.

---

# Diferencia entre correo de grupo y correo de canal

## Correo del Grupo

```text
ventas@empresa.com
```

Destino:

```text
Outlook
└─ Grupo
    └─ Conversations
```

---

## Correo del Canal

```text
general.xxxxx@amer.teams.ms
```

Destino:

```text
Teams
└─ Canal
    └─ Publicación
```

---

# Correo al grupo vs publicación en Teams

Conceptualmente ambos sirven para comunicarse con el mismo conjunto de personas.

## Correo

```text
Outlook
└─ Conversations
```

## Teams

```text
Teams
└─ General
```

Sin embargo, son sistemas distintos:

- El correo vive en Outlook.
- La publicación vive en Teams.

No son la misma conversación.

---

# Visibilidad de los grupos

No todos los usuarios ven todos los grupos.

Normalmente:

```text
Usuario
↓
Ve los grupos de los que es miembro
```

Además puede descubrir grupos públicos o grupos configurados para permitir solicitudes de acceso.

---

# No encontrar un grupo en Outlook

No es correcto asumir:

```text
No aparece en Outlook
↓
No existe Grupo M365
```

La única conclusión segura es:

```text
No aparece en mi experiencia actual de Outlook
```

El grupo puede existir igualmente.

Las causas pueden incluir:

- No ser miembro.
- Restricciones de visibilidad.
- Configuración del tenant.
- Ocultación del grupo en Outlook.

---

# Modelo mental final

```text
Microsoft 365 Group
│
├─ Outlook
│   ├─ Mailbox
│   ├─ Conversations
│   └─ Calendario
│
├─ SharePoint
│   └─ Sitio y documentos
│
└─ Teams (opcional)
    ├─ Team
    └─ Channels
```

Y la regla más importante:

```text
Todo Team estándar
    ↓
Tiene Grupo M365

Todo Grupo M365
    ↓
Tiene SharePoint

No todo Grupo M365
    ↓
Tiene Team
```
