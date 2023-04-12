---
marp: true
title: Preservacion y recreacion de videojuegos retro usando software libre
description: --
theme: lead
transition: fade
paginate: true
_paginate: false
---

![bg opacity](./assets/gradient.jpg)

#  <!--fit--> Preservación y recreación 
#  <!--fit--> de videojuegos retro con
#  <!--fit-->  Software Libre

Erik Girón

https://kreigiron.github.io/flisol-2023

<style scoped>a { color: #36c; }</style>

<!-- Saludos e Introduccion -->

---
![bg right 80%](https://upload.wikimedia.org/wikipedia/commons/9/91/Final_Fantasy_logo_with_japanese_name.svg)

# ¿Para que preservar?
## Videojuegos como expresión artística

* Soundtrack
  
* Vídeo
  
* Historia

* Todo combinado

<!-- insertar pics de juego viejos famoso (sf, super metroid, sb3, dkc) -->


---
# ¿Para qué preservar?
## Videojuegos como logro técnico
![bg left 80%](https://upload.wikimedia.org/wikipedia/commons/7/75/RP2A03E.jpg)
* Piezas unicas escritas a mano.
  * Efectos visuales, Musica, Interaccion.
* Ejecucion en hardware obsoleto o fuera de produccion.
  * Sensible al "ritmo" o velocidad de hardware para una correcta reproduccion.
* Plataformas o tiendas en linea privativas del fabricante.
<!-- tienden a morir, e.g. 3ds store que cerro el mes pasado, etc-->

---
# ¿Para qué preservar?
![bg right 50%](https://img.buzzfeed.com/buzzfeed-static/static/2020-04/15/22/asset/1052735824f9/sub-buzz-1257-1586990219-2.jpg)
## Nostalgia

---
<!--
## Por qué con FOSS?
- Libre de ataduras privativas del fabricante
  - Dominio público
- Mejora continua
  - Desarrollo colaborativo


---
-->

![bg left 80%](https://upload.wikimedia.org/wikipedia/commons/4/46/Heat_decap_with_MAPP_gas.jpg)
# Cómo preservarlo?
## Hardware (Consolas y dispositivos fisicos):
* Ingenieria inversa del hardware.
* Recreacion por el uso uso de especificaciones abiertas.

---
# Cómo preservarlo?
![bg right 80%](https://upload.wikimedia.org/wikipedia/commons/a/aa/Floppy_disk_2009_G1.jpg)
## Software (Juegos)
- Medios de almacenamiento vulnerables 
  - cartucho
    - Hardware de lectura no disponible u obsoleto
  - diskettes 
    - Deterioro magneticop
  - CD y medios opticos
    - Deteorioro ambiental  
---
# Cómo preservarlo?
## Proyectos de preservación
* Redump project - http://redump.org/
  - Guias y herramientas para
    - extraer - dump
    - comparar ' checksum
    - compartir - share
---


## Grupos de preservación de imágenes de juego
* Gaming Alexandria
  - https://www.gamingalexandria.com/wp/
* Videogame preservation collective
  - https://www.preservegames.org/
* Archive.org

---

# Como recrearlos?
## Recreación por hardware 
![bg right 80%](https://junkerhq.net/xrgb/images/b/b1/Ossc-logo-small.png)
![bg right 80%](https://junkerhq.net/xrgb/images/1/18/Ossc_v1.7.jpg)
- Hardware original y clones
  - CRT
    - Upscalers por hardware
      - Retrothink
      - Framemeister
    - Open souce
      - OSSC
  - Repro carts <!-- everdrive -->

---
# Como recrearlos?
## Recreación por Software
  - Port multiplataforma por liberacion de codigo del fabricante liberados bajo una licencia FOSS
    - Doom
      - <!-- imagen doom corriendo en una refri -->
---
# Como recrearlos?
## Recreación por Software
  - Port multiplataforma por liberacion de codigo del fabricante liberados bajo una licencia FOSS
    - Quake
      - OpenArena
---
# Recreación por Software
## Ingeniería inversa
https://www.retroreversing.com/
  - Port multiplataforma por reverse engineering liberados bajo una licencia FOSS   
    - Super Mario 64 - https://github.com/n64decomp/sm64 - Licencia CC0
    - Super Metroid - https://github.com/snesrev/sm - Licencia MIT
    - Zelda - A link to the past https://github.com/snesrev/zelda3
    - Zelda Ocarina of Time https://github.com/HarbourMasters/Shipwright 
    - Diablo - https://github.com/diasurgical/devilutionX Licencia SUL (?)
  


---
# Recreación por Software
## Emulación
  * LLE para consolas antiguas. <!-- Ejemplos de emuladores FOSS de nes, snes-->
    * carecen de OS regularmente
    * Programadas a bajo nivel
  * HLE para consolas de 5ta + generacion    <!-- Ejemplos de emuladores FOSS de psx, n64, ps3-->
    * Tienen OS
    * Programadas a alto nivel con SDKs proveidos 


---

## Ejemplos sobresalientes de emuladores FOSS
  - Zsnes (obsoleto)
    - Programado en ASM x86
    - Liberado en 2000 bajo la GPL
    - Repo link
---  
## Ejemplos sobresalientes de emuladores FOSS  
  - BSnes/Higan
    - Programado mayormente en C
    - Enfocado en exactitud

---
## Ejemplos sobresalientes de emuladores FOSS  
  - Duckstation https://github.com/stenzek/duckstation
---
## Ejemplos sobresalientes de emuladores FOSS  
  - PCSX2
---
## Ejemplos sobresalientes de emuladores FOSS 
  - Dolphin
---
## Ejemplos sobresalientes de emuladores FOSS 
  - RPSC3
---
## Ejemplos sobresalientes de emuladores FOSS 
  - Yuzu
---
## Ejemplos sobresalientes de emuladores FOSS 
  - Ryujinx
--- 
## Ejemplos sobresalientes de emuladores FOSS 
  - Plataformas libretro
    - Retroarch
    - Lakka https://www.lakka.tv/
    - Retropie
    - Recalbox
    - Emuelec


---

# Reproduccion por FPGA:
* Que es un FPGA?
  * Hardware programable
    * Industria
    * Medicina
    * Videojuegos
--- 
## Proyectos de recreacion FOSS por FPGA
* MisT
* MisTER

---
# Conclusiones
* 4 principios del software libre
  * como manera de recrear y ejecutar aplicaciones y juegos de plataformas obsoletas <!-- Ejecutarlo donde sea cuando sea sin depender del fabricante -->
    * Plataforma de ejecucion de dominio publico
  * como medio de aprendizaje de tecnicas y optimizacion a bajo nivel 
    * Desarrollo colaborativo
  * como plataforma de distribucion de las que antes eran tecnologias privativas 
    * e.g. MiSTer project
  * como manera de mejorarlo continuamente 
    * e.g. upscalers(ossc), overclocking

---
# Dudas

---
![Marp bg 60%](https://raw.githubusercontent.com/marp-team/marp/master/marp.png)

---

<!-- _backgroundColor: "#123" -->
<!-- _color: "#fff" -->

##### <!--fit--> [Marp CLI](https://github.com/marp-team/marp-cli) + [GitHub Pages](https://github.com/pages) | [Netlify](https://www.netlify.com/) | [Vercel](https://vercel.com/)

##### <!--fit--> 👉 The easiest way to host<br />your Marp deck on the web

---

![bg right 60%](https://upload.wikimedia.org/wikipedia/commons/9/91/Final_Fantasy_logo_with_japanese_name.svg)

## **[GitHub Pages](https://github.com/pages)**

#### Ready to write & host your deck!

[![Use this as template h:1.5em](https://img.shields.io/badge/-Use%20this%20as%20template-brightgreen?style=for-the-badge&logo=github)](https://github.com/yhatt/marp-cli-example/generate)

---

![bg right 60%](https://icongr.am/simple/netlify.svg?colored)

## **[Netlify](https://www.netlify.com/)**

#### Ready to write & host your deck!

[![Deploy to Netlify h:1.5em](./assets/netlify-deploy-button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yhatt/marp-cli-example)

---

![bg right 60%](https://icongr.am/simple/zeit.svg)

## **[Vercel](https://vercel.com/)**

#### Ready to write & host your deck!

[![Deploy to Vercel h:1.5em](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/yhatt/marp-cli-example)

---

### <!--fit--> :ok_hand:

---

![bg 40% opacity blur](https://avatars1.githubusercontent.com/u/3993388?v=4)

### Created by Yuki Hattori ([@yhatt](https://github.com/yhatt))

https://github.com/yhatt/marp-cli-example
