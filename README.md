# Sistema de Notas de Alumnos

## Descripción

Sistema de gestión de notas desarrollado por consola que permite registrar alumnos, almacenar sus calificaciones, consultar información académica y obtener estadísticas básicas del curso.

El objetivo del proyecto es aplicar conceptos de análisis de requerimientos, diagramas de flujo y organización de software antes de la etapa de desarrollo.

---

## Funcionalidades

* Mostrar menú principal de opciones.
* Registrar alumnos con nombre y nota.
* Visualizar la lista completa de alumnos cargados.
* Calcular el promedio general del curso.
* Mostrar alumnos aprobados (nota mayor o igual a 6).
* Mostrar alumnos desaprobados (nota menor a 6).
* Buscar alumnos por nombre.
* Salir del sistema.

---

## Requerimientos Funcionales

| Código | Descripción                                |
| ------ | ------------------------------------------ |
| RF-01  | Mostrar menú de opciones.                  |
| RF-02  | Permitir cargar alumnos con nombre y nota. |
| RF-03  | Mostrar la lista de alumnos registrados.   |
| RF-04  | Calcular y mostrar el promedio general.    |
| RF-05  | Mostrar alumnos aprobados.                 |
| RF-06  | Mostrar alumnos desaprobados.              |
| RF-07  | Buscar alumnos por nombre.                 |
| RF-08  | Permitir salir del programa.               |

---

## Requerimientos No Funcionales

| Código | Descripción                       |
| ------ | --------------------------------- |
| RNF-01 | Mensajes claros y en español.     |
| RNF-02 | Validación de notas entre 1 y 10. |
| RNF-03 | Validación de entradas numéricas. |
| RNF-04 | Código organizado en funciones.   |
| RNF-05 | Documentación mediante README.    |

---

## Estructura del Proyecto

```text
sistema-notas/
│
├── docs/
│   ├── requerimientos.md
│   └── diagrama_flujo.md
│
├── main.py
└── README.md
```

---

## Diagrama de Flujo

El diagrama de flujo del sistema se encuentra en:

```text
docs/diagrama_flujo.md
```

Desarrollado utilizando Mermaid para su visualización en GitHub.

---

## Tecnologías Utilizadas

* Python 3
* Git
* GitHub
* Mermaid

---

## Cómo Ejecutar

1. Clonar el repositorio:

```bash
git clone https://github.com/zairacunha/sistema-notas.git
```

2. Ingresar al proyecto:

```bash
cd sistema-notas
```

3. Ejecutar el programa:

```bash
python main.py
```

---

## Objetivo Académico

Este proyecto fue desarrollado como actividad práctica para aplicar conceptos de análisis de requerimientos, diseño de software y diagramas de flujo utilizando Mermaid, siguiendo las etapas del ciclo de vida del software.

## Autora

**Zaira Cunha - [@zairacunha](https://github.com/zairacunha)**

Actividad práctica de Requerimientos y Diagramas de Flujo.
