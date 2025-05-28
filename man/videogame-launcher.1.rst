..
   SPDX-License-Identifier: AGPL-3.0-or-later

   ----------------------------------------------------------------------
   Copyright © 2024, 2025  Pellegrino Prevete

   All rights reserved
   ----------------------------------------------------------------------

   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU Affero General Public License for more details.

   You should have received a copy of the GNU Affero General Public License
   along with this program.  If not, see <https://www.gnu.org/licenses/>.


====================================
videogame-launcher
====================================

--------------------------------------------------------------------------------
Videogame Launcher
--------------------------------------------------------------------------------
:Version: videogame-launcher |version|
:Manual section: 1


Synopsis
========

videogame-launcher *[options]* *app_id*


Description
===========

Seamlessly launch videogames.

It works cross-platform on GNU/Linux,
Android and Windows, so it is a dependency
of almost all the videogames published on the
Ur application store.


Options
========

-e game_launcher        It can be 'duckstation',
                        'fceux', 'gearboy', 'mame',
   		        'retroarch', 'pcsx2'.
-p game_platform        Game platform. It can be
                        'playstation', 'arcade',
   		        'mame2010', 'nes', 'gameboy',
                        'playstation2'.
-l game_lang            Game languages.
-H                      Enables on-screen
                        controller HUD.
-s game_settings        Duckstation settings file.
-f                      Launch the game in full-screen.

-h                      Display help.
-c                      Enable color output
-v                      Enable verbose output


Bugs
====

https://github.com/themartiancompany/videogame-launcher/-/issues

Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.

See also
========

* duckstation-nogui
* fceux
* gearboy -h
* mame
* pcsx2

.. include:: variables.rst
