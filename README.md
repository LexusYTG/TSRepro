# TSRepro
Un reproductor de música sencillo compacto y completo que cabe en un png de 144 p

# TSrepro - Reproductor de Música Android

![Licencia GPL v3](https://img.shields.io/badge/Licencia-GPL%20v3-blue.svg)
![Tamaño APK](https://img.shields.io/badge/APK-85%20KB-green.svg)
![Plataforma](https://img.shields.io/badge/Plataforma-Android-lightgrey.svg)

## 📱 Descripción

**TSrepro** es un reproductor de música ligero y de código abierto para Android, desarrollado por **Turing Software**. Diseñado para ofrecer una experiencia de audio limpia y eficiente sin consumir recursos excesivos.

## ✨ Características

- 🎵 **Soporte múltiple formatos**: MP3, WAV, OGG, M4A, FLAC
- 🎨 **Interfaz moderna**: Modo claro/oscuro con diseño Material
- 📱 **Reproducción en segundo plano**: Con notificación persistente
- 🔄 **Modos de repetición**: Desactivado, lista, canción única
- 🔀 **Reproducción aleatoria**
- ⭐ **Favoritos**: Marca y filtra tus canciones preferidas
- 📜 **Letras sincronizadas**: Soporte para archivos .lrc
- 🎛️ **Ecualizador**: Múltiples preajustes de audio
- ⏰ **Temporizador de apagado**: 15, 30, 60 minutos
- 🔍 **Búsqueda rápida**: Por título y artista
- 📂 **Carpeta personalizable**: Selecciona tu directorio de música
- 🖼️ **Placeholders inteligentes**: Arte visual generado automáticamente

## 📥 Instalación

**APK**: 85 KB (el tamaño de la instalación puede variar según el dispositivo)

1. Descarga el archivo APK desde [Releases](https://github.com/TuringSoftware/TSrepro/releases)
2. Habilita "Orígenes desconocidos" en ajustes de seguridad
3. Instala la aplicación
4. Concede permisos de almacenamiento cuando se solicite

## 🚀 Uso

1. **Primer inicio**: La aplicación escaneará automáticamente la carpeta de música
2. **Navegación**:
   - Lista principal: Todas las canciones
   - Miniplayer: Controles rápidos en la parte inferior
   - Player completo: Toca el miniplayer para expandir
3. **Controles**:
   - Play/Pause, anterior, siguiente
   - Barra de progreso deslizable
   - Control de volumen integrado
4. **Organización**: Usa el interruptor de favoritos y la barra de búsqueda

## ⚙️ Configuración

Accede a los ajustes desde el botón ⚙️ en la barra superior:

- **Modo oscuro/claro**
- **Carpeta de música personalizada**
- **Preajuste de ecualizador**
- **Temporizador de apagado**
- **Ordenación** (título, artista, duración)

## 🛠️ Desarrollo

### Requisitos
- Android API 16+ (Jelly Bean)
- Android Studio
- Permiso READ_EXTERNAL_STORAGE

### Estructura del proyecto
```
TSrepro/
├── MainActivity.java      # Actividad principal e UI
├── MusicPlayer.java       # Lógica de reproducción
└── FileManager.java       # Gestión de archivos y escaneo
```

### Compilación
```bash
git clone https://github.com/TuringSoftware/TSrepro.git
cd TSrepro
# Abrir en Android Studio y compilar
```

## 📄 Licencia

Este proyecto está bajo la **Licencia Pública General de GNU v3.0**. 
Puedes usar, modificar y distribuir este software libremente, manteniendo la atribución y bajo la misma licencia.

```text
Copyright (C) 2025 Turing Software
Este programa es software libre: puedes redistribuirlo y/o modificar
lo bajo los términos de la Licencia Pública General de GNU publicada por
la Free Software Foundation, ya sea la versión 3 de la Licencia, o
(a tu elección) cualquier versión posterior.
```

## 💝 Donaciones

El uso de **TSrepro es completamente gratuito**. No se requieren donaciones, pero si deseas apoyar el desarrollo y mantenimiento del proyecto:

**Para Argentina:**
- **CBU**: 0000085700204655142304
- **Alias**: tester33ytg

Tu contribución ayuda a seguir mejorando esta aplicación y desarrollar nuevos proyectos de código abierto.

## 🙏 Agradecimientos

Un especial agradecimiento a:

- **La comunidad de código abierto** por las herramientas y bibliotecas
- **Los colaboradores** que han reportado errores y sugerido mejoras
- **Los usuarios** por su confianza y feedback continuo

## 📞 Soporte

Si encuentras algún problema o tienes sugerencias:
- Abre un [issue](https://github.com/TuringSoftware/TSrepro/issues)
- Contacta al desarrollador principal: **Leonardo.S.NIVOIDA**

---

**¡Disfruta de tu música con TSrepro! 🎶**
