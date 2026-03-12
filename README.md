# Grupo 4 - Consultar Citas

## Microservicio
Consulta de citas médicas por paciente.

## Endpoint implementado
GET /citas/{paciente_id}

## Parámetros
| Parámetro    | Tipo | Descripción                  |
|--------------|------|------------------------------|
| paciente_id  | int  | ID del paciente a consultar  |

## Ejemplo Request
GET http://172.19.64.246:8004/citas/1

## Ejemplo Response
[
  {
    "id": 1,
    "paciente_id": 1,
    "fecha": "2025-03-12 10:00:00",
    "estado": "activa"
  }
]

## Ejemplo Response (sin citas)
[]

## IP y Puerto
- IP: 172.19.64.246
- Puerto: 8004
- URL base: http://172.19.64.246:8004
- Swagger: http://172.19.64.246:8004/docs
