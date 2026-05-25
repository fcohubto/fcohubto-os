# fcohubto · os

Sistema Operativo Personal de Francisco Orellana — Product Designer estratégico.

Dashboard publicado en GitHub Pages que centraliza las 6 capas del sistema personal:

| Módulo | Descripción |
|---|---|
| **Inbox** | Ideas en bruto con estados y persistencia en localStorage |
| **System Map** | Estado visual de todos los repositorios del sistema |
| **Architecture Spec** | Las 3 capas (Francisco → OLIVA → Olivacraft) y sus reglas |
| **Prompt Registry** | Tabla versionada de prompts por modelo R/C/P |
| **Execution Pipeline** | Kanban de todo lo que está en movimiento |
| **OLIVA OS** | Acceso directo al framework de pensamiento con IA |

## Stack

- HTML + CSS + JS vanilla — sin frameworks externos
- Tipografía: Fraunces (serif) + Plus Jakarta Sans (sans-serif)
- Persistencia: localStorage para el Inbox
- Hosting: GitHub Pages

## Uso

Abrir [fcohubto.github.io/fcohubto-os](https://fcohubto.github.io/fcohubto-os/) en cualquier navegador.  
Navegar con los links del sidebar o con las teclas ↑ ↓.

## Estructura del sistema

```
Francisco System  ←  fcohubto-os  (este repo)
       ↓
   OLIVA OS        ←  fw_oliva
       ↓
  Olivacraft       ←  olivacraftos
```

---

v1 · Mayo 2026
