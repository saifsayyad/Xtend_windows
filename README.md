# Xtend_windows

Command to run xtend batch compiler is:

``java -jar path/to/xtend_windows_fix.jar -cp path/to/xtend_windows_fix.jar path/to/input -d output/path``

``path/to/input``: Directory containing all the ``.xtend`` files.

fixed the ``org.eclipse.xtend.lib.macro.file.Path.getParent(Path.java:129)`` problem which is claimed to be fixed for windows,
but not fixed!

for detail please follow: https://bugs.eclipse.org/bugs/show_bug.cgi?id=421000
