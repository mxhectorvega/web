---
layout: post
title:  "Sway un gestor de ventanas en mosaico para Wayland"
date:   2021-12-02 10:00:00 +0700
tags: [archlinux, fedora, wayland, pipewire]
---

<center>
<img src="https://raw.githubusercontent.com/mxhectorvega/mxhectorvega.github.io/master/_posts/sway_window_manager/logo_sway.png" style="max-width:20%;width:auto;height:auto;">
</center>

Entremos en contexto: según la wiki ["sway (WM)"](https://swaywm.org/) es un administrador de ventanas en mosaico y compositor de Wayland, inspirado en i3, y escrito en "C", diseñado como un reemplazo directo para i3 usando el protocolo de servidor de pantalla más moderno ["wayland"](https://gitlab.freedesktop.org/wlroots/wlroots) y la biblioteca de compositores [wlroots](https://gitlab.freedesktop.org/wlroots/wlroots), hasta ahí estamos bien, pero... <mark>que hay de la configuración? funcionalidad? personalización? es bueno para una estacion de trabajo?</mark>

En el poco tiempo que llevo usando este gestor de ventanas en mosaico (3 meses) he notado mucha fluidez a comparación con el servidor x (xorg), ademas de encontrar a la mano herramientas nativas para wayland para capturar y grabar pantalla, así como gestor de portapapeles entre otras cosas útiles, que al final del día hacen mas cómodo el manejo del mismo, lo acompañé de una barra útil con botones y emojis representativos (waybar). Todo lo anterior esta instalando en una laptop con procesador Celeron 2.4Ghz, 4GB Ram y HDD. No conforme con eso le agregue Zram para que estuviera mas veloz 🔥.

**Puede probar mi configuracion siguiendo estos pasos:**
Puede ejecutar el script de instalacion automatizada que aplicara toda la configuracion y programas adicionales o clonar el repositorio y copiar manualmente los archivos que necesite.

1. Ejecute desde ```bash <(curl -L is.gd/swayarchmx)```
2. Ó clone el repositorio ```git clone https://github.com/mxhectorvega/sway-arch```

**Capturas de pantalla:**
<center>
<img src="https://raw.githubusercontent.com/mxhectorvega/mxhectorvega.github.io/master/_posts/sway_window_manager/captura.png" style="max-width:100%;width:auto;height:auto;">
</center>

**Comunidad:**
- [Canal Youtube](https://youtube.com/mxhectorvega)
- [Grupo Telegram de ArchLinux](https://t.me/waylandes)
