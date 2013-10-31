otfeatures
==========

A SASS mix-in for turning OpenType features on and off in your embedded web fonts. (Only useful if you're using a web font with embedded OpenType features such as ligatures, swashes, etc)

OpenType Features Key
---------------------
@mixin otfeatures($c2sc: 0, $calt: 0, $clig: 0, $dlig: 0, $frac: 0, $hist: 0, $hlig: 0, $kern: 0, $liga: 0, $nalt: 0, $salt: 0, $ss01: 0, $ss02: 0, $ss03: 0, $ss04: 0, $ss05: 0, $swsh: 0, $zero: 0)  
  
"c2sc" : small caps from caps  
"calt" : contextual alternates  
"clig" : contextual ligatures  
"dlig" : discretionary ligatures  
"hist" : historical character alternatives  
"hlig" : historical ligatures  
"kern" : enable use of embedded kerning table  
"liga" : common ligatures  
"nalt" : alternate annotation   
"salt" : stylistic alternatives  
"smcp" : small caps  
"ss01" : alternate stylistic set 1  
"ss02" : alternate stylistic set 2   
"ss03" : alternate stylistic set 3  
"ss04" : alternate stylistic set 4  
"ss05" : alternate stylistic set 5  
"swsh" : swashes  
"zero" : slashed-zero  
