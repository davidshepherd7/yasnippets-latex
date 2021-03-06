What is it?
-----------

Yasnippets-latex is a bundle of [LaTeX][1] snippets for use with the
[YASnippet][2] template system for [Emacs][3].

[1]: http://www.latex-project.org/
[2]: http://github.com/capitaomorte/yasnippet
[3]: http://www.gnu.org/software/emacs/

Thanks
------

This snippet bundle has been created in collaboration by:
Mads D. Kristensen
Bjorn Reese 
Song Qiang
Claudio Marforio
Francois Garillot
Kevin Lynch
Marcio M. Ribeiro
Rasmus Borgsmidt

Licencing stuff
---------------

Copyright (c) 2010, Mads D. Kristensen <madsdk@gmail.com>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Installation
------------

In order to use these snippets you need to install Emacs, AucTeX,
RefTeX, and YASnippet. Once that is done installation is done by
simply copying the files .yas-parents, .yas-ignore-filenames-as-triggers,
.yas-make-groups, and the snippets into the 'snippets/latex-mode'
subdirectory within your YASnippet installation. It may also be advisable 
to delete the existing latex snippets (to prevent clashes).

You can also use the installation script install.sh. The script takes 
a single argument which is the directory in which you have installed
yasnippet. 

If Emacs is running you need to issue the 'yas/reload-all' command in
order to load the snippets.
