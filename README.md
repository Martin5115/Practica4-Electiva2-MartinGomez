# Practica4-Electiva2-MartinGomez


**Estudiante:** Martin Gomez
**Materia:** Electiva 2 (DevOps)
**Institución:** ITLA

## Descripción

Esta práctica implementa un flujo de integración continua con GitHub Actions. Cada vez que se sube código a la rama `main`, el workflow se ejecuta automáticamente, corre un programa "Hola Mundo" en JavaScript y envía una notificación a [ntfy.sh/devops-itla](https://ntfy.sh/devops-itla).

## Estructura del proyecto

```
.
├── .github/
│   └── workflows/
│       └── alerta.yml   # Workflow de GitHub Actions
├── hola.js              # Programa Hola Mundo
└── README.md
