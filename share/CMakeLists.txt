# SPDX-License-Identifier: GPL-3.0-only
# MuseScore-Studio-CLA-applies
#
# MuseScore Studio
# Music Composition & Notation
#
# Copyright (C) 2021 MuseScore Limited
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License version 3 as
# published by the Free Software Foundation.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <https://www.gnu.org/licenses/>.

subdirs(autobotscripts icons templates wallpapers locale styles sound manual instruments)

install (DIRECTORY
    plugins
    DESTINATION ${Mscore_SHARE_NAME}${Mscore_INSTALL_NAME}
    PATTERN ".*" EXCLUDE
    )

install (DIRECTORY
    extensions
    DESTINATION ${Mscore_SHARE_NAME}${Mscore_INSTALL_NAME}
    PATTERN ".*" EXCLUDE
    )

install (DIRECTORY
    workspaces
    DESTINATION ${Mscore_SHARE_NAME}${Mscore_INSTALL_NAME}
    PATTERN ".*" EXCLUDE
    )
