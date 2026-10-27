# Análisis de Evento en AWS CloudTrail

- **Nombre del evento (Event Name):** `LookupEvents`
- **Servicio de origen (Event Source):** `cloudtrail.amazonaws.com`
- **Usuario / Identidad (User Name):** `RobinsonFabianAldanaGomez` (ARN: `arn:aws:iam::654654478122:user/RobinsonFabianAldanaGomez`)
- **ID de Cuenta (Account ID):** `654654478122`
- **Región de AWS (AWS Region):** `us-east-1`
- **Fecha y Hora (Event Time):** `2026-10-27T02:28:52Z`
- **Dirección IP de origen (Source IP Address):** `186.154.37.80`

## Conclusión y Auditoría
Este registro demuestra la consulta realizada en el historial de eventos de CloudTrail para rastrear acciones como la creación de instancias (`RunInstances`). Permite verificar de forma transparente quién ejecutó la acción, desde qué dirección IP, bajo qué rol o usuario de IAM y en qué marca temporal exacta dentro de la infraestructura de AWS.