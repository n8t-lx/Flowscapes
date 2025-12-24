# Flowscapes, What I want it to do.
Printing to Output

say, "Hello, World!"

Variables
/- Remember, always stored locally unless told so not to! If you want to boost performance disable the "dynamic-data-modification" library, which you will learn about later. -/
var, 5
varnull, "!NULL" /- for NULL
varstr, "Hello"
global varglobal, 5

-/ no lib /- 
var, is num 5 
var, is string "Hello"
var, is string "!NULL"
global var, is string "Global Hello"

User Input 

input, var to string

If and Else
 
if, string is "Hello" /- or is not /- 
  say, "variable string is hello"
  else,
    say, "variable string is not hello"
  Done

Optionalities

library-remove, GarbageCollection
library, low-level


Error Handling

/-  /main.fs/  Line 5, missing comma for if 
Remember, a comma tells your
command something is coming
right after! Your code has not been compiled. -/

/- /main.fs/ Line 37, print is not a part
of our syntax. Did you mean, 
say? Remember, if a ten year old
cant understand it, then it might 
not compile. If you are a high 
level programmer, make sure to 
include your low-level library. Your code has not been compiled. -/

Package Management

scape, library "low-level"
scape, projects "BSS Macro"

Native Graphics

draw, shape "Circle" at y50 / x50 color blue /- Or, colorhex 30 / 150 / 255 -/

Shell - Shellscapes

shellscapes

File Extensions 

Standard - .fs 
Header - .fsh

Syncing

library, "low-level"

permission, "$USER" 

sync, to "/home/$USER/testing/sync.txt"
/- synced successfully. always stay careful when syncing. for security, you can not access any possible kernel, user or any locked files. you will need permission to do so. -/
sync.txt - write "Sync was successful."

Shell access
library, "low-level"
/- permission is mandatory at all costs -/
shellscapes, "cd Downloads" / "ls -f"

Permission 

/- Please enter your password for syncing. Examine these closely. 'every-sync-command' -/

-> 1234  /- For calling specifics for permissions, we will use single quotes.

/- Please enter your password for shell access. Examine these closely. 'every-sync-command' -/

-> 1234 /- Examples !! -/

Memory access
library, "low-level"
reserve, 1024 as "My Memory"

release, "My Memory"

Pointers

honey, 10000
honeygps, honeygps to honey

Loops 

do, 15
  say, "+1 Honey!"
  Done

  repeat, until honey is 1000000
    say, "Farm pine!"
 Done
 -/ dont worry about capitals its not gonna matter /-

 Functions
  pollen, 100

 motif, grind
  pollen, pollen * 5
  done 

  grind, 

  Math 
  pollen, 5
  pollen, pollen * 5 

  structs

  structure, 
    level, 8
    bluemask, true 

  Climax
  library, "low-level"
  climax, performance /- Permissions required -/

  Waiting
  rest, 1

  Logical operators

  if, honey is 10000 and, mask is true 

  Universal data modification
  /- Unlike in rust you must specify if it is immutable but you can choose this -/
  library, "default-mutable"
  library-remove, "dynamic-data-modification"
  
  /- with dynamic-data-modification -/
    var,  "string"
    var,  var + 5 

    /- without -/
    
    var, honey is num 100
    honey, is num honey + 50 

    displaytext, string "Total:"
    finaloutput,  string display_text + honey become, string

    displaytext,  num 100
    -/ this would give you an error /- 
    -main.fs- line 68, displaytext is a string, 
    please dont try to squeeze in a number inside of it
    you must make it dynamic or just make a new variable
 your code has not compiled /-

  arrays 

  mybees, "Tabby" / "Photon" / "Buoyant" 
  

  Flowscapes
  
  The language based off of a geometry dash level and a beautiful creo song.
  Made to just 'flow' when you are writing. 
  Beautiful human-readable syntax, simple to learn.
  High level and low level, using libraries.
  Fast and quite minimal.
  Made on christmas eve because a guy was bored macroing in BSS 
  Happy christmas & new year 

  sincerely n8tlx.
