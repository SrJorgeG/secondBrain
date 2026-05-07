# 🔄 Guía de Sincronización

## Estructura del Repositorio

Este Second Brain usa **Obsidian** como interfaz principal de lectura/edición, pero todo el contenido se sincroniza con GitHub.

```
second-brain/ (repo Git)
├── 📄 README.md
├── 📄 Index.md
├── 📄 .gitignore (excluye archivos de caché de Obsidian)
├── 📥 00-Inbox/
├── 🗂️ 01-Areas/
│   ├── General-Voz/
│   ├── OpenClaw/
│   └── Trading-Inversiones/
├── 📚 02-Resources/
│   ├── Documentacion/
│   ├── Guides/
│   └── Templates/
├── 🎯 03-Projects/
├── 📦 04-Archive/
└── 📅 05-Daily/
    └── 2025/
```

## 📝 Tipos de Documentos

| Tipo | Extensión | Uso |
|------|-----------|-----|
| Notas | `.md` | Principal - Se ven perfecto en Obsidian |
| Guías | `.md` | Documentación extensa |
| Templates | `.md` | Plantillas reutilizables |
| Datos | `.csv`, `.json` | Datos estructurados (próximamente) |
| Hojas cálculo | `.xlsx` | Análisis financiero (próximamente) |
| Diagramas | `.png`, `.svg` | Gráficos (próximamente) |
| Código | `.py`, `.js` | Scripts de automatización (próximamente) |

## 🔄 Flujo de Trabajo

### Uso Diario (Local)
1. Abrir Obsidian: `openclaw-brain`
2. Editar/Crear notas en markdown
3. Cerrar Obsidian

### Backup (Git)
```bash
# Desde ~/openclaw-workspace/second-brain/
git add .
git commit -m "Actualización: $(date +%Y-%m-%d)"
git push origin main
```

### Recuperación (si cambias de PC)
```bash
git clone https://github.com/TU-USUARIO/second-brain.git
cd second-brain
openclaw-brain  # o abrir con Obsidian manualmente
```

## 💡 Ventajas de esta arquitectura

1. **Obsidian** = Excelente experiencia de lectura/escritura
2. **Git** = Historial completo, backup, sincronización
3. **Markdown** = Formato universal, portable
4. **GitHub** = Backup en la nube, acceso desde web

## 📚 Recursos

- [Obsidian](https://obsidian.md/) - Editor markdown
- [Git](https://git-scm.com/) - Control de versiones
- [GitHub](https://github.com/) - Hosting del repositorio
