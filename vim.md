# vim/vi
- normal
    - move:
        - jk, hl
        - 0, $            : line herd / line end
        - ctrl u, ctrl d : page up   / page down
        - gg, G          : file head / file end
        - w, b           : word by word
    - copy   : yy
    - paste  : p
    - delete : dd, x
    - align  : >>, <<
    - undo   : u
    - redo   : ctrl r
    - join   : J
    - repeat : .

- visual(V)

- command:
    - set list/ nolist
    - set number/ nonumber

- search
    - /
    - n, N: next
    - f, F: find

- substitute
    - s/[old]/[new]/g: 1 line
    - %s/[old]/[new]/g: whole file

