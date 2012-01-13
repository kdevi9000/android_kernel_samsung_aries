#@FUGU ICSSGS README.txt
# Copyright 2011 Trae Santiago
# ================================================
#
# This file is part of BuildAndPackage
#
# BuildAndPackage is free software: you 
# can redistribute it and/or modify it under the 
# terms of the GNU General Public License as 
# published by the Free Software Foundation, 
# either version 3 of the License, or (at your 
# option) any later version.
# 
# BuildAndPackage is distributed in the
# hope that it will be useful, but WITHOUT ANY 
# WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR 
# PURPOSE. See the GNU General Public License 
# for more details.
# 
# You should have received a copy of the GNU 
# General Public License along with BuildAndPackage. 
# If not, see: <http://www.gnu.org/licenses/>.
# (T.S / T.B / Trae32566 / Trae Santiago)

INSTRUCTIONS:
1. Fill out the userSettings.cfg in BuildAndPackage/resources folder
2. Create a tag at the beginning commit of your repository using the following commands:

$ git log --pretty=format:%H | tail -1
$ git tag -a Start ResultAbove

3. run BuildAndPackage.py from the command prompt using Python 3, IE:
    "$ python3 BuildAndPackage.py"
4. You will find the made files in the BuildAndPackage directory
