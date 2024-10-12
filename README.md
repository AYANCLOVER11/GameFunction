# GameMachanics
visual studio 2022
configuration

Property -> c++ -> general -> Additional Include Directories -> (a\b\c)
a.SDL2 -> include 
b.SDL2_ttf -> include 
c.SDL2_image -> include 

Property -> Linker -> general -> Additional Library Directories -> (a\b\c)
a. SDL2 -> x64
b. SDL2_ttf -> x64
c. SDL2_image -> x64

Property -> Linker -> imput -> Additional Dependency -> (a,b,c,d)
a. SDL2.lib
b. SDL2main.lib
c. SDL2_image.lib
d. SDL2_ttf.lib
