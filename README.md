# Universidad — Talleres

Repositorio con los proyectos y talleres evaluados del curso. Cada carpeta es un proyecto independiente con sus propias dependencias, tests y documentación.

---

## Proyectos

| Carpeta | Nombre | Descripción | Stack |
|---|---|---|---|
| [`taller_evaluado_04`](./taller_evaluado_04) | Taller Evaluado 04 | Funciones utilitarias básicas con cobertura de tests | Python, Pytest |
| [`taller_08`](./taller_08) | Taller Evaluado 02 — Encriptador/Desencriptador | Cifrado y descifrado de texto usando AES-256-CBC por línea de comandos | Python, Pycryptodome, Pytest |
| [`Solenme_1_FastAPI`](./Solenme_1_FastAPI/time-api-fastapi) | Solemne 1 — Time API | API REST con FastAPI que retorna la fecha y hora actual en JSON | Python, FastAPI, Docker |

---

## Estructura

```
Universidad_talleres/
├── taller_evaluado_04/       # Taller Evaluado 04
├── taller_08/                # Taller Evaluado 02 — Encriptador AES
└── Solenme_1_FastAPI/        # Solemne 1 — Time API FastAPI
```

---

## Requisitos generales

- Python 3.11+
- [uv](https://github.com/astral-sh/uv) (gestor de dependencias recomendado)

Cada proyecto tiene su propio `requirements.txt`. Para instalar dependencias en cualquier proyecto:

```bash
cd <carpeta-proyecto>
uv venv && source .venv/bin/activate
uv pip install -r requirements.txt
```
