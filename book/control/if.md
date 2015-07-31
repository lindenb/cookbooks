# If statements

## ![tcltk](../../img/icn/tlctk32.png "TCL/TK") TCL/TK

Reference : http://www.tcl.tk/man/tcl8.4/TclCmd/if.htm

```tcl
if {$vbl == 1} { puts "vbl is one" }
```

With an else-clause:
```tcl
if {$vbl == 1} {
   puts "vbl is one"
} else {
   puts "vbl is not one"
}
```
With an elseif-clause too:

```tcl
if {$vbl == 1} {
   puts "vbl is one"
} elseif {$vbl == 2} {
   puts "vbl is two"
} else {
   puts "vbl is not one or two"
}
```
