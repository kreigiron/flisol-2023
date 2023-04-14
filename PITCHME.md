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
## Recreación por Software: port FOSS
  - Port multiplataforma por liberacion de codigo del fabricante liberados bajo una licencia FOSS
---
![bg left 80%](https://happymag.tv/wp-content/uploads/2020/10/doompotato3-870x524.jpg)
# Como recrearlos?
## Recreación por Software: port FOSS

### Doom
  * https://github.com/id-Software/DOOM
---
![bg right 80%](https://upload.wikimedia.org/wikipedia/commons/e/e8/OpenArena_0.8.8_main_menu.png)
# Como recrearlos?
## Recreación por Software: port FOSS
### Quake
  - Quake https://ioquake3.org/
    - OpenArena https://github.com/OpenArena/

---
# Recreación por Software
## Ingeniería inversa

  - Port multiplataforma por reverse engineering liberados bajo una licencia FOSS   
    - https://www.retroreversing.com/
---
![bg left 80%](https://media.techeblog.com/images/super-mario-64-pc-port-60fps.jpg)
# Recreación por Software
## Ingeniería inversa
- Super Mario 64 - https://github.com/n64decomp/sm64 - Licencia CC0

---
![bg right 60%](https://raw.githubusercontent.com/kreigiron/flisol-2023/assets/zelda64code.png)
# Recreación por Software
## Ingeniería inversa

- Zelda Ocarina of Time https://github.com/HarbourMasters/Shipwright 
<!-- demo -->

---
# Recreación por Software
## Ingeniería inversa
  - Otros ports
    - Super Metroid - https://github.com/snesrev/sm - Licencia MIT
    - Zelda - A link to the past https://github.com/snesrev/zelda3
    - Diablo - https://github.com/diasurgical/devilutionX Licencia SUL 
    - entre otros

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
![bg right 80%](https://upload.wikimedia.org/wikipedia/commons/f/f0/ZSNES_Windows_Screenshot.png)
## Ejemplos sobresalientes de emuladores FOSS
  - Zsnes (obsoleto)
    - snes
    - Programado en ASM x86
    - Liberado en 2000 bajo la GPL
      - https://sourceforge.net/projects/zsnes/
      - https://github.com/xyproto/zsnes (fork)
---  
![bg left 60%](https://upload.wikimedia.org/wikipedia/commons/a/ad/The_logo_for_multi-system_emulator_higan.svg)
## Ejemplos sobresalientes de emuladores FOSS  
  - BSnes/Higan
    - snes y multiconsola (higan)
    - C/C++
    - Enfocado en exactitud    
    - Licencia GPLv3
      - https://github.com/bsnes-emu/bsnes
      - https://github.com/higan-emu/higan

---
![bg right 60%](https://upload.wikimedia.org/wikipedia/commons/a/a2/Logo_Duckstation.svg)
## Ejemplos sobresalientes de emuladores FOSS  
  - Duckstation 
    - PSX
    - C++
    - Mejoras tecnicas a la consola 
      - anti alias
      - z buffer emulation
    - Licencia GPLv3
      - https://github.com/stenzek/duckstation
---
![bg left 60%](https://upload.wikimedia.org/wikipedia/commons/0/09/Ishiiruka_Dolphin_logo.png)
## Ejemplos sobresalientes de emuladores FOSS 
  - Dolphin
    - GameCube/Wii
    - C++
    - Mejoras tecnicas a la consola
      - HD, UHD
    - Con mucha actividad de desarrollo
    - Licencia GPLv2+
      - https://github.com/dolphin-emu/dolphin
---
![bg right 60%](https://upload.wikimedia.org/wikipedia/commons/4/45/RPCS3_vector_logo_%28alternative_trademark%29.svg)
## Ejemplos sobresalientes de emuladores FOSS 
  - RPSC3
    - PS3
    - C++
    - 60%+ de compatibilidad
    - Licencia GPLv2
      - https://github.com/RPCS3/rpcs3
---
![bg left 60%](https://upload.wikimedia.org/wikipedia/commons/3/35/Yuzu_Emulator.svg)
## Ejemplos sobresalientes de emuladores FOSS 
  - Yuzu
    - Switch
    - C
    - Corre en SteamDeck!
    - GPLv3
      - https://github.com/yuzu-emu/yuzu
---
## Ejemplos sobresalientes de emuladores FOSS 
![bg right 60%](https://upload.wikimedia.org/wikipedia/commons/0/07/Ryujinx_Logo.png)
  - Ryujinx
    - Switch
    - C# (!)
    - Alternativa a Yuzu
    - MIT
      - https://github.com/Ryujinx/Ryujinx
--- 
## Ejemplos sobresalientes de emuladores FOSS 
![bg left 60%](https://upload.wikimedia.org/wikipedia/commons/2/20/Retroarch_Lakka.svg)
  - Plataformas libretro
    - Retroarch
    - Lakka https://www.lakka.tv/
    - Retropie
    - Recalbox
    - Emuelec


---
![bg right 60%](https://upload.wikimedia.org/wikipedia/commons/9/96/Embedded_World_2016%2C_Altera_Cyclone-V_SE_%28cropped%29.jpg)
# Recreacion por FPGA:
* Que es un FPGA?
  * Hardware programable
    * Industria
    * Medicina
    * Videojuegos
--- 
![bg left 60%](https://upload.wikimedia.org/wikipedia/commons/7/71/LAB_VHDL_Tiny861_7.png)
## Recreacion de consolas por FPGA
 - No es Emulacion, es recreacion del hardware en el FPGA
 - Nucleos intercambiables segun el hardware.


   
---
![bg right 60%](https://github.com/MiSTer-devel/Wiki_MiSTer/wiki/pictures/MiSTer.jpg)
## Proyectos de recreacion FOSS por FPGA
   * MisT
     - Cyclone EP3C25 FPGA
     - nucleos desde Atari ST hasta Amiga
   * MisTER
     - FPGA  'DE10-Nano' modular
     - nucleos desde PDP-11 hasta PSX
     - Activo 

---
# Conclusiones
* 4 principios del software libre
  * Como manera de recrear y ejecutar aplicaciones y juegos de plataformas obsoletas <!-- Ejecutarlo donde sea cuando sea sin depender del fabricante -->
    * Plataforma de ejecucion de dominio publico
  * Como medio de aprendizaje de tecnicas y optimizacion a bajo nivel 
    * Desarrollo colaborativo
  * Como plataforma de distribucion de las que antes eran tecnologias privativas 
    * e.g. MiSTer project
  * Como manera de mejorarlo continuamente 
    * e.g. upscalers(ossc), overclocking

---

## Dudas, comentarios
---
# Gracias
### Created by Erik Giron ([@kreig](https://github.com/kreigiron))
