# Open File Dialog

## ![tcltk](../../img/icn/tlctk32.png "TCL/TK") TCL/TK

Reference : http://www.tcl.tk/man/tcl8.4/TkCmd/getOpenFile.htm

```tcl
set types {
    {{Text Files}       {.txt}        }
    {{TCL Scripts}      {.tcl}        }
    {{C Source Files}   {.c}      TEXT}
    {{GIF Files}        {.gif}        }
    {{GIF Files}        {}        GIFF}
    {{All Files}        *             }
}
set filename [tk_getOpenFile -filetypes $types]

if {$filename != ""} {
    # Open the file ...
}
```
