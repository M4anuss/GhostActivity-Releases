# GhostActivity

Aplicación de escritorio para **Discord Rich Presence** en Windows — legítima, local y sin selfbots.

> Este repositorio es solo para **descargar e instalar** la app. El código fuente está en un repositorio privado del equipo Bonemelt Studios.

![GhostActivity](https://raw.githubusercontent.com/M4anuss/GhostActivity-Releases/main/assets/logo.png)

---

## Descargar e instalar

**No necesitas CMD, Node.js, Rust ni npm.**

1. Abre **[Releases](https://github.com/M4anuss/GhostActivity-Releases/releases)** (pestaña *Releases* arriba).
2. Descarga **`GhostActivity_Setup.exe`** de la última versión.
3. Doble clic → sigue el asistente → abre GhostActivity.
4. Crea una app en el [Discord Developer Portal](https://discord.com/developers/applications) y copia el **Application ID**.
5. En GhostActivity: pega el ID → **Probar conexión** → configura tu presencia → **Activar presencia**.

### Requisitos

- Windows 10/11 (64 bits)
- [Discord desktop](https://discord.com/download) abierto
- WebView2 (el instalador lo gestiona si falta)

### Durante la instalación

- Acceso directo en **Escritorio** y **Menú Inicio** (*Bonemelt Studios*).
- Te preguntará si quieres **iniciar con Windows** (también puedes cambiarlo después en la app).

### Tus datos

La configuración se guarda en:

```text
%APPDATA%\com.ghostactivity.app\data\
```

### Desinstalar

**Configuración de Windows → Aplicaciones → GhostActivity → Desinstalar**

La desinstalación también quita la entrada de **inicio automático** con Windows.

---

## Primera versión

Si aún no hay archivos en [Releases](https://github.com/M4anuss/GhostActivity-Releases/releases), el equipo está publicando el instalador. Vuelve en unos minutos o revisa que exista el tag `v0.1.0` (o superior) en Releases.

---

## Problemas frecuentes

| Problema | Qué hacer |
|----------|-----------|
| «Discord no está abierto» | Abre la app de escritorio de Discord (no el navegador) y prueba de nuevo. |
| App ID inválido | Usa el Application ID numérico del [Developer Portal](https://discord.com/developers/applications). |
| La presencia no se ve | Activa la presencia en la app y pulsa **Aplicar cambios ahora** tras editar. |
| Imagen pequeña no aparece | La asset key debe coincidir **exactamente** con la del Portal; hace falta imagen grande + pequeña. |
| Los botones no los veo yo | Es normal: Discord solo muestra botones a **otras personas** en tu perfil. |

---

## Windows SmartScreen

Si Windows muestra *“Editor desconocido”*:

1. Pulsa **Más información**.
2. **Ejecutar de todas formas**.

Es normal en versiones sin firma de código comercial. Las versiones firmadas reducirán este aviso.

---

## Soporte

- Problemas de instalación o uso: abre un [Issue](https://github.com/M4anuss/GhostActivity-Releases/issues) en este repositorio.
- No publiques tokens de Discord ni Application Secrets.

---

## Licencia

MIT — Bonemelt Studios
