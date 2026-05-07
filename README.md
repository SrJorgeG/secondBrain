# 🧠 Second Brain

> Sistema personal de gestión del conocimiento integrado con OpenClaw, Trading e Inversiones.

[![Obsidian](https://img.shields.io/badge/Obsidian-%23483699.svg?style=for-the-badge&logo=obsidian&logoColor=white)](https://obsidian.md/)
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)](https://www.markdownguide.org/)

---

## 📖 Descripción

Este repositorio contiene mi **Second Brain** personal - un sistema de gestión del conocimiento construido con [Obsidian](https://obsidian.md/) y sincronizado mediante Git. Está organizado siguiendo el método **PARA** (Projects, Areas, Resources, Archive) y refleja la estructura de mi servidor de Discord.

### 🎯 Objetivos

- 📚 **Centralizar conocimiento** de trading, tecnología y proyectos
- 🔄 **Sincronización** entre dispositivos mediante Git
- 🔗 **Conectar ideas** mediante links bidireccionales ([[Obsidian-style]])
- 📈 **Trackear progreso** en trading y desarrollo personal
- 🤖 **Integración** con OpenClaw para automatizaciones

---

## 📁 Estructura

```
secondBrain/
├── 📥 00-Inbox/              # Captura rápida (procesar regularmente)
├── 🗂️ 01-Areas/             # Áreas de responsabilidad continua
│   ├── 🤖 OpenClaw/          # Configuración y documentación OpenClaw
│   ├── 📈 Trading-Inversiones/  # Trading, análisis, operaciones
│   └── 💬 General-Voz/       # Comunicaciones y reuniones
├── 📚 02-Resources/
│   ├── 📖 Documentacion/     # Documentación técnica
│   ├── 📖 Guides/            # Guías completas
│   │   └── Guía Trading Completa.md  # (21KB - 600+ líneas)
│   └── 📝 Templates/         # Plantillas reutilizables
├── 🎯 03-Projects/           # Proyectos con objetivo y deadline
├── 📦 04-Archive/            # Notas antiguas/inactivas
└── 📅 05-Daily/              # Notas diarias (journaling)
    └── 2025/
```

---

## 🚀 Uso Rápido

### Local (Obsidian)

```bash
# Clonar
 git clone git@github.com:SrJorgeG/secondBrain.git
 cd secondBrain

# Abrir con Obsidian
 obsidian .
```

### Sincronización

```bash
# Después de editar en Obsidian
git add .
git commit -m "Actualización: $(date +%Y-%m-%d)"
git push
```

---

## 🔄 Flujo de Trabajo (Método PARA)

1. **📥 Capturar** → Todo entra a `00-Inbox/` primero
2. **🗂️ Procesar** → Mover a área correspondiente o crear recurso  
3. **🔗 Desarrollar** → Conectar notas con links `[[nota-relacionada]]`
4. **📅 Revisar** → Revisión semanal de inbox y áreas activas

---

## 🗺️ Mapas de Contenido (MOCs)

Los MOCs (Maps of Content) son índices dinámicos:

- 🗺️ **[Index](Index.md)** - Índice central de todo el sistema
- 📈 **[Trading MOC](01-Areas/Trading-Inversiones/Trading%20MOC.md)** - Todo sobre trading e inversiones
- 🤖 **[OpenClaw MOC](01-Areas/OpenClaw/OpenClaw%20MOC.md)** - Documentación y configuración OpenClaw
- 💬 **[General MOC](01-Areas/General-Voz/General%20MOC.md)** - Comunicaciones y reuniones

---

## 📝 Plantillas Disponibles

| Plantilla | Uso |
|-----------|-----|
| [Nota Diaria](02-Resources/Templates/Plantilla%20-%20Nota%20Diaria.md) | Journaling diario |
| [Operación Trading](02-Resources/Templates/Plantilla%20-%20Operaci%C3%B3n%20Trading.md) | Registrar trades |
| [Análisis Empresa](02-Resources/Templates/Plantilla%20-%20An%C3%A1lisis%20Empresa.md) | Análisis fundamental |

---

## 🛠️ Herramientas

- **[Obsidian](https://obsidian.md/)** - Editor markdown con links bidireccionales
- **Git** - Control de versiones y sincronización
- **GitHub** - Backup en la nube
- **OpenClaw** - Asistente AI para automatizaciones

---

## 📊 Estadísticas

- **13 archivos** markdown organizados
- **1,151 líneas** de contenido
- **464 KB** de conocimiento estructurado
- **3 plantillas** reutilizables
- **3 áreas** principales de conocimiento

---

## 🔐 Notas

- Todo el contenido es **markdown puro** - portable a cualquier plataforma
- **.gitignore** excluye archivos de caché de Obsidian (workspace.json, etc.)
- Compatible con cualquier editor de markdown

---

## 📅 Historial

- **2025-05-07** - Setup inicial del Second Brain

---

<p align="center">
  <i>Construido con Obsidian + Git + Cafeína ☕</i>
</p>
